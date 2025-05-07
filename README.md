# 🧱 InfraCraft: Mastering Backend, DevOps, AI & Big Data Infrastructure

**From building APIs to deploying intelligent, data-driven systems at scale**

InfraCraft is a 4-month, project-based engineering bootcamp designed to teach you how to design, build, deploy, and manage world-class backend applications, cloud infrastructure, and AI/data pipelines.

---

## 🚀 Overview

This curriculum is ideal for self-taught engineers, indie hackers, or early-stage builders who want to:

- Go from basic backend experience to full-scale deployments
- Learn DevOps, networking, container orchestration, and observability
- Build and serve AI features and data products
- Master both streaming and batch Big Data systems

You will build real infrastructure and deploy working products, with Docker, FastAPI, CI/CD, Terraform, K8s, Kafka, and more.

---

## 🧰 Tech Stack & Tools

| Technology      | Use & Function |
|----------------|----------------|
| **FastAPI / Node.js** | Backend API frameworks for serving HTTP and gRPC endpoints |
| **PostgreSQL / Redis** | Primary relational database and caching layer |
| **Docker / Docker Compose** | Containerization and service orchestration for dev and prod |
| **Nginx / Traefik** | Reverse proxy and TLS termination layer |
| **GitHub Actions** | CI/CD pipelines to automate builds, tests, and deployments |
| **Terraform** | Infrastructure as Code to manage cloud resources |
| **Grafana / Prometheus / Loki** | Observability: metrics, logs, dashboards |
| **Ollama / vLLM / HuggingFace** | Local or cloud-based AI model serving |
| **Weaviate / Chroma** | Vector databases for AI-powered search and embeddings |
| **Kafka / Redpanda** | Real-time data streaming infrastructure |
| **Apache Spark / DuckDB** | Distributed and local data processing engines |
| **Airflow / Prefect** | Data pipeline orchestration (ETL, analytics) |
| **MinIO / S3** | Object storage for data lakes and large file storage |
| **Kubernetes (K3s)** | Container orchestration and production cluster management |

---

## 📚 Course Structure

| Month | Focus Area                              | Time Commitment | Outcome |
|-------|------------------------------------------|------------------|---------|
| 1     | Backend & Docker                         | ~10–15 hrs/week | Fully Dockerized backend + API |
| 2     | DevOps, CI/CD, Cloud Infrastructure      | ~10–15 hrs/week | Deployed app w/ CI/CD & IaC |
| 3     | AI Infrastructure & Model Deployment     | ~12–18 hrs/week | AI-powered API w/ vector search |
| 4     | Big Data Infra & Real-Time Processing    | ~12–20 hrs/week | Streaming + batch pipeline + analytics stack |

---

## 🛠️ Projects

Each module culminates in a deployable, documented project. By the end of the course, you'll have:

### ✅ **World-Class Backend Stack**
- Authenticated FastAPI or Node API
- PostgreSQL, Redis, Docker Compose
- Production-ready container setup with Nginx or Traefik

### ✅ **CI/CD Pipeline**
- Automated build/test/deploy with GitHub Actions
- Push to GitHub Container Registry
- Deploy to VPS or cloud with Terraform

### ✅ **AI Q&A System**
- Inference server running local or remote LLMs
- Upload + process documents, extract context
- Vector search with semantic recall (Weaviate)

### ✅ **Big Data Pipeline**
- Kafka pipeline for real-time ingestion
- Spark or DuckDB-based transformation
- OLAP DB for dashboarding and insights

---

## 📦 Repo Layout (Suggested)

```
.
├── month1/
│   └── backend-api/
│       ├── api/          # FastAPI/Node.js application code
│       ├── database/     # PostgreSQL configuration and migrations
│       ├── cache/        # Redis setup and caching logic
│       └── nginx/        # Nginx/Traefik configuration files
│
├── month2/
│   └── devops-cicd/
│       ├── terraform/    # Infrastructure as Code (IaC) configurations
│       ├── github-actions/ # CI/CD pipeline definitions
│       └── monitoring/   # Grafana, Prometheus, and Loki setup
│
├── month3/
│   └── ai-infrastructure/
│       ├── llm-server/   # Ollama/vLLM model serving setup
│       ├── vector-db/    # Weaviate/Chroma vector database
│       └── document-processing/ # Document handling and processing
│
└── month4/
    └── big-data/
        ├── kafka-pipeline/    # Kafka/Redpanda streaming setup
        ├── spark-processing/  # Apache Spark/DuckDB processing
        └── analytics/        # Data analysis and visualization
```

### 📁 Folder Structure Explanation

The repository is organized into four main directories, each corresponding to a month of the course:

1. **Month 1 - Backend & Docker (`month1/`)**
   - Focuses on building a production-ready backend API
   - Separates concerns between API logic, database, caching, and web server
   - Enables easy containerization and service orchestration

2. **Month 2 - DevOps & Infrastructure (`month2/`)**
   - Houses infrastructure code and deployment configurations
   - Separates IaC, CI/CD, and monitoring concerns
   - Makes it easy to manage different environments (dev, staging, prod)

3. **Month 3 - AI Infrastructure (`month3/`)**
   - Organizes AI/ML components into distinct services
   - Separates model serving, vector storage, and document processing
   - Enables modular development of AI features

4. **Month 4 - Big Data (`month4/`)**
   - Structures data pipeline components
   - Separates streaming, batch processing, and analytics
   - Facilitates building end-to-end data solutions

This structure promotes:
- Clear separation of concerns
- Modular development
- Easy navigation between different components
- Scalable project organization
- Clear progression through the course material

