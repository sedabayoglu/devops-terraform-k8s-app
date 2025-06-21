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
