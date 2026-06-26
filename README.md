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
  \__\_\|_||_| |_||_||___/ \___/     |_| \_||_|\_\\___/ |___/|_|  
</pre>
</p>

---

## Building Software That Solves Real Problems

I'm **Sinenhlahla Qiniso Nkosi**, a software developer with a background in applied mathematics and computer science. I build enterprise systems, data-driven applications, and research-backed solutions that address real challenges.

My work spans three core areas: designing reliable distributed systems, developing machine learning applications for African language processing, and creating data analytics platforms that inform decision-making. Each project reflects my commitment to clean architecture, practical problem-solving, and measurable impact.

Currently, I develop Java-based enterprise applications while completing my Honours in Computer Science at the University of Pretoria. Beyond my day job, I explore how technology can tackle problems faced by communities across South Africa, whether that's electricity grid stability or accessible financial services.

This repository documents that journey. You'll find projects ranging from microservices architectures to NLP research, each representing a deliberate effort to learn, iterate, and improve.

---

## Featured Work

### Cloud-Sim Bank: Enterprise Banking Architecture

<p align="center">
  <img src="https://raw.githubusercontent.com/inkosii/youth_cloud_banking_system/main/Documentation/architecture_diagram.png" alt="Cloud-Sim Bank Architecture" width="90%">
</p>

**Repository:** [youth_cloud_banking_system](https://github.com/inkosii/youth_cloud_banking_system)

This project explores how modern enterprise systems are built, deployed, and monitored at scale. I designed and implemented a cloud-native banking platform that demonstrates microservices architecture, distributed systems patterns, and operational excellence.

**What's Inside:**

The platform routes all client requests through a Kong API Gateway, which enforces security and rate limiting. Behind the gateway sit two Java Spring Boot microservices: the Account Service manages user accounts and user operations, while the Transaction Service handles the core banking logic for deposits, withdrawals, and transfers. A PostgreSQL database ensures data persistence with properly designed entity relationships and referential integrity. For observability, Prometheus scrapes metrics from all services and feeds them into Grafana dashboards where you can monitor request throughput, service latency, and database performance in real-time. The ELK Stack (Elasticsearch, Logstash, Kibana) centralizes all logs, making it possible to search across services and debug production issues efficiently.

All services run in Docker containers orchestrated with Docker Compose, creating a reproducible local environment that mirrors production architecture.

**Key Technologies:**
- Java Spring Boot microservices
- Kong API Gateway for request routing
- PostgreSQL with ER modeling
- Prometheus and Grafana for monitoring
- ELK Stack for centralized logging
- Docker and Docker Compose

**Why This Project Matters:** It demonstrates how large-scale systems are built with clear separation of concerns, observability baked in from the start, and operational patterns that allow teams to understand what's happening in production.

---

### Cross-Lingual Embeddings for South African Languages

**Repository:** [Cross-Lingual-Embeddings-NLP-2026](https://github.com/inkosii/Cross-Lingual-Embeddings-NLP-2026)

This honours project investigates a specific problem: how do we build natural language processing systems for languages with limited digital resources? I focused on isiZulu, Sepedi, and Setswana—three of South Africa's most widely spoken languages.

**The Research:**

Most NLP models are trained on English because there's abundant data available. When you want to work with African languages, you have less training data to work with. My approach was to create multilingual word embeddings by training FastText embeddings for each language separately, then aligning their semantic spaces using orthogonal Procrustes mapping. This technique allows knowledge learned from one language to transfer to another.

I evaluated the quality of these alignments by testing how well the system could perform bilingual lexicon induction (matching words across languages with similar meanings), cross-lingual similarity tasks, and downstream NLP applications.

**Why This Matters:** Most AI systems today are built around English. If we want technology to serve all South Africans, we need systems that understand local languages. This project demonstrates one approach to that challenge and contributes to the broader work of making NLP more inclusive.

**Key Technologies:**
- FastText word embeddings
- Orthogonal Procrustes alignment
- Python, NumPy, Pandas
- Gensim and scikit-learn
- Jupyter Notebooks for experimentation

---

## Other Work

**Data & Analytics:**
- Electricity Demand Forecasting — ARIMA/ARIMAX time-series models predicting power demand using temperature and time-of-day variables
- Eskom Load Shedding Impact Analysis — Quantifying how electricity crises affect South Africa's economy using StatsSA datasets and Streamlit dashboards
- Youth Unemployment Analysis — Interactive Power BI dashboards analyzing employment trends with ILOSTAT data

**Machine Learning:**
- Graduate Prediction Models — ML systems to identify students at risk of dropping out
- Model and Bias Audit — Evaluating machine learning models for fairness and performance across demographics

**Full-Stack Applications:**
- SA Taxi Platform — Browser-based app for finding fares, selecting seats (SVG), making payments, and accessing safety resources
- Smart Clinic Management System — Healthcare application for patient and appointment management
- Student Dashboard (NFC Card) — Multi-purpose student card with attendance tracking, payments, and academic calculators

---

## How I Work

**System Design:** I think in terms of how components interact, where data flows, where failures might happen, and how to build systems that are easy to understand and modify.

**Practical Problem-Solving:** I start by understanding the real problem before jumping to code. What are people actually trying to accomplish? What constraints exist? What would success look like?

**Observability:** I build monitoring, logging, and metrics into systems from the start. You can't fix what you can't see.

**Documentation:** I document decisions, not just code. Why did I choose this approach? What were the tradeoffs? What might we do differently next time?

**Continuous Improvement:** Each project teaches me something. I carry those lessons forward.

---

## Technical Stack

**Languages:** Java, Python, JavaScript, SQL, Bash

**Backend & Architecture:** Spring Boot, REST APIs, Microservices, Database Design, Docker

**Data & Analytics:** Pandas, NumPy, scikit-learn, Jupyter Notebooks, Streamlit, Power BI

**Machine Learning:** NLP, Time-series Forecasting, Model Evaluation, Cross-lingual Embeddings

**DevOps & Operations:** Docker, Docker Compose, Kong API Gateway, Prometheus, Grafana, ELK Stack, CI/CD

**Frontend:** HTML5, CSS3, JavaScript, Responsive Design

---

## Get In Touch

Email: [snenkosi41@gmail.com](mailto:snenkosi41@gmail.com)

GitHub: [@inkosii](https://github.com/inkosii)

---

<p align="center">
Built with intention. Crafted with care.
</p>
