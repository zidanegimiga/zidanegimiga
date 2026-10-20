# Hey, I'm Zidane

**Full-stack engineer based in Nairobi. I build backends that don't fall over and AI features people actually use.**

I've spent around seven years shipping production software across healthcare, fintech, media and e-commerce. These days most of my work sits where solid backend engineering meets applied AI: pipelines, retrieval, document intelligence, and the interfaces that make it all usable.

- 🔭 Building AI products and the infrastructure under them
- 🌱 Going deeper on agentic AI and multi-agent orchestration
- 🧭 Growing into engineering leadership, without giving up the code
- 💬 Ask me about queues, retries, and why your job ran twice
- ⚡ Fun fact: I once ran backstage for a fashion show. Turns out coordinating models and coordinating microservices is not that different.

---

## 🛠️ What I Work With

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Backend**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

**Frontend and Mobile**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Data and AI**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)

**Infrastructure**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![NGINX](https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

---

## 🚀 Featured Projects

### 🏥 [Claims Engine](https://github.com/zidanegimiga/case-engine)
- A REST API that adjudicates healthcare insurance claims: upload a PDF claim form or invoice, get back a decision with reasons
- Vision models pull structured data from scanned documents, with Tesseract as an offline fallback behind a swappable provider interface
- A three-stage pipeline of rules plus an XGBoost fraud model, with SHAP explanations for every prediction
- Python, FastAPI, MongoDB, Streamlit dashboard, Docker, pytest

### 🎙️ [Interview Transcriber](https://github.com/zidanegimiga/interview-transcriptor) · [Live demo](https://interview-transcriptor-frontend.vercel.app)
- Upload an interview recording, get back a transcript with speaker labels plus a summary, sentiment, Q&A pairs, strengths and red flags
- FastAPI and async MongoDB on the backend, Next.js on the front, Deepgram for transcription and GPT-4o-mini for analysis
- Background processing with webhooks instead of polling, real-time UI updates, and 44 backend tests

### 📡 [Embed Widget Lab](https://github.com/zidanegimiga/embed-widget-lab)
- A draggable React widget any site can embed with one script tag, isolated from the host page with Shadow DOM
- Streams live alerts over WebSocket or server-sent events, fed by RabbitMQ through a durable queue and a fanout exchange
- Origin allowlists, token checks and rate limiting, and it refuses to boot in production without its secrets

### 🎫 [Docket](https://github.com/zidanegimiga/docket)
- A support ticket tracker built to show how I structure a codebase, not just what it does
- Next.js and Express in a Turborepo, PostgreSQL with Prisma, and shared Zod contracts so the API, the UI and the tests all validate against one schema
- Layered routes, services and repositories wired in one place so everything can be faked in tests, plus an honest write-up of the trade-offs

### 🧩 More Things I've Built
- ⚽ [Football Data Surveyor](https://github.com/zidanegimiga/football_data_surveyor): ask questions about football data in plain English and Gemini turns them into MongoDB queries
- 🧠 [Semantic Embeddings Service](https://github.com/zidanegimiga/RAG-semantic-embeddings-generator): generates embeddings from MongoDB records into ChromaDB for retrieval
- ✨ [Cosmic Ink](https://github.com/zidanegimiga/graffiti_app) · [Live demo](https://graffiti-app.vercel.app): paint glowing particle trails across deep space on an HTML canvas, built one concept per commit

### 🚧 Currently Building
- **Daedalus:** an AI onboarding assistant that answers new hires' questions from a company's own tools, with live citations. Python, FastAPI, PostgreSQL with pgvector, LangGraph.
- **Jalada AI:** helps Kenyans keep income and expense records from receipt photos and messages. Chatbot plus dashboard, designed for basic phones.

---

## 🏗️ Things I've Shipped at Work

- 🏥 A claims pipeline processing **10,000+ insurance claims a month**, with distributed locking and automatic recovery of failed jobs
- 🩺 A React widget embedded in major Kenyan hospitals, built on an architecture designed for **100,000 visits a day**
- 📊 A natural-language analytics platform over **50,000+ survey records** that took analyst time-to-insight from hours to **under 2 minutes**
- 🗳️ A real-time voting platform handling **20,000+ concurrent users**
- 💬 A reusable WhatsApp integration rolled out to **15+ client CRMs**, cutting delivery from 3 weeks to under 4 days

---

## 📈 GitHub Stats

<table>
  <tr>
    <td><img src="https://github-readme-stats.vercel.app/api?username=zidanegimiga&show_icons=true&hide_border=true" alt="GitHub stats" /></td>
    <td><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=zidanegimiga&layout=compact&hide_border=true" alt="Top languages" /></td>
  </tr>
</table>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=zidanegimiga&hide_border=true" alt="GitHub streak" />
</p>

---

## 🤝 Let's Talk

I'm open to full-stack, backend and AI engineering roles in Nairobi or remote.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://ke.linkedin.com/in/zidane-gimiga-976379135)
[![X](https://img.shields.io/badge/@iamGimiga-000000?style=flat-square&logo=x&logoColor=white)](https://twitter.com/iamGimiga)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:hellozidanegimiga@gmail.com)
