#DevOps

## Perguntas

### Em geral

<details>
<summary>O que é DevOps?</summary><br><b>

A definição de DevOps de empresas selecionadas:

**Amazonas**:

"DevOps é a combinação de filosofias culturais, práticas e ferramentas que aumentam a capacidade de uma organização de fornecer aplicativos e serviços em alta velocidade: evoluindo e melhorando produtos em um ritmo mais rápido do que as organizações que usam processos tradicionais de desenvolvimento de software e gerenciamento de infraestrutura. Essa velocidade permite que as organizações para melhor atender seus clientes e competir de forma mais eficaz no mercado."

**Microsoft**:

"DevOps é a união de pessoas, processos e produtos para permitir a entrega contínua de valor aos nossos usuários finais. A contração de "Dev" e "Ops" refere-se à substituição de Desenvolvimento e Operações em silos para criar equipes multidisciplinares que agora trabalham em conjunto com e práticas e ferramentas eficientes. As práticas essenciais de DevOps incluem planejamento ágil, integração contínua, entrega contínua e monitoramento de aplicativos."

**Chapéu vermelho**:

"DevOps descreve abordagens para acelerar os processos pelos quais uma ideia (como um novo recurso de software, uma solicitação de aprimoramento ou uma correção de bug) passa do desenvolvimento para a implantação em um ambiente de produção onde pode agregar valor ao usuário. Essas abordagens exigem que as equipes de desenvolvimento e operações se comuniquem com frequência e abordem seu trabalho com empatia pelos colegas de equipe. Escalabilidade e provisionamento flexível também são necessários. Com o DevOps, aqueles que mais precisam de energia, obtêm-no por meio de autoatendimento e automação. Desenvolvedores, geralmente codificando em um ambiente de desenvolvimento padrão, trabalhe em estreita colaboração com as operações de TI para acelerar compilações, testes e lançamentos de software, sem sacrificar a confiabilidade."

**Google**:

"...O movimento organizacional e cultural que visa aumentar a velocidade de entrega de software, melhorar a confiabilidade do serviço e construir propriedade compartilhada entre as partes interessadas do software"
</b></details>

<details>
<resumo>Quais são os benefícios do DevOps? O que isso pode nos ajudar a alcançar?</summary><br><b>

  * Colaboração
  * Entrega melhorada
  * Segurança
  * Velocidade
  * Escala
  * Confiabilidade
</b></details>

<details>
<Summary>Quais são os antipadrões do DevOps?</summary><br><b>

Alguns exemplos:

* Uma pessoa é responsável por tarefas específicas. Por exemplo, há apenas uma pessoa que tem permissão para mesclar o código de todos os outros no repositório.
* Tratar a produção de forma diferente do ambiente de desenvolvimento. Por exemplo, não implementar a segurança no ambiente de desenvolvimento
* Não permitir que alguém avance para a produção na sexta-feira ;)
</b></detalhes>

<detalhes>
<summary>Como você descreveria um engenheiro de DevOps bem-sucedido ou uma equipe?</summary><br><b>

A resposta pode se concentrar em:

* Colaboração
* Comunicação
* Configurar e melhorar fluxos de trabalho e processos (relacionados a testes, entrega, ...)
* Lidar com problemas

Coisas para pensar:

* Em que equipes ou engenheiros de DevOps NÃO devem se concentrar ou fazer?
* As equipes ou engenheiros de DevOps precisam ser inovadores ou praticar a inovação como parte de sua função?
</b></detalhes>

<detalhes>
<resumo>Um dos membros de sua equipe sugere definir uma meta de "implantar pelo menos 20 vezes por dia" em relação ao CD. Qual é a sua opinião sobre isso?</summary><br><b>

Um par de pensamentos:

1. Por que é um objetivo importante? Isso está afetando o negócio de alguma forma? Um dos KPIs? Em outras palavras, isso importa?
2. Isso pode introduzir riscos, como perder qualidade em favor da quantidade
3. Você pode querer definir uma meta possivelmente melhor, como "ser capaz de implantar sempre que precisarmos implantar"
</b></detalhes>

### Ferramentas

<details>
<summary>O que você leva em consideração ao escolher uma ferramenta/tecnologia?</summary><br><b>

Algumas ideias para pensar:

  * maduro/estável vs. de ponta
  * tamanho da comunidade
  * aspectos de arquitetura - agente vs. sem agente, mestre vs. sem mestre, etc.
  * curva de aprendizado
</b></details>

<details>
<resumo>Você pode descrever qual ferramenta ou plataforma você escolheu usar em algumas das seguintes áreas e como?

  * CI/CD
  * Infraestrutura de provisionamento
  * Gerenciamento de configurações
  * Monitoramento e alerta
  * Exploração madeireira
  * Revisão de código
  * Cobertura de código
  * Acompanhamento de problemas
  * Containers e Orquestração de Containers
  * Testes</summary><br><b>

Esta é uma versão mais prática da pergunta anterior, onde você pode fazer perguntas específicas adicionais sobre a tecnologia que você escolheu

  * CI/CD - Jenkins, Circle CI, Travis, Drone, Argo CD, Zuul
  * Infraestrutura de provisionamento - Terraform, CloudFormation
  * Gerenciamento de configuração - Ansible, Puppet, Chef
  * Monitoramento e alertas - Prometheus, Nagios
  * Logging - Logstash, Graylog, Fluentd
  * Revisão do código - Gerrit, Conselho de Revisão
  * Cobertura de código - Cobertura, Clover, JaCoCo
  * Rastreamento de problemas - Jira, Bugzilla
  * Orquestração de Containers e Containers - Docker, Podman, Kubernetes, Nomad
  * Testes - Robot, Serenity, Gauge
</b></details>

<details>
<summary>Um membro de sua equipe sugere substituir a plataforma CI/CD atual usada pela organização por uma nova. Como você responderia?</summary><br><b>

Coisas para pensar:

* O que ganhamos com isso? Existem novos recursos na nova plataforma? A nova plataforma lida com algumas das limitações apresentadas na plataforma atual?
* Em que se baseia esta sugestão? Em outras palavras, ele/ela experimentou a nova plataforma? Houve extensa pesquisa técnica?
* O que a mudança de uma plataforma para outra exigirá da organização? Por exemplo, treinar usuários que usam a plataforma? Quanto tempo a equipe tem para investir nessa mudança?
</b></details>
### Controle de versão

<details>
<summary>O que é controle de versão?</summary><br><b>

* O controle de versão é o sistema de rastreamento e gerenciamento de alterações no código do software.
* Ajuda as equipes de software a gerenciar alterações no código-fonte ao longo do tempo.
* O controle de versão também ajuda os desenvolvedores a se moverem mais rapidamente e permite que as equipes de software preservem a eficiência e a agilidade à medida que a equipe é dimensionada para incluir mais desenvolvedores.
</b></details>

<details>
<summary>O que é um commit?</summary><br><b>

* No Git, um commit é um instantâneo do seu repositório em um momento específico.
* O comando git commit salvará todas as alterações preparadas, juntamente com uma breve descrição do usuário, em um “commit” para o repositório local.
</b></details>

<details>
<summary>O que é uma mesclagem?</summary><br><b>

* Mesclar é a maneira do Git de reunir um histórico bifurcado novamente. O comando git merge permite que você pegue as linhas independentes de desenvolvimento criadas pelo git branch e integre-as em um único branch.
</b></details>

<detalhes>
<summary>O que é um conflito de mesclagem?</summary><br><b>

* Um conflito de mesclagem é um evento que ocorre quando o Git não consegue resolver automaticamente as diferenças no código entre dois commits. Quando todas as mudanças no código ocorrem em linhas diferentes ou em arquivos diferentes, o Git irá mesclar commits com sucesso sem sua ajuda.
</b></details>

<details>
<summary>Quais práticas recomendadas você conhece em relação ao controle de versão?</summary><br><b>
	
* Use uma mensagem de confirmação descritiva
* Faça de cada commit uma unidade lógica
* Incorpore as mudanças dos outros com frequência
* Compartilhe suas alterações com frequência
* Coordenar com seus colegas de trabalho
* Não comite arquivos gerados
</b></details>

<details>
<summary>Você prefere um modelo de "configuração->implantação" ou "implantação->configuração"? Por quê?</summary><br><b>

Ambos têm vantagens e desvantagens.
Com o modelo "configuração->implantação", por exemplo, onde você cria uma imagem para ser usada por várias implantações, há menos chance de as implantações serem diferentes umas das outras, portanto, há uma clara vantagem de um ambiente consistente.
</b></details>

<details>
<summary>Explicar infraestrutura mutável x imutável</summary><br><b>

No paradigma de infraestrutura mutável, as mudanças são aplicadas na infraestrutura existente e ao longo do tempo
a infraestrutura constrói um histórico de mudanças. Ansible, Puppet e Chef são exemplos de ferramentas que
seguir o paradigma de infraestrutura mutável.

No paradigma de infraestrutura imutável, cada mudança é, na verdade, uma nova infraestrutura. Então uma mudança
para um servidor resultará em um novo servidor em vez de atualizá-lo. Terraform é um exemplo de tecnologia
que segue o paradigma da infraestrutura imutável.
</b></details>

### Distribuição de Software

<details>
<summary>Explicar "Distribuição de software"</summary><br><b>

Leia [este](https://venam.nixers.net/blog/unix/2020/03/29/distro-pkgs.html) artigo fantástico sobre o assunto.

Do artigo: "Assim, a distribuição de software é sobre o mecanismo e a comunidade que assume o fardo e as decisões para construir um conjunto de software coerente que pode ser distribuído."
</b></details>

<detalhes>
<resumo>Por que existem várias distribuições de software? Que diferenças eles podem ter?</summary><br><b>

Diferentes distribuições podem focar em coisas diferentes como: focar em ambientes diferentes (servidor vs. móvel vs. desktop), suportar hardware específico, especializar-se em diferentes domínios (segurança, multimídia, ...), etc. Basicamente, diferentes aspectos do software e o que ele suporta, obtêm prioridade diferente em cada distribuição.
</b></details>

<details>
<summary>O que é um repositório de software?</summary><br><b>

Wikipedia: "Um repositório de software, ou "repo" para abreviar, é um local de armazenamento para pacotes de software. Muitas vezes, um índice é armazenado, assim como metadados."

Leia mais [aqui](https://en.wikipedia.org/wiki/Software_repository)
</b></details>

<details>
<resumo>Quais são as formas de distribuir software? Quais são as vantagens e desvantagens de cada método?</summary><br><b>

  * Source - Mantenha o script de compilação dentro do sistema de controle de versão para que o usuário possa compilar seu aplicativo após a clonagem do repositório. Vantagem: O usuário pode verificar rapidamente diferentes versões do aplicativo. Desvantagem: requer ferramentas de compilação instaladas na máquina do usuário.
  * Arquivo - colete todos os arquivos do seu aplicativo em um arquivo (por exemplo, tar) e entregue-o ao usuário. Vantagem: O usuário obtém tudo o que precisa em um arquivo. Desvantagem: Requer repetir o mesmo procedimento ao atualizar, não é bom se houver muitas dependências.
  * Pacote - depende do sistema operacional, você pode usar o formato do pacote do sistema operacional (por exemplo, em RHEL/Fefodra é RPM) para entregar seu software com uma maneira de instalar, desinstalar e atualizá-lo usando os comandos padrão do empacotador. Vantagens: O gerenciador de pacotes cuida do suporte para instalação, desinstalação, atualização e gerenciamento de dependências. Desvantagem: Requer o gerenciamento do repositório de pacotes.
  * Imagens - Imagens de VM ou contêiner em que seu pacote está incluído com tudo o que precisa para ser executado com sucesso. Vantagem: tudo é pré-instalado, possui alto grau de isolamento do ambiente. Desvantagem: Requer conhecimento de construção e otimização de imagens.
</b></details>

<details>
<resumo>Você conhece os modelos "A Catedral e o Bazar"? Explique cada um dos modelos</summary><br><b>

* Cathedral - código-fonte lançado quando o software é lançado
* Bazaar - o código-fonte está sempre disponível publicamente (por exemplo, Linux Kernel)
</b></details>

<detalhes>
<resumo>O que é cache? Como funciona? Por que é importante?</summary><br><b>

O cache é o acesso rápido a recursos usados ​​com frequência que são computacionalmente caros ou intensivos em E/S e não mudam com frequência. Pode haver várias camadas de cache que podem começar de caches de CPU para sistemas de cache distribuídos. Os mais comuns estão no cache de memória e no cache distribuído. <br/> Caches são tipicamente estruturas de dados que contêm alguns dados, como uma tabela de hash ou um dicionário. No entanto, qualquer estrutura de dados pode fornecer recursos de cache, como conjunto, conjunto classificado, dicionário classificado, etc. Embora o cache seja usado em muitos aplicativos, eles podem criar bugs sutis se não forem implementados corretamente ou usados ​​corretamente. Por exemplo, a invalidação, expiração ou atualização de cache geralmente é bastante desafiadora e difícil.
</b></detalhes>

<details>
<summary>Explain stateless vs. stateful</summary><br><b>

Stateless applications don't store any data in the host which makes it ideal for horizontal scaling and microservices.
Stateful applications depend on the storage to save state and data, typically databases are stateful applications.
</b></details>

<details>
<summary>What is Reliability? How does it fit DevOps?</summary><br><b>

Reliability, when used in DevOps context, is the ability of a system to recover from infrastructure failure or disruption. Part of it is also being able to scale based on your organization or team demands.
</b></details>

<details>
<summary>What does "Availability" mean? What means are there to track Availability of a service?</summary><br><b>
</b></details>

<details>
<summary>Why isn't 100% availability a target? Why do most companies or teams set it to be 99%.X?</summary><br><b>
</b></details>

<details>
<summary>Describe the workflow of setting up some type of web server (Apache, IIS, Tomcat, ...)</summary><br><b>
</b></details>

<details>
<summary>How does a web server work?</summary><br><b>
<a href="https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_web_server" title="Click here to redirect to MDN official page" style="background-color:#FFFFFF;color:#000000;text-decoration:none">According to MDN Web Docs -</a>
	
We can understand web servers using two view points, which is:
	
	(i) Hardware (ii) Software

(i)   A web server is nothing but a remote computer which stores website's component files(HTML,CSS and Javascript files) and web server's software.A web server connects to
      the Internet and supports physical data interchange with other devices connected to the web.
	
(ii)  On the software side, a web server includes several parts that control how web users access hosted files. At a minimum, this is an HTTP server. An HTTP server is software       that understands URLs (web addresses) and HTTP (the protocol your browser uses to view webpages). An HTTP server can be accessed through the domain names of the websites         it stores, and it delivers the content of these hosted websites to the end user's device.
	
## How communication between web server and web browsers established:
	
 Whenever a browser needs a file that is hosted on a web server, the browser requests the page from the web server and the web server responds with that page.
This communcation between web browser and web server happens in the following ways:

(1) User enters the domain name in the browser,and the browser then search for the IP address of the entered name. It can be done in 2 ways- 
	
    -By searching in its cache. 
    -By requesting one or more DNS (Domain Name System) Servers.

(2) After knowing the IP Address, the browser requests the file via HTTP and the request reaches the correct (hardware) web server.

(3) The (software) HTTP server accepts the request, finds the requested document, and sends it back to the browser, also through HTTP. (If the server doesn't find the requested document, it returns a 404 response instead.)

(4) The Browser finally gets the webpages and displays it, or displays the error message.

</b></details>

<details>
<summary>Explain "Open Source"</summary><br><b>
</b></details>

<details>
<summary>Describe the architecture of service/app/project/... you designed and/or implemented</summary><br><b>
</b></details>

<details>
<summary>What types of tests are you familiar with?</summary><br><b>

Styling, unit, functional, API, integration, smoke, scenario, ...

You should be able to explain those that you mention.
</b></details>

<details>
<summary>You need to install periodically a package (unless it's already exists) on different operating systems (Ubuntu, RHEL, ...). How would you do it?</summary><br><b>

There are multiple ways to answer this question (there is no right and wrong here):

* Simple cron job
* Pipeline with configuration management technology (such Puppet, Ansible, Chef, etc.)
...
</b></details>

<details>
<summary>What is Chaos Engineering?</summary><br><b>

Wikipedia: "Chaos engineering is the discipline of experimenting on a software system in production in order to build confidence in the system's capability to withstand turbulent and unexpected conditions"

Read about Chaos Engineering [here](https://en.wikipedia.org/wiki/Chaos_engineering)
</b></details>

<details>
<summary>What is "infrastructure as code"? What implementation of IAC are you familiar with?</summary><br><b>

IAC (infrastructure as code) is a declarative approach of defining infrastructure or architecture of a system. Some implementations are ARM templates for Azure and Terraform that can work across multiple cloud providers.
</b></details>

<details>
<summary>What benefits does infrastructure-as-code have?</summary><br><b>

- fully automated process of provisioning, modifying and deleting your infrastructure
- version control for your infrastructure which allows you to quickly rollback to previous versions
- validate infrastructure quality and stability with automated tests and code reviews
- makes infrastructure tasks less repetitive
</b></details>

<details>
<summary>How do you manage build artifacts?</summary><br><b>

Build artifacts are usually stored in a repository. They can be used in release pipelines for deployment purposes. Usually there is retention period on the build artifacts.
</b></details>

<details>
<summary>What Continuous Integration solution are you using/prefer and why?</summary><br><b>
</b></details>

<details>
<summary>What deployment strategies are you familiar with or have used?</summary><br><b>

	There are several deployment strategies:
	* Rolling
	* Blue green deployment
	* Canary releases
	* Recreate strategy

</b></details>

<details>
<summary>You joined a team where everyone developing one project and the practice is to run tests locally on their workstation and push it to the repository if the tests passed. What is the problem with the process as it is now and how to improve it?</summary><br><b>
</b></details>

<details>
<summary>Explain test-driven development (TDD)</summary><br><b>
</b></details>

<details>
<summary>Explain agile software development</summary><br><b>
</b></details>

<details>
<summary>What do you think about the following sentence?: "Implementing or practicing DevOps leads to more secure software"</summary><br><b>
</b></details>

<details>
<summary>Do you know what is a "post-mortem meeting"? What is your opinion on that?</summary><br><b>
</b></details>

<details>
<summary>What is a configuration drift? What problems is it causing?</summary><br><b>

Configuration drift happens when in an environment of servers with the exact same configuration and software, a certain server
or servers are being applied with updates or configuration which other servers don't get and over time these servers become
slightly different than all others.

This situation might lead to bugs which hard to identify and reproduce.
</b></details>

<details>
<summary>How to deal with a configuration drift?</summary><br><b>
	Configuration drift can be avoided with desired state configuration (DSC) implementation. Desired state configuration can be a declarative file that defined how a system should be. There are tools to enforce desired state such a terraform or azure dsc. There are incremental or complete strategies.
</b></details>

<details>
<summary>Explain Declarative and Procedural styles. The technologies you are familiar with (or using) are using procedural or declarative style?</summary><br><b>

Declarative - You write code that specifies the desired end state
Procedural - You describe the steps to get to the desired end state

Declarative Tools - Terraform, Puppet, CloudFormation
Procedural Tools - Ansible, Chef

To better emphasize the difference, consider creating two virtual instances/servers.
In declarative style, you would specify two servers and the tool will figure out how to reach that state.
In procedural style, you need to specify the steps to reach the end state of two instances/servers - for example, create a loop and in each iteration of the loop create one instance (running the loop twice of course).
</b></details>

<details>
<summary>Do you have experience with testing cross-projects changes? (aka cross-dependency)</summary><br><b>

Note: cross-dependency is when you have two or more changes to separate projects and you would like to test them in mutual build instead of testing each change separately.
</b></details>

<details>
<summary>Have you contributed to an open source project? Tell me about this experience</summary><br><b>
</b></details>

<details>
<summary>What is Distributed Tracing?</summary><br><b>
</b></details>

### GitOps

<details>
<summary>What is GitOps?</summary><br><b>

GitLab: "GitOps is an operational framework that takes DevOps best practices used for application development such as version control, collaboration, compliance, and CI/CD tooling, and applies them to infrastructure automation".

Read more [here](https://about.gitlab.com/topics/gitops)
</b></details>

<details>
<summary>What are some of the advantages of applying GitOps?</summary><br><b>

* It introduces limited/granular access to infrastructure
* It makes it easier to trace who makes changes to infrastructure

</b></details>

<details>
<summary>When a repository refereed to as "GitOps Repository" what does it means?</summary><br><b>

A repository that doesn't holds the application source code, but the configuration, infra, ... files that required to test and deploy the application.
</b></details>

<details>
<summary>What are some practical implementations or practices of GitOp?</summary><br><b>

* Store Infra files in a version control repository (like Git)
* Apply review/approval process for changes
</b></details>

<details>
<summary>Two engineers in your team argue on where to put the configuration and infra related files of a certain application. One of them suggests to put it in the same repo as the application repository and the other one suggests to put to put it in its own separate repository. What's your take on that?</summary><br><b>

One might say we need more details as to what these configuration and infra files look like exactly and how complex the application and its CI/CD pipeline(s), but in general, most of the time you will want to put configuration and infra related files in their own separate repository and not in the repository of the application for multiple reasons:

* Every change submitted to the configuration, shouldn't trigger the CI/CD of the application, it should be testing out and applying the modified configuration, not the application itself
* When you mix application code with conifguration and infra related files
</b></details>

#### SRE

<details>
<summary>What are the differences between SRE and DevOps?</summary><br><b>

Google: "One could view DevOps as a generalization of several core SRE principles to a wider range of organizations, management structures, and personnel."

Read more about it [here](https://sre.google/sre-book/introduction)
</b></details>

<details>
<summary>What SRE team is responsible for?</summary><br><b>

Google: "the SRE team is responsible for availability, latency, performance, efficiency, change management, monitoring, emergency response, and capacity planning of their services"

Read more about it [here](https://sre.google/sre-book/introduction)
</b></details>

<details>
<summary>What is an error budget?</summary><br><b>

Atlassian: "An error budget is the maximum amount of time that a technical system can fail without contractual consequences."

Read more about it [here](https://www.atlassian.com/incident-management/kpis/error-budget)
</b></details>

<details>
<summary>What do you think about the following statement: "100% is the only right availability target for a system"</summary><br><b>

Wrong. No system can guarantee 100% availability as no system is safe from experiencing zero downtime.
Many systems and services will fall somewhere between 99% and 100% uptime (or at least this is how most systems and services should be).
</b></details>

<details>
<summary>What are MTTF (mean time to failure) and MTTR (mean time to repair)? What these metrics help us to evaluate?</summary><br><b>

	* MTTF (mean time to failure) other known as uptime, can be defined as how long the system runs before if fails.
	* MTTR (mean time to recover) on the other hand, is the amount of time it takes to repair a broken system.
	* MTBF (mean time between failures) is the amount of time between failures of the system.
</b></details>

<details>
<summary>What is the role of monitoring in SRE?</summary><br><b>

Google: "Monitoring is one of the primary means by which service owners keep track of a system’s health and availability"

Read more about it [here](https://sre.google/sre-book/introduction)
</b></details>
