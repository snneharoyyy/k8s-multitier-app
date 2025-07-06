# ☸️ Kubernetes Multi-Tier App on Minikube

This project deploys a static frontend and Node.js backend using Kubernetes on Minikube.

Stack
- Docker
- Kubernetes
- Minikube
- Node.js + NGINX

Deploy Locally

```bash
minikube start
eval $(minikube docker-env)
docker build -t frontend-image ./frontend
docker build -t backend-image ./backend
kubectl apply -f k8s-manifests/
minikube service frontend-service
ubernetes Multi-Tier App on Minikube

This project deploys a static frontend and Node.js backend using Kubernetes on Minikube.

Stack
- Docker
- Kubernetes
- Minikube
- Node.js + NGINX

Deploy Locally

```bash
minikube start
eval $(minikube docker-env)
docker build -t frontend-image ./frontend
docker build -t backend-image ./backend
kubectl apply -f k8s-manifests/
minikube service frontend-service
