# 👋 Hi, I'm Satnam

### Fresher DevOps Engineer | Cloud • Docker • Kubernetes • CI/CD • Linux

<p align="center">
  <a href="https://satnamgrover.in">
    <img src="https://img.shields.io/badge/Portfolio-Visit%20Portfolio-000000?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio">
  </a>
  <a href="https://www.linkedin.com/in/satnamgrover/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:satnamgrover27@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

---

## 🚀 About Me

I'm a **BCA graduate and aspiring DevOps Engineer** focused on building practical experience with cloud infrastructure, containers, Kubernetes, CI/CD, Linux, and automation.

I learn by building projects, deploying applications, troubleshooting infrastructure, and understanding how different DevOps tools work together in a real deployment workflow.

My goal is to start my career in a **DevOps / Cloud Engineering role** where I can contribute to real projects while continuing to grow my skills.

---

## 🧰 My DevOps Stack

### ☁️ Cloud

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS">
  <img src="https://img.shields.io/badge/EKS-FF9900?style=for-the-badge&logo=amazoneks&logoColor=white" alt="Amazon EKS">
  <img src="https://img.shields.io/badge/ECR-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="Amazon ECR">
</p>

### 🐳 Containers & Orchestration

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes">
  <img src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white" alt="Helm">
  <img src="https://img.shields.io/badge/Minikube-3970E4?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Minikube">
</p>

### 🔄 CI/CD & Version Control

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" alt="Jenkins">
  <img src="https://img.shields.io/badge/GitLab%20CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white" alt="GitLab CI">
</p>

### 🏗️ Infrastructure & Automation

<p>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform">
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white" alt="Ansible">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash">
</p>

### 📊 Monitoring

<p>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" alt="Prometheus">
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana">
</p>

### 💻 Programming & Scripting

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/YAML-CB171E?style=for-the-badge&logo=yaml&logoColor=white" alt="YAML">
</p>

---

# 📌 Featured Projects

## ☸️ Python Application Deployment on AWS EKS

A hands-on DevOps project focused on containerizing and deploying a Python application on **Amazon EKS**.

### Architecture

```text
                   ┌──────────────┐
                   │   Developer  │
                   └──────┬───────┘
                          │
                          ▼
                   ┌──────────────┐
                   │    GitHub    │
                   └──────┬───────┘
                          │
                          ▼
                   ┌──────────────┐
                   │    Jenkins   │
                   └──────┬───────┘
                          │
                          ▼
                   ┌──────────────┐
                   │ Docker Build │
                   └──────┬───────┘
                          │
                          ▼
                   ┌──────────────┐
                   │  Amazon ECR  │
                   └──────┬───────┘
                          │
                          ▼
                   ┌──────────────┐
                   │  Amazon EKS  │
                   └──────┬───────┘
                          │
                 ┌────────┴────────┐
                 ▼                 ▼
          ┌─────────────┐   ┌─────────────┐
          │ Kubernetes  │   │ Kubernetes  │
          │ Deployment  │   │   Service   │
          └─────────────┘   └─────────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │    Monitoring   │
                 │ Prometheus +    │
                 │    Grafana      │
                 └─────────────────┘
```

### What I worked on

* Containerized the application using Docker
* Created a Jenkins-based CI/CD workflow
* Built and tagged Docker images
* Used Amazon ECR as a container registry
* Deployed the application to Amazon EKS
* Created Kubernetes deployment and service resources
* Worked with Kubernetes configuration files
* Configured application monitoring with Prometheus and Grafana
* Worked with AWS IAM permissions

🔗 **[View Repository](https://github.com/satnamgrover/DevOps-python-app)**

---

## 🐳 Flask CI/CD Pipeline

A CI/CD project demonstrating an automated workflow for building, testing, containerizing, and deploying a Python Flask application.

### Pipeline

```text
       Git Push
          │
          ▼
      ┌─────────┐
      │ Checkout│
      └────┬────┘
           │
           ▼
      ┌─────────┐
      │  Lint   │
      └────┬────┘
           │
           ▼
      ┌─────────┐
      │  Test   │
      └────┬────┘
           │
           ▼
      ┌─────────┐
      │ Docker  │
      │  Build  │
      └────┬────┘
           │
           ▼
      ┌─────────────┐
      │ Docker Hub  │
      └──────┬──────┘
             │
             ▼
         Deployment
```

### Technologies

`Python` `Flask` `Git` `Jenkins` `Docker` `Docker Hub` `CI/CD`

### What I worked on

* Created a Flask application
* Configured a Jenkins pipeline
* Added automated linting and testing
* Built Docker images through the pipeline
* Pushed container images to Docker Hub
* Automated application deployment
* Worked with Git-based CI/CD workflows

🔗 **[View Repository](https://github.com/satnamgrover/DevOps-python-app)**

---

## 💬 Full Stack Chat Application

A full-stack application deployed using containers and Kubernetes, with separate application components and persistent database storage.

### Architecture

```text
                 Kubernetes Cluster
                        │
              ┌─────────┴─────────┐
              │                   │
              ▼                   ▼
        ┌───────────┐       ┌───────────┐
        │  Frontend │       │  Backend  │
        │   Pod     │       │    Pod    │
        └─────┬─────┘       └─────┬─────┘
              │                   │
              └─────────┬─────────┘
                        │
                        ▼
                  ┌───────────┐
                  │ Database  │
                  │ StatefulSet│
                  └─────┬─────┘
                        │
                        ▼
                 ┌──────────────┐
                 │ Persistent   │
                 │ Volume / PVC │
                 └──────────────┘
```

### Technologies

`Docker` `Kubernetes` `Jenkins` `Minikube` `Persistent Volumes`

### What I worked on

* Containerized application components
* Created Docker images
* Deployed frontend and backend components on Kubernetes
* Configured Kubernetes Services
* Used StatefulSet for database deployment
* Configured Persistent Volume and Persistent Volume Claim
* Practiced application deployment using Minikube
* Integrated deployment workflow with Jenkins

---

# ⚙️ DevOps Concepts I Practice

```text
Linux
  │
  ├── System Administration
  ├── Users & Permissions
  ├── Processes
  ├── Networking
  └── Shell Commands

Git
  │
  ├── Branching
  ├── Merging
  ├── Remote Repositories
  └── Collaboration

Docker
  │
  ├── Images
  ├── Containers
  ├── Dockerfiles
  ├── Volumes
  └── Container Networking

Kubernetes
  │
  ├── Pods
  ├── Deployments
  ├── Services
  ├── ConfigMaps
  ├── Secrets
  ├── StatefulSets
  └── Persistent Storage

Cloud
  │
  ├── AWS
  ├── EC2
  ├── IAM
  ├── ECR
  ├── EKS
  └── VPC

Automation
  │
  ├── Jenkins
  ├── Terraform
  ├── Ansible
  └── Python / Bash
```

---

# 📚 Currently Learning

I'm continuously improving my practical DevOps knowledge through projects, labs, and troubleshooting.

### Current Focus

* ☁️ AWS Cloud Infrastructure
* ☸️ Kubernetes
* 🏗️ Terraform
* ⚙️ Ansible
* 🔄 CI/CD Automation
* 🐳 Docker
* 🐧 Linux Administration
* 📊 Prometheus & Grafana
* 🐍 Python Automation
* 🔐 Cloud Security & IAM

---

# 🎓 Education

**Bachelor of Computer Applications (BCA)**
Punjabi University

---

# 🎯 Career Objective

I'm looking for an opportunity to start my career as a **DevOps Engineer, Junior DevOps Engineer, DevOps Intern, or Cloud Engineer**.

I want to work on real-world infrastructure and deployment problems while developing strong skills in **AWS, Linux, Docker, Kubernetes, CI/CD, Infrastructure as Code, and automation**.

---

# 🌐 Portfolio

### [Visit My DevOps Portfolio →](https://satnamgrover.in)

Explore my projects, technical skills, DevOps workflows, and hands-on work.

---

# 🤝 Connect With Me

<p align="left">
  <a href="https://satnamgrover.in">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio">
  </a>
  <a href="https://www.linkedin.com/in/satnamgrover/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:satnamgrover27@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
  </a>
</p>

---

<p align="center">
  <b>Build • Deploy • Automate • Learn 🚀</b>
</p>
