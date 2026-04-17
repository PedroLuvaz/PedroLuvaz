<div align="center">

```
██████╗ ███████╗██████╗ ██████╗  ██████╗
██╔══██╗██╔════╝██╔══██╗██╔══██╗██╔═══██╗
██████╔╝█████╗  ██║  ██║██████╔╝██║   ██║
██╔═══╝ ██╔══╝  ██║  ██║██╔══██╗██║   ██║
██║     ███████╗██████╔╝██║  ██║╚██████╔╝
╚═╝     ╚══════╝╚═════╝ ╚═╝  ╚═╝ ╚═════╝
```

### `backend engineer · ai integrations · cloud systems`

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230A66C2.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pedro-andrade-0a8146235/)
[![Email](https://img.shields.io/badge/Email-%23EA4335.svg?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pedrolucas0721@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-%23111111.svg?style=for-the-badge&logo=vercel&logoColor=white)](https://gitfollio.vercel.app/PedroLuvaz)

</div>

---

## $ whoami

Backend developer com foco em **sistemas de IA em produção**, **automação inteligente** e **arquitetura cloud-native**. Atuo no desenvolvimento do **Modall** (Entrega+) — uma plataforma de atendimento automatizado via WhatsApp com CRM integrado, processamento assíncrono e orquestração de múltiplos modelos de linguagem.

Formando em **Ciência da Computação pela UEPB** (previsão: dez/2026), com experiência paralela em pesquisa aplicada de usabilidade no **NUTES/LUFH**.

```python
pedro = {
    "role":     "Backend Developer @ Entrega+",
    "education":"B.Sc. Computer Science @ UEPB",
    "stack":    ["Python", "FastAPI", "Flask", "PostgreSQL", "Docker", "GCP"],
    "focus":    ["Scalable APIs", "AI Integrations", "Async Processing", "Multi-tenant Systems"],
    "experience": [
        "REST API design & integration",
        "Database modeling & optimization",
        "Background jobs & scheduling",
        "Clean code & maintainability"
    ],
    "studying": ["C#/.NET (WinForms)", "System Design", "Distributed Systems"],
    "interests":["Algorithms", "Performance", "Backend Architecture"],
    "location": "Santa Cruz do Capibaribe, PE - Brasil",
}
```

---

## ⚙️ Stack Técnica

<div align="center">

**Back-end & APIs**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**IA & Integrações**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white)
![WhatsApp](https://img.shields.io/badge/WhatsApp_APIs-25D366?style=flat-square&logo=whatsapp&logoColor=white)

**Cloud & Infra**

![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Cloud Run](https://img.shields.io/badge/Cloud_Run-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Cloud Tasks](https://img.shields.io/badge/Cloud_Tasks-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Banco de Dados**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Firestore](https://img.shields.io/badge/Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=python&logoColor=white)

</div>

---

## 💼 Experiência

### 🔷 Backend Developer — Entrega+ *(2025 — atual)*

Desenvolvimento do **Modall**, plataforma de automação de atendimento via WhatsApp com IA e CRM integrado.

- Integração com **OpenAI Assistants API** (tool calling, thread management no Firestore)
- Integração com **Gemini** e múltiplas APIs WhatsApp (Z-API, Meta, GreenAPI)
- Processamento assíncrono com **Cloud Tasks** + execução idempotente
- Controle de consumo por plano: limites, bloqueios e logging via **BigQuery**
- Arquitetura **multi-tenant** com separação SQL + NoSQL (PostgreSQL + Firestore)
- Fallback e retry em APIs externas; pool de conexões com `pre_ping`
- Redirecionamento inteligente para atendimento humano e controle de horário comercial

### 🔷 Pesquisador & Desenvolvedor — NUTES/LUFH, UEPB *(2023 — 2025)*

Laboratório de Usabilidade e Fatores Humanos — foco em **IHC e tecnologias assistivas**.

- Desenvolvimento de ferramentas em **C# (.NET)** para mensuração de usabilidade
- Coleta e análise de métricas de desempenho de interfaces com grafos
- Aplicação de avaliação heurística e modelagem de interações

---

## 🧱 Padrões Arquiteturais

```
✓ Arquitetura orientada a eventos       ✓ Controle de estado distribuído
✓ Execução idempotente de tarefas       ✓ Tool calling com modelos de IA
✓ Sistema multi-tenant                  ✓ Fallback e retry em APIs externas
✓ Persistência híbrida SQL + NoSQL      ✓ Logging estruturado de tokens/custos
✓ Controle transacional (SQLAlchemy)    ✓ Processamento assíncrono com filas
```

---

## 📂 Projetos

| Projeto | Descrição | Stack |
|---------|-----------|-------|
| [**eng2marketplace**](https://github.com/PedroLuvaz/eng2marketplace) | Marketplace com autenticação JWT e CRUD completo | Python · FastAPI · PostgreSQL |
| [**sistemaOdonto**](https://github.com/PedroLuvaz/sistemaOdonto) | Sistema de gestão odontológica com ORM | C# · .NET · Entity Framework |
| [**Project-TubeTool**](https://github.com/PedroLuvaz/Project-TubeTool) | Automação de cálculos e análise de dados | Python |

---

## 📊 GitHub Stats

<div align="center">
  <img height="160em" src="https://github-readme-stats.vercel.app/api?username=PedroLuvaz&show_icons=true&theme=github_dark&hide_border=true&custom_title=Stats" />
  <img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=PedroLuvaz&layout=compact&theme=github_dark&hide_border=true" />
</div>

---

## 🎓 Formação

**Bacharelado em Ciência da Computação** — UEPB *(previsão: dez/2026)*  
Ênfase em Engenharia de Software, Arquitetura de Sistemas e Inteligência Artificial.

---

<div align="center">

*"Build systems that hold under pressure — the rest is detail."*

</div>
