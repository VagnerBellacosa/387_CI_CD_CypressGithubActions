# O que é o fluxo de trabalho do GitOps?

Publicado 14 de maio de 2024•*7* minutos (tempo de leitura)



Copiar URL

## Ir para seção

[Introdução](https://www.redhat.com/pt-br/topics/devops/what-is-gitops-workflow#introdução)[O que é o repositório git?](https://www.redhat.com/pt-br/topics/devops/what-is-gitops-workflow#o-que-é-o-repositório-git)[O que é infraestrutura como código?](https://www.redhat.com/pt-br/topics/devops/what-is-gitops-workflow#o-que-é-infraestrutura-como-código)[O que é um pipeline de CI/CD?](https://www.redhat.com/pt-br/topics/devops/what-is-gitops-workflow#o-que-é-um-pipeline-de-ci/cd)[Operadores do Kubernetes e GitOps com Kubernetes](https://www.redhat.com/pt-br/topics/devops/what-is-gitops-workflow#operadores-do-kubernetes-e-gitops-com-kubernetes)[O que é observabilidade em um fluxo de trabalho de GitOps?](https://www.redhat.com/pt-br/topics/devops/what-is-gitops-workflow#o-que-é-observabilidade-em-um-fluxo-de-trabalho-de-gitops)[O que é o Red Hat OpenShift Observability?](https://www.redhat.com/pt-br/topics/devops/what-is-gitops-workflow#o-que-é-o-red-hat-openshift-observability)[O que é o Red Hat OpenShift GitOps?](https://www.redhat.com/pt-br/topics/devops/what-is-gitops-workflow#o-que-é-o-red-hat-openshift-gitops)[Próximas etapas](https://www.redhat.com/pt-br/topics/devops/what-is-gitops-workflow#próximas-etapas)

## Introdução ao GitOps e aos fluxos de trabalho do GitOps

O [GitOps](https://www.redhat.com/pt-br/topics/devops/what-is-gitops) é uma abordagem moderna de desenvolvimento e implantação de software onde toda a infraestrutura e o ciclo de vida da aplicação são gerenciados por repositórios git como single source of truth. Nesse fluxo de trabalho, os desenvolvedores alocam alterações de código e configurações de infraestrutura em repositórios git, acionando pipelines automatizados de [CI/CD](https://www.redhat.com/pt-br/topics/devops/what-cicd-pipeline) que criam, testam e implantam aplicações e alterações de infraestrutura com base no estado do repositório git. 

Operadores e administradores usam arquivos de configuração declarativos armazenados no Git para definir o estado desejado da infraestrutura e ferramentas de sincronização contínua, como o [Argo CD](https://www.redhat.com/pt-br/topics/devops/what-is-argocd), para garantir que o ambiente ativo corresponda ao repositório git. Isso fornece controle de versão, colaboração e auditabilidade para o código e a infraestrutura e leva, por fim, a uma entrega de software e gerenciamento de infraestrutura eficientes e confiáveis.

Assim, você pode gerenciar a configuração do cluster e as implantações de aplicações, trazendo a automação para um processo que antes era manual. Por exemplo, o GitOps permite gerenciar clusters do [Red Hat® OpenShift® Container Platform](https://www.redhat.com/pt-br/technologies/cloud-computing/openshift/container-platform) em ambientes [Kubernetes](https://www.redhat.com/pt-br/topics/containers/what-is-kubernetes) com vários clusters. 

Essas funções ajudam a remediar os desafios que a abordagem [multicloud](https://www.redhat.com/pt-br/topics/devops/o-que-e-gitops-multicloud) traz, como a necessidade de consistência, segurança e colaboração ao mover as cargas de trabalho entre a [nuvem pública](https://www.redhat.com/pt-br/topics/cloud-computing/what-is-public-cloud), a [nuvem privada](https://www.redhat.com/pt-br/topics/cloud-computing/what-is-private-cloud) e até mesmo ambientes on-premises. 

Neste artigo, abordaremos os fundamentos dos fluxos de trabalho do GitOps.

## O que é o repositório git?

No GitOps, o repositório git é a single source of truth para a configuração de sistemas e aplicações. Ele consiste em uma descrição declarativa da infraestrutura do seu ambiente e funciona em conjunto com os processos automatizados gerenciados pelas ferramentas GitOps, como o Argo CD. A automação faz com que o estado real do ambiente esteja em conformidade com o estado descrito. Você também pode usar o repositório para visualizar a lista de alterações no estado do sistema, pois o histórico do Git oferece controle de alterações. 

Além disso, armazenar a infraestrutura e a configuração como código ajuda a reduzir a dispersão. Você pode armazenar a configuração de clusters e aplicações como código nos repositórios git. 

## Recursos da Red Hat

[Leia mais](https://www.redhat.com/pt-br/resources)

## O que é infraestrutura como código (IaC)?

[Infraestrutura como código (IaC)](https://www.redhat.com/pt-br/topics/automation/what-is-infrastructure-as-code-iac) é o gerenciamento e provisionamento de infraestrutura por código, e não por processos manuais.

Com a IaC, são criados arquivos de configuração que incluem as especificações da infraestrutura. Isso facilita a edição e distribuição de configurações e garante que você provisione sempre o mesmo ambiente. Ao codificar e documentar as especificações de configuração, a IaC auxilia no [gerenciamento de configuração](https://www.redhat.com/pt-br/topics/automation/what-is-configuration-management) e ajuda a evitar alterações de configuração ad-hoc não documentadas. Há dois tipos de abordagem de IaC: declarativa ou imperativa.

A abordagem **declarativa** define o estado desejado do sistema, incluindo os recursos necessários, as propriedades que eles precisam ter e uma ferramenta de IaC para configurá-lo. Ela também mantém uma lista do estado atual dos objetos do seu sistema. Por outro lado, a abordagem **imperativa** define os comandos específicos necessários para alcançar a configuração desejada. Depois, esses comandos precisam ser executados na ordem correta. 

Muitas das ferramentas de IaC que usam uma abordagem declarativa provisionam automaticamente a infraestrutura desejada. Se você alterar o estado desejado, uma ferramenta de IaC declarativa aplicará as alterações para você. Uma ferramenta imperativa exige que você saiba como as alterações deverão ser aplicadas.

A IaC é uma parte importante da implementação de práticas de [DevOps](https://www.redhat.com/pt-br/topics/devops) e de integração e entrega contínuas (CI/CD). Ela elimina a maior parte do trabalho de provisionamento realizado pelos desenvolvedores. Assim, eles podem executar um script para preparar a infraestrutura. Dessa forma, as implantações de aplicações não ficam aguardando a infraestrutura, e os sysadmins não gerenciam processos manuais demorados. 

A prática de CI/CD conta com monitoramento e automação contínuos durante o ciclo de vida da aplicação, desde a integração e o teste até a entrega e a implantação. 
O alinhamento das equipes de desenvolvimento e de operações usando uma abordagem de DevOps com IaC gera menos erros, implantações manuais e inconsistências.

O GitOps pode ser considerado uma evolução no modelo de infraestrutura como código (IaC) que usa o Git como o sistema de controle de versão para configurações de infraestrutura. 

## O que é um pipeline de CI/CD?

Pipeline é um processo que orienta o desenvolvimento de software por um caminho de criação, testes e implantação do código, também conhecido como [integração e entrega/implementação contínuas (CI/CD).](https://www.redhat.com/pt-br/topics/devops/what-is-ci-cd) O objetivo da automação do pipeline é minimizar erros humanos e manter a consistência do processo até o lançamento do software. As ferramentas usadas no pipeline podem incluir compilação de código, testes de unidade, análise de código, segurança e criação de binários. Para ambientes de containers, esse [pipeline](https://www.redhat.com/pt-br/topics/devops/what-cicd-pipeline) ainda pode conter o empacotamento do código em uma imagem de container a ser implantada em uma nuvem híbrida.

O CI/CD é a essência de uma metodologia DevOps, pois une as equipes de desenvolvedores e operações de TI para fazer a implantação do software. À medida que as empresas usam cada vez mais aplicações personalizadas para se destacarem, a taxa de liberação de código se tornou um diferencial competitivo.

Pipelines CI/CD geralmente são acionados por um evento externo, como um código enviado a um repositório. Em um fluxo de trabalho do GitOps, alterações são feitas usando pull requests que modificam o estado no repositório git. 

Para implementar uma nova versão usando um fluxo de trabalho do GitOps, é feita uma pull request no Git, que cria uma alteração no estado declarado do cluster. O operador do GitOps, que fica entre o pipeline do GitOps e o sistema de orquestração, seleciona a confirmação e extrai a nova declaração de estado do Git.  

Uma vez aprovadas e integradas, as alterações são aplicadas automaticamente à infraestrutura dinâmica. Os desenvolvedores podem continuar usando seus próprios fluxos de trabalho padrão e práticas de CI/CD.

[Mais informações sobre CI/CD](https://www.redhat.com/pt-br/topics/devops/what-is-ci-cd)



## Operadores do Kubernetes e GitOps com Kubernetes

Ao usar o GitOps com Kubernetes no seu fluxo de trabalho, o operador normalmente será um operador do Kubernetes. 

O [operador do Kubernetes](https://www.redhat.com/pt-br/topics/containers/o-que-e-um-operador-kubernetes) é um método de empacotar, implantar e gerenciar aplicações do Kubernetes. É um controlador específico para aplicações que amplia as funcionalidades da API do Kubernetes a fim de criar, configurar e gerenciar instâncias de aplicações complexas para um usuário do Kubernetes. O operador é baseado nos conceitos básicos de controlador e recursos do Kubernetes. No entanto, ele inclui o conhecimento específico de uma aplicação ou domínio para automatizar o ciclo de vida inteiro do software que gerencia. 

No GitOps, o operador compara o estado desejado no repositório ao estado real da infraestrutura implantada. Ele atualizará a infraestrutura sempre que uma diferença for percebida entre o estado atual e o que já existe no repositório. O operador também pode monitorar um repositório de imagens de container e fazer atualizações seguindo o processo de implantar novas imagens.

## O que é observabilidade em um fluxo de trabalho de GitOps?

[Observabilidade](https://www.redhat.com/pt-br/topics/devops/what-is-observability) se refere à capacidade de monitorar, mensurar e entender o estado de um sistema ou aplicação pela análise de seus resultados, logs e métricas de desempenho. Em sistemas de software modernos e na cloud computing, a observabilidade desempenha um papel de extrema importância, pois garante a confiabilidade, o desempenho e a segurança das aplicações e da infraestrutura.

A observabilidade absorve e estende os sistemas de monitoramento clássicos e ajuda as equipes a identificar a causa raiz dos problemas. Com ela, os stakeholders também esclarecem dúvidas sobre suas aplicações e negócios, como, por exemplo, previsões sobre possíveis erros. 

Benefícios da observabilidade: 

- Mais confiabilidade: detecte e resolva problemas antes que eles sejam escalonados. Assim, você minimiza o tempo de inatividade e mantém a disponibilidade dos sistemas para os usuários.
- Solução de problemas eficiente: identifique rapidamente a causa raiz dos problemas e os resolva com eficiência, tendo em mãos insights detalhados sobre o comportamento de um sistema.
- Desempenho otimizado: identifique áreas para otimização, como obstáculos no sistema ou recursos subutilizados, possibilitando uma alocação de recursos mais eficiente e um desempenho melhor.
- Processo de tomada de decisões orientado por dados: receba informações atualizadas sobre desempenho e comportamento do sistema, permitindo a tomada de decisões baseada em dados e a melhoria contínua.

## O que é o Red Hat OpenShift Observability?

O Red Hat® OpenShift® Observability resolve a complexidade arquitetônica moderna conectando ferramentas e tecnologias de observabilidade para criar uma experiência unificada. O objetivo da plataforma é proporcionar visibilidade, monitoramento e análise em tempo real de várias métricas, logs, traces e eventos do sistema para os usuários conseguirem solucionar problemas rapidamente, antes que afetem suas aplicações ou os usuários finais.

## O que é o Red Hat OpenShift GitOps?

O

[Red Hat OpenShift GitOps](https://www.redhat.com/pt-br/technologies/cloud-computing/openshift/gitops) é um operador que instala e configura uma instância do Argo CD por você. Ele gerencia a configuração da infraestrutura e as implantações de aplicações, organizando o processo de implantação com base nesses repositórios de configuração. Pelo menos dois repositórios são sempre centrais no processo: um repositório de aplicação com o código-fonte e um repositório de configuração do ambiente que define o estado desejado da aplicação.

Para a manutenção dos recursos do cluster, o Red Hat OpenShift GitOps usa o Argo CD, uma ferramenta open source responsável pela parte da implantação contínua das práticas de integração e implantação contínuas (CI/CD) das aplicações. O Argo CD atua como controlador do Red Hat OpenShift GitOps, monitorando as configurações e descrições de estado das aplicações conforme definido em um repositório git. Ele compara o estado definido ao estado real e relata quaisquer configurações que desviem da descrição especificada. 

Com base nesses relatórios, os administradores podem sincronizar novamente as configurações com o estado definido. Essa atualização de sincronização pode ser manual ou automatizada. No caso da automação, a configuração é basicamente autorrecuperável.

Em outras palavras, o Red Hat OpenShift GitOps promove um fluxo de trabalho do GitOps ideal, no qual os desenvolvedores alocam seu código e alterações de configuração em repositórios git, que acionam pipelines automatizados de CI/CD. Esses pipelines são responsáveis por criar, testar e implantar aplicações e infraestrutura com base no estado do repositório git. Nesse caso, o Red Hat OpenShift GitOps é o operador que define o estado desejado da infraestrutura usando arquivos de configuração declarativos armazenados no Git. Com isso, o Argo CD garante que o ambiente real se alinhe consistentemente ao estado especificado no repositório git. Essa abordagem promove o controle de versão, a colaboração e a rastreabilidade do código e da infraestrutura, otimizando a entrega do software e o gerenciamento da infraestrutura enquanto reforça a confiabilidade.

## Próximas etapas

Agora você entende como os fluxos de trabalho do GitOps podem aumentar a produtividade e a velocidade do desenvolvimento e das implantações, ao mesmo tempo que melhoram a estabilidade e a confiabilidade dos sistemas.

É hora de você testar o desenvolvimento com GitOps.

[Desenvolva com o GitOps](https://developers.redhat.com/learn/openshift/develop-gitops)