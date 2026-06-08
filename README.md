# Employee Management System 🚀

A containerized Employee Management System built using **Flask** and **MySQL**, deployed on **AWS EC2** with a complete **CI/CD pipeline using Jenkins, Docker, Docker Compose, and GitHub Webhooks**.

---

## 📌 Project Overview

This project provides a web-based platform to manage employee records efficiently through CRUD operations.

### Features

- ➕ Add Employee
- 👀 View Employees
- ✏️ Update Employee Details
- ❌ Delete Employee
- 🗄️ MySQL Database Integration
- 🐳 Dockerized Application
- 🔄 Automated CI/CD Deployment
- ☁️ AWS EC2 Hosting

---

## 🏗️ System Architecture

```text
Developer
    │
    ▼
GitHub Repository
    │
    ▼
GitHub Webhook
    │
    ▼
Jenkins CI/CD Pipeline
    │
    ▼
Docker Compose
    │
    ├── Flask Application
    │
    └── MySQL Database
    │
    ▼
AWS EC2 Instance
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|----------|
| Flask | Backend Framework |
| MySQL | Database |
| HTML/CSS | Frontend |
| Docker | Containerization |
| Docker Compose | Multi-Container Management |
| Jenkins | CI/CD Automation |
| GitHub | Version Control |
| AWS EC2 | Cloud Hosting |

---

## 📂 Project Structure

```text
employee-management-system/
│
├── app.py
├── requirements.txt
├── Dockerfile
├── docker-compose.yml
├── Jenkinsfile
│
├── mysql/
│   └── init.sql
│
├── templates/
│   ├── index.html
│   ├── add_employee.html
│   └── edit_employee.html
│
└── static/
    └── style.css
```

---

## 🚀 Local Setup

### Clone Repository

```bash
git clone https://github.com/prawinrk/employee-management-system.git
cd employee-management-system
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux/macOS

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
python app.py
```

Open:

```text
http://localhost:5000
```

---

## 🐳 Docker Deployment

Build and run containers:

```bash
docker compose up -d --build
```

Verify containers:

```bash
docker ps
```

---

## ☁️ AWS Deployment

The application is deployed on an AWS EC2 instance using:

- Ubuntu Server
- Docker
- Docker Compose
- Jenkins

---

## ⚙️ CI/CD Pipeline

The deployment process is fully automated.

```text
Code Change
     │
     ▼
Git Push
     │
     ▼
GitHub Webhook
     │
     ▼
Jenkins Pipeline
     │
     ▼
Docker Build
     │
     ▼
Docker Compose Deployment
     │
     ▼
Updated Application on AWS EC2
```

---

## 📋 Jenkins Pipeline Stages

- Source Code Checkout
- Build Docker Image
- Deploy Containers using Docker Compose
- Verify Deployment
- Continuous Delivery through GitHub Webhooks

---

## 🎯 Key Learning Outcomes

- Flask CRUD Development
- MySQL Database Integration
- Docker Containerization
- Docker Compose Orchestration
- Jenkins CI/CD Automation
- GitHub Webhook Integration
- AWS EC2 Deployment
- End-to-End DevOps Workflow

---

## 👨‍💻 Author

**Prawin R K**

GitHub: https://github.com/prawinrk

---

## ⭐ Project Highlights

- End-to-End DevOps Project
- Real-World CI/CD Pipeline
- Automated Deployment with Jenkins
- Containerized Architecture
- Cloud Deployment on AWS EC2
- Resume-Friendly Project

---

If you found this project useful, please consider giving it a ⭐ on GitHub.