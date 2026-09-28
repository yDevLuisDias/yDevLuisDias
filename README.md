<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1200&color=6DB33F&center=true&vCenter=true&width=700&lines=Ol%C3%A1%2C+eu+sou+Luis+Henrique+%F0%9F%91%8B;Engenheiro+de+IA+Aplicada;Agentes+%C2%B7+RAG+%C2%B7+Backend+%C2%B7+Dados" alt="Luis Henrique — Engenheiro de IA Aplicada" />

**Construo agentes de IA que trabalham de verdade: em produção, com clientes reais.**
<br>
<sub>🇺🇸 *I build AI agents that actually work: in production, with real customers.*</sub>

<br>

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/luisdevhenrique)
[![Gmail](https://img.shields.io/badge/-Gmail-c14438?style=for-the-badge&logo=Gmail&logoColor=white)](mailto:luiscosta.official@gmail.com)
[![Nexus OS](https://img.shields.io/badge/-Nexus_OS-111827?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yDevLuisDias/CAIS---NEXUS-OS)

</div>

---

## 🏆 Em destaque

> ### Top 100 de mais de 20.000 candidatos (Top 0,5%)
> **Programa iFood GenAI (2025)**: selecionado pela capacidade de construir soluções reais com IA Generativa.
>
> <sub>🇺🇸 *Top 100 out of 20,000+ candidates (top 0.5%) in the iFood GenAI Program (2025), selected for building real-world Generative AI solutions.*</sub>

---

## 👨‍💻 Sobre mim

Fundador da **Nexus OS**, estudante de Análise e Desenvolvimento de Sistemas (**Unijorge**) e de Licenciatura em Matemática (**IFBA**). Trabalho na fronteira entre **backend, dados e IA aplicada**: transformo dados brutos e não estruturados em informação útil para o negócio e entrego APIs robustas com Java e Spring Boot.

<sub>🇺🇸 *Founder of Nexus OS, studying Systems Analysis & Development and Mathematics Education. I work at the intersection of backend, data and applied AI: turning raw, unstructured data into business value and shipping robust Java/Spring Boot APIs.*</sub>

| | |
|---|---|
| 🔭 **Construindo agora** | Agentes autônomos de IA e pipelines de dados na Nexus OS |
| 🌱 **Aprofundando em** | Spring Boot, orquestração de LLMs e arquiteturas orientadas a dados |
| 💬 **Converse comigo sobre** | Java, Spring, IA generativa aplicada a negócio e engenharia de dados |

---

## 🎓 Formação

<sub>🇺🇸 *Education*</sub>

| Curso | Instituição | Status |
|---|---|---|
| 💻 Análise e Desenvolvimento de Sistemas | Unijorge | Cursando |
| 📐 Licenciatura em Matemática | IFBA | Cursando |

Estudo tecnologia e matemática ao mesmo tempo: a matemática me dá a base para entender *por que* os modelos funcionam, e a engenharia me permite colocá-los em produção.

<sub>🇺🇸 *I study technology and mathematics side by side: math gives me the foundation to understand why models work, and engineering lets me put them into production.*</sub>

---

## 🌋 Sismos + IA · projeto de iniciativa própria

<div align="center">

![Status](https://img.shields.io/badge/status-em_desenvolvimento-yellow?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SeisBench](https://img.shields.io/badge/SeisBench-0B3D91?style=for-the-badge)
![Machine Learning](https://img.shields.io/badge/Machine_Learning-FF6F00?style=for-the-badge)

</div>

Nascido dos estudos de cálculo e ondas sísmicas na licenciatura, este projeto busca construir um **sistema de detecção e alerta precoce** baseado em IA, treinando um modelo próprio sobre dados sísmicos públicos. O foco é segurança de estruturas de risco, como **barragens de rejeito** e áreas de **sismicidade induzida por mineração**.

<sub>🇺🇸 *Born from calculus and seismic-wave studies, this project aims to build an AI-based early detection and warning system, training a custom model on public seismic data. The focus is the safety of high-risk structures such as tailings dams and mining-induced seismicity.*</sub>

```mermaid
flowchart LR
    A[🌍 Dados sísmicos públicos<br/>SeisBench] --> B[🧹 Limpeza e preparo<br/>CSV · 13 mil+ registros]
    B --> C[🧠 Treinamento<br/>modelo de detecção]
    C --> D[📈 Avaliação]
    D --> E[🚨 Alerta precoce<br/><i>em desenvolvimento</i>]
```

<details>
<summary><b>📍 Estágio atual / Current status</b></summary>
<br>

- ✅ Base de **mais de 13 mil registros** sísmicos em CSV, obtidos via SeisBench
- ✅ Modelo de IA com acesso a essa base
- 🚧 Treinamento, avaliação e alertas em desenvolvimento

<sub>🇺🇸 *13,000+ seismic records via SeisBench · model connected to the dataset · training, evaluation and alerting in progress.*</sub>

</details>

---

## 🚀 Nexus OS · CAIS

**Fundador & Engenheiro de IA**

O **CAIS** é um agente de IA autônomo que atende clientes pelo **WhatsApp** com respostas personalizadas, usando arquitetura **RAG** sobre uma base própria em PostgreSQL. É versátil o bastante para segmentos como **construtoras, imobiliárias e barbearias**, entre outros.

<sub>🇺🇸 *CAIS is an autonomous AI agent that serves customers on WhatsApp with personalized answers, using RAG over a custom PostgreSQL knowledge base. Flexible enough for construction firms, real estate agencies, barbershops and more.*</sub>

```mermaid
flowchart LR
    A[📱 Cliente no WhatsApp] --> B[⚙️ n8n<br/>orquestração de fluxos]
    B --> C[☕ API Java / Spring]
    C --> D[(🐘 PostgreSQL<br/>base de conhecimento)]
    D -->|contexto recuperado| E[🧠 LLM<br/>OpenAI · Gemini Flash]
    E --> C
    C --> B
    B --> F[💬 Resposta personalizada]
```

<details>
<summary><b>🔍 Ver o que tem por baixo do capô / Under the hood</b></summary>
<br>

- 🤖 **Orquestração de LLMs**: OpenAI e Gemini Flash em produção, com foco em respostas contextualizadas e confiáveis
- 🧠 **RAG**: recuperação de contexto sobre base própria em PostgreSQL para personalizar cada resposta
- ⚙️ **RPA & BPM**: automação de processos de negócio ponta a ponta, integrando fluxos via **n8n**
- 🔌 **Backend & integrações**: APIs REST/HTTP com Java e Spring, conectando o agente a canais e sistemas do cliente

<sub>🇺🇸 *LLM orchestration in production · RAG over PostgreSQL · end-to-end process automation with n8n · REST integrations with Java/Spring.*</sub>

`Java` `Spring` `OpenAI` `Gemini Flash` `n8n` `RAG` `PostgreSQL` `REST APIs`

</details>

**[➡️ Ver o repositório do CAIS](https://github.com/yDevLuisDias/CAIS---NEXUS-OS)**

---

## 🛠️ Stack

<sub>🇺🇸 *Tech stack: what I use to build things*</sub>

<div align="center">

<img src="https://skillicons.dev/icons?i=java,spring,postgres,python,js,html,css,docker,git,github,linux,fedora&perline=12" alt="Stack" />

</div>

<br>

<table>
<tr>
<td width="50%" valign="top">

#### ☕ Backend
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![Spring Batch](https://img.shields.io/badge/Spring_Batch-6DB33F?style=flat-square&logo=spring&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white)
![REST](https://img.shields.io/badge/REST_APIs-009688?style=flat-square&logo=fastapi&logoColor=white)

</td>
<td width="50%" valign="top">

#### 🧠 IA & Agentes
![Spring AI](https://img.shields.io/badge/Spring_AI-6DB33F?style=flat-square&logo=spring&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_Flash-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-FF6F00?style=flat-square&logo=databricks&logoColor=white)
![Agents](https://img.shields.io/badge/AI_Agents-000000?style=flat-square&logo=robotframework&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🗄️ Dados & Automação
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![ETL](https://img.shields.io/badge/ETL-0A66C2?style=flat-square&logo=apacheairflow&logoColor=white)
![RPA](https://img.shields.io/badge/RPA-FF5722?style=flat-square&logo=uipath&logoColor=white)
![CSV/JSON/XML](https://img.shields.io/badge/CSV_·_JSON_·_XML-555555?style=flat-square&logo=files&logoColor=white)

</td>
<td width="50%" valign="top">

#### 🧰 Linguagens & Ferramentas
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Fedora](https://img.shields.io/badge/Fedora_Linux-51A2DA?style=flat-square&logo=fedora&logoColor=white)

</td>
</tr>
</table>

---

## 📌 Projetos

<sub>🇺🇸 *Featured projects: click a name to open the repo*</sub>

| Projeto | O que faz · <sub>🇺🇸 *what it does*</sub> | Stack | Atividade |
|---|---|---|---|
| 🤖 **[CAIS · Nexus OS](https://github.com/yDevLuisDias/CAIS---NEXUS-OS)** | Agente de IA no WhatsApp com RAG sobre PostgreSQL, em produção com clientes reais. <br><sub>🇺🇸 *WhatsApp AI agent with RAG over PostgreSQL, live with real customers.*</sub> | ![](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white) ![](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) | ![](https://img.shields.io/github/last-commit/yDevLuisDias/CAIS---NEXUS-OS?style=flat-square&label=%C3%BAltimo%20commit&color=6DB33F&labelColor=1f2937) |
| ⚡ **[AI-Driver ETL](https://github.com/yDevLuisDias/AI-Driver-ETL)** | Extrai dados estruturados de texto livre e classifica intenção de compra para qualificar leads. <br><sub>🇺🇸 *Extracts structured data from free text and classifies purchase intent to qualify leads.*</sub> | ![](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![](https://img.shields.io/badge/Spring_AI-6DB33F?style=flat-square&logo=spring&logoColor=white) ![](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) | ![](https://img.shields.io/github/last-commit/yDevLuisDias/AI-Driver-ETL?style=flat-square&label=%C3%BAltimo%20commit&color=6DB33F&labelColor=1f2937) |
| 🏦 **[Bank Account](https://github.com/yDevLuisDias/Bank-Account)** | API REST bancária com Spring Security, JPA e arquitetura em camadas (core/infra). <br><sub>🇺🇸 *Banking REST API with Spring Security, JPA and a layered architecture.*</sub> | ![](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white) ![](https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white) | ![](https://img.shields.io/github/last-commit/yDevLuisDias/Bank-Account?style=flat-square&label=%C3%BAltimo%20commit&color=6DB33F&labelColor=1f2937) |
| 📄 **[CSV Processor](https://github.com/yDevLuisDias/CSV-Processor)** | Lê, valida e exporta CSV, separando registros válidos de inválidos. <br><sub>🇺🇸 *Reads, validates and exports CSV, splitting valid from invalid records.*</sub> | ![](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![](https://img.shields.io/badge/OOP-555555?style=flat-square) | ![](https://img.shields.io/github/last-commit/yDevLuisDias/CSV-Processor?style=flat-square&label=%C3%BAltimo%20commit&color=6DB33F&labelColor=1f2937) |
| 🌍 **[BioCode](https://github.com/yDevLuisDias/bio_code)** | Jogo educativo que ensina lógica de programação com missões de sustentabilidade (COP30). <br><sub>🇺🇸 *Educational game teaching programming logic through sustainability missions.*</sub> | ![](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![](https://img.shields.io/badge/Canvas-E34F26?style=flat-square&logo=html5&logoColor=white) | ![](https://img.shields.io/github/last-commit/yDevLuisDias/bio_code?style=flat-square&label=%C3%BAltimo%20commit&color=6DB33F&labelColor=1f2937) |
| 🚧 **[ETL-Process](https://github.com/yDevLuisDias/ETL-Process)** | *Em desenvolvimento:* PoC de ETL com Spring Batch para CSV, JSON e XML. <br><sub>🇺🇸 *WIP: Spring Batch ETL proof of concept for CSV, JSON and XML.*</sub> | ![](https://img.shields.io/badge/Spring_Batch-6DB33F?style=flat-square&logo=spring&logoColor=white) ![](https://img.shields.io/badge/status-em_constru%C3%A7%C3%A3o-yellow?style=flat-square) | ![](https://img.shields.io/github/last-commit/yDevLuisDias/ETL-Process?style=flat-square&label=%C3%BAltimo%20commit&color=6DB33F&labelColor=1f2937) |

---

## 📊 Minha atividade no GitHub

<sub>🇺🇸 *My GitHub activity: commits, pull requests, issues and contributions*</sub>

<div align="center">

<img src="https://streak-stats.demolab.com?user=yDevLuisDias&theme=tokyonight&hide_border=true" alt="Streak" />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=yDevLuisDias&theme=tokyonight" alt="Profile details" />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=yDevLuisDias&theme=tokyonight" width="49%" alt="Commits, PRs, issues e stars" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=yDevLuisDias&theme=tokyonight&utcOffset=-3" width="49%" alt="Horário mais produtivo" />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=yDevLuisDias&theme=tokyonight" width="49%" alt="Repos por linguagem" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=yDevLuisDias&theme=tokyonight" width="49%" alt="Linguagens por commit" />

</div>

### ⚡ Atividade recente

<sub>🇺🇸 *Latest activity (updated automatically)*</sub>

<!--START_SECTION:activity-->
<!--END_SECTION:activity-->

### 🐍 Contribuições

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yDevLuisDias/yDevLuisDias/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/yDevLuisDias/yDevLuisDias/output/github-snake.svg" />
  <img alt="Snake animation" src="https://raw.githubusercontent.com/yDevLuisDias/yDevLuisDias/output/github-snake.svg" />
</picture>

</div>

---

<div align="center">

### 🤝 Vamos construir algo?

Tem um processo que dá para automatizar com IA? Uma vaga? Uma ideia?
<br>
<sub>🇺🇸 *Got a process that could be automated with AI? A role? An idea?*</sub>

[![Falar no LinkedIn](https://img.shields.io/badge/Falar_no_LinkedIn-0A66C2?style=for-the-badge&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/luisdevhenrique)
[![Enviar e-mail](https://img.shields.io/badge/Enviar_e--mail-c14438?style=for-the-badge&logo=Gmail&logoColor=white)](mailto:luiscosta.official@gmail.com)

<br>

<img src="https://komarev.com/ghpvc/?username=yDevLuisDias&label=Visitas&color=6DB33F&style=flat-square" alt="Visitas" />

</div>
