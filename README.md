<!-- ====================================================== -->
<!--                       ASCII BANNER                     -->
<!-- ====================================================== -->
<p align="center">
<pre style="font-size: 12px; color: #00D9FF;">
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

![Typing Animation](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=4000&pause=1000&color=00D9FF&center=true&vCenter=true&multiline=true&width=600&height=100&lines=Junior+Java+Developer+at+FNB;Enterprise+Systems+%26+Cloud+Architecture;NLP+Research+on+African+Languages)

</div>

---

<div align="center" style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); padding: 30px; border-radius: 10px; margin: 20px 0;">

## Hi, I'm Sinenhlahla

**Java Developer** | **FNB Enablement Office of the CIO**  
**Honours in Computer Science** | **University of Pretoria**

</div>

I build systems that scale. Backend infrastructure, distributed architectures, and machine learning applications that solve real problems. At FNB, I contribute to enterprise Java development within the core infrastructure team. Outside of work, I research NLP for South African languages and design cloud systems.

This is where I document both sides of that work.

---

<div style="background: #f6f8fa; border-left: 4px solid #667eea; padding: 20px; border-radius: 5px; margin: 20px 0;">

## What I Build

| Focus Area | Tech Stack |
|:-----------|:-----------|
| **Enterprise Backend** | Java, Spring Boot, REST APIs, Microservices, Database Design |
| **Cloud & Infrastructure** | Docker, Kong API Gateway, Prometheus, Grafana, ELK Stack |
| **Machine Learning** | NLP, Cross-lingual Embeddings, Time-Series Forecasting, Model Evaluation |
| **Data Engineering** | Python, Pandas, NumPy, scikit-learn, Streamlit |
| **Full-Stack Development** | HTML5, CSS3, JavaScript, Responsive Design |

</div>

---

## Featured Projects

### 1. Cloud-Sim Bank: Enterprise Microservices Architecture

<div align="center">

[![Java](https://img.shields.io/badge/Java-Spring%20Boot-ED8B00?style=flat-square&logo=spring&logoColor=white)](https://spring.io/)
[![Kong](https://img.shields.io/badge/Kong-API%20Gateway-003D7A?style=flat-square&logo=kong&logoColor=white)](https://konghq.com/)
[![Docker](https://img.shields.io/badge/Docker-Containerization-2496ED?style=flat-square&logo=docker&logoColor=white)](https://www.docker.com/)
[![Prometheus](https://img.shields.io/badge/Prometheus-Monitoring-E6522C?style=flat-square&logo=prometheus&logoColor=white)](https://prometheus.io/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-336791?style=flat-square&logo=postgresql&logoColor=white)](https://www.postgresql.org/)

</div>

**Repository:** [youth_cloud_banking_system](https://github.com/inkosii/youth_cloud_banking_system)

A production-grade banking platform built to explore modern enterprise architecture. It demonstrates how distributed services communicate, how to monitor systems at scale, and how to structure code so teams can work independently.

**System Architecture:**

<p align="center">
  <img src="https://raw.githubusercontent.com/inkosii/youth_cloud_banking_system/main/Documentation/architecture_diagram.png" alt="Cloud-Sim Bank Architecture" width="90%">
</p>

<div style="background: #f0f4ff; padding: 20px; border-radius: 8px; margin: 20px 0; border: 1px solid #667eea;">

**How It Works:**

```
Client
  │
  ├─ Kong API Gateway (8000)
  │  - Request routing
  │  - Rate limiting
  │  - Authentication
  │
  ├─ Account Service (8081)
  │  - User management
  │  - Account operations
  │
  ├─ Transaction Service (8082)
  │  - Deposits/Withdrawals
  │  - Transfer logic
  │
  └─ PostgreSQL (5432)
     - Persistent storage
     - ER modeled schema

Observer Layer:
  • Prometheus (9090) → Metrics collection
  • Grafana (3000) → Dashboard visualization  
  • ELK Stack (9200, 5601) → Centralized logging
```

</div>

**Component Breakdown:**

| Component | Purpose | Technology |
|:----------|:--------|:-----------|
| API Gateway | Routes requests, enforces policies | Kong |
| Account Service | Manages user accounts and operations | Java Spring Boot |
| Transaction Service | Processes banking transactions | Java Spring Boot |
| Database | Data persistence | PostgreSQL |
| Metrics | System observability | Prometheus + Grafana |
| Logs | Centralized log aggregation | Elasticsearch, Logstash, Kibana |

**What's Actually Running:**

Prometheus collecting metrics from all services:
<p align="center">
  <img src="https://raw.githubusercontent.com/inkosii/youth_cloud_banking_system/main/Documentation/prometheus-.JPG" alt="Prometheus Targets" width="85%">
</p>

<p align="center" style="font-size: 12px; color: #666;">All services reporting metrics successfully</p>

Grafana dashboards showing throughput, latency, and health:
<p align="center">
  <img src="https://raw.githubusercontent.com/inkosii/youth_cloud_banking_system/main/Documentation/grafana-dashboard.JPG" alt="Grafana Dashboard" width="85%">
</p>

<p align="center" style="font-size: 12px; color: #666;">Real-time metrics: request throughput, response latency, service health</p>

Kibana making logs searchable across all services:
<p align="center">
  <img src="https://raw.githubusercontent.com/inkosii/youth_cloud_banking_system/main/Documentation/kibana-logs.JPG" alt="Kibana Logs Dashboard" width="85%">
</p>

<p align="center" style="font-size: 12px; color: #666;">Centralized logs for debugging and compliance</p>

**Why This Approach Matters:**

When you separate concerns like this, each service can be developed, tested, and deployed independently. The API gateway handles cross-cutting concerns like authentication and rate limiting. Monitoring is built in from the start, not bolted on later. When something breaks, you have metrics and logs to understand what happened. This is how modern systems work at scale.

---

### 2. Cross-Lingual Embeddings for South African Languages

<div align="center">

[![NLP](https://img.shields.io/badge/NLP-FastText-4B8BBE?style=flat-square&logo=python&logoColor=white)](https://fasttext.cc/)
[![Research](https://img.shields.io/badge/Research-Embeddings-FF6B6B?style=flat-square)](https://github.com/inkosii/Cross-Lingual-Embeddings-NLP-2026)
[![Languages](https://img.shields.io/badge/Languages-isiZulu%2CSepedi%2CSetswana-1ABC9C?style=flat-square)](https://github.com/inkosii/Cross-Lingual-Embeddings-NLP-2026)

</div>

**Repository:** [Cross-Lingual-Embeddings-NLP-2026](https://github.com/inkosii/Cross-Lingual-Embeddings-NLP-2026)

An honours research project investigating a real problem: how do you build NLP systems for languages that don't have large amounts of digital training data?

**The Challenge:**

Most AI models perform well on English because there's abundant training data. South Africa has 11 official languages. If technology can't understand them, it can't serve the people who speak them. This project explores cross-lingual embeddings where knowledge learned from one language transfers to another.

<div style="background: #fff3e0; padding: 20px; border-radius: 8px; margin: 20px 0; border: 1px solid #ff9800;">

**What We Did:**

1. Trained FastText embeddings for isiZulu, Sepedi, and Setswana
2. Used orthogonal Procrustes mapping to align semantic spaces across languages
3. Evaluated alignment quality through bilingual lexicon induction and downstream tasks
4. Analyzed what makes alignment work (morphological similarity, vocabulary overlap, etc.)

</div>

**Results Across Alignment Strategies:**

<p align="center">
  <img src="https://raw.githubusercontent.com/inkosii/Cross-Lingual-Embeddings-NLP-2026/main/evaluation-20260531T194328Z-3-001/evaluation/final_results.png" alt="Cross-Lingual Alignment Results" width="80%">
</p>

<p align="center" style="font-size: 12px; color: #666;">Final performance metrics across all alignment strategies</p>

**Strategy Comparison Between Languages:**

<p align="center">
  <img src="https://raw.githubusercontent.com/inkosii/Cross-Lingual-Embeddings-NLP-2026/main/evaluation-20260531T194328Z-3-001/evaluation/strategy_comparison_zul_sep.png" alt="Strategy Comparison" width="80%">
</p>

<p align="center" style="font-size: 12px; color: #666;">Comparing different embedding alignment techniques</p>

**Morphological Similarity Matters:**

<p align="center">
  <img src="https://raw.githubusercontent.com/inkosii/Cross-Lingual-Embeddings-NLP-2026/main/evaluation-20260531T194328Z-3-001/evaluation/translation_accuracy.png" alt="Translation Accuracy" width="75%">
</p>

<p align="center" style="font-size: 12px; color: #666;">Words that look similar across languages align better</p>

**Visualizing the Semantic Space (t-SNE):**

<p align="center">
  <img src="https://raw.githubusercontent.com/inkosii/Cross-Lingual-Embeddings-NLP-2026/main/evaluation-20260531T194328Z-3-001/evaluation/tsne_eng_zul.png" alt="t-SNE Embedding Space" width="75%">
</p>

<p align="center" style="font-size: 12px; color: #666;">How English and isiZulu semantic spaces align after Procrustes mapping</p>

**Key Findings:**

- Orthogonal Procrustes mapping creates stable, meaningful alignments
- Morphologically similar languages transfer knowledge better
- Just a few hundred bilingual word pairs can bootstrap high-quality embeddings
- Anchor words act as bridges between semantic spaces

| Evaluation | Metric |
|:-----------|:-------|
| Bilingual Lexicon Induction | How accurately we match words across languages |
| Edit Distance vs Similarity | Morphological similarity predicts alignment quality |
| Vocabulary Growth | More training data improves embedding stability |
| Strategy Comparison | Different alignment techniques have different tradeoffs |

**Why This Matters:**

Language is inseparable from culture and identity. If AI systems only work in English, they encode a particular worldview. This work is part of a larger effort to make machine learning systems that understand and serve the full diversity of languages and communities.

---

<div style="background: #e8f5e9; padding: 20px; border-radius: 8px; margin: 20px 0; border: 1px solid #4caf50;">

## Other Work

**Data & Analytics**
- Electricity Demand Forecasting with ARIMA/ARIMAX models
- Eskom Load Shedding Impact Analysis (Streamlit dashboards)
- Youth Unemployment Analysis (Power BI visualizations)

**Machine Learning**
- Graduate Prediction Models (Random Forest classification)
- Model and Bias Audit (fairness evaluation)

**Full-Stack Applications**
- SA Taxi Platform (fares, routes, seat selection, QR payments)
- Smart Clinic Management System
- Student Dashboard with NFC functionality

</div>

---

<div style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); padding: 30px; border-radius: 8px; margin: 20px 0; color: white;">

## Technical Foundation

```
Backend Infrastructure
├─ Java & Spring Boot
├─ REST API design
├─ Microservices architecture
└─ System design

Data & Analysis
├─ Python data stack
├─ Statistical modeling
├─ Time-series forecasting
└─ ML pipeline development

Operations
├─ Docker containerization
├─ Prometheus monitoring
├─ Grafana dashboards
├─ ELK stack logging
└─ Kong API gateway

Language & NLP
├─ FastText embeddings
├─ Cross-lingual alignment
├─ Gensim toolkit
└─ Evaluation methodologies
```

</div>

---

## How I Work

**Start with understanding.** What's the actual problem? What constraints exist? What does success look like?

**Design for people.** Not just now, but how this system will grow and how teams will collaborate on it.

**Build observability in.** Monitoring, logging, and metrics from day one. You can't fix what you can't see.

**Document the reasoning.** Why this approach? What were the tradeoffs? What might we change next time?

**Learn and iterate.** Each project teaches something. I carry those lessons forward.

---

<div align="center">

## Connect

[![Email](https://img.shields.io/badge/Email-snenkosi41%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:snenkosi41@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-@inkosii-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/inkosii)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sinenhlahla%20Nkosi-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://za.linkedin.com/in/sinenhlahla-nkosi-9305b8372)

</div>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=inkosii&label=Profile+Views&color=667eea&style=flat-square" alt="Profile Views">
</p>

<div align="center" style="margin-top: 40px; padding: 20px; background: #f6f8fa; border-radius: 8px;">

Built with intention. Crafted with care.

*Continuously learning, building, and improving*

</div>
