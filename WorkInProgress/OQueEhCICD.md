# O que é CI/CD?

Publicado 25 de janeiro de 2023•*8* minutos (tempo de leitura)



Copiar URL

## Ir para seção

[Visão geral](https://www.redhat.com/pt-br/topics/devops/what-is-ci-cd#visão-geral)[Por que CI/CD é importante?](https://www.redhat.com/pt-br/topics/devops/what-is-ci-cd#por-que-ci/cd-é-importante)[Integração contínua](https://www.redhat.com/pt-br/topics/devops/what-is-ci-cd#integração-contínua)[O que é “CD” em CI/CD?](https://www.redhat.com/pt-br/topics/devops/what-is-ci-cd#o-que-é-“cd”-em-ci/cd)[Entrega contínua](https://www.redhat.com/pt-br/topics/devops/what-is-ci-cd#entrega-contínua)[Implantação contínua](https://www.redhat.com/pt-br/topics/devops/what-is-ci-cd#implantação-contínua)[CI/CD vs. DevOps](https://www.redhat.com/pt-br/topics/devops/what-is-ci-cd#ci/cd-vs.-devops)[O que é segurança de CI/CD?](https://www.redhat.com/pt-br/topics/devops/what-is-ci-cd#o-que-é-segurança-de-ci/cd)[Ferramentas de CI/CD](https://www.redhat.com/pt-br/topics/devops/what-is-ci-cd#ferramentas-de-ci/cd)[Como a Red Hat pode ajudar](https://www.redhat.com/pt-br/topics/devops/what-is-ci-cd#como-a-red-hat-pode-ajudar)

## Visão geral

O propósito da abordagem de CI/CD, sigla em inglês para integração e entrega/implantação contínuas, é otimizar e acelerar o ciclo de vida de desenvolvimento de software.A

[integração contínua](https://www.redhat.com/pt-br/topics/integration) (CI) é a prática de integrar, de forma [automática](https://www.redhat.com/pt-br/topics/automation) e frequente, mudanças a um repositório de código-fonte compartilhado.Já a implantação e/ou [entrega contínua](https://www.redhat.com/pt-br/topics/devops/what-is-continuous-delivery) (CD) é um processo em duas etapas relacionado a integração, teste e entrega de mudanças no código. A entrega contínua é quase uma implantação automática em produção, enquanto a implantação contínua implica em automaticamente lançar atualizações no ambiente de produção.

 

![CI/CD Flow](https://www.redhat.com/rhdc/managed-files/styles/wysiwyg_full_width/private/ci-cd-flow-desktop.png.webp?itok=mDEvsSsp)

 

Juntas, essas práticas relacionadas são muitas vezes chamadas de [“pipeline de CI/CD”](https://www.redhat.com/pt-br/topics/devops/what-cicd-pipeline). Para implementá-las, é preciso que as equipes de operações e desenvolvimento trabalhem em conjunto seguindo princípios ágeis, com uma abordagem de [DevOps](https://www.redhat.com/pt-br/topics/devops) ou de [engenharia de confiabilidade de sites (SRE)](https://www.redhat.com/pt-br/topics/devops/what-is-sre).

## Por que CI/CD é importante?

Com uma abordagem de CI/CD, as empresas podem evitar bugs e falhas no código, além de manter um ciclo contínuo de desenvolvimento e atualizações do software. 

À medida que as apps evoluem, as funcionalidades de CI/CD ajudam a reduzir a complexidade, aumentar a eficiência e simplificar os fluxos de trabalho.

E como o pipeline de CI/CD automatiza o trabalho humano que geralmente é necessário para um novo código passar da confirmação à produção, o tempo de inatividade é minimizado e as versões atualizadas do código são disponibilizadas mais rápido. Além disso, com a capacidade de agilizar a integração de atualizações e mudanças no código, é possível incorporar o feedback dos usuários de maneira mais frequente e eficaz. Isso gera resultados positivos para os usuários finais e uma maior satisfação dos clientes em geral. 

## Recursos da Red Hat

[Leia mais](https://www.redhat.com/pt-br/resources)

## O que é integração contínua?

Na sigla CI/CD, “CI” sempre se refere à integração contínua. Trata-se de um processo de automação que ajuda desenvolvedores a consolidar mudanças no código em uma ramificação (ou “tronco”) compartilhada com mais frequência. À medida que as atualizações são feitas, etapas de teste automatizadas são acionadas para garantir a confiabilidade das mudanças consolidadas no código. 

No desenvolvimento moderno de aplicações, o objetivo é ter muitos desenvolvedores trabalhando ao mesmo tempo em diferentes funcionalidades da mesma app. No entanto, se uma organização tiver que consolidar todo o código-fonte ramificado em apenas um dia (conhecido como “merge day” ou “dia de consolidação”), o trabalho poderá ser monótono, manual e demorado. 

O motivo é que, quando um desenvolvedor trabalha isoladamente fazendo mudanças na aplicação, há uma chance de que ocorram conflitos com outras alterações feitas ao mesmo tempo por outros desenvolvedores. Esse problema pode ser agravado se cada uma dessas pessoas tiver seu próprio [ambiente de desenvolvimento integrado (IDE)](https://www.redhat.com/pt-br/topics/middleware/what-is-ide) personalizado. O ideal seria que a equipe entrasse em acordo com apenas um IDE baseado na [nuvem](https://www.redhat.com/pt-br/topics/cloud-computing).

A CI pode ser uma solução para o problema de ter muitas ramificações simultâneas e possivelmente conflitantes de uma app em desenvolvimento.

Uma implementação bem-sucedida de CI significa que, após um desenvolvedor consolidar mudanças no código de uma aplicação, essas atualizações são validadas com a automação da compilação e dos testes em diferentes níveis da app. Normalmente, são executados testes automáticos de unidade e integração para garantir que as mudanças não danificaram a app. Para isso, são testados desde classes e função até os módulos que formam a aplicação inteira. Um dos benefícios da CI é que, caso os testes automatizados identifiquem um conflito entre o código novo e o anterior, é mais fácil corrigir tais bugs de forma mais rápida e frequente.

## O que é “CD” em CI/CD?

“CD” se refere à entrega contínua e/ou à implantação contínua, conceitos relacionados e usados alternadamente às vezes. Em ambos os casos, trata-se da automação de estágios subsequentes do pipeline, mas são usados separadamente de vez em quando para ilustrar o nível de automação. A escolha entre entrega contínua e implantação contínua depende da tolerância a riscos e das necessidades específicas das equipes de desenvolvimento e operações.

## O que é entrega contínua?

 Entrega contínua se refere à automação da liberação do código validado para um repositório, seguida da automação da compilação e dos testes de unidade e integração executada na CI. Portanto, para que o processo de entrega contínua seja eficaz, é importante já ter a prática de CI incorporada ao pipeline de desenvolvimento.

Na entrega contínua, todos os estágios (da consolidação das mudanças no código à disponibilização de versões prontas para a produção) envolvem a automação de testes e da liberação do código. No final do processo, a equipe de operações pode implantar uma app em produção rapidamente.

Em geral, a entrega contínua serve para automaticamente verificar se há bugs nas mudanças feitas por desenvolvedores em uma aplicação e carregá-las em um repositório, como o GitHub ou um registro de containers. Nesse repositório, a equipe de operações pode implantar essas mudanças em um ambiente de produção ativo. É uma resposta para o problema da falta de visibilidade e comunicação entre equipes de desenvolvimento e linha de negócios. Nesse sentido, a finalidade da entrega contínua é ter uma base de código sempre pronta para a implantação em um ambiente de produção, com o mínimo de esforço para implantar código novo.

[Mais informações sobre a entrega contínua](https://www.redhat.com/pt-br/topics/devops/what-is-continuous-delivery)





## O que é implantação contínua?

O estágio final de um pipeline de CI/CD bem desenvolvido é a implantação contínua. A implantação contínua é uma extensão da entrega contínua que se refere à liberação automática das mudanças feitas por desenvolvedores, do repositório à produção, onde podem ser usadas por clientes.

A CD resolve o problema da sobrecarga de trabalho das equipes de operações com processos manuais que atrasam a entrega de apps. Esse conceito aproveita os benefícios da entrega contínua ao automatizar a próxima etapa no pipeline.

Na prática, a implantação contínua significa que as mudanças feitas por desenvolvedores em uma aplicação na nuvem podem entrar em vigor em questão de minutos, caso passem em todos os testes automatizados. Isso faz com que seja muito mais fácil receber e incorporar continuamente o feedback dos usuários. Juntas, todas essas práticas associadas de CI/CD tornam o processo de implantação menos arriscado, além de facilitar a liberação gradual de mudanças nas apps. 

No entanto, como não há interferência manual no estágio final do pipeline antes da entrada em produção, a implantação contínua é altamente dependente de uma automação bem desenvolvida dos testes. Isso requer muito investimento inicial, já que tais testes precisam ser executados nos vários estágios do pipeline de CI/CD.

[Mais informações sobre a automação da implantação](https://www.redhat.com/pt-br/topics/application-development-and-delivery/o-que-e-automacao-da-implantacao)





## CI/CD vs. DevOps

O pipeline de CI/CD é uma parte essencial da metodologia de [DevOps](https://www.redhat.com/pt-br/topics/devops), que tem como objetivo promover a colaboração entre as equipes de desenvolvimento e operações. Ambos os conceitos têm como foco a automação dos processos de integração de código. Isso significa agilizar os processos para levar uma ideia (como uma nova funcionalidade, solicitação de melhoria ou correção de um bug) do desenvolvimento para a implantação no ambiente de produção, onde vai gerar valor para os usuários.

No framework colaborativo do DevOps, a segurança é uma responsabilidade compartilhada e integrada do início ao fim. É uma mentalidade tão importante que resultou na criação do termo “[DevSecOps](https://www.redhat.com/pt-br/topics/devops/what-is-devsecops)” para enfatizar a necessidade de criar uma base de segurança para sustentar as iniciativas de DevOps. O DevSecOps (desenvolvimento, segurança e operação) é uma abordagem de cultura, automação e design de plataforma que integra a segurança como uma responsabilidade compartilhada em todo o ciclo de vida de TI. Um componente essencial do DevSecOps é a introdução de um pipeline de CI/CD seguro.

[Por que escolher a Red Hat para implementar o DevOps?](https://www.redhat.com/pt-br/topics/devops/why-choose-red-hat-for-devops)





## O que é segurança de CI/CD?

A

[segurança de CI/CD](https://www.redhat.com/pt-br/topics/security/o-que-e-seguranca-de-cicd) é utilizada para proteger pipelines de códigos com a automação de verificações e testes para evitar vulnerabilidades na entrega do software. Incorporar a segurança aos seus pipelines de dados (como métodos de segurança como [shift left e shift right ](https://www.redhat.com/pt-br/topics/security/shift-left-e-shift-right)) ajuda a proteger os códigos de ataques, evitar vazamentos de dados, ficar em conformidade com as políticas e assegurar a qualidade.

A natureza ágil do desenvolvimento e da implantação sem uma segurança adequada pode expôr o pipeline a riscos como:

- Exposição de dados confidenciais a fontes externas
- Utilização de códigos ou componentes de terceiros não confiáveis
- Acesso não autorizado a ferramentas de compilação ou repositórios de código-fonte

Identificar e mitigar vulnerabilidades ao longo do ciclo de desenvolvimento de software assegura a realização de testes minuciosos nos códigos alterados e a aderência a padrões de segurança antes da implantação na produção.

## Quais são as ferramentas de CI/CD mais comuns?

As ferramentas de CI/CD ajudam a equipe a automatizar o desenvolvimento, a implantação e os testes. Algumas ferramentas tratam especificamente da integração (CI), algumas [gerenciam](https://www.redhat.com/pt-br/topics/management) o desenvolvimento e a implantação (CD) e outras são especializadas em testes contínuos ou funções relacionadas.

Tekton Pipelines é um framework de CI/CD para plataformas Kubernetes que proporciona uma experiência de CI/CD nativa em nuvem padrão com containers.

[Mais informações sobre o Tekton Pipelines ](https://cloud.redhat.com/learn/topics/ci-cd?extIdCarryOver=true&intcmp=7013a000002wBnmAAE&sc_cid=7013a000002DgC5AAK']])





Além do Tekton Pipelines, confira estas outras ferramentas open source de CI/CD:

- [Jenkins](https://cloud.redhat.com/blog/deploying-jenkins-on-openshift-part-1?extIdCarryOver=true&intcmp=7013a000002wBnmAAE&sc_cid=7013a000002DgC5AAK']]&cicd=32h281b), projetado para lidar com tudo, desde um simples servidor de CI até um hub de CD completo.
- [Spinnaker](https://spinnaker.io/), uma plataforma de CD criada para ambientes [multicloud](https://www.redhat.com/pt-br/topics/cloud-computing/what-is-multicloud).
- [GoCD](https://www.gocd.org/), um servidor de CI/CD voltado para modelagem e visualização.
- [Concourse](https://concourse-ci.org/), “uma plataforma open source contínua”.
- [Screwdriver](https://screwdriver.cd/), uma plataforma de compilação criada para CD.

Convém às equipes considerar as ferramentas de CI/CD gerenciadas, disponíveis em uma variedade de fornecedores. Todos os principais [provedores de nuvem pública](https://www.redhat.com/pt-br/topics/cloud-computing/what-are-cloud-providers) oferecem soluções de CI/CD, além de [GitLab](https://about.gitlab.com/), [CircleCI](https://circleci.com/), [Travis CI](https://www.travis-ci.com/), [Atlassian Bamboo](https://www.atlassian.com/software/bamboo) e muitos outros.

Aliás, é provável que qualquer ferramenta essencial para DevOps faça parte de um processo de CI/CD. As ferramentas de [automação de configuração](https://www.redhat.com/pt-br/topics/automation/what-is-configuration-management) (como [Ansible](https://www.redhat.com/pt-br/technologies/management/ansible), [Chef](https://www.chef.io/) e [Puppet](https://puppet.com/)), runtime de containers (como [Docker](https://www.redhat.com/pt-br/topics/containers/what-is-docker), [rkt](https://cloud.redhat.com/learn/topics/rkt) e [cri-o](https://cri-o.io/)) e [orquestração de containers](https://www.redhat.com/pt-br/topics/containers/what-is-container-orchestration) ([Kubernetes](https://www.redhat.com/pt-br/topics/containers/what-is-kubernetes)) não são necessariamente ferramentas de CI/CD, mas aparecem em vários fluxos de trabalho desse tipo.

Há muitas maneiras de implementar as práticas de CI/CD de acordo com sua estratégia de desenvolvimento de aplicações e preferência de provedor de nuvem. O [Red Hat® OpenShift® Service on AWS](https://www.redhat.com/pt-br/technologies/cloud-computing/openshift/aws) oferece diversas opções para facilitar seu próprio fluxo de trabalho de CI/CD, como, por exemplo, o [Tekton Pipelines e o OpenShift Pipelines](https://cloud.redhat.com/learn/ci/cd-pipelines-and-red-hat-openshift-service-aws). Usando o Red Hat OpenShift, empresas podem empregar práticas de CI/CD para automatizar o desenvolvimento, testes e a implantação de suas aplicações em diversas plataformas on-premise e na nuvem. 

## Como a Red Hat pode ajudar

Nossos especialistas podem ajudar sua empresa a desenvolver as práticas, ferramentas e a cultura necessárias para modernizar e criar aplicações de forma mais eficiente, acelerando sua [jornada para o desenvolvimento de aplicações nativas em nuvem.O](https://www.redhat.com/pt-br/services/consulting/cloud-native-development)

[Red Hat® OpenShift](https://www.redhat.com/pt-br/technologies/cloud-computing/openshift)® ajuda as empresas a melhorar a [produtividade dos desenvolvedores](https://www.redhat.com/pt-br/products/developer-productivity), automatizar os pipelines de CI/CD e mudar os esforços de segurança no início e durante todo o ciclo de desenvolvimento.O

[Red Hat OpenShift Pipelines](https://www.redhat.com/pt-br/technologies/cloud-computing/openshift/pipelines) foi projetado para executar cada etapa do pipeline de CI/CD em um container próprio. Assim, cada uma delas pode ser escalada de forma independente para atender às demandas do pipeline. Isso significa que administradores e desenvolvedores podem criar blueprints do pipeline para as aplicações com base nos requisitos específicos da empresa e de segurança.O

[Red Hat OpenShift GitOps](https://www.redhat.com/pt-br/technologies/cloud-computing/openshift/gitops) é um [operador](https://www.redhat.com/pt-br/technologies/red-hat-openshift/para-que-servem-os-operadores-do-red-hat-openshift) com um fluxo de trabalho que agrega repositórios Git, ferramentas de integração e entrega contínuas (CI/CD) e Kubernetes para um desenvolvimento de software mais rápido, seguro e escalável. Tudo isso sem comprometer a qualidade.Com o OpenShift [GitOps](https://www.redhat.com/pt-br/topics/devops/what-is-gitops), os clientes podem criar e integrar fluxos de trabalho de CD orientados por Git declarativo diretamente em sua plataforma de desenvolvimento de aplicações.O

[Red Hat Ansible® Automation Platform](https://www.redhat.com/pt-br/technologies/management/ansible) oferece todas as ferramentas que você precisa para implementar a automação em toda a empresa, incluindo uma [solução orientada a eventos](https://www.redhat.com/pt-br/technologies/management/ansible/event-driven-ansible), analytics e coleções de conteúdo prontas. Com uma linguagem comum baseada em YAML e abordagem de estado desejado, você pode usar o mesmo conteúdo de automação nas operações cotidianas e no pipeline de CI/CD. E, como a solução funciona com praticamente todos os aspectos da infraestrutura de TI, você pode implantar ambientes consistentes de desenvolvimento, teste e produção de maneira fácil e rápida, aumentando a confiabilidade e a resiliência das aplicações.O

Ansible Automation Platform [também se integra](https://www.redhat.com/pt-br/technologies/cloud-computing/openshift/ansible-on-openshift) ao [Red Hat Advanced Cluster Management for Kubernetes](https://www.redhat.com/pt-br/technologies/management/advanced-cluster-management) para você orquestrar clusters do Kubernetes no seu pipeline de CI/CD. Use a linguagem de automação legível por humanos para criar e manter com mais facilidade os operadores do Red Hat OpenShift.

[Veja como a automação oferece suporte para os pipelines de CI/CD](https://www.redhat.com/pt-br/engage/ansible-pipelines-whitepaper-s-202012162024)