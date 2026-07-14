<div align="center">

# Hi, I'm Rakesh Kumar 👋

### M.Tech CSE (AI & ML) @ VIT Vellore · Building ML systems that don't fall apart in production

[![Portfolio](https://img.shields.io/badge/Portfolio-visit-8A2BE2?style=for-the-badge&logo=googlechrome&logoColor=white)](#)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](#)
[![GitHub](https://img.shields.io/badge/GitHub-follow-181717?style=for-the-badge&logo=github&logoColor=white)](#)
[![Email](https://img.shields.io/badge/Email-say%20hi-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rakeshofficial7317@gmail.com)

<sub>💡 Replace the `#` links above with your actual Portfolio / LinkedIn / GitHub URLs</sub>

</div>

---

### 🧑‍💻 About Me

- 🎓 Currently pursuing **M.Tech in CSE (AI & ML)** at VIT Vellore (GPA: 8.38/10)
- 🔬 Actively doing **research in adversarial ML for LLM security** — prompt injection detection — targeting a publishable paper
- 🛠️ Comfortable across the full stack of an ML system: **feature engineering → model architecture → deployment → monitoring → retraining**
- 🌐 Background in full-stack web development (React, Node.js, Express) before moving deeper into ML/DL and GenAI
- 📍 Based in India, open to **Student Intern** roles in ML, GenAI, and enterprise AI systems
- ⚡ Fun fact: I've built a system that detects when its own model is going stale — and fixes itself

---

### 🛡️ Responsible AI — Why It's Not an Afterthought for Me

A model that's 99% accurate in the lab and silently decaying in production isn't a safe model — it's a **ticking clock**. That belief shows up directly in how I build things:

- **Drift-aware by design** — my phishing detection system runs Page-Hinkley, ADWIN, and DDM concept-drift detectors in real time over live predictions, so degradation is caught in *dozens of samples*, not months of hindsight.
- **Human-in-the-loop, not human-out-of-the-loop** — instead of blind auto-retraining, uncertain predictions are routed to an active learning loop where a human oracle labels only the samples the model is genuinely unsure about, keeping a person in the decision path where it matters most.
- **Evaluation before deployment, not instead of it** — every model I ship gets tested for out-of-distribution generalization (not just in-distribution accuracy), because a benchmark score is not a safety guarantee.
- **Transparency over black boxes** — meta-learner feature importances, attention weights, and branch-level scores are surfaced explicitly, not hidden behind a single opaque probability.
- **Security-first LLM research** — my current research on prompt injection detection is fundamentally about making LLM systems *robust against adversarial manipulation* before they're deployed at scale.
- **Observability as a first-class concern** — exploring LangSmith, prompt evaluation, and observability tooling because a GenAI system you can't monitor is a GenAI system you can't trust.

I care about this because the gap between "works in the demo" and "safe in the world" is exactly where most AI harm actually happens — and closing that gap is the part of ML engineering I find most interesting.

---

### 🧰 Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**ML / DL**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**GenAI / NLP**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-Vector%20Search-blue?style=flat-square)

**MLOps / Infra**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

---

### 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

**🔍 Enterprise Multimodal RAG System**
<br>Hybrid Retrieval & Hierarchical Memory

Multimodal RAG supporting PDFs, images, audio, video, websites, YouTube, and source code. Hybrid retrieval (Dense + BM25), cross-encoder reranking, multimodal embeddings (BGE, ImageBind), hierarchical memory via LangGraph SQLite (short-term) + MongoDB (long-term). Deployed on AWS with FastAPI, ECS, ALB, CloudFront, evaluated with Ragas.

`Python` `FastAPI` `React` `LangChain` `LangGraph` `AWS` `Docker`

</td>
<td width="50%" valign="top">

**☁️ Distributed Cloud Deployment Platform**
<br>Kafka, ClickHouse, AWS ECS Fargate

A Git-to-deployment platform with isolated Docker builds on ECS + S3 and a custom streaming reverse proxy. V2 added PostgreSQL/Prisma for deployment metadata and migrated logging to a Kafka + ClickHouse pipeline for persistent, real-time build log ingestion.

`AWS ECS Fargate` `Kafka` `ClickHouse` `PostgreSQL` `Docker` `Next.js`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🛡️ GramBeddings — Hybrid Phishing URL Detection**
<br>DeepTCN, Meta-Stacking, Concept Drift Monitoring

Three-branch ensemble (SGD+TF-IDF, DeepTCN+Attention — AUC 0.9932, Isolation Forest) fused via a Random Forest meta-learner. 80,008-dim sparse feature pipeline with CSR compression cutting memory from 32GB → 200MB. Real-time drift monitoring (Page-Hinkley, ADWIN, DDM) over 160K predictions with an active learning loop for human-in-the-loop retraining.

`PyTorch` `Scikit-learn` `TF-IDF` `Isolation Forest` `SciPy`

</td>
<td width="50%" valign="top">

**🧪 Currently Researching**
<br>Prompt Injection Detection for LLM Security

Hybrid word-level + character-level BiLSTM with cross-attention fusion, normalization preprocessing, evaluated against novel attack types — synonym substitution, zero-width Unicode injection, homoglyph substitution, and combined attacks. Working toward a publishable paper.

`PyTorch` `NLP` `Adversarial ML` `LLM Security`

</td>
</tr>
</table>

---

### 💼 Experience

**Full Stack Web Developer Intern** — Johnnette AI *(Jul 2023 – Oct 2023)*
Built full-stack apps with React.js/Node.js/Express.js; RESTful auth APIs with JWT + RBAC; reusable React component libraries.

---

### 📜 Certifications

- Full Stack Web Development — 100xDevs
- Data Science with Python — Udemy

### 🤝 Positions of Responsibility

- **Uddesya Club — Member**, community outreach (food drives, blood donation camps, education programs reaching 50–200 beneficiaries)
- **DSA Coordinator** — ran DSA workshops and mentoring sessions for juniors, improving competitive programming ratings

---

### 📫 Let's Connect

I'm looking for **Student Intern** opportunities in ML, GenAI, and enterprise AI — feel free to reach out.

<div align="center">

[![Email](https://img.shields.io/badge/Email-rakeshofficial7317%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:rakeshofficial7317@gmail.com)
[![Phone](https://img.shields.io/badge/Phone-%2B91%207355066278-25D366?style=flat-square&logo=whatsapp&logoColor=white)](tel:+917355066278)

</div>

<div align="center">
<sub>⭐️ Thanks for stopping by — check out my pinned repos below!</sub>
</div>
