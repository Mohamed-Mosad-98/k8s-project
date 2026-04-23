# 🚀 k8s-project

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![VMware](https://img.shields.io/badge/VMware-607078?style=for-the-badge&logo=vmware&logoColor=white)

## 📌 Project Overview

A full-stack multi-tier web application deployed on **Kubernetes (Minikube)** inside an **Ubuntu Virtual Machine on VMware**.

This project demonstrates real DevOps deployment practices using:

- Dockerized services
- Kubernetes Deployments & Services
- Flask REST API
- MySQL Database
- Nginx Frontend

The frontend login page sends submitted credentials to the backend API, which stores them inside MySQL.

---

## 🏗️ Architecture

User Browser  
⬇️  
Frontend (Nginx)  
⬇️  
Backend API (Flask)  
⬇️  
MySQL Database

Managed entirely using Kubernetes.

---

## 🛠️ Technologies Used

- Kubernetes (Minikube)
- Docker
- Python Flask
- MySQL
- Nginx
- HTML / CSS
- Ubuntu Linux
- VMware Workstation
- Git & GitHub

---

## 📁 Project Structure
k8s-project/
├── Backend/
│   ├── app.py
│   ├── requirements.txt
│   └── Dockerfile
│
├── my-nginx/
│   ├── Dockerfile
│   └── html/
│       └── index.html
│
└── k8s/
    ├── frontend-deployment.yaml
    ├── frontend-service.yaml
    ├── backend-deployment.yaml
    ├── backend-service.yaml
    ├── mysql-deployment.yaml
    └── mysql-service.yaml

---


## ☸️ Kubernetes Resources

### Deployments

- Frontend Deployment
- Backend Deployment
- MySQL Deployment

### Services

- Frontend Service (**NodePort**)
- Backend Service
- MySQL Service (**ClusterIP**)

---

## ⚙️ Deployment Steps

### 1️⃣ Build Docker Images

docker build -t frontend-image ./my-nginx  
docker build -t backend-image ./Backend

### 2️⃣ Start Minikube

minikube start

### 3️⃣ Apply Kubernetes Files

kubectl apply -f k8s/

### 4️⃣ Verify Running Resources

kubectl get pods  
kubectl get svc

---

## ✅ Project Results

- Frontend page deployed successfully
- Backend API connected successfully
- MySQL database working correctly
- Credentials inserted into database
- Services exposed via Kubernetes
- Full project running inside Minikube cluster

---

## 📷 Screenshots

### 🔹 Frontend Login Page

(Add screenshot here)

### 🔹 Successful Submission

(Add screenshot here)

### 🔹 Stored Credentials in MySQL

(Add screenshot here)

### 🔹 Running on Ubuntu VM (VMware)

(Add screenshot here)

---

## 🎯 Skills Demonstrated

- Kubernetes Administration
- Docker Containerization
- Multi-tier Application Deployment
- Flask API Development
- Database Integration
- Linux System Usage
- Troubleshooting Services
- YAML Configuration
- Networking Concepts
- DevOps Fundamentals

---

## 💼 Why This Project Matters

This project reflects practical hands-on experience with technologies commonly required in:

- DevOps Engineer Roles
- Cloud Engineer Roles
- Site Reliability Engineer (SRE)
- Platform Engineering
- Infrastructure Support

---

## 👨‍💻 Author

**Mohamed Mosad**

🔗 GitHub: https://github.com/Mohamed-Mosad-98  
🔗 LinkedIn: https://www.linkedin.com/in/mohamed-mosad-fahmy/

---

## ⭐ If you found this project useful, feel free to star the repository.
