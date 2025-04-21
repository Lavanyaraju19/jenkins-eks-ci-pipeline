🚀 Jenkins to EKS CI/CD Pipeline

Deploy containerized workloads to AWS EKS using Jenkins pipelines. Automates Docker builds, Helm deployment, and Kubernetes rollout.

 🧰 Tools
- Jenkins
- Docker
- AWS EKS
- Helm (optional)

 🛠️ Pipeline Stages
- Code checkout
- Docker image build
- Push to registry
- K8s deployment to EKS

✅ Prerequisites
- AWS CLI
- EKS cluster configured
- Jenkins running with Docker agent

📁 Project Structure

- `jenkins/` — Jenkinsfile, scripts
- `eks/` — K8s manifests for EKS deployment
- `docker/` — Dockerfile and image setup
- `charts/` — Helm (optional)
- `README.md`
- `LICENSE`
