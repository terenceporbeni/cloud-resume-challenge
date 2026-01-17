# Cloud Resume Challenge – AWS

This project implements the **Cloud Resume Challenge** using modern cloud engineering best practices, including **Infrastructure as Code (Terraform)** and secure AWS services.

## 📌 Project Overview

The goal of this project is to build and deploy a cloud-hosted resume that demonstrates real-world AWS skills beyond basic certification knowledge.

The solution uses:
- AWS-managed services
- Infrastructure as Code
- Secure, production-style architecture

---

## 🧱 Architecture (Current State)
Browser
↓
CloudFront (HTTPS)
↓
S3 (Private Bucket)


---

## 🛠 Technologies Used

- **Frontend**
  - HTML
  - CSS
  - JavaScript

- **AWS Services**
  - Amazon S3 (private static site storage)
  - Amazon CloudFront (CDN + HTTPS)
  - IAM (least privilege access)
  - Terraform (Infrastructure as Code)

- **Tools**
  - Git & GitHub
  - VS Code
  - AWS CLI
  - Terraform

---

## ✅ Completed Milestones

### Day 1 – Environment & Version Control
- Local tooling setup
- GitHub repository initialization
- Project structure created

### Day 2 – Frontend Resume
- Resume website built with HTML/CSS/JS
- Responsive layout
- Placeholder visitor counter
- Resume content updated professionally

### Day 3 – AWS Deployment (IaC)
- Terraform AWS provider configuration
- Private S3 bucket created
- Frontend files uploaded via Terraform
- CloudFront distribution configured
- HTTPS enabled
- Secure bucket policy using Origin Access Control (OAC)

---

## 🔜 Upcoming Work

- DynamoDB visitor counter
- AWS Lambda (Python backend)
- API Gateway integration
- Frontend-to-backend connectivity
- CI/CD automation

---

## 🌍 Live Site

The resume is deployed using CloudFront and accessible via HTTPS.

---

## 📄 License
This project is for learning and demonstration purposes.

