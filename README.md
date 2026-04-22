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

```text
User Browser
     │
     ▼
Frontend (Nginx)
     │
     ▼
Backend API (Flask)
     │
     ▼
MySQL Database
