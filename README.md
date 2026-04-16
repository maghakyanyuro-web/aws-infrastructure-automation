# AWS Infrastructure Automation with Terraform

This repository demonstrates how to automate the deployment of a cloud network infrastructure on AWS using Terraform. It also includes containerization with Docker and a CI/CD workflow.

## 🚀 Project Overview
The goal of this project is to provision a secure and scalable AWS environment automatically.

### Key Features:
- **Infrastructure as Code (IaC):** Defined using Terraform for consistency and reusability.
- **Networking:** Custom VPC setup with Public Subnets, Internet Gateway, and Route Tables.
- **Compute:** Automated EC2 instance provisioning.
- **Security:** Security Groups configured for controlled SSH (port 22) and Web (port 80) access.
- **Containerization:** Ready-to-use Dockerfile for application deployment.
- **CI/CD:** Basic GitHub Actions workflow for automation.

## 🛠 Tech Stack
- **Provider:** AWS
- **IaC Tool:** Terraform
- **Containerization:** Docker
- **CI/CD:** GitHub Actions
- **OS:** Linux (Ubuntu)

## 📁 Project Structure
- `main.tf`: Core infrastructure logic (VPC, Subnets, EC2).
- `variables.tf`: Input variables for flexible configuration.
- `outputs.tf`: Important information displayed after deployment (e.g., Public IP).
- `Dockerfile`: Instructions to build the application container.

---
