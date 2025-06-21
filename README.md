# DevOps Terraform + Kubernetes Demo App 🚀

This is a simple DevOps demo project that containerizes a Node.js application using Docker, deploys it to a local Kubernetes cluster (Minikube), and exposes it via a Kubernetes Service.

## 🔧 Tech Stack

- Node.js (Express.js)
- Docker
- Kubernetes (Minikube)
- Terraform (placeholder for future infrastructure automation)

## 📁 Project Structure
devops-terraform-k8s-app/
├── app/                  # Node.js app with Dockerfile
│   ├── Dockerfile
│   ├── index.js
│   └── package.json
├── k8s/                  # Kubernetes YAML files
│   ├── deployment.yaml
│   └── service.yaml
└── .gitignore
---

## 🚀 Getting Started

### 1. Build and Push Docker Image
```bash
cd app
docker build -t sedabayog/nodejs-devops-app:latest .
docker push sedabayog/nodejs-devops-app:latest
minikube start
cd ../k8s
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
minikube service devops-service📦 Docker Image

You can pull the image from DockerHub:
🔗 docker.io/sedabayog/nodejs-devops-app

⸻

🛠️ To Do / Coming Soon
	•	Add Terraform scripts for cloud infrastructure (AWS EC2)
	•	Add GitHub Actions for CI/CD pipeline
	•	Helm charts for production-level deployment

⸻

👩‍💻 Author

Seda Bayoğlu
💼 GitHub Profile
🛠️ DevOps Enthusiast | Docker | Kubernetes | CI/CD | Open to Collaboration
