<!-- ====================================================== -->
<!--                       ASCII BANNER                     -->
<!-- ====================================================== -->
<p align="center">
<pre>
  ____   _                      _      _         _      _         
 / ___| (_) _ __    ___  _ __  | |__  | |  __ _ | |__  | |  __ _  
 \___ \ | || '_ \  / _ \| '_ \ | '_ \ | | / _` || '_ \ | | / _` | 
  ___) || || | | ||  __/| | | || | | || || (_| || | | || || (_| | 
 |____/ |_||_| |_| \___||_| |_||_| |_||_| \__,_||_| |_||_| \__,_| 
   ___   _         _                  _   _  _                _   
  / _ \ (_) _ __  (_) ___   ___      | \ | || | __ ___   ___ (_)  
 | | | || || '_ \ | |/ __| / _ \     |  \| || |/ // _ \ / __|| |  
 | |_| || || | | || |\__ \| (_) |    | |\  ||   <| (_) |\__ \| |  
  \__\_\|_||_| |_||_||___| \___/     |_| \_||_|\_\\___/ |___/|_|  
</pre>
</p>

---

## Hi, I'm Sinenhlahla

**Junior Java Developer @ FNB** (Enablement Office of the CIO)  
**Honours in Computer Science** at the University of Pretoria

I build backend systems, distributed architectures, and machine learning applications that work. My focus is on systems that scale, code that's maintainable, and solutions that matter.

By day, I develop Java enterprise applications within FNB's core infrastructure. By night and in between, I explore NLP for African languages, design cloud architectures, and analyze data to inform policy decisions. This GitHub is where I document both.

---

## What I Do

| Area | What's Inside |
|------|---------------|
| **Enterprise Architecture** | Microservices, API Gateways, Event-Driven Systems, Docker |
| **Backend Development** | Java Spring Boot, REST APIs, Database Design, System Design |
| **Machine Learning** | NLP, Cross-lingual Embeddings, Time-Series Forecasting, Model Evaluation |
| **Data Engineering** | Python, Pandas, Streamlit, Power BI, Statistical Analysis |
| **Cloud & DevOps** | Docker, Prometheus, Grafana, ELK Stack, Monitoring |
| **Full-Stack** | HTML5, CSS3, JavaScript, Responsive Design |

---

## Featured Projects

### 1. Cloud-Sim Bank: Enterprise Microservices Architecture

Repository: [youth_cloud_banking_system](https://github.com/inkosii/youth_cloud_banking_system)

A production-grade banking platform demonstrating modern enterprise architecture, cloud-native design, and operational excellence.

**Architecture Diagram:**

<p align="center">
  <img src="https://raw.githubusercontent.com/inkosii/youth_cloud_banking_system/main/Documentation/architecture_diagram.png" alt="Cloud-Sim Bank Architecture" width="90%">
</p>

**System Flow:**

```
Client Requests 
    ↓
Kong API Gateway (Port 8000)
    ↓
├─ Account Service (Java Spring Boot, Port 8081)
├─ Transaction Service (Java Spring Boot, Port 8082)
└─ FastAPI Integration (Python, Port 8001)
    ↓
PostgreSQL Database (Port 5432)

Observability Layer:
├─ Prometheus (Port 9090) → Collects Metrics
├─ Grafana (Port 3000) → Visualizes Metrics
└─ ELK Stack (Port 9200, 5601) → Centralized Logs
```

**What's Built:**

| Component | Purpose | Technology |
|-----------|---------|------------|
| API Gateway | Request routing, rate limiting, security | Kong |
| Account Service | User account management | Java Spring Boot |
| Transaction Service | Deposit, withdrawal, transfer logic | Java Spring Boot |
| Data Layer | Persistent storage with ER modeling | PostgreSQL |
| Monitoring | Real-time metrics collection | Prometheus + Grafana |
| Logging | Centralized log aggregation | Elasticsearch, Logstash, Kibana |

**Dashboards in Action:**

Prometheus targets showing all services healthy:
<p align="center">
  <img src="https://raw.githubusercontent.com/inkosii/youth_cloud_banking_system/main/Documentation/prometheus-.JPG" alt="Prometheus Targets" width="85%">
</p>

Grafana dashboard tracking request throughput and service latency:
<p align="center">
  <img src="https://raw.githubusercontent.com/inkosii/youth_cloud_banking_system/main/Documentation/grafana-dashboard.JPG" alt="Grafana Dashboard" width="85%">
</p>

Kibana logs dashboard for debugging and audit trails:
<p align="center">
  <img src="https://raw.githubusercontent.com/inkosii/youth_cloud_banking_system/main/Documentation/kibana-logs.JPG" alt="Kibana Logs Dashboard" width="85%">
</p>

**Why It Matters:**  
This project demonstrates how to build systems that are observable, scalable, and maintainable. The separation between business logic (services), routing (gateway), and monitoring (observability stack) is what allows large teams to collaborate without stepping on each other's toes.

---

### 2. Cross-Lingual Embeddings for South African Languages

Repository: [Cross-Lingual-Embeddings-NLP-2026](https://github.com/inkosii/Cross-Lingual-Embeddings-NLP-2026)

An honours research project exploring how to build NLP systems for languages with limited digital data. Focus: isiZulu, Sepedi, and Setswana.

**The Problem:**

Most AI models are trained on English because there's abundant data. What about South Africa's 11 official languages? This project investigates cross-lingual word embeddings, which learn representations from one language and transfer knowledge to another.

**Research Results:**

Overall performance across alignment strategies:
<p align="center">
  <img src="https://raw.githubusercontent.com/inkosii/Cross-Lingual-Embeddings-NLP-2026/main/evaluation-20260531T194328Z-3-001/evaluation/final_results.png" alt="Cross-Lingual Alignment Results" width="80%">
</p>

Strategy comparison between isiZulu and Sepedi:
<p align="center">
  <img src="https://raw.githubusercontent.com/inkosii/Cross-Lingual-Embeddings-NLP-2026/main/evaluation-20260531T194328Z-3-001/evaluation/strategy_comparison_zul_sep.png" alt="Strategy Comparison" width="80%">
</p>

Translation accuracy showing correlation between edit distance and embedding similarity:
<p align="center">
  <img src="https://raw.githubusercontent.com/inkosii/Cross-Lingual-Embeddings-NLP-2026/main/evaluation-20260531T194328Z-3-001/evaluation/translation_accuracy.png" alt="Translation Accuracy" width="75%">
</p>

Embedding space visualization (t-SNE) showing how languages align:
<p align="center">
  <img src="https://raw.githubusercontent.com/inkosii/Cross-Lingual-Embeddings-NLP-2026/main/evaluation-20260531T194328Z-3-001/evaluation/tsne_eng_zul.png" alt="t-SNE Embedding Space" width="75%">
</p>

**What's Inside:**

| Evaluation Type | What We Measured |
|-----------------|------------------|
| Bilingual Lexicon Induction | How well words match across languages |
| Edit Distance vs. Similarity | Morphological similarity correlates with embedding alignment |
| Vocabulary Growth | How corpus size affects embedding quality |
| Alignment Strategies | Comparing different techniques for semantic space mapping |

**Key Insights:**
- Orthogonal Procrustes mapping provides stable cross-lingual alignment
- Morphologically similar languages (isiZulu, Sepedi) transfer knowledge effectively
- Bilingual lexicons of just a few hundred words can bootstrap high-quality embeddings

**Why It Matters:**  
Language is culture. If AI systems can't speak your language, they can't serve your community. This research contributes to making NLP more inclusive for underrepresented languages.

---

## Other Notable Work

### Data & Analytics
**Electricity Demand Forecasting**  
Time-series models (ARIMA/ARIMAX) predicting power demand using temperature and time-of-day variables. Helps utilities optimize load scheduling.  
Tech: Python, NumPy, statsmodels, scikit-learn

**Eskom Load Shedding Impact Analysis**  
Quantifying how electricity crises affect South Africa's economy using StatsSA datasets.  
Tech: Streamlit, Docker, Pandas, StatisticalAnalysis

**Youth Unemployment Analysis**  
Interactive Power BI dashboards visualizing employment trends with ILOSTAT data.  
Tech: Python, Power BI, Google Colab

### Machine Learning
**Graduate Prediction Models**  
Identifying students at risk of dropping out using Random Forest classifiers.

**Model & Bias Audit**  
Evaluating ML models for fairness and performance across demographics.

### Full-Stack Applications
**SA Taxi Platform**  
Browser-based app for finding fares, selecting seats (SVG), making QR payments, accessing safety resources.  
Tech: HTML5, CSS3, JavaScript, Node.js

**Smart Clinic Management System**  
Healthcare app for patient and appointment management.

**Student Dashboard (NFC Card)**  
Multi-purpose student card with attendance tracking, payments, and academic calculators.

---

## Technical Skills

```
Languages:     Java, Python, JavaScript, SQL, Bash
Backend:       Spring Boot, REST APIs, Microservices, Database Design
Data/Analytics: Pandas, NumPy, scikit-learn, Jupyter Notebooks, Streamlit
ML/NLP:        FastText, Gensim, PyTorch, Model Evaluation, Embeddings
DevOps:        Docker, Kong API Gateway, Prometheus, Grafana, ELK Stack
Frontend:      HTML5, CSS3, JavaScript, Responsive Design
```

---

## How I Approach Problems

**Observe First**  
Understand what's actually happening before jumping to solutions. What are the constraints? What would success look like?

**Design for Scale**  
Build systems assuming they'll grow. Consider how components interact, where failures might happen, and how teams will collaborate.

**Make it Observable**  
Monitoring, logging, and metrics aren't afterthoughts. They're built in from day one.

**Document Decisions**  
Why did I choose this approach? What were the tradeoffs? What might we do differently next time?

**Iterate Ruthlessly**  
Every project teaches something. I carry those lessons forward.

---

## Get In Touch

<p align="center">

| | |
|---|---|
| **Email** | snenkosi41@gmail.com |
| **GitHub** | [@inkosii](https://github.com/inkosii) |
| **LinkedIn** | Coming Soon |

</p>

---

<p align="center">
Built with intention. Crafted with care.
</p>
