# viva-security-ai
# VIVA Security AI

**AI-powered, open-source security platform for VIVA Super Save.**  
Built for anomaly detection, malware classification, fraud prevention, and real-time security automation.

---

## Core Features
- User Behavior Analytics (UBA)
- Anomaly Detection (Isolation Forest, Autoencoders)
- Malware Detection (Static + Dynamic)
- Fraud Detection (Graph-Based)
- Real-time Inference + SOAR Automation

---

## Tech Stack
- ML: PyTorch, Scikit-Learn, XGBoost
- Serving: FastAPI, Triton, BentoML
- Pipelines: Apache Kafka, Spark, Feast
- Storage: ClickHouse, Delta Lake
- Dashboards: OpenSearch, Grafana
- Orchestration: Docker, Kubernetes, Terraform

---

##  Getting Started (Dev)

```bash
# clone
git clone https://github.com/YOUR_USERNAME/viva-security-ai.git
cd viva-security-ai

# run dev stack
docker-compose up --build

# run model API server
cd model-serving/api
uvicorn app:app --reload
