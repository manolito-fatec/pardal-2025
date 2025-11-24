<h1 align="center"> Pardal </h1>

<p align="center">
      <img src="doc/images/Logo-Pardal.png" alt="Pardal logo" width="200">
</p>

<h3 align="center">Repository dedicated to versioning the API project developed in the 6th semester of the Technologist in Database</h3>

---

## 🎯 Objective

> [!IMPORTANT]
> The purpose of this project is to centralize and optimize a support ticket management system, ensuring greater organization, faster response times, and visibility across all levels of operations. Currently, the client faces challenges with manual ticket control using a legacy database, lack of consolidated history, and absence of performance indicators to support strategic decisions.
>
> With this solution, it will be possible to improve communication among teams, reduce resolution times, identify process improvement opportunities, ensure LGPD compliance in data handling, and enhance customer service quality, making the entire process more efficient, secure, and transparent.

---

# 🔍 Topics

- <a href="#documentation">📚 Documentation</a>
- <a href="#technologies">🔌 Technologies</a>
- <a href="#requirements">📋 Requirements</a>
- <a href="#backlog">📈 Product Backlog</a>
- <a href="#sprint-backlog">🔄 Sprint Backlog</a>
- <a href="#team">👥 Team Members</a>

---

## 📚 Documentation <a id="documentation"></a>

> [!NOTE]
> Project documentation and guides:

- [Database](https://github.com/manolito-fatec/web-server-2025-2/tree/main/src/main/resources/db)
- [Project Standards](https://github.com/manolito-fatec/pardal-2025/wiki)
- [Documentation](https://github.com/manolito-fatec/pardal-2025/tree/main/doc)
- [User Guide](https://github.com/manolito-fatec/pardal-2025/tree/main/doc/user%20guide) 

---

## 🔌 Technologies <a id="technologies"></a>

> [!NOTE]
> Technologies used in the development of the project:

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
<a href="https://www.docker.com/" target="_blank"><img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
</a>
<a href="https://www.vaultproject.io/" target="_blank"><img src="https://img.shields.io/badge/Vault-000000?style=for-the-badge&logo=vault&logoColor=white" alt="Vault">
</a>

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
</h4>

---

<br>

## 📋 Requirements <a id="requirements"></a>

### 📌 Non-Functional Requirements (NFR)

| **ID** | **Title**                                             |
| :----: | :---------------------------------------------------- |
|  NFR1  | API Documentation – Application Programming Interface |
|  NFR2  | User Guide                                            |
|  NFR3  | Database Design                                       |
|  NFR4  | Non-Relational Database                               |
|  NFR5  | LGPD Compliance                                       |

---

### 📌 Functional Requirements (Epics) (FR)

| **ID** | **Role**      | **Epic**           | **Description**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| :----: | :------------ | :----------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|  FR1   | Administrator | LGPD Modernization | The system must ensure that personal and sensitive data entered in free-text fields (title, description, and ticket comments) are automatically identified and anonymized before being persisted in the database. This will require the use of regular expressions (Regex) for structured data (CPF, email, phone number) and integration with an NLP service for semantic analysis of sensitive information (health, religion, political opinion, etc.). The goal is to ensure continuous LGPD compliance and prevent improper data storage. |
|  FR2   | Manager       | Insights           | The system must provide an analytics component that automatically generates insights about tickets, identifying recurrence patterns, critical categories, and SLA compliance. This feature aims to support strategic decision-making and improve operational efficiency.                                                                                                                                                                                                                                                                      |
|  FR3   | Manager       | Dashboards         | The system must provide managers with an interactive dashboard displaying performance indicators (KPIs), including total tickets created, average resolution time, recurrence rate, and SLA compliance. The dashboard must allow filtering by period, agent, company, category, and priority, enabling detailed and comparative analysis.                                                                                                                                                                                                     |
|  FR4   | Administrator | User Management    | The system must provide an administrative interface that allows administrators to manage users (create, edit, deactivate, and assign roles/profiles). This ensures proper access control so that each user only views and interacts with information relevant to their responsibilities.                                                                                                                                                                                                                                                      |
|  FR5   | Operator      | Ticket Search      | The system must provide authenticated operators with an advanced search mechanism for tickets, allowing filtering by status, category, agent, company, priority, and date range. The goal is to enable quick access to specific tickets and improve service productivity.                                                                                                                                                                                                                                                                     |

---

<br>

## 📈 Product Backlog <a id="backlog"></a>

| 🗃️ ID | 🏅 Rank | 🔥 Priority | 📝 User Story                                                                                                                                                                                            | 🚀 Sprint | 🎯 Partner Requirement |
| :---: | :-----: | :---------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------: | :--------------------: |
| US01  |    1    |    High     | As an admin, I want personal data to be anonymized in ticket descriptions, to ensure LGPD compliance.                                                                                                    | Sprint 1  |    FR1, NFR1, NFR2     |
| US02  |    2    |    High     | As an admin, I want sensitive data (health, religion, etc.) to be anonymized through semantic analysis (NLP), to strengthen LGPD compliance.                                                             | Sprint 1  |       FR1, NFR1        |
| US03  |    4    |    High     | As a support manager, I want to view the forecast of tickets at risk of exceeding SLA, so I can act preventively.                                                                                        | Sprint 2  |       FR2, NFR2        |
| US04  |    5    |    High     | As a manager, I want to filter insights by client, product, and date, to obtain exclusive insights for each scenario.                                                                                    | Sprint 2  |       FR2, NFR2        |
| US05  |    6    |    High     | As a manager, I want to analyze seasonality and ticket volume over time, to allocate the team during critical periods.                                                                                   | Sprint 2  |       FR2, NFR2        |
| US06  |    9    |   Medium    | As a product team, I want to view AI prescriptive insights, to identify improvements and opportunities in the system (exclusive to system improvement requests).                                         | Sprint 3  |       FR3, NFR2        |
| US07  |    7    |   Medium    | As a manager, I want to identify the most common root causes of tickets, to plan training and product improvements.                                                                                      | Sprint 2  |       FR3, NFR2        |
| US08  |    3    |   Medium    | As a manager, I want to view macro support metrics (total, AHT, recurrence, SLA), to monitor efficiency.                                                                                                 | Sprint 1  |       FR2, NFR2        |
| US09  |   10    |     Low     | As a manager, I want to filter dashboards by product and client, to identify the main sources of demand.                                                                                                 | Sprint 3  |       FR3, NFR2        |
| US10  |   11    |   Medium    | As a manager, I want to export reports (PDF/Excel), to share results with other departments.                                                                                                             | Sprint 3  |       FR4, NFR2        |
| US11  |   12    |   Medium    | As an admin, I want to create, edit, and remove users, to keep access up to date.                                                                                                                        | Sprint 3  |       FR4, NFR2        |
| US12  |   13    |   Medium    | As an admin, I want to reset user passwords to ensure access in case of issues, and receive a confirmation email.                                                                                        | Sprint 3  |       FR4, NFR2        |
| US13  |   14    |     Low     | As a support agent, I want to search for specific tickets and view the full history, to speed up service.                                                                                                | Sprint 3  |       FR5, NFR2        |
| US14  |   15    |     Low     | As a support agent, I want to consult a chatbot to obtain information about tickets, to get faster and more effective search results.                                                                    |     -     |       FR5, NFR2        |
| US15  |    8    |    High     | As a product manager, I want an automated process that analyzes ticket texts, extracts suggestions, groups them by theme, and presents them in a dashboard, so I can take data-driven roadmap decisions. | Sprint 2  |       FR3, NFR2        |

---

## 🔄 Sprint Backlog <a id="sprint-backlog"></a>

## [Sprint 1️⃣ - 09/08 to 09/28](#sprint1)

<p align="left">
  <a href="https://github.com/manolito-fatec/web-server-2025-2/releases/tag/v1.0">Web Server Repository</a> |
  <a href="https://github.com/manolito-fatec/web-client-2025-2/releases/tag/v1.0">Web Client Repository</a> |
  <a href="https://github.com/manolito-fatec/ai-server-2025-2/releases/tag/v1.0">AI Service Repository</a> 
</p>

> The DoD and DoR documents for this sprint are available [here](doc/DoD%20and%20DoR%20documents/DoD_DoR_Sprint_1.pdf).
>
> 📊 The Sprint Burndown Chart can be found [here](doc/images/Burndown-Sprint-1.png).

| 🗃️ User Story ID | 🚨 Estimate | 🎯 Goal | 🛠️ Status |
| :--------------: | :---------: | :-----: | :-------: |
|       US01       |     10      |   ✅    |  Done ✅  |
|       US02       |     05      |   ✅    |  Done ✅  |
|       US08       |     10      |   ✅    |  Done ✅  |

---

## [Sprint 2️⃣ - 09/29 to 10/12](#sprint2)

<p align="left">
  <a href="https://github.com/manolito-fatec/web-server-2025-2/releases/tag/v2.0">Web Server Repository</a> |
  <a href="https://github.com/manolito-fatec/web-client-2025-2/releases/tag/v2.0">Web Client Repository</a> |
  <a href="https://github.com/manolito-fatec/ai-server-2025-2/releases/tag/v2.0">AI Service Repository</a>
</p>

> The DoD and DoR documents for this sprint are available [here](doc/DoD%20and%20DoR%20documents/DoD_DoR_Sprint_2.pdf).
>
> 📊 The Sprint Burndown Chart can be found [here](doc/images/Burndown-Sprint-2.png).

| 🗃️ User Story ID | 🚨 Estimate | 🎯 Goal |   🛠️ Status    |
| :--------------: | :---------: | :-----: | :------------: |
|       US03       |     20      |   ✅    |    Done ✅     |
|       US04       |     05      |   ✅    |    Done ✅     |
|       US05       |     13      |   ✅    |    Done ✅     |
|       US15       |     15      |   ✅    |    Done ✅     |
|       US07       |     03      |    -    |    Done ✅     |
|       US11       |     13      |    -    | Done ✅ |

---

## [Sprint 3️⃣ - 11/03 to 11/23](#sprint3)

<p align="left">
  <a href="https://github.com/manolito-fatec/web-server-2025-2/releases/tag/v3.0">Web Server Repository</a> |
  <a href="https://github.com/manolito-fatec/web-client-2025-2/releases/tag/v3.0">Web Client Repository</a> |
  <a href="https://github.com/manolito-fatec/ai-server-2025-2/releases/tag/v3.0">AI Service Repository</a> 
</p>

> The DoD and DoR documents for this sprint are available [here](doc/DoD%20and%20DoR%20documents/DoD_DoR_Sprint_3.pdf).
>
> 📊 The Sprint Burndown Chart can be found [here](doc/images/Burndown-Sprint-3.png).

| 🗃️ User Story ID | 🚨 Estimate | 🎯 Goal |   🛠️ Status    |
| :--------------: | :---------: | :-----: | :------------: |
|       US09       |     13      |   ✅    | Done ✅ |
|       US10       |     08      |   ✅    | Done ✅ |
|       US12       |     08      |   ✅    | Done ✅ |
|       US13       |     20      |   ✅    | Done ✅ |

---

<br>

## 👥 Team Members <a id="team"></a>

| Name                                | Role          | LinkedIn                                                                        |
| ----------------------------------- | ------------- | ------------------------------------------------------------------------------- |
| **Julio Cesar Ferreira De Freitas** | Product Owner | [LinkedIn](https://www.linkedin.com/in/julio-freitas-415b73216)                 |
| **Beatriz A Y Bonatto**             | Scrum Master  | [LinkedIn](https://br.linkedin.com/in/beatriz-bonatto-263530156)                |
| **Paulo Arantes Machado**           | Developer     | [LinkedIn](https://www.linkedin.com/in/paulo-antonio-arantes-machado-a8a89b23b) |
| **Otavio Calderan Bruguel**         | Developer     | [LinkedIn](https://www.linkedin.com/in/otavio-calderan-578b48239)               |
| **André Hideaki Wakugawa**          | Developer     | [LinkedIn](https://www.linkedin.com/in/andrewakugawa/)                          |
| **Cauê Vieira da Silva**            | Developer     | [LinkedIn](https://www.linkedin.com/in/cau%C3%AA-vieira-ba62b4244/)             |
| **Gabriel Bartolomeu Guska**        | Developer     | [LinkedIn](https://www.linkedin.com/in/gabiel-guska-5860a1271/)                 |
