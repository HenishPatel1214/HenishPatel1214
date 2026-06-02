<h1 align="center">Hi, I'm Henish Patel</h1>

<p align="center">
  <strong>Software Engineer | Cloud-Native Systems, AI Infrastructure & Distributed Data</strong><br/>
  Computer Science + Data Science @ University of Utah ('27) (GPA 3.57)
</p>

<p align="center">
  <a href="https://henishpatel1214.github.io/henish-portfolio/">🌐 Portfolio</a> •
  <a href="https://henishpatel1214.github.io/henish-portfolio/resume/Henish_Patel_Resume.pdf">📄 Resume</a> •
  <a href="mailto:harrypatel1214@gmail.com">✉️ Email</a> •
  <a href="https://www.linkedin.com/in/henishpatel2004/">💼 LinkedIn</a>
</p>

---

## ⚙️ Engineering Focus

I build cloud-native systems, AI infrastructure, and distributed data platforms with a focus on performance, reliability, and operational clarity.

- **Cloud-Native Systems:** Kubernetes Operators, CRDs, reconciliation loops, Helm, Argo CD, RBAC, NetworkPolicies, observability, and GitOps workflows.
- **AI Infrastructure:** Model serving, distributed inference, vLLM, Ollama, CUDA optimization, TensorRT-LLM, PyTorch, and GPU-aware deployment patterns.
- **Data Engineering:** R-tree spatial indexing, checksum validation, zero-downtime migrations, ETL optimization, and distributed data integrity.
- **Systems Architecture:** Immutable state, Merkle-tree versioning, WebSocket orchestration, OAuth2/RBAC security, and observability-first design.

---

## 🛠️ Tech Stack

### Languages

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)

### Frameworks & Tools

![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-111827?style=for-the-badge&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

### Infrastructure & Databases

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo%20CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

---

## 🚀 Selected Architecture

- **[Model Deployment Operator](https://github.com/HenishPatel1214/model-deployment-operator)**  
  Built a production-style **Go Kubernetes Operator** for managing AI model inference workloads through a custom `ModelDeployment` CRD. The controller reconciles Deployments, Services, HPAs, benchmark Jobs, status phases, finalizers, and optional RAG-ready Qdrant dependencies. Includes **Prometheus/Grafana observability**, cost/resource reporting, **Helm**, **Argo CD GitOps**, NetworkPolicies, and GitHub Actions CI.

- **NVIDIA Local AI Cluster**  
  Built a high-performance NVIDIA GPU cluster utilizing **CUDA**, **Docker**, **vLLM**, and **TensorRT-LLM** for distributed local inference. Benchmarked and optimized Llama 3 model serving workloads with a focus on latency, throughput, and GPU utilization.

- **Agentic SaaS Pricing & Identity Layer**  
  Engineered a high-throughput API metering layer for usage-based billing across autonomous agent workflows. Implemented zero-trust agent identities, Redis-backed rate limiting, concurrency control, and request-level authorization patterns.

- **mySpecSheet Telemetry & State Management**  
  Architected a vehicle data backend using **Merkle-tree versioning** for immutable state history and **MCP server patterns** for sandboxed data manipulation, telemetry synchronization, and structured workflow automation.

---

## 💼 Experience Snapshot

- **Full Stack Software Engineer @ mySpecSheet**  
  Implemented custom **LSP extensions** reducing context switching by 38%, and developed a **WebSocket orchestration layer** achieving sub-50ms latency for telemetry synchronization.

- **SUDO Software Platform Services Intern @ University of Utah**  
  Optimized GIS geospatial indexing using **R-trees**, improving spatial query performance by 27%. Architected ETL pipelines reducing processing time from 4 hours to 15 minutes.

- **Data Analyst Intern @ University of Utah Health**  
  Led zero-downtime migration to AWS using S3 and EC2, implementing strict **MD5 checksum validation** to ensure data integrity across 500GB+ datasets.

---

## 📌 Featured Project: Model Deployment Operator

**Model Deployment Operator** is a Go Kubernetes Operator for managing AI model inference workloads through a custom `ModelDeployment` CRD.

Instead of manually deploying model-serving infrastructure with separate Kubernetes manifests, the operator lets users define a declarative model deployment and automatically manages the lifecycle of the required Kubernetes resources.

### What it does

- Defines a custom `ModelDeployment` CRD for AI inference workloads
- Reconciles model specs into Kubernetes Deployments, Services, HPAs, benchmark Jobs, and ConfigMaps
- Supports Ollama-style and vLLM-style inference deployments
- Tracks status phases including `Pending`, `Running`, `Degraded`, `Scaling`, and `Failed`
- Uses finalizers for cleanup behavior
- Includes Prometheus and Grafana observability assets
- Provides benchmark support for latency, throughput, and error tracking
- Adds cost/resource reporting for model deployments
- Supports RAG-ready deployments with optional Qdrant resources
- Includes Helm, Argo CD, NetworkPolicy, and GitHub Actions CI support

### Skills demonstrated

`Go` · `Kubernetes` · `Kubebuilder` · `controller-runtime` · `CRDs` · `Operators` · `Helm` · `Argo CD` · `Prometheus` · `Grafana` · `GitOps` · `MLOps` · `Platform Engineering`

**Repository:** [github.com/HenishPatel1214/model-deployment-operator](https://github.com/HenishPatel1214/model-deployment-operator)

---

## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=HenishPatel1214&show_icons=true&rank_icon=github&theme=transparent&hide_border=true" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=HenishPatel1214&layout=compact&theme=transparent&hide_border=true" alt="Top languages" />
</p>

---

<p align="center">
  <i>“Systems fail. Build them so they fail predictably, recover automatically, and log immutably.”</i>
</p>
