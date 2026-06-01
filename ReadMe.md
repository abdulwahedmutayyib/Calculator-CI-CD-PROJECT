# 🚀 DevOps Calculator Application

A production-style DevOps project demonstrating containerization, Kubernetes orchestration, CI/CD automation, monitoring, observability, and autoscaling.

## 📌 Project Overview

This project is a full-stack calculator application deployed on Kubernetes with separate frontend and backend services.

The objective was to implement a complete DevOps workflow from development to deployment, monitoring, and scaling.

---

## 🏗 Architecture

* Frontend: HTML, CSS, JavaScript, NGINX
* Backend: Python Flask
* Containerization: Docker
* Orchestration: Kubernetes (Minikube)
* Networking: Kubernetes Services + NGINX Ingress
* CI/CD: GitHub Actions
* Container Registry: Docker Hub
* Monitoring: Prometheus
* Visualization: Grafana
* Autoscaling: Horizontal Pod Autoscaler (HPA)

---

## ⚙ Features

### Application

* Calculator frontend
* Flask REST API backend
* Frontend and backend deployed independently

### Kubernetes

* Separate Deployments
* Separate Services
* Ingress-based routing
* LoadBalancer exposure
* Resource Requests and Limits

### CI/CD

* Automated GitHub Actions pipeline
* Docker image build
* Docker image push to Docker Hub
* Automatic Kubernetes deployment updates
* Automated rollout restart

### Monitoring & Observability

* Prometheus metrics collection
* Grafana dashboards
* Cluster monitoring
* Pod monitoring
* CPU and memory utilization tracking

### Autoscaling

* Horizontal Pod Autoscaler
* CPU-based scaling
* Configurable minimum and maximum replicas

---

## 📂 Project Structure

project-root/

├── .github/workflows/

│ ├── ci.yml

│ └── cd.yml

│

├── frontend/

│ ├── index.html

│ ├── script.js

│ ├── style.css

│ ├── nginx.conf

│ └── Dockerfile

│

├── k8s/

│ ├── deployment.yaml

│ ├── service.yaml

│ ├── frontend-deployment.yaml

│ ├── frontend-service.yaml

│ ├── ingress.yaml

│ └── hpa.yaml

│

├── calculator.py

├── logic.py

├── requirements.txt

├── Dockerfile

└── README.md

---

## 🚀 Deployment Flow

1. Developer pushes code to GitHub
2. GitHub Actions CI executes tests
3. CD pipeline builds Docker images
4. Images are pushed to Docker Hub
5. Kubernetes deployments are updated
6. New pods are rolled out automatically
7. Prometheus collects metrics
8. Grafana visualizes application health
9. HPA scales pods based on CPU utilization

---

## 📊 Monitoring Stack

### Prometheus

Collects:

* Pod metrics
* Node metrics
* CPU utilization
* Memory utilization

### Grafana

Visualizes:

* Cluster health
* Pod resource consumption
* Deployment metrics
* Autoscaling behavior

---

## 📈 Horizontal Pod Autoscaler

Configuration:

* Minimum Replicas: 2
* Maximum Replicas: 5
* Target CPU Utilization: 50%

The backend deployment automatically scales based on CPU consumption.

---

## 🛠 Skills Demonstrated

* Docker
* Kubernetes
* Ingress Controller
* Services & Networking
* CI/CD Pipelines
* GitHub Actions
* Docker Hub
* Prometheus
* Grafana
* Horizontal Pod Autoscaler
* Resource Management
* Monitoring & Observability

---

## 👨‍💻 Author

Abdul Wahed

DevOps Engineer | Docker | Kubernetes | Terraform | CI/CD | AWS


