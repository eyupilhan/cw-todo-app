# CI/CD Pipeline for Multi-Container Todo Application on AWS

## Overview

This project demonstrates a complete CI/CD pipeline for deploying a multi-container Todo application on AWS using Jenkins, Terraform, Ansible, Docker, and Amazon ECR.

The application consists of three services:

* React Frontend
* Node.js Backend
* PostgreSQL Database

Infrastructure provisioning, application deployment, and container management are fully automated using Infrastructure as Code (IaC) and configuration management tools.

---

## Architecture

* AWS EC2
* Terraform
* Jenkins
* Ansible
* Docker
* Amazon ECR
* PostgreSQL
* Node.js
* React
* Git & GitHub

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

## Features

* Infrastructure provisioning with Terraform
* Jenkins Pipeline for CI/CD automation
* Dynamic Ansible inventory
* Docker image creation
* Amazon ECR integration
* Automated deployment with Ansible
* Multi-container application architecture
* Environment variable templating
* Infrastructure as Code (IaC)

---

## Deployment Workflow

```text
Developer Push
      │
      ▼
GitHub Repository
      │
      ▼
Jenkins Pipeline
      │
      ▼
Terraform Provisioning
      │
      ▼
Docker Image Build
      │
      ▼
Amazon ECR
      │
      ▼
Ansible Deployment
      │
      ▼
React + Node.js + PostgreSQL
```

---

## Technologies Used

* AWS EC2
* Terraform
* Jenkins
* Ansible
* Docker
* Amazon ECR
* PostgreSQL
* Node.js
* React
* Linux
* Git & GitHub

---

## Learning Outcomes

Through this project, I gained practical experience with:

* Designing end-to-end CI/CD pipelines
* Provisioning AWS infrastructure using Terraform
* Deploying applications with Ansible
* Building and managing Docker images
* Using Amazon ECR as a container registry
* Managing multi-container applications
* Automating deployments with Jenkins
* Dynamic inventory management in Ansible

---

## Notes

This project was completed as part of my DevOps training and demonstrates practical experience with modern DevOps tools and deployment workflows.

It is intended for learning and portfolio purposes.
