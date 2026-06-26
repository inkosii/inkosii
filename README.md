<!-- ====================================================== -->
<!--                       ASCII BANNER                     -->
<!-- ====================================================== -->
<p align="center">
<pre>
  ____   _                      _      _         _      _         
 / ___| (_) _ __    ___  _ __  | |__  | |  __ _ | |__  | |  __ _  
 \___ \ | || '_ \  / _ \| '_ \ | '_ \ | | / _` || '_ \ | | / _` | 
  ___) || || | | ||  __/| | | || | | || || (_| || | | || || (_| | 
 |____| |_||_| |_| \___||_| |_||_| |_||_| \__,_||_| |_||_| \__,_| 
   ___   _         _                  _   _  _                _   
  / _ \ (_) _ __  (_) ___   ___      | \ | || | __ ___   ___ (_)  
 | | | || || '_ \ | |/ __| / _ \     |  \| || |/ // _ \ / __|| |  
 | |_| || || | | || |\__ \| (_) |    | |\  ||   <| (_) |\__ \| |  
  \__\_\|_||_| |_||_||___| \___/     |_| \_||_|\_\\___/ |___/|_|  
</pre>
</p>

<div align="center">

![Typing Animation](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=4000&pause=1000&color=00D9FF&center=true&vCenter=true&multiline=true&width=600&height=100&lines=Junior+Java+Developer+%40+FNB;Building+Systems+That+Scale;Exploring+AI+for+African+Languages)

</div>

---

## 🚀 Hi, I'm Sinenhlahla

**Junior Java Developer @ FNB** (Enablement Office of the CIO)  
**Honours in Computer Science** at the University of Pretoria

I build backend systems, distributed architectures, and machine learning applications that work. My focus is on systems that scale, code that's maintainable, and solutions that matter.

By day, I develop Java enterprise applications within FNB's core infrastructure. By night and in between, I explore NLP for African languages, design cloud architectures, and analyze data to inform policy decisions. This GitHub is where I document both.

---

## <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="40"> What I Do

| 🎯 Area | 🛠️ What's Inside |
|---------|------------------|
| **Enterprise Architecture** | Microservices, API Gateways, Event-Driven Systems, Docker |
| **Backend Development** | Java Spring Boot, REST APIs, Database Design, System Design |
| **Machine Learning** | NLP, Cross-lingual Embeddings, Time-Series Forecasting, Model Evaluation |
| **Data Engineering** | Python, Pandas, Streamlit, Power BI, Statistical Analysis |
| **Cloud & DevOps** | Docker, Prometheus, Grafana, ELK Stack, Monitoring |
| **Full-Stack** | HTML5, CSS3, JavaScript, Responsive Design |

---

## 🎨 Featured Projects

### 1️⃣ Cloud-Sim Bank: Enterprise Microservices Architecture

<img src="https://img.shields.io/badge/Java-Spring%20Boot-ED8B00?style=flat-square&logo=spring&logoColor=white" /> <img src="https://img.shields.io/badge/Kong-API%20Gateway-003D7A?style=flat-square&logo=kong&logoColor=white" /> <img src="https://img.shields.io/badge/Docker-Containerization-2496ED?style=flat-square&logo=docker&logoColor=white" /> <img src="https://img.shields.io/badge/Prometheus-Monitoring-E6522C?style=flat-square&logo=prometheus&logoColor=white" />

**Repository:** [youth_cloud_banking_system](https://github.com/inkosii/youth_cloud_banking_system)

A production-grade banking platform demonstrating modern enterprise architecture, cloud-native design, and operational excellence.

**Architecture Diagram:**

<p align="center">
  <img src="https://raw.githubusercontent.com/inkosii/youth_cloud_banking_system/main/Documentation/architecture_diagram.png" alt="Cloud-Sim Bank Architecture" width="90%">
</p>

**System Flow:**

```
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│  Client Requests                                           │
│       ↓                                                     │
│  Kong API Gateway (Port 8000)                             │
│       ↓                                                     │
│  ┌─────────────────────────────────────────┐              │
│  │  Microservices Layer                   │              │
│  ├─────────────────────────────────────────┤              │
│  │ • Account Service (Java, Port 8081)    │              │
│  │ • Transaction Service (Java, Port 8082) │              │
│  │ • FastAPI Integration (Python, 8001)   │              │
│  └─────────────────────────────────────────┘              │
│       ↓                                                     │
│  PostgreSQL Database (Port 5432)                          │
│                                                             │
│  ═══════════════════════════════════════════              │
│  Observability Layer:                                     │
│  ├─ Prometheus (Port 9090) → Metrics                      │
│  ├─ Grafana (Port 3000) → Dashboards                      │
│  └─ ELK Stack → Centralized Logs                          │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

**What's Built:**

| 🔧 Component | 📋 Purpose | 💻 Technology |
|:----------:|:----------:|:----------:|
| API Gateway | Request routing, rate limiting, security | Kong |
| Account Service | User account management | Java Spring Boot |
| Transaction Service | Deposit, withdrawal, transfer logic | Java Spring Boot |
| Data Layer | Persistent storage with ER modeling | PostgreSQL |
| Monitoring | Real-time metrics collection | Prometheus + Grafana |
| Logging | Centralized log aggregation | ELK Stack |

**Dashboards in Action:**

Prometheus targets showing all services healthy:
<p align="center">
  <img src="https://raw.githubusercontent.com/inkosii/youth_cloud_banking_system/main/Documentation/prometheus-.JPG" alt="Prometheus Targets" width="85%">
  <br>
  <sub><i>✓ All services reporting metrics successfully</i></sub>
</p>

Grafana dashboard tracking request throughput and service latency:
<p align="center">
  <img src="https://raw.githubusercontent.com/inkosii/youth_cloud_banking_system/main/Documentation/grafana-dashboard.JPG" alt="Grafana Dashboard" width="85%">
  <br>
  <sub><i>Real-time metrics: throughput, latency, service health</i></sub>
</p>

Kibana logs dashboard for debugging and audit trails:
<p align="center">
  <img src="https://raw.githubusercontent.com/inkosii/youth_cloud_banking_system/main/Documentation/kibana-logs.JPG" alt="Kibana Logs Dashboard" width="85%">
  <br>
  <sub><i>Searchable logs across all services</i></sub>
</p>

**Why It Matters:**  
This project demonstrates how to build systems that are observable, scalable, and maintainable. The separation between business logic (services), routing (gateway), and monitoring (observability stack) is what allows large teams to collaborate without stepping on each other's toes.

---

### 2️⃣ Cross-Lingual Embeddings for South African Languages

<img src="https://img.shields.io/badge/NLP-FastText-4B8BBE?style=flat-square&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/Research-Embeddings-FF6B6B?style=flat-square" /> <img src="https://img.shields.io/badge/Languages-isiZulu%2C%20Sepedi%2C%20Setswana-1ABC9C?style=flat-square" />

**Repository:** [Cross-Lingual-Embeddings-NLP-2026](https://github.com/inkosii/Cross-Lingual-Embeddings-NLP-2026)

An honours research project exploring how to build NLP systems for languages with limited digital data. Focus: isiZulu, Sepedi, and Setswana.

**The Problem:**

Most AI models are trained on English because there's abundant data. What about South Africa's 11 official languages? This project investigates cross-lingual word embeddings, which learn representations from one language and transfer knowledge to another.

**Research Results:**

Overall performance across alignment strategies:
<p align="center">
  <img src="https://raw.githubusercontent.com/inkosii/Cross-Lingual-Embeddings-NLP-2026/main/evaluation-20260531T194328Z-3-001/evaluation/final_results.png" alt="Cross-Lingual Alignment Results" width="80%">
  <br>
  <sub><i>Final performance metrics across all alignment strategies</i></sub>
</p>

Strategy comparison between isiZulu and Sepedi:
<p align="center">
  <img src="https://raw.githubusercontent.com/inkosii/Cross-Lingual-Embeddings-NLP-2026/main/evaluation-20260531T194328Z-3-001/evaluation/strategy_comparison_zul_sep.png" alt="Strategy Comparison" width="80%">
  <br>
  <sub><i>Comparing different embedding alignment techniques</i></sub>
</p>

Translation accuracy showing correlation between edit distance and embedding similarity:
<p align="center">
  <img src="https://raw.githubusercontent.com/inkosii/Cross-Lingual-Embeddings-NLP-2026/main/evaluation-20260531T194328Z-3-001/evaluation/translation_accuracy.png" alt="Translation Accuracy" width="75%">
  <br>
  <sub><i>Morphological similarity correlates with embedding alignment quality</i></sub>
</p>

Embedding space visualization (t-SNE) showing how languages align:
<p align="center">
  <img src="https://raw.githubusercontent.com/inkosii/Cross-Lingual-Embeddings-NLP-2026/main/evaluation-20260531T194328Z-3-001/evaluation/tsne_eng_zul.png" alt="t-SNE Embedding Space" width="75%">
  <br>
  <sub><i>Semantic space alignment between English and isiZulu</i></sub>
</p>

**What's Inside:**

| 📊 Evaluation Type | 🔍 What We Measured |
|:-:|:-:|
| Bilingual Lexicon Induction | How well words match across languages |
| Edit Distance vs. Similarity | Morphological similarity correlates with embedding alignment |
| Vocabulary Growth | How corpus size affects embedding quality |
| Alignment Strategies | Comparing different techniques for semantic space mapping |

**Key Insights:**
- ✓ Orthogonal Procrustes mapping provides stable cross-lingual alignment
- ✓ Morphologically similar languages (isiZulu, Sepedi) transfer knowledge effectively
- ✓ Bilingual lexicons of just a few hundred words can bootstrap high-quality embeddings

**Why It Matters:**  
Language is culture. If AI systems can't speak your language, they can't serve your community. This research contributes to making NLP more inclusive for underrepresented languages.

---

## 📚 Other Notable Work

### 📊 Data & Analytics
- **Electricity Demand Forecasting** - Time-series models (ARIMA/ARIMAX) predicting power demand  
- **Eskom Load Shedding Impact Analysis** - Quantifying electricity crisis effects on economy  
- **Youth Unemployment Analysis** - Interactive Power BI dashboards with ILOSTAT data  

### 🤖 Machine Learning
- **Graduate Prediction Models** - Identifying students at risk using Random Forest classifiers
- **Model & Bias Audit** - Evaluating ML models for fairness across demographics

### 💼 Full-Stack Applications
- **SA Taxi Platform** - Browser-based app for fares, seat selection, QR payments, safety resources
- **Smart Clinic Management System** - Healthcare app for patient and appointment management
- **Student Dashboard (NFC Card)** - Multi-purpose card with attendance, payments, calculators

---

## 💻 Technical Skills

```
╔════════════════════════════════════════════════════════════╗
║  Languages      │  Java, Python, JavaScript, SQL, Bash    ║
║  Backend        │  Spring Boot, REST APIs, Microservices  ║
║  Data/Analytics │  Pandas, NumPy, scikit-learn, Jupyter  ║
║  ML/NLP         │  FastText, Gensim, PyTorch, Embeddings ║
║  DevOps         │  Docker, Kong, Prometheus, Grafana     ║
║  Frontend       │  HTML5, CSS3, JavaScript, Responsive   ║
╚════════════════════════════════════════════════════════════╝
```

---

## 🎯 How I Approach Problems

```
Observe First → Design for Scale → Make it Observable → Document Decisions → Iterate
     ↓              ↓                    ↓                      ↓              ↓
Understand    Build for Growth    Monitoring,             Why did I      Every project
constraints   and collaboration   logging, metrics        choose this?   teaches me
                                  baked in from day 1                     something
```

**Observe First**  
Understand what's actually happening before jumping to solutions.

**Design for Scale**  
Build systems assuming they'll grow and teams will collaborate on them.

**Make it Observable**  
Monitoring, logging, and metrics aren't afterthoughts.

**Document Decisions**  
Why this approach? What were the tradeoffs? What could be better?

**Iterate Ruthlessly**  
Each project teaches something new.

---

## 📬 Get In Touch

<p align="center">

[![Email Badge](https://img.shields.io/badge/Email-snenkosi41%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:snenkosi41@gmail.com)
[![GitHub Badge](https://img.shields.io/badge/GitHub-@inkosii-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/inkosii)
[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-Coming%20Soon-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/inkosii)

</p>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=inkosii&label=Profile+Views&color=0E83F0&style=flat-square" alt="Profile Views">
</p>

<div align="center">

**Built with intention. Crafted with care.**

*Last updated: 2026* | *Continuously evolving*

</div>
