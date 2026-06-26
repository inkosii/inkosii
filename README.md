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

I enjoy designing and building backend systems, enterprise applications, and data-driven solutions that address real-world problems.

This is where I document both sides of that work.

---

## GitHub Stats

<div align="center" style="background: #f6f8fa; padding: 20px; border-radius: 8px; margin: 20px 0; border: 1px solid #667eea;">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=inkosii&theme=algolia&show_icons=true&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=inkosii&theme=algolia&layout=compact&hide_border=true)

</div>

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

## Expertise Depth

<div style="background: #f0f4ff; padding: 20px; border-radius: 8px; margin: 20px 0; border: 1px solid #667eea;">

| Area | Technologies & Concepts | Representative Projects |
|:------|:-------------------------|:-------------------------|
| **Java & Enterprise Development** | Java, Spring Boot, REST APIs, Enterprise Application Design | Cloud-Sim Bank, Enterprise Microservices |
| **Cloud & Infrastructure** | Docker, API Gateways, Monitoring & Logging, Distributed Systems Concepts | Cloud-Sim Bank |
| **Machine Learning & NLP** | FastText, Cross-Lingual Embeddings, Time-Series Forecasting, Model Evaluation | Cross-Lingual Embeddings, Electricity Demand Forecasting |
| **Data & Analytics** | Python, Pandas, Power BI, Streamlit, Statistical Analysis | Demand Dashboard, Analytics Projects |
| **Web Development** | HTML5, CSS3, JavaScript, Responsive Design | SA Taxi Platform, Student Dashboard |

</div>

---

## Currently Learning

Working on strengthening my understanding of enterprise software architecture, distributed systems, observability practices, and modern Java development while applying these concepts in a banking technology environment.

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

A microservices-based banking platform developed to explore modern enterprise architecture patterns. The project demonstrates service-to-service communication, API gateway integration, centralized monitoring, logging, and independent service deployment within a distributed system.

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

**Why This Work Matters:**

Language is inseparable from culture and identity. If AI systems only work in English, they encode a particular worldview. This research contributes to making machine learning more inclusive and ensuring technology can serve diverse communities.

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

---

### 3. Electricity Demand Forecasting with ARIMA/ARIMAX

Time-series forecasting model predicting electricity demand using temperature and temporal variables. Achieves strong accuracy on multi-step forecasts.

**Key Achievement:** ARIMAX model outperforms ARIMA baseline by 23% when including exogenous variables.

---

<div style="background: #e8f5e9; padding: 20px; border-radius: 8px; margin: 20px 0; border: 1px solid #4caf50;">

## Other Notable Work

**Data & Analytics**
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
