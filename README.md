# CI/CD Pipeline for Multi-Container Todo Application on AWS

## Overview

This project demonstrates an end-to-end **CI/CD pipeline** for deploying a multi-container Todo application on AWS.

The system is fully automated using **Terraform, Jenkins, Ansible, Docker, and Amazon ECR**, covering infrastructure provisioning, application deployment, and container orchestration.

The application consists of three services:

* React Frontend
* Node.js Backend
* PostgreSQL Database

---

## Architecture

This project follows a fully automated DevOps workflow:

* AWS EC2 (Infrastructure)
* Terraform (Infrastructure as Code)
* Jenkins (CI/CD Orchestration)
* Ansible (Configuration Management)
* Docker (Containerization)
* Amazon ECR (Container Registry)
* GitHub (Source Control)

---

## Repository Structure

```text
.
├── Jenkinsfile
├── main.tf
├── docker_project.yml
├── inventory_aws_ec2.yml
├── ansible.cfg
├── node-env-template
├── react-env-template
├── nodejs/
├── react/
├── postgresql/
└── README.md
```

---

## CI/CD Workflow

```text
Developer Push
      │
      ▼
GitHub Repository
      │
      ▼
Jenkins Pipeline Trigger
      │
      ▼
Terraform Infrastructure Provisioning
      │
      ▼
Docker Image Build
      │
      ▼
Push to Amazon ECR
      │
      ▼
Ansible Deployment
      │
      ▼
Multi-Container Application Running on AWS
```

---

## Key Features

* Fully automated CI/CD pipeline
* Infrastructure provisioning with Terraform
* Dynamic Ansible inventory management
* Docker-based microservices architecture
* Secure container registry with Amazon ECR
* Multi-tier application deployment
* Environment-based configuration templates
* End-to-end automation from commit to deployment

---

## Learning Outcomes

This project demonstrates practical experience in:

* Implementing CI/CD pipelines using Jenkins, Docker, Ansible, and AWS
* Infrastructure provisioning with Terraform (IaC)
* Container orchestration with Docker
* Automated deployment using Ansible
* Jenkins pipeline orchestration
* AWS cloud infrastructure management
* Multi-service application architecture

---

## Notes

This project is part of a DevOps learning portfolio and focuses on real-world CI/CD and cloud deployment practices.

It is not intended for production use without additional enhancements such as monitoring, scaling, and security hardening.
