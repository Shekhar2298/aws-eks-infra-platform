# AWS EKS Infrastructure Automation Platform

Hi, I'm Chandrashekhar Wadibhasme 👋  
This project is my personal hands-on work to strengthen my skills in **AWS Infrastructure, Kubernetes (EKS), Terraform, and DevOps automation**.

I built this project to simulate how modern cloud teams (like Amazon/eero) manage scalable, secure, production-style infrastructure.

---

## Why I Built This

While working as an AWS DevOps Intern, I realized that real DevOps is not just about tools — it's about:

- Building reliable systems  
- Automating manual work  
- Supporting engineering teams  
- Improving monitoring and deployments  
- Driving operational excellence  

So I created this project to practice those exact responsibilities in a real-world way.

---

## Project Overview

This repository demonstrates how to provision and operate a Kubernetes platform on AWS using Infrastructure-as-Code and DevOps best practices.

The platform includes:

- AWS EKS Cluster provisioning  
- Terraform-managed infrastructure  
- CI/CD automation for deployments  
- Centralized monitoring and logging  
- Operational improvements through scripting  

---

## Tech Stack

- **Cloud:** AWS (EC2, IAM, VPC, S3, CloudWatch)  
- **Infrastructure as Code:** Terraform  
- **Containerization:** Docker  
- **Orchestration:** Kubernetes (EKS)  
- **Deployment Management:** Helm  
- **CI/CD:** GitHub Actions  
- **Monitoring:** Prometheus + Grafana  
- **Scripting:** Bash, Python  

---

## Key Features

### Infrastructure Automation (Terraform)

- Provisioned AWS resources using Terraform:
  - VPC + Subnets
  - IAM Roles
  - EKS Cluster
  - Node Groups

### Kubernetes Operations (EKS)

- Deployed containerized workloads on Kubernetes
- Managed deployments using Helm charts
- Followed best practices for scalability and maintainability

### CI/CD Pipeline

- Automated build and deployment workflows
- Reduced manual deployment effort using GitHub Actions

### Monitoring and Logging

- Configured Prometheus for metrics collection
- Built Grafana dashboards for visibility
- Integrated CloudWatch logs for troubleshooting

### Operational Excellence

- Automated repetitive tasks using Bash/Python scripts
- Practiced incident troubleshooting and RCA-style debugging

---

## Repository Structure

```bash
aws-eks-infra-platform/
│
├── terraform/              # Infrastructure provisioning code
│   ├── vpc/
│   ├── eks/
│   └── iam/
│
├── k8s-manifests/          # Kubernetes YAML files
│   ├── deployments/
│   ├── services/
│   └── ingress/
│
├── helm-charts/            # Helm-based application deployments
│
├── ci-cd/                  # GitHub Actions workflows
│
├── monitoring/             # Prometheus + Grafana setup
│
└── scripts/                # Automation scripts (Bash/Python)

What I Learned

This project helped me gain strong practical experience in:

Terraform Infrastructure-as-Code workflows

AWS EKS cluster operations

Deployment automation with CI/CD

Monitoring cloud-native workloads

Troubleshooting real DevOps issues

Thinking like an infrastructure engineer

Future Improvements

Some enhancements I plan to add next:

Security hardening (RBAC + IAM best practices)

Blue/Green deployments with ArgoCD

Cost optimization and cluster autoscaling

Centralized logging with ELK stack
