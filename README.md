# 🚀 End-to-End DevOps CI/CD Project

# Tools & Technologies
- **AWS EC2** — Hosted Jenkins and Kubernetes cluster  
- **Git & GitHub** — Source code management and webhook trigger / cloned repo 
- **Jenkins** — Automated CI/CD pipeline setup  
- **Docker & DockerHub** — Containerization and image storage  
- **Kubernetes** — Deployment and scaling of containerized app  

---

### 🧩 Project Overview
This project implements a complete CI/CD pipeline for a web application deployed on AWS.  
Repository is Cloned and Every code change pushed to GitHub automatically triggers:
1. **Code Checkout** from GitHub  
2. **Docker Image Build** using Jenkins  
3. **Push Image** to DockerHub  
4. **Deploy to Kubernetes Cluster** on AWS  

---

### 🛠️ Pipeline Flow
A[Developer] --> B[GitHub]
B --> C[Jenkins CI/CD]
C --> D[Docker Build & Push]
D --> E[Kubernetes Deploy]
E --> F[Application Live on AWS]
