<div align="center">

# Aman Yadav
### Backend Engineer & Applied Machine Learning Practitioner

[![Portfolio](https://img.shields.io/badge/Portfolio-actas--aa.vercel.app-2563EB?style=flat-square&logo=vercel&logoColor=white)](https://actas-aa.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aman--Yadav77-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/Aman-Yadav77/)
[![Email](https://img.shields.io/badge/Email-amanstorm77%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:amanstorm77@gmail.com)
[![Location](https://img.shields.io/badge/Location-India-1E293B?style=flat-square&logo=googlemaps&logoColor=white)](https://actas-aa.vercel.app/)

<p align="center">
  Mathematics & Computing undergraduate architecting scalable, high-concurrency backend systems, distributed async task pipelines, and production machine learning models.
</p>

---

</div>

## Executive Summary

- **Background:** Undergraduate in Mathematics & Computing, combining mathematical depth (linear algebra, probability, numerical optimization) with production software engineering.
- **Backend & Distributed Systems:** Building resilient, high-throughput APIs and async queue workers using FastAPI, Django, Celery, Redis, and PostgreSQL.
- **Applied Machine Learning:** Designing predictive sequence architectures, degradation modeling, and telemetry analytics with PyTorch, Scikit-Learn, and Pandas.
- **Industry Experience:** Former engineering intern at Maruti Suzuki, delivering an industrial-grade telemetry stream processing and validation pipeline for raw vehicle sensor feeds.

---

## Technical Arsenal

### Languages & Core Foundations
`Python` • `C++` • `SQL (PostgreSQL)` • `TypeScript` • `Bash` • `Linear Algebra & Numerical Methods`

### Backend & Distributed Architecture
`FastAPI` • `Django` • `Celery` • `Redis` • `AsyncIO` • `RESTful APIs` • `Alembic` • `JWT & RBAC Auth`

### Machine Learning & Data Science
`PyTorch` • `Scikit-Learn` • `Pandas` • `NumPy` • `1D-CNN + LSTM` • `Time-Series & Telemetry ML` • `Streamlit`

### DevOps & Engineering Tooling
`Docker` • `Git / GitHub` • `CI/CD Pipelines` • `Linux / Shell` • `Pre-commit Hooks` • `Postman`

---

## Featured Projects

### 1. [EduPulse](https://github.com/AmanYdv77/edupulse) — Student Performance Forecasting & Academic Early-Warning Platform
> *Dual-model predictive academic intelligence platform built with Django, React 19, PostgreSQL, Redis, and Celery.*

- **Dual-Model ML Architecture:** Designed a two-tier predictive engine using baseline behavioral priors and longitudinal institutional models with `GroupedKFold` cross-validation and demographic quarantine to ensure zero PII leakage and ethical AI inference.
- **High-Performance Distributed Stack:** Engineered an asynchronous Celery worker fleet backed by an isolated dual-Redis architecture (dedicated cache + queue broker), generational caching, and automated Docker Compose CI/CD deployment.
- **Tech Stack:** `Django` • `React 19` • `TypeScript` • `PostgreSQL` • `Redis` • `Celery` • `Scikit-Learn` • `Docker`
- **Links:** [![Code](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github)](https://github.com/AmanYdv77/edupulse)

---

### 2. [PingGuard](https://github.com/AmanYdv77/PingGuard) — Distributed HTTP Uptime & Keep-Alive Monitoring Engine
> *Self-hosted, high-concurrency uptime engine managing asynchronous heartbeats and scheduled health checks.*

- **Decoupled Asynchronous Probing:** Separated FastAPI control plane API interactions from outbound probing workloads via Celery workers and periodic database sweeps using row-level locking (`FOR UPDATE SKIP LOCKED`) to eliminate duplicate task dispatching.
- **SSRF & DNS-Rebinding Hardening:** Implemented strict network security controls including pre-flight async DNS resolution against private CIDR blocklists and direct IP pinning to prevent Time-of-Check to Time-of-Use (TOCTOU) DNS rebinding attacks.
- **Tech Stack:** `FastAPI` • `PostgreSQL 15` • `Redis 7` • `Celery` • `AsyncIO` • `Docker`
- **Links:** [![Code](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github)](https://github.com/AmanYdv77/PingGuard)

---

### 3. [EV-Lifespan](https://github.com/AmanYdv77/ev-lifespan) — EV Battery Remaining Useful Life (RUL) Prediction Platform
> *End-to-end deep learning prognostic platform estimating lithium-ion battery degradation from multi-channel sensor telemetry.*

- **Hybrid Deep Sequence Architecture:** Developed a 2-tier spatial-temporal model fusing a 1D-CNN (feature extraction across voltage, current, and temperature profiles) with 2-layer Stacked LSTM networks over sliding cycle windows.
- **Quantitative Benchmark Performance:** Achieved an **RMSE of 19.40 cycles** and **MAE of 15.67 cycles** with **< 15ms inference latency**, packaged in a multi-stage Docker container with a unified FastAPI backend and interactive dark-mode React dashboard.
- **Tech Stack:** `PyTorch` • `FastAPI` • `React 18` • `1D-CNN + LSTM` • `Docker` • `Recharts`
- **Links:** [![Code](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github)](https://github.com/AmanYdv77/ev-lifespan)

---

## Industry Experience Project

### [TelematicsPro](https://github.com/AmanYdv77/telematics_pro) — Industrial Vehicle Telematics & Sensor Processing Suite
> *Developed during engineering internship at Maruti Suzuki for high-throughput automotive sensor ingestion, validation, and analytics.*

- **6-Stage Ingestion & Normalization Pipeline:** Built a modular telemetry processing suite that automatically maps vendor-specific headers to a 40-feature automotive taxonomy, decomposes 3-axis accelerometer vectors, and handles trip segmentation.
- **Kinematic Derivation & Statistical Cleansing:** Engineered Haversine trajectory distance calculation, idle duration tracking, aggressive driving event detection (hard braking & rapid acceleration), and robust outlier treatment (IQR & Z-score) with full JSON audit logs.
- **Tech Stack:** `Python` • `Streamlit` • `Pandas` • `NumPy` • `Sensor Telemetry` • `Kinematics ML`
- **Links:** [![Live App](https://img.shields.io/badge/Live_App-telematicspro.streamlit.app-4F46E5?style=flat-square&logo=streamlit&logoColor=white)](https://telematicspro.streamlit.app/) [![Code](https://img.shields.io/badge/GitHub-Repository-181717?style=flat-square&logo=github)](https://github.com/AmanYdv77/telematics_pro)

---

## GitHub Analytics

<div align="center">
  <table border="0">
    <tr>
      <td>
        <img height="165em" src="https://github-readme-stats.vercel.app/api?username=AmanYdv77&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="Aman's GitHub Stats" />
      </td>
      <td>
        <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AmanYdv77&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" alt="Top Languages" />
      </td>
    </tr>
  </table>
  <br/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=AmanYdv77&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</div>

---

## Connect & Collaborate

- **Interactive Portfolio:** [actas-aa.vercel.app](https://actas-aa.vercel.app/)
- **LinkedIn:** [linkedin.com/in/Aman-Yadav77](https://www.linkedin.com/in/Aman-Yadav77/)
- **Email:** [amanstorm77@gmail.com](mailto:amanstorm77@gmail.com)
- **Open to:** Backend engineering roles, distributed systems challenges, applied ML opportunities, and open-source contributions.
