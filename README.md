# Hey there! 👋 I'm Sai Prasad Reddy Kukudala

**ML • Data Engineering • Backend • Applied AI**

I build practical systems that connect data, machine learning models, APIs, databases, and deployment workflows.  
My work focuses on ML engineering, data engineering, LLM agents and evaluation, GenAI/RAG pipelines, MLOps, and AI-focused backend development.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/saiprasadkukudala)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://sai-portfolio-egbw.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github)](https://github.com/Saiprasad48)
[![Email](https://img.shields.io/badge/Email-red?style=for-the-badge&logo=gmail&logoColor=white)](mailto:saiprasadkukudala18@gmail.com)

---

## About Me

- 🤖 Interested in **Machine Learning, Data Engineering, Backend Development, and Applied AI**
- 🧠 Building **LLM agents that are measured, not guessed**: eval harnesses, guardrails, and observability
- 🛠️ Building production-style projects using APIs, databases, Docker, CI/CD, cloud deployment, and ML workflows
- 📊 Focused on creating projects that are useful, explainable, and easy to understand
- 🚀 Open to full-time roles in **ML Engineering, Data Engineering, Data Science, and AI-focused Backend Development**

---

## Tech Stack

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat&logo=postgresql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-orange?style=flat&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-yellow?style=flat&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![HTML/CSS](https://img.shields.io/badge/HTML%2FCSS-E34F26?style=flat&logo=html5&logoColor=white)

### ML / Data / AI
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=flat)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat)
![SHAP](https://img.shields.io/badge/SHAP-111111?style=flat)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white)

### GenAI / Agents / Search
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat)
![MCP](https://img.shields.io/badge/MCP-6E56CF?style=flat)
![LLM Evals](https://img.shields.io/badge/LLM%20Evals-0E75B6?style=flat)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat)
![RAG](https://img.shields.io/badge/RAG-6A5ACD?style=flat)
![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat)

### Backend / Full Stack / Tools
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat&logo=render&logoColor=black)
![Neon](https://img.shields.io/badge/Neon-00E599?style=flat)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## Featured Projects

### ⭐ QueryPilot: AI Data Analyst (LangGraph Agent + MCP)
Production-style AI data analyst that answers business questions in plain English over a 100k order ecommerce warehouse. It finds the right tables with hybrid search, writes and validates SQL, runs it on a read-only database role, and explains the result with charts, streamed live. Follow-up questions keep their context.

**Built with:** LangGraph, MCP, FastAPI, Next.js, TypeScript, PostgreSQL, pgvector, dbt, Redis, Docker, GitHub Actions, Gemini, Groq  
**Highlights:**
- Eval harness measuring execution accuracy against verified SQL: **90% → 100%** after catching a join fan-out bug, **97.8%** across 90 repeated runs, plus held-out and adversarial safety suites
- Safety in layers: AST SQL guard (sqlglot), read-only Postgres role, and refusal of writes, prompt injections, and private data requests
- Model fallbacks with circuit breakers cut worst-case latency from **66 s to about 5 s** on free-tier quotas; Redis caching answers repeat questions in under a second
- dbt warehouse (15 models, 38 data tests), CI with GitHub Actions, deployed on Vercel, Render, Neon, and Upstash for **$0 per month**

[GitHub](https://github.com/Saiprasad48/querypilot) · [Live Demo](https://querypilot-flame.vercel.app) · [API Docs](https://querypilot-api-9l7d.onrender.com/docs)

---

### QueryMind: AI SQL Data Analyst Assistant
Full-stack AI data analyst assistant that converts natural language questions into safe SQL queries and helps users explore database insights through a web interface.

**Built with:** React, FastAPI, PostgreSQL, Gemini API, Text-to-SQL, Docker, Vercel, Render, Neon  
**Highlights:** Schema-aware SQL generation, read-only SQL validation, FastAPI backend, React frontend, and full free-tier deployment.

[GitHub](https://github.com/Saiprasad48/querymind-ai) · [Live Demo](https://querymind-ai-umber.vercel.app) · [API Docs](https://querymind-ai-backend.onrender.com/docs)

---

### Smart IT Helpdesk & Asset Management System
Full-stack IT support platform with JWT authentication, role-based access control, ticket workflows, asset inventory, and analytics dashboards.

**Built with:** React, FastAPI, PostgreSQL, SQLAlchemy, Docker, Scikit-learn  
**Highlights:** Integrated TF-IDF and Logistic Regression to classify support tickets into Hardware, Software, Network, Account Access, and Other.

[GitHub](https://github.com/Saiprasad48/smart-it-helpdesk)

---

### Customer Churn Prediction with Explainable AI
End-to-end churn prediction system using telecom customer data, SQL-based EDA, classification modeling, explainability, and dashboarding.

**Built with:** Python, SQL, Scikit-learn, XGBoost, SHAP, Streamlit, Power BI, Docker  
**Highlights:** Used SHAP explanations to show customer-level churn probability and top churn reasons.

[GitHub](https://github.com/Saiprasad48/customer-churn-prediction-explainability)

---

### AI Job Match & Resume Analyzer using RAG
RAG-powered resume analysis application that compares resumes against job descriptions and generates match scores, skill gaps, keyword suggestions, and project recommendations.

**Built with:** Python, LangChain, Hugging Face, FAISS, PostgreSQL, Streamlit, Docker  

[GitHub](https://github.com/Saiprasad48/ai-job-match-resume-analyzer)

---

### Retail Demand Forecasting with MLOps
End-to-end sales forecasting pipeline with time-series feature engineering, LightGBM model training, MLflow experiment tracking, FastAPI serving, and PostgreSQL storage.

**Built with:** Python, LightGBM, MLflow, FastAPI, PostgreSQL, Docker  

[GitHub](https://github.com/Saiprasad48/retail-demand-forecasting-mlops)

---

### PostgreSQL-Based Image Retrieval with pgvector
PostgreSQL-native image similarity search system using ResNet-50 embeddings, pgvector, and HNSW indexing on CIFAR-10.

**Built with:** PostgreSQL, pgvector, HNSW, ResNet-50, Python  
**Highlights:** Reduced filtered query latency from 891 ms to 203 ms using adaptive filtered ANN retrieval and compact vector reranking.

[GitHub](https://github.com/Saiprasad48/postgresql-image-retrieval-pgvector)

---

## What I’m Working On

- Building LLM agents with real evaluation: golden sets, held-out sets, and adversarial safety suites
- Making AI systems reliable in production: guardrails, model fallbacks, caching, and rate limiting
- Building AI-focused full-stack projects with real deployment workflows and CI/CD
- Strengthening data modeling (dbt), cloud deployment, Docker, database, and API design skills

---

## Let’s Connect

- 💼 [LinkedIn](https://www.linkedin.com/in/saiprasadkukudala)
- 🌐 [Portfolio](https://sai-portfolio-egbw.vercel.app)
- 📧 saiprasadkukudala18@gmail.com
- 💻 [GitHub](https://github.com/Saiprasad48)

---

![Profile Views](https://komarev.com/ghpvc/?username=Saiprasad48&label=Profile%20views&color=0e75b6&style=flat)
