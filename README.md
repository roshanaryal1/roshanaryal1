<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Roshan Aryal, AI and software engineer, Auckland" src="assets/banner-light.svg" width="100%">
</picture>

I build AI products end to end, from the model and the data pipeline to the
interface, the tests and the deployment, and I measure whether they actually
work. I finish my Bachelor of Information Technology in December 2026 and am
looking for **graduate AI, machine learning or software engineering roles in
New Zealand from January 2027**.

[![Email](https://img.shields.io/badge/Email-roshanaryaal%40gmail.com-087F78?style=flat-square&logo=gmail&logoColor=white)](mailto:roshanaryaal@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-roshanaryaal-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/roshanaryaal/)
[![Website](https://img.shields.io/badge/Web-roshanaryal.com-192430?style=flat-square&logo=googlechrome&logoColor=white)](https://www.roshanaryal.com)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0001--4758--4977-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0001-4758-4977)

## Featured work

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://rentmate.roshanaryal.com"><img src="assets/rentmate.png" alt="RentMate home page"></a>
      <h3>RentMate</h3>
      <p>Peer-to-peer equipment rental marketplace, built solo and live in production. In-browser semantic search on ONNX embeddings with a TF-IDF fallback, a RAG assistant, and a 50-query retrieval evaluation wired into CI as a deploy gate (96% pass).</p>
      <p><b>React · Firebase · Vercel · Stripe (test mode)</b><br><a href="https://rentmate.roshanaryal.com">Live site</a> · code private</p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/roshanaryal1/credit-desk"><img src="assets/credit-desk.png" alt="Credit Desk review queue"></a>
      <h3>Credit Desk</h3>
      <p>Credit operations desk for invoice finance. Deterministic checks flag risky invoices, an LLM explains each flag and must cite the source records, a validator rejects anything it cannot ground, and an analyst makes every decision. Includes a trust panel and exact decision replay.</p>
      <p><b>TypeScript · Next.js · PostgreSQL (Drizzle) · OpenAI API</b><br><a href="https://creditdesk.roshanaryal.com">Live demo</a> · <a href="https://github.com/roshanaryal1/credit-desk">code</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/roshanaryal1/SafeRoute"><img src="assets/saferoute.png" alt="SafeRoute inputs and SHAP explanation"></a>
      <h3>SafeRoute</h3>
      <p>Explainable road-risk scoring that shows which conditions raised or lowered every score. <b>First place, Innovation Challenge 2026</b>; selected for the SSD 2026 project showcase. Random Forest with TreeSHAP, R² 0.88 on held-out synthetic data, 32 automated tests.</p>
      <p><b>Python · scikit-learn · SHAP · Streamlit</b><br><a href="https://roadaccident-roshanar-aryal.streamlit.app/">Live demo</a> · <a href="https://github.com/roshanaryal1/SafeRoute">code</a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/roshanaryal1/serialisation-ceiling-artifact"><img src="assets/serialisation-ceiling.png" alt="Cold-start decomposition chart"></a>
      <h3>Why browser search breaks between 61,000 and 67,000 documents</h3>
      <p>Found and fixed a hard failure in in-browser semantic search: the JSON vector file exceeds Chrome's maximum string length. A binary format is 5.19× smaller and cannot hit the limit. <b>Paper accepted at SSD 2026.</b> CI re-runs the analysis and checks the published numbers on every push.</p>
      <p><b>JavaScript · WebAssembly · Playwright · Python</b><br><a href="https://github.com/roshanaryal1/serialisation-ceiling-artifact">code and data</a></p>
    </td>
  </tr>
</table>

## Experience

**AI Engineer (independent contractor), Apprento, Auckland** · April to August 2026

- Built and deployed HireIQ, an AI candidate-intelligence platform, end to end
  into a live recruiter workflow: LLM orchestration, authentication and access
  control, PostgreSQL data layer.
- Structured LLM scoring engine with Pydantic v2 schema validation, corrective
  retry on malformed output and multi-provider failover, replacing a 30 to 45
  minute manual process with a pipeline that runs in under 30 seconds.
- Audit logging with SHA-256-hashed personal data; deployed on Railway and
  Vercel with GitHub Actions CI/CD.
- Stack: Python, FastAPI, SQLAlchemy, PostgreSQL with pgvector, Anthropic
  Claude, React 19, Vite, Sentry, OpenTelemetry.

**Industry capstone, India New Zealand Business Council** · 2026, in progress

- Trade-intelligence platform built by a three-person team under a formal MOU.
  My scope: the SIP pipeline, the FTA Implementation Centre, the approved-facts
  library and a cross-repository news engine.

**Independent research** · 2025 to present

- Four studies in 2026, each with a public, reproducible pipeline: one paper
  accepted, one through peer review, one under review, one preprint.

## Tech stack

| Area | Tools |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) |
| **LLM APIs** | ![Anthropic Claude](https://img.shields.io/badge/Anthropic_Claude-191919?style=flat-square&logo=anthropic&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white) ![Google Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) ![xAI Grok](https://img.shields.io/badge/xAI_Grok-000000?style=flat-square&logo=x&logoColor=white) ![Alibaba Qwen](https://img.shields.io/badge/Alibaba_Qwen-FF6A00?style=flat-square&logo=alibabacloud&logoColor=white) ![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square) ![Together AI](https://img.shields.io/badge/Together_AI-0F6FFF?style=flat-square) ![OpenAI-compatible APIs](https://img.shields.io/badge/OpenAI--compatible_APIs-5C6178?style=flat-square) |
| **AI engineering** | ![RAG](https://img.shields.io/badge/RAG-087F78?style=flat-square) ![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Transformers.js](https://img.shields.io/badge/Transformers.js-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![ONNX Runtime](https://img.shields.io/badge/ONNX_Runtime-005CED?style=flat-square&logo=onnx&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white) ![LLM evaluation](https://img.shields.io/badge/LLM_evaluation-087F78?style=flat-square) ![MLX local models](https://img.shields.io/badge/MLX_local_models-000000?style=flat-square&logo=apple&logoColor=white) |
| **ML and data** | ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![SHAP](https://img.shields.io/badge/SHAP-FF0051?style=flat-square) ![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white) ![statsmodels](https://img.shields.io/badge/statsmodels-4051B5?style=flat-square) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) |
| **Backend** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white) |
| **Frontend** | ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) |
| **Data and integrations** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) ![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white) ![Vercel Blob](https://img.shields.io/badge/Vercel_Blob-000000?style=flat-square&logo=vercel&logoColor=white) ![REST APIs and webhooks](https://img.shields.io/badge/REST_APIs_and_webhooks-5C6178?style=flat-square) |
| **Delivery and quality** | ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) ![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white) ![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) |

I work with any REST or OpenAI-compatible API: LLM providers, payments,
authentication, storage and public data services.

## Research

| Work | Status | Code and data |
|---|---|---|
| A Serialisation Ceiling in Browser-Native Semantic Retrieval | Accepted, SSD 2026 (Atlantis Press, Springer Nature) | [repo](https://github.com/roshanaryal1/serialisation-ceiling-artifact) |
| Large Language Models as Systems Architects | Peer review complete, in production at Cureus Journal of Computer Science · [DOI](https://doi.org/10.5281/zenodo.22245991) | [repo](https://github.com/roshanaryal1/llm-architects) |
| Model, Not Mode: fast versus reasoning modes across six LLM families | Preprint · [DOI](https://doi.org/10.20944/preprints202610.2826.v1) | [repo](https://github.com/roshanaryal1/reasoning-mode-grid) |
| Light condition, weather and injury severity in NZ road crashes, 2010-2024 | Under peer review · [DOI](https://doi.org/10.5281/zenodo.21839911) | [repo](https://github.com/roshanaryal1/cas-severity) |

## More projects

- [home-lab](https://github.com/roshanaryal1/home-lab): a 24/7 local AI system
  on an Apple Mac mini, built to the reference architecture from the
  llm-architects study. Python, SQLite, local LLMs.
- [Task-manager-and-reminder](https://github.com/roshanaryal1/Task-manager-and-reminder):
  TaskFlow, a full-stack task manager with reminders and analytics.
  React, TypeScript, Vite.
- [quiz-app-froentend](https://github.com/roshanaryal1/quiz-app-froentend):
  quiz tournament web app. React.
- Data science coursework:
  [diabetes-prediction](https://github.com/roshanaryal1/diabetes-prediction) ·
  [air-nz-stock-linear-regression](https://github.com/roshanaryal1/air-nz-stock-linear-regression) ·
  [Dimensionality-Reduction-](https://github.com/roshanaryal1/Dimensionality-Reduction-)

New repositories start from my
[repo-template](https://github.com/roshanaryal1/repo-template), one template
for projects, research and coursework.

## Education

**Bachelor of Information Technology**, Otago Polytechnic, Auckland
International Campus · 2024 to 2026, completing December 2026
