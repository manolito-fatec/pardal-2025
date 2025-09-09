
<h1 align="center"> Pardal</h1>
<h3 align="center">Repositório dedicado ao versionamento do projeto API do 6º semestre de Banco de Dados.</h3>

---

## 🎯 Objetivo do Projeto
> [!IMPORTANT]
> O objetivo do projeto é centralizar e otimizar a gestão dos chamados de suporte, garantindo maior organização, agilidade no atendimento e visibilidade para todos os níveis da operação. Atualmente, o cliente enfrenta dificuldades no controle manual dos chamados utilizando um banco de dados legado, falta de histórico consolidado e ausência de indicadores que apoiem decisões estratégicas. Com essa solução, será possível melhorar a comunicação entre as equipes, reduzir o tempo de resolução, identificar pontos de melhoria nos processos, garantir conformidade com a LGPD no tratamento dos dados e elevar a qualidade do atendimento ao cliente final, tornando o processo mais eficiente, seguro e transparente.
 
---

# 🔍 Tópicos
- <a href="#documentacoes">📚 Documentações</a>
- <a href="#tecnologias">🔌 Tecnologias</a>
- <a href="#requisitos">📋 Requisitos</a>
- <a href="#backlog">📈 Product Backlog</a>
- <a href="#sprint-backlog">🔄 Sprint Backlog</a>
- <a href="#membros">👥 Membros</a>

---

## 📚 Documentações <a id="documentacoes"></a>

> [!NOTE]
> Documentações e guias do projeto:

- Banco de Dados (Em breve)
- [Padrão de Projeto](https://github.com/manolito-fatec/pardal-2025/wiki/Padr%C3%A3o-de-Projeto)
- Documentação de Produto (Em breve)
- Manual do Usuário (Em breve)

---

## 🔌Tecnologias <a id="tecnologias"></a>
> [!NOTE]
> Tecnologias utilizadas no desenvolvimento do projeto:

<h3>BackEnd</h3>
<h4 align="left">
<a href="https://www.java.com/pt-BR/" target="_blank"><img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"></a>
<a href="https://spring.io/projects/spring-boot" target="_blank"><img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot"></a>
<a href="https://spring.io/projects/spring-security" target="_blank"><img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Spring Security"></a>
<a href="https://spring.io/projects/spring-web" target="_blank"><img src="https://img.shields.io/badge/Spring%20Web-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Spring Web"></a>
<a href="https://swagger.io/" target="_blank"><img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=white" alt="Swagger"></a>
<a href="https://jwt.io/" target="_blank"><img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" alt="JWT"></a>
<a href="https://junit.org/" target="_blank"><img src="https://img.shields.io/badge/JUnit-25A162?style=for-the-badge&logo=junit5&logoColor=white" alt="JUnit"></a>
<a href="https://www.python.org/" target="_blank"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"></a>
<a href="https://www.mongodb.com/" target="_blank"><img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"></a>
</h4>
<h3>FrontEnd</h3>
<h4 align="left">
<a href="https://devdocs.io/html/" target="_blank"><img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=FFFFFF" alt="HTML5"></a>
<a href="https://developer.mozilla.org/en-US/docs/Web/CSS" target="_blank"><img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=FFFFFF" alt="CSS3"></a>
<a href="https://www.typescriptlang.org/docs/handbook/2/objects.html" target="_blank"><img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=FFFFFF" alt="TypeScript"></a>
<a href="https://vuejs.org/" target="_blank"><img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue.js"></a>
<a href="https://www.primefaces.org/primevue/" target="_blank"><img src="https://img.shields.io/badge/PrimeVue-4CAF50?style=for-the-badge&logo=vue.js&logoColor=white" alt="PrimeVue"></a>
<a href="https://axios-http.com/" target="_blank"><img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white" alt="Axios"></a>
<a href="https://vitest.dev/" target="_blank"><img src="https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white" alt="Vitest"></a>
<a href="https://redis.io/" target="_blank"><img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"></a>
</h4>

---

<br>

## 📋 Requisitos <a id="requisitos"></a>

### 📌 Requisitos Não Funcionais (RNF)
| **ID** | **Título** |
| :----: | :--------- |
| RNF1   | Documentação API – Application Programming Interface |
| RNF2   | Manual do Usuário |
| RNF3   | Modelagem do Banco de Dados |
| RNF4   | Uso de Banco de Dados Não Relacional |
| RNF5   | Implementação da LGPD |

---

### 📌 Requisitos Funcionais (Épicos) (RF)
| **ID** | **Título** | **Título** | **Título** |
| :----: | :--------- | :--------- | :--------- |
| RF1    | Administrador | Modernização LGPD | O sistema deverá garantir que dados pessoais e dados sensíveis inseridos em campos de texto livre (título, descrição e comentários dos chamados) sejam automaticamente identificados e anonimizados antes de serem persistidos no banco de dados. Para isso, deverá utilizar expressões regulares (Regex) para dados estruturados (CPF, e-mail, telefone) e integração com serviço de NLP para análise semântica de informações sensíveis (saúde, religião, opinião política, etc.). O objetivo é assegurar a conformidade contínua com a LGPD e evitar o armazenamento indevido de dados. |
| RF2    | Gestor | Insights | O sistema deverá fornecer um componente de análise que apresente insights automáticos sobre os chamados, identificando padrões de reincidência, categorias mais críticas e cumprimento de SLA. Esse recurso terá como objetivo apoiar a tomada de decisão estratégica e aumentar a eficiência no atendimento. |
| RF3    | Gestor | Dashboards | O sistema deverá apresentar ao gestor um dashboard interativo com indicadores de desempenho (KPIs), incluindo total de tickets criados, tempo médio de resolução, taxa de reincidência e conformidade com SLA. O dashboard deverá permitir a aplicação de filtros por período, agente, empresa, categoria e prioridade, possibilitando uma visão detalhada e comparativa da operação. |
| RF4    | Administrador | Administração de Usuários | O sistema deverá disponibilizar uma interface administrativa que permita ao administrador gerenciar usuários (criação, edição, desativação e atribuição de papéis/perfis). Esse recurso terá como objetivo garantir o controle de acesso adequado, assegurando que cada usuário visualize e interaja apenas com as informações que são de sua responsabilidade. |
| RF5    | Operador | Pesquisa de Chamados | O sistema deverá disponibilizar ao operador autenticado um mecanismo de pesquisa avançada de chamados, permitindo a aplicação de filtros por status, categoria, agente, empresa, prioridade e intervalo de datas. O objetivo é facilitar a localização rápida de chamados específicos e otimizar a produtividade do atendimento. |

---

<br>

## 📈 Product Backlog <a id="backlog"></a>

|🗃️ Id| 🏅 Rank| 🔥 Prioridade| 📝 User Story| 🚀 Sprint| 🎯 Requisito do Parceiro|
|:--------:|:--------:|:--------:|:--------|:--------:|:--------|
|US01|1|Alta|Eu, como operador, desejo visualizar a quantidade de cards atribuídos a mim e filtrar os cards dos meus projetos com base no período de criação e finalização, para acompanhar meu progresso e gerenciar melhor minhas tarefas.|1|RF1,RNF1,RNF2,RNF5|
|US02|2|Alta|Eu, como operador, desejo visualizar todos os cards com base em seu status para acompanhar o andamento das tarefas nos projetos.|1|RF1,RNF1,RNF2,RNF5|
|US03|3|Alta|Eu, como operador, desejo visualizar o tempo médio de conclusão dos cards finalizados e a quantidade de projetos em que estou participando para acompanhar meu desempenho e a eficiência na conclusão das tarefas.|2|RF2,RNF1,RNF2,RNF5|
|US04|4|Alta|Eu, como gestor, desejo visualizar a quantidade de cards atribuídos a cada operador sob minha gestão, assim como os cards designados a mim, para monitorar a distribuição de tarefas e gerenciar melhor a equipe.|2|RF2,RNF1,RNF2,RNF5|
|US05|5|Alta|Eu, como gestor, desejo filtrar os cards dos projetos que gerencio e que estão atribuídos a mim, considerando um período específico, para acompanhar a evolução das tarefas e a finalização das atividades.|2|RF2,RNF1,RNF2,RNF5|
|US06|6|Alta|Eu, como gestor, desejo visualizar todos os cards dos operadores que gerencio, filtrando-os com base em seu status, para monitorar o andamento das tarefas e a progressão dos projetos.|3|RF2,RNF1,RNF2,RNF5|
|US07|7|Alta|Eu, como gestor, desejo visualizar informações por meio de indicadores que destaquem o tempo médio de conclusão dos cards finalizados pela equipe. Quero acompanhar o tempo médio que cada operador da equipe leva para finalizar uma tarefa, para avaliar a produtividade individual e coletiva.|2|RF2,RNF1,RNF2,RNF5|
|US08|8|Alta|Eu, como gestor, desejo visualizar informações sobre retrabalhos e também obter detalhes sobre as issues dos projetos, incluindo a quantidade total, tipo, gravidade e prioridade, para analisar a eficiência da equipe e priorizar as ações corretivas de forma adequada.|1|RF3,RNF1,RNF2,RNF5|
|US09|9|Alta|Eu,como gestor de projetos, quero visualizar o total de cards organizados por tags, para poder analisar rapidamente a distribuição das tarefas e acompanhar o progresso de cada área do projeto de forma mais eficiente.|3|RF3,RNF1,RNF2,RNF5|
|US10|10|Média|Eu, como operador, gestor ou admin, desejo fazer autenticação na aplicação para acessar meus indicadores, para monitorar o desempenho e os dados relevantes.|3|RF4,RNF1,RNF2,RNF5|
|US11|11|Média|Eu, como admin, desejo realizar o cadastro de novos usuários, sendo obrigatório associar ao menos uma ferramenta de gestão de projetos (Taiga, Trello ou Jira) durante o processo de criação da conta, para fins de integração e rastreamento das atividades no pipeline de ETL.|3|RF4,RNF1,RNF2,RNF5|
|US12|12|Média|Eu, como admin, desejo visualizar informações sobre a quantidade de projetos e o número de cards em cada projeto, para ter uma visão abrangente do andamento e da gestão dos projetos.|3|RF4,RNF1,RNF2,RNF5|
|US13|13|Média|Eu, como admin, desejo visualizar a quantidade de cards criados e finalizados dentro de um período específico, para monitorar o progresso das tarefas.|3|RF5,RNF1,RNF2,RNF5|
|US14|14|Média|Eu, como admin, desejo visualizar uma tabela que liste cada projeto, o gestor responsável e o número de pessoas alocadas em cada um, a fim de ter uma visão clara da estrutura e alocação de recursos nos projetos.|3|RF5,RNF1,RNF2,RNF5|
|US15|15|Média|Eu, como administrador, desejo visualizar, para cada projeto, detalhes sobre as issues dos projetos, incluindo a quantidade total, tipo, gravidade e prioridade, para analisar a eficiência da equipe e priorizar as ações corretivas de forma adequada.|1|RF2,RNF1,RNF2,RNF5|
|US16|16|Baixa|Eu, como admin, desejo integrar novas ferramentas ao sistema, permitindo a ampliação das funcionalidades e a interoperabilidade com diferentes plataformas, a fim de melhorar a eficiência e a experiência dos usuários.|3|RF4,RNF1,RNF2,RNF5|
|US17|17|Baixa|Eu, como admin, quero realizar a exportação dos dados do Dashboard para um arquivo CSV, para que eu possa analisar, compartilhar ou arquivar os dados de forma prática e organizada, fora da plataforma.|3|RF3,RNF1,RNF2,RNF5|
|US18|18|Baixa|Eu, como admin, para fins de auditoria e acompanhamento, desejo visualizar uma tabela abrangente que registre cada ação realizada na aplicação, incluindo detalhes como o usuário que a executou, o tipo de ação e o timestamp da ocorrência.|3|RF4,RNF1,RNF2,RNF5|

---

## 🔄 Sprint Backlog <a id="sprint-backlog"></a>

## [Sprint 1️⃣ - 08/09 a 28/09](#sprint1)

| 🗃️ User Story ID | 🚨 Estimativa | 🎯 Meta | 🛠️ Status |
| :-------------: | :-------------: | :------: | :-------------: |
|US01|10| ✅ |⏳ Em andamento|
|US02|05|✅|⏳ Em andamento|
|US03|10| ✅ |⏳ Em andamento|

---

<br>

## 👥 Team Members <a id="membros"></a>
|Nome|Função|LinkedIn|  
| -------- | -------- | -------- |
|**Julio Cesar Ferreira De Freitas**|Product Owner|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white"  />](https://www.linkedin.com/in/julio-freitas-415b73216?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)|
|**Beatriz A Y Bonatto**|Scrum Maste|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://br.linkedin.com/in/beatriz-bonatto-263530156)|
|**Paulo Arantes Machado**|Desenvolvedor|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/paulo-antonio-arantes-machado-a8a89b23b)|
|**Otavio Calderan Bruguel**|Desenvolvedor|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/otavio-calderan-578b48239)|
|**André Hideaki Wakugawa**|Desenvolvedor|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/andrewakugawa/)|
|**Cauê Vieira da Silva**|Desenvolvedor|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/cau%C3%AA-vieira-ba62b4244/)|
|**Gabriel Bartolomeu Guska**|Desenvolvedor|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/gabiel-guska-5860a1271/)|
