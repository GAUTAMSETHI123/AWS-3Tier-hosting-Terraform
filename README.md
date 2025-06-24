# <u>🚀 AWS Three-Tier Web Architecture</u>

---

## <u>📘 Description</u>

This project is a **hands-on walkthrough** of a three-tier web architecture in AWS.  
We will be creating the necessary **network**, **security**, **application**, and **database components** to run this architecture in an **available** and **scalable** manner.

The project includes both:
- 🔧 Manual setup instructions using the AWS Console
- 🛠️ Infrastructure as Code (IaC) using tools like Terraform or CloudFormation

---

## <u>🎯 Audience</u>

This demo is intended for learners with technical roles, especially **Scaler Learners** aiming to understand **AWS architecture patterns**.

> ✅ **Expected Knowledge:**  
> You should have a basic understanding of the following AWS services:
> - VPC  
> - EC2  
> - RDS  
> - S3  
> - ELB  
> - IAM  
> - AWS Console navigation

---

## <u>🔧 Pre-requisites</u>

Before getting started, ensure you have the following:

- ✅ An [AWS account](https://aws.amazon.com/free/)
- ✅ An IDE or text editor of your choice (e.g., VS Code)
- ✅ Basic knowledge of:
  - Web applications
  - Databases
  - Cloud and networking fundamentals

---

## <u>🗂️ Architecture Overview</u>

> _Insert architecture diagram here_  
> 📌 Tip: Use [Excalidraw](https://excalidraw.com/) or [Canva](https://canva.com/) to create a neat visual

Expected layout:
- **Tier 1 (Presentation Layer):** Load Balancer (e.g., ALB/ELB)
- **Tier 2 (Application Layer):** EC2 instances running Dockerized microservice
- **Tier 3 (Data Layer):** RDS (MySQL/PostgreSQL)

---

