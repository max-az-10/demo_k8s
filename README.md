# Swiggy Clone – DevOps Project

# Project Overview
A DevOps project demonstrating the deployment and monitoring of a containerized Swiggy clone application on AWS using Docker, Kubernetes, Terraform, Jenkins, Prometheus, and Grafana.

# Architecture
GitHub → Jenkins → SonarQube → Docker → Docker Hub → AWS EKS → Kubernetes → LoadBalancer
Prometheus collects Kubernetes/application metrics, while Grafana provides dashboards for monitoring and visualization.

# Technologies Used
AWS / EKS
Kubernetes
Terraform
Docker
Jenkins
Git & GitHub
Docker Hub
SonarQube
Prometheus
Grafana
Linux

# Infrastructure as Code
Provisioned AWS infrastructure using Terraform
Created and managed an AWS EKS cluster
Automated infrastructure deployment and configuration
Used reusable Terraform configuration to maintain infrastructure consistentl

# Containerization
Containerized the application using Docker
Created Docker images for application deployment
Published container images to Docker Hub

# CI/CD Pipeline
Integrated GitHub with Jenkins
Automated application build and deployment
Integrated SonarQube for code-quality analysis
Built and pushed Docker images through the pipeline
Automated deployment to Kubernetes/EKS

# Kubernetes Deployment
Deployed the application to AWS EKS
Created Kubernetes deployment and service resources
Managed application workloads using Kubernetes
Exposed the application using a LoadBalancer

# demo_k8s Text 2000
