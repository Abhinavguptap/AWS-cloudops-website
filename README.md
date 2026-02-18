# 🚀 AWS CloudOps Web Deployment with CI/CD

This project demonstrates a complete CloudOps and DevOps workflow by deploying a static website on AWS EC2 using Nginx and implementing an automated CI/CD pipeline with GitHub Actions.

---

## 🌐 Live Demo
http://15.206.75.97

---

## 🧱 Architecture

GitHub → GitHub Actions → SSH → AWS EC2 → Nginx → Public Website

---

## ⚙️ Technologies Used

- AWS EC2 (Ubuntu 24.04)
- Nginx Web Server
- AWS IAM
- AWS CloudWatch Monitoring
- GitHub Actions (CI/CD)
- SSH Deployment

---

## 🚀 Features

- Deployed production-ready Nginx server on AWS EC2
- Hosted static website with public IP access
- Configured security groups and SSH access
- Implemented IAM user for controlled AWS access
- Enabled EC2 monitoring with CloudWatch
- Automated deployment using GitHub Actions CI/CD
- Secure key-based SSH deployment workflow

---

## 🔄 CI/CD Pipeline

The pipeline automatically deploys the website to EC2 whenever code is pushed to the `main` branch.

### Workflow:
1. Developer pushes code to GitHub
2. GitHub Actions triggers workflow
3. Secure SSH connection to EC2
4. Website files deployed to `/var/www/html`
5. Nginx serves updated site

---

## 📂 Project Structure
├── index.html
└── .github
└── workflows
└── deploy.yml

---

## 🔐 Security

- SSH key-based authentication
- IAM least-privilege access model
- AWS security group firewall rules
- GitHub Secrets for private key storage

---

## 📊 Monitoring

- EC2 CPU & network metrics via CloudWatch
- Instance health monitoring enabled

---

## 🎯 Learning Outcomes

- AWS EC2 provisioning & configuration
- Linux server & Nginx setup
- IAM access management
- Cloud monitoring with CloudWatch
- CI/CD pipeline design
- Automated deployment workflows

---

## 👨‍💻 Author

**Abhinav Gupta**  
Cloud & DevOps Enthusiast  

---

## 📌 Future Improvements

- HTTPS with Let's Encrypt
- Custom domain with Route53
- Load balancer & auto scaling
- Docker containerization
- Terraform IaC deployment

