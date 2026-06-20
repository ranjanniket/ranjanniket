# Hi, I'm Niket Ranjan 👋

### DevOps / SRE Engineer · Cloud Infrastructure · AI/ML Production Systems

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ranjanniket-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/ranjanniket)
[![Email](https://img.shields.io/badge/Email-niketranjan50@gmail.com-EA4335?style=flat&logo=gmail)](mailto:niketranjan50@gmail.com)
[![Location](https://img.shields.io/badge/📍-Pune,%20India-2ea44f?style=flat)]()

---

DevOps/SRE Engineer with **3+ years** of hands-on experience architecting cloud-native infrastructure and deploying production-grade AI/ML systems at scale. Currently at **Red Hat**, I bridge the gap between DevOps automation and LLM/RAG systems — building infrastructure that's secure, observable, and production-ready.

🎤 **International Speaker** — Presented at [DevConf.CZ 2025](https://www.devconf.info/cz/) in Brno, Czech Republic on *Automating and Scaling ML and LLM Workloads in Production.*

---

## 🏢 Experience

**Software Maintenance Engineer — Red Hat** *(Feb 2024 – Present)*
> Sustaining Engineering | Pune, India

- Architected an **AI-powered internal documentation system** using RAG (Retrieval-Augmented Generation), unifying Confluence and GitLab data for intelligent search and Q&A
- Built end-to-end **AWS infrastructure** (Lambda, S3, EC2, SageMaker, EKS) using Terraform for automated data ingestion and LLM interaction
- Designed **CI/CD pipelines for kernel RPM builds**, automating build and deployment workflows
- Implemented **critical CVE security patches** across RHEL kernel subsystems
- Manage QA and testing for kernel releases using automated testing methodologies

**Performance & Scale Engineering — Red Hat** *(Aug 2023 – Feb 2024)*

- Automated **Event-Driven Ansible (EDA)** and **Ansible Tower** infrastructure management via APIs
- Developed Ansible playbooks processing **millions of events** with Automation Controller integration
- Deployed EDA and Ansible Tower on **AWS with external PostgreSQL** at scale
- Integrated **Elasticsearch & Kibana** for performance analytics and observability

**DevOps Engineer — Constems-AI Systems** *(Sept 2022 – Aug 2023)*

- Designed and managed multiple **EKS Kubernetes clusters** with Cluster Autoscaler & Karpenter
- Built and maintained **Helm charts** for streamlined application deployments
- Provisioned infrastructure using **Terraform** with state management in S3, deployed via Jenkins pipelines
- Implemented **CI/CD pipelines** using Jenkins & ArgoCD for automated deployments
- Deployed **Prometheus + Grafana** monitoring with custom exporters (Node, Blackbox, cAdvisor)
- Built **ELK stack** for centralized logging with automated S3 backups
- Optimized AWS costs through resource analysis and efficiency improvements

---

## 🛠️ Tech Stack

**Cloud & Infrastructure**

![AWS](https://img.shields.io/badge/AWS-Expert-FF9900?style=flat&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-Proficient-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-IaC-7B42BC?style=flat&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-Automation-EE0000?style=flat&logo=ansible&logoColor=white)

`AWS (Lambda · S3 · EC2 · EKS · SageMaker)` `Azure` `GCP` `Terraform` `Ansible` `Ansible Tower` `Event-Driven Ansible`

**Container Orchestration & CI/CD**

![Kubernetes](https://img.shields.io/badge/Kubernetes-Expert-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Containers-2496ED?style=flat&logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-CI%2FCD-D24939?style=flat&logo=jenkins&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-GitOps-EF7B4D?style=flat&logo=argo&logoColor=white)

`Kubernetes` `Docker` `Podman` `Helm` `EKS` `Jenkins` `GitHub Actions` `GitLab CI/CD` `ArgoCD`

**Monitoring & Observability**

![Prometheus](https://img.shields.io/badge/Prometheus-Monitoring-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-Dashboards-F46800?style=flat&logo=grafana&logoColor=white)
![ELK](https://img.shields.io/badge/ELK-Logging-005571?style=flat&logo=elastic&logoColor=white)

`Prometheus` `Grafana` `ELK Stack` `Loki` `Promtail` `Node Exporter` `Blackbox Exporter` `cAdvisor`

**AI/ML & MLOps**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

`RAG Implementation` `LLM Production Systems` `Vector Databases` `Model Serving` `CI/CD for ML` `Automated Retraining` `Python` `Bash`

**OS & Networking**

`RHEL` `Ubuntu` `Linux System Administration` `Nginx` `HAProxy`

---

## 🎤 Conference Speaking

### DevConf.CZ 2025 · Brno, Czech Republic 🇨🇿

> **"Automating and Scaling ML and LLM Workloads in Production"**
>
> *June 12–14, 2025 · Faculty of Information Technology, Brno University of Technology*

<a href="https://www.devconf.info/cz/"><img src="https://img.shields.io/badge/DevConf.CZ_2025-Speaker-blue?style=for-the-badge" /></a>

- Presented real-world experience building **secure, self-hosted LLM systems** for production environments at Red Hat
- Deep-dived into **RAG architecture**, secure model deployment, and automated retraining with GitLab pipelines
- Demonstrated how to make large language models **scalable, resilient, and production-ready** using DevOps automation

---

## 🚀 Featured Project

### AI-Powered Internal Documentation Platform *(RAG + LLM)*
**Production-grade AI system deployed at Red Hat**

| Metric | Result |
|--------|--------|
| ⚡ Document lookup speed | **50% faster** |
| 📚 Pages auto-indexed | **1,000+ pages**, refreshed weekly |
| 🚀 Environment spin-up | **< 30 minutes** |
| 🔄 Update latency | **Near real-time** via event-driven architecture |

**What it does:** A RAG-based internal knowledge platform unifying Confluence and GitLab, delivered as an API, Next.js UI, and Slackbot for instant context-aware answers.

**Infrastructure (Terraform-provisioned on AWS):**
- S3 (raw/processed data) · Lambda (event-driven ingestion) · EC2 (RAG API) · SageMaker (LLM) · EKS (orchestration)
- Dual ingestion: weekly full exports + webhook-driven real-time updates
- Automated PDF/Markdown processing, chunking, and metadata extraction

**DevOps & Production:**
- CI/CD via Jenkins/GitLab pipelines · Prometheus + Grafana observability · RBAC security · Multi-environment rollouts

`AWS` `Terraform` `Python` `RAG` `LLM` `Next.js` `GitLab CI/CD` `Prometheus` `Grafana` `EKS`

---

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=tokyonight&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=yourusername&layout=compact&theme=tokyonight&hide_border=true)

---

## 🎯 Currently

- 🔭 Building production-ready **AI/ML infrastructure** for enterprise applications
- 🌱 Exploring **advanced Kubernetes patterns** and service mesh technologies
- 💡 Contributing to **open-source DevOps tools** and automation frameworks
- 📝 Writing about **MLOps best practices** and cloud-native architectures

---

## 📫 Let's Connect

| | |
|---|---|
| **Email** | [niketranjan50@gmail.com](mailto:niketranjan50@gmail.com) |
| **LinkedIn** | [linkedin.com/in/ranjanniket](https://linkedin.com/in/ranjanniket) |
| **Phone** | +91 6350522371 |
| **Location** | Pune, Maharashtra, India |

---

<p align="center">
  <b>Open to · DevOps/SRE · Cloud Infrastructure · MLOps Engineering · AI/ML Platform Engineering</b><br/>
  <i>⭐ Specialization: Bridging DevOps & AI/ML — deploying production-grade LLM systems on cloud-native infrastructure</i>
</p>
