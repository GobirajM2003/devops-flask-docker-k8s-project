# 🚀 DevOps Project: Flask + Docker + Kubernetes

## 📌 Overview
This project demonstrates a complete DevOps workflow:
- Flask Backend API
- Docker Containerization
- Kubernetes Deployment
- Service Exposure via NodePort

## 🛠 Tech Stack
- Python (Flask)
- Docker
- Kubernetes (Minikube)

## 🚀 Steps to Run

### 1. Run Locally
python Layer1_backend.py

### 2. Docker
docker build -t flask-app .
docker run -d -p 9000:9000 flask-app

### 3. Kubernetes
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml

## 🌐 Output
http://<minikube-ip>:<nodeport>/api/data

## 📷 Sample Output
{"message": "Hello from the backend!"}

## 👨‍💻 Author
Gobi Raj
