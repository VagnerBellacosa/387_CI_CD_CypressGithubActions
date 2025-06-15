# O que é DevOps?

- 05/10/2023

O DevOps combina desenvolvimento (Dev) e operações (Ops) para unir pessoas, processos e tecnologia no planejamento, desenvolvimento, entrega e operações de aplicativos. O DevOps permite a coordenação e a colaboração entre funções anteriormente isoladas, como desenvolvimento, operações de TI, engenharia de qualidade e segurança.

As equipes adotam a cultura, as práticas e as ferramentas de DevOps para aumentar a confiança nos aplicativos que criam, responder melhor às necessidades dos clientes e atingir as metas de negócios com mais rapidez. O DevOps ajuda as equipes a fornecer valor continuamente aos clientes, criando produtos melhores e mais confiáveis.



## DevOps e o ciclo de vida do aplicativo

O DevOps influencia o [ciclo de vida do aplicativo](https://en.wikipedia.org/wiki/Application_lifecycle_management) ao longo de todas fases de [planejamento](https://learn.microsoft.com/pt-br/devops/plan/planning-efficient-workloads-with-devops), [desenvolvimento](https://learn.microsoft.com/pt-br/devops/develop/developing-modern-software-with-devops), [entrega](https://learn.microsoft.com/pt-br/devops/deliver/delivering-quality-services-with-devops) e [operações](https://learn.microsoft.com/pt-br/devops/operate/operating-reliable-systems-with-devops). Cada fase depende das outras, e as fases não são específicas a uma função. Uma cultura de DevOps envolve todas as funções em cada fase até certo ponto.

O diagrama a seguir ilustra as fases do estilo de vida do aplicativo de DevOps:

![Conceptual diagram that illustrates the DevOps application lifecycle.](https://learn.microsoft.com/pt-br/devops/_img/devops-lifecycle.png)



## Metas e benefícios do DevOps

Quando uma equipe adota a cultura, as práticas e as ferramentas de DevOps, ela pode alcançar coisas incríveis:

![img](https://learn.microsoft.com/pt-br/devops/_img/benefits-accelerate-time-to-market.svg)

### Acelerar o tempo para colocação no mercado

Com a eficiência potencializada, colaboração aprimorada da equipe, ferramentas de automação e implantação contínua, as equipes conseguem reduzir rapidamente o tempo desde o início do produto até o lançamento no mercado.

![img](https://learn.microsoft.com/pt-br/devops/_img/benefits-adapt-to-market.svg)

### Adapte-se ao mercado e à concorrência

Uma cultura de DevOps exige que as equipes tenham um foco no cliente em primeiro lugar. Ao unir agilidade, colaboração em equipe e foco na experiência do cliente, as equipes podem entregar valor continuamente aos seus clientes e aumentar sua competitividade no mercado.

![img](https://learn.microsoft.com/pt-br/devops/_img/benefits-maintain-stability.svg)

### Mantenha a estabilidade e a confiabilidade do sistema

Ao adotar práticas de melhoria contínua, as equipes são capazes de aumentar a estabilidade e a confiabilidade dos produtos e serviços que implantam. Essas práticas ajudam a reduzir falhas e riscos.

![img](https://learn.microsoft.com/pt-br/devops/_img/benefits-improve-mean-time.svg)

### Melhore o tempo médio para recuperação

A *métrica de tempo médio para recuperação* indica quanto tempo é necessário para se recuperar de uma falha ou violação. Para gerenciar falhas de software, violações de segurança e planos de melhoria contínua, as equipes devem medir e trabalhar para melhorar essa métrica.



## Adote uma cultura de DevOps

Para implementar totalmente o DevOps, você deve adotar uma cultura de DevOps. Cultivar uma cultura de DevOps exige mudanças profundas na forma como as pessoas trabalham e colaboram umas com as outras. No entanto, quando se lançam a esse desafio, as organizações podem criar o ambiente ideal para a evolução de equipes de alto desempenho. Embora a adoção de práticas de DevOps automatize e otimize processos por meio da tecnologia, se não houver a mudança para uma cultura de DevOps dentro da organização e de suas pessoas, você não obterá todos os benefícios do DevOps.

A imagem a seguir captura os principais aspectos da [cultura de local ao vivo da Microsoft](https://learn.microsoft.com/pt-br/devops/operate/how-microsoft-operates-devops#live-site-culture).

![Diagram of Microsoft's live site culture.](https://learn.microsoft.com/pt-br/devops/_img/live-site-culture.png)

As práticas a seguir são componentes-chave de uma cultura de DevOps:

- **Colaboração, visibilidade e alinhamento**: uma marca registrada de uma cultura de DevOps saudável é a colaboração entre equipes. A colaboração começa com a visibilidade. As equipes de desenvolvimento, TI e outras devem compartilhar seus processos, prioridades e preocupações de DevOps umas com as outras. Ao planejar seu trabalho em conjunto, eles estão mais bem posicionados para se alinhar em metas e medidas de sucesso relacionadas ao negócio.
- **Alterações no escopo e contabilidade**: à medida que as equipes se alinham, elas assumem a propriedade e se envolvem em outras fases do ciclo de vida, não apenas naquelas que são essenciais para suas funções. Por exemplo, os desenvolvedores tornam-se responsáveis não apenas pela inovação e a qualidade estabelecidas na fase de desenvolvimento, mas também pelo desempenho e estabilidade que suas alterações trazem a software na fase de operação. Ao mesmo tempo, os operadores de TI certamente incluirão governança, segurança e conformidade na fase de planejamento e desenvolvimento.
- **Ciclos de lançamento mais curtos**: as equipes de DevOps se mantêm ágeis lançando versões de software em ciclos curtos. Ciclos de lançamento mais curtos facilitam o planejamento e o gerenciamento de riscos, pois o progresso é incremental, reduzindo também o impacto sobre a estabilidade do sistema. A redução do ciclo de lançamento também permite que as organizações se adaptem melhor e reajam de maneira mais ágil à evolução das necessidades dos clientes e à pressão da concorrência.
- **Aprendizagem contínua**: as equipes de alto desempenho de DevOps estabelecem uma mentalidade de crescimento. Elas falham rapidamente e incorporam os aprendizados em seus processos. Elas se esforçam para melhorar continuamente, aumentar a satisfação do cliente e acelerar a inovação e a adaptabilidade ao mercado.



## Implementar práticas de DevOps

Você implementa o DevOps seguindo as práticas de DevOps (descritas nas seções a seguir) durante todo o ciclo de vida do aplicativo. Algumas dessas práticas ajudam a acelerar, automatizar e melhorar uma fase específica. Outras abrangem várias fases, ajudando as equipes a criar processos contínuos que ajudam a melhorar a produtividade.



### CI/CD (integração contínua e entrega contínua)

A Integração Contínua (CI) é a prática usada pelas equipes de desenvolvimento para automatizar, mesclar e testar código. A CI ajuda a capturar bugs no início do ciclo de desenvolvimento, o que os torna mais baratos de corrigir. Os testes automatizados são executados como parte do processo de CI para garantir a qualidade. Os sistemas de CI produzem artefatos e os alimentam para liberar processos para impulsionar implantações frequentes.

A CD (entrega contínua) é um processo pelo qual o código é criado, testado e implantado em um ou mais ambientes de teste e produção. Implantar e testar em vários ambientes aumenta a qualidade. Os sistemas de CD produzem artefatos implantáveis, incluindo infraestrutura e aplicativos. Os processos de lançamento automatizados consomem esses artefatos para lançar novas versões e correções para os sistemas existentes. Os sistemas que monitoram e enviam alertas são executados continuamente para gerar visibilidade de todo o processo de CD.



### Controle de versão

O controle de versão é a prática de gerenciar código por meio de versões – acompanhando as revisões e o histórico de alterações para facilitar a revisão e a recuperação do código. Essa prática costuma ser implementada usando sistemas de controle de versão, como o Git, que permitem que vários desenvolvedores colaborem na criação do código. Esses sistemas fornecem um processo claro para mesclar alterações de código ocorridas no mesmo arquivo, gerenciar conflitos e reverter alterações para estados anteriores.

O uso do controle de versão é uma prática fundamental de DevOps que ajuda as equipes de desenvolvimento a trabalharem juntas, dividir as tarefas de codificação entre os membros da equipe e armazenar o código completo para fácil recuperação, se necessário. O controle de versão também é um elemento necessário em outras práticas, como a integração contínua e a infraestrutura como código.



### Desenvolvimento de software Agile

O Agile é uma abordagem de desenvolvimento de software que enfatiza a colaboração em equipe, os comentários do cliente e do usuário e a alta adaptabilidade para mudanças por meio de ciclos de lançamento curtos. As equipes que praticam o Agile fornecem mudanças e aprimoramentos contínuos aos clientes, coletam seus comentários e aprendem e se ajustam com base nos desejos e nas necessidades dos clientes. O Agile é substancialmente diferente de outras estruturas mais tradicionais, como a cascata, que inclui longos ciclos de versão definidos por fases sequenciais. O Kanban e o Scrum são duas estruturas populares associadas ao Agile.



### Infraestrutura como código

A infraestrutura como código define os recursos e as topologias do sistema de uma maneira descritiva que permite às equipes gerenciar esses recursos da maneira como codificariam. Essas definições também podem ser armazenadas e versionadas em sistemas de controle de versão, onde podem ser revisadas e revertidas – novamente como código.

A prática de infraestrutura como código ajuda as equipes a implantar os recursos do sistema de maneira confiável, repetível e controlada. A infraestrutura como código também ajuda a automatizar a implantação e reduz o risco de erro humano, especialmente para ambientes grandes e complexos. Essa solução confiável e repetível para a implantação de ambientes permite que as equipes mantenham ambientes de desenvolvimento e teste idênticos ao ambiente de produção. Da mesma maneira, a duplicação de ambientes para diferentes data centers e plataformas em nuvem também se torna mais simples e eficiente.



### Gerenciamento de configuração

O gerenciamento de configuração refere-se ao gerenciamento do estado dos recursos em um sistema, incluindo servidores, máquinas virtuais e bancos de dados. Usando ferramentas de gerenciamento de configuração, as equipes podem implementar alterações de maneira controlada e sistemática, reduzindo os riscos de modificar a configuração do sistema. As equipes usam ferramentas de gerenciamento de configuração para acompanhar o estado do sistema e ajudar a evitar desvios de configuração, já que é assim que a configuração de um recurso de sistema se desvia do estado desejado ao longo do tempo.

Juntamente com a infraestrutura como código, é fácil criar modelos e automatizar a definição e configuração do sistema, o que ajuda as equipes a operar ambientes complexos em escala.



### Monitoramento contínuo

O monitoramento contínuo significa ter visibilidade total e em tempo real do desempenho e da integridade de toda a pilha de aplicativos. Essa visibilidade varia desde a infraestrutura subjacente que executa o aplicativo até componentes de software de nível superior. A visibilidade é obtida por meio da coleta de telemetria e metadados e configuração de alertas para condições predefinidas que merecem atenção de um operador. A telemetria compreende dados de eventos e logs coletados de várias partes do sistema e armazenados em um local onde possam ser analisados e consultados.

As equipes de alto desempenho de DevOps garantem a definição de alertas acionáveis e significativos e a coleta de uma telemetria abundante para que seja possível extrair insights de grandes quantidades de dados. Esses insights ajudam a equipe a mitigar problemas em tempo real e a ver como melhorar o aplicativo em ciclos de desenvolvimento futuros.



## Planejamento

Na fase de planejamento, as equipes de DevOps idealizam, definem e descrevem os recursos e as funcionalidades dos aplicativos e sistemas que planejam construir. As equipes acompanham o progresso das tarefas em níveis baixos e altos de granularidade, desde produtos individuais até portfólios de vários produtos. As equipes usam as seguintes práticas de DevOps para planejar com [agilidade](https://learn.microsoft.com/pt-br/devops/plan/what-is-agile) e visibilidade:

- Crie listas de pendências.
- Acompanhe bugs.
- Gerencie o [desenvolvimento de software Agile](https://learn.microsoft.com/pt-br/devops/plan/what-is-agile-development) com [Scrum](https://learn.microsoft.com/pt-br/devops/plan/what-is-scrum).
- Use [quadros Kanban](https://learn.microsoft.com/pt-br/devops/plan/what-is-kanban).
- Visualize o progresso com painéis.

Para obter uma visão geral das diversas lições aprendidas e práticas adotadas pela Microsoft para dar suporte ao planejamento de DevOps nas equipes de software da empresa, consulte [Como a Microsoft faz planejamento com o DevOps](https://learn.microsoft.com/pt-br/devops/plan/how-microsoft-plans-devops).



## Desenvolvimento

A fase de desenvolvimento inclui todos os aspectos do desenvolvimento de código de software. Nesta fase, as equipes de DevOps executam as seguintes tarefas:

- [Selecionar um ambiente de desenvolvimento](https://learn.microsoft.com/pt-br/devops/develop/selecting-development-environment).
- Escrever, testar, revisar e integrar o código.
- Criar o código em artefatos para implantar em vários ambientes.
- Usar o [controle de versão](https://learn.microsoft.com/pt-br/devops/develop/git/what-is-version-control), geralmente [Git](https://learn.microsoft.com/pt-br/devops/develop/git/what-is-git), para colaborar no código e trabalhar paralelamente.

Para inovar rapidamente sem sacrificar a qualidade, a estabilidade e a produtividade, as equipes de DevOps:

- Usam ferramentas altamente produtivas.
- Automatizam etapas cotidianas e manuais.
- Iteram em pequenos incrementos por meio do [teste automatizado](https://learn.microsoft.com/pt-br/devops/develop/shift-left-make-testing-fast-reliable) e [integração contínua (CI)](https://learn.microsoft.com/pt-br/devops/develop/what-is-continuous-integration).

Para obter uma visão geral das práticas de desenvolvimento adotadas pela Microsoft para dar suporte à sua migração para o DevOps, consulte [Como a Microsoft desenvolve com o DevOps](https://learn.microsoft.com/pt-br/devops/develop/how-microsoft-develops-devops).



## Entregar

A entrega é o processo de implantação consistente e confiável de aplicativos em ambientes de produção, de preferência por meio de [entrega contínua (CD)](https://learn.microsoft.com/pt-br/devops/deliver/what-is-continuous-delivery).

Na fase de entrega, as equipes de DevOps:

- Definem um processo de gerenciamento de versões com etapas claras de aprovação manual.
- Defina portões automatizados para mover aplicativos entre estágios até a liberação final para os clientes.
- Automatize os processos de entrega para torná-los escaláveis, repetíveis, controlados e [bem testados](https://learn.microsoft.com/pt-br/devops/deliver/shift-right-test-production).

A entrega também inclui a implantação e a configuração da infraestrutura fundamental do ambiente de entrega. As equipes de DevOps usam tecnologias como [infraestrutura como código (IaC)](https://learn.microsoft.com/pt-br/devops/deliver/what-is-infrastructure-as-code), [contêineres](https://azure.microsoft.com/services/container-service) e [microsserviços](https://learn.microsoft.com/pt-br/devops/deliver/what-are-microservices) para fornecer ambientes de infraestrutura totalmente governados.

[As práticas de implantação segura](https://learn.microsoft.com/pt-br/devops/operate/safe-deployment-practices) podem identificar problemas antes que eles afetem a experiência do cliente. Essas práticas ajudam as equipes de DevOps a realizar entregas frequentes com facilidade, confiança e tranquilidade.

Os princípios e processos mais importantes de DevOps que a Microsoft evoluiu para fornecer sistemas de entrega eficientes são descritos em [Como a Microsoft fornece software com o DevOps](https://learn.microsoft.com/pt-br/devops/deliver/how-microsoft-delivers-devops).



## Operações

A fase de operações envolve manutenção, [monitoramento](https://learn.microsoft.com/pt-br/devops/operate/what-is-monitoring) e solução de problemas de aplicativos em ambientes de produção, incluindo nuvens híbridas ou públicas, como o [Azure](https://azure.microsoft.com/overview/what-is-azure). As equipes de DevOps visam a [confiabilidade do sistema](https://learn.microsoft.com/pt-br/devops/operate/operating-reliable-systems-with-devops), alta disponibilidade, [segurança forte](https://learn.microsoft.com/pt-br/devops/operate/security-in-devops) e [tempo de inatividade zero](https://learn.microsoft.com/pt-br/devops/operate/achieving-no-downtime-versioned-service-updates).

A entrega automatizada e as práticas de implantação segura ajudam as equipes a identificar e mitigar problemas rapidamente quando eles ocorrem. Manter esse nível de vigilância requer telemetria avançada, alertas acionáveis e visibilidade total sobre os aplicativos e o sistema subjacente.

As práticas que a Microsoft usa para operar plataformas online complexas são descritas em [Como a Microsoft opera sistemas confiáveis com o DevOps](https://learn.microsoft.com/pt-br/devops/operate/how-microsoft-operates-devops).



## Próximas etapas

- [Planejar cargas de trabalho eficientes com DevOps](https://learn.microsoft.com/pt-br/devops/plan/planning-efficient-workloads-with-devops)
- [Desenvolver software moderno com o DevOps](https://learn.microsoft.com/pt-br/devops/develop/developing-modern-software-with-devops)
- [Fornecer serviços de qualidade com o DevOps](https://learn.microsoft.com/pt-br/devops/deliver/delivering-quality-services-with-devops)
- [Operar sistemas confiáveis com DevOps](https://learn.microsoft.com/pt-br/devops/operate/operating-reliable-systems-with-devops)



### Outros recursos

- [Soluções de DevOps no Azure](https://azure.microsoft.com/solutions/devops/#overview)
- [O percurso de DevOps na Microsoft](https://azure.microsoft.com/solutions/devops/devops-at-microsoft/#devops-stories)
- [Comece a fazer DevOps com o Azure](https://azure.microsoft.com/free/devops/)
- [Segurança em DevOps (DevSecOps)](https://learn.microsoft.com/pt-br/devops/operate/security-in-devops)
- [O que é engenharia de plataforma?](https://learn.microsoft.com/pt-br/platform-engineering/what-is-platform-engineering)



### Treinamento e certificações

- [Introdução ao Azure DevOps](https://learn.microsoft.com/pt-br/training/paths/evolve-your-devops-practices/)
- [Introduza o DevOps Dojo: crie eficiências que dão suporte à sua empresa](https://learn.microsoft.com/pt-br/training/paths/devops-dojo-white-belt-foundation/)
- [AZ-400: Começar um percurso de transformação no DevOps](https://learn.microsoft.com/pt-br/training/paths/az-400-get-started-devops-transformation-journey/)
- [facilitar a comunicação e a colaboração](https://learn.microsoft.com/pt-br/training/paths/az-400-facilitate-communication-collaboration/)
- [Exame AZ-400: Designing and Implementing Microsoft DevOps Solutions](https://learn.microsoft.com/pt-br/certifications/exams/az-400?wt.mc_id=learningredirect_certs-web-wwl)
- [AZ-400: Implementar segurança e validar bases de código para conformidade](https://learn.microsoft.com/pt-br/training/paths/az-400-implement-security-validate-code-bases-compliance/)

------

## Comentários

Esta página foi útil?

YesNo

[Fornecer comentários sobre o produto](https://developercommunity.visualstudio.com/spaces/21/index.html)

------

## Recursos adicionais

Documentação

- [Planejar cargas de trabalho eficientes com DevOps - Azure DevOps](https://learn.microsoft.com/pt-br/devops/plan/planning-efficient-workloads-with-devops?source=recommendations)

  Saiba mais sobre a fase de planejamento do DevOps. Veja como usar uma abordagem Agile no desenvolvimento de software para que você possa se adaptar a novas necessidades.

- [Introdução ao desenvolvimento de software em DevOps - Azure DevOps](https://learn.microsoft.com/pt-br/devops/develop/developing-modern-software-with-devops?source=recommendations)

  Aprenda a aproveitar as principais ferramentas de DevOps, como o Git, para gerenciar com mais eficiência seu processo de desenvolvimento.

- [Vídeos e recursos do DevOps para eventos e palestras - Azure DevOps](https://learn.microsoft.com/pt-br/devops/events-and-talks/?source=recommendations)

  Assista a vídeos e apresentações relacionados a transformações, eventos e produtos do DevOps.

Mostrar mais 4

Treinamento

Roteiro de aprendizagem

[Fundamentos do DevOps: Os princípios e práticas fundamentais do AZ-2008 - Training](https://learn.microsoft.com/pt-br/training/paths/devops-foundations-core-principles-practices/?source=recommendations)

Explore as práticas de DevOps usando o GitHub. Suas equipes de desenvolvimento e operações experimentarão melhor colaboração, agilidade, integração contínua, entrega contínua, automação e excelência operacional em todas as fases do ciclo de vida do aplicativo. (AZ-2008)

Certificação

[Microsoft Certificado: DevOps Engineer Expert - Certifications](https://learn.microsoft.com/pt-br/credentials/certifications/devops-engineer/?source=recommendations)

Esta certificação mede sua capacidade de realizar as seguintes tarefas técnicas: Projetar e implementar processos e comunicações, projetar e implementar uma estratégia de controle do código-fonte, projetar e implementar pipelines de criação e liberação, desenvolver um plano de segurança e conformidade e implementar uma estratégia de instrumentação.

Neste artigo[DevOps e o ciclo de vida do aplicativo](https://learn.microsoft.com/pt-br/devops/what-is-devops#devops-and-the-application-lifecycle)[Metas e benefícios do DevOps](https://learn.microsoft.com/pt-br/devops/what-is-devops#devops-goals-and-benefits)[Adote uma cultura de DevOps](https://learn.microsoft.com/pt-br/devops/what-is-devops#adopt-a-devops-culture)[Implementar práticas de DevOps](https://learn.microsoft.com/pt-br/devops/what-is-devops#implement-devops-practices)[Planejamento](https://learn.microsoft.com/pt-br/devops/what-is-devops#planning)[Desenvolvimento](https://learn.microsoft.com/pt-br/devops/what-is-devops#development)[Entregar](https://learn.microsoft.com/pt-br/devops/what-is-devops#deliver)[Operações](https://learn.microsoft.com/pt-br/devops/what-is-devops#operations)[Próximas etapas](https://learn.microsoft.com/pt-br/devops/what-is-devops#next-steps)

[Português (Brasil)](https://learn.microsoft.com/pt-br/locale?target=https%3A%2F%2Flearn.microsoft.com%2Fpt-br%2Fdevops%2Fwhat-is-devops)

[Suas opções de privacidade](https://aka.ms/yourcaliforniaprivacychoices)



[Learn](https://learn.microsoft.com/pt-br/)

DescobrirDocumentação do produtoLinguagens de desenvolvimentoTópicos

[Entrar](https://learn.microsoft.com/pt-br/devops/what-is-devops#)

[DevOps](https://learn.microsoft.com/pt-br/devops/)[Plano](https://learn.microsoft.com/pt-br/devops/plan/planning-efficient-workloads-with-devops/)[Desenvolver](https://learn.microsoft.com/pt-br/devops/develop/developing-modern-software-with-devops/)[Fornecimento](https://learn.microsoft.com/pt-br/devops/deliver/delivering-quality-services-with-devops/)[Operar](https://learn.microsoft.com/pt-br/devops/operate/operating-reliable-systems-with-devops/)[DevSecOps](https://learn.microsoft.com/pt-br/devops/operate/security-in-devops/)Ferramentas e recursos de DevOps

Pesquisar

- [Documentação do DevOps](https://learn.microsoft.com/pt-br/devops/overview/)
- [O que é DevOps?](https://learn.microsoft.com/pt-br/devops/what-is-devops)
- Planejar cargas de trabalho eficientes
- Desenvolver software moderno
- Fornecer serviços de qualidade
- Operar sistemas confiáveis
- DevSecOps
- [Eventos e conversas](https://learn.microsoft.com/pt-br/devops/events-and-talks/)

Baixar PDF

[Learn](https://learn.microsoft.com/pt-br/) [DevOps](https://learn.microsoft.com/pt-br/devops/) 

