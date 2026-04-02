📌 Project Title
E-Commerce Application Deployment using DevOps (AWS EKS + CI/CD Pipeline)

📖 Overview
This project demonstrates a complete end-to-end DevOps pipeline for deploying an E-Commerce application using modern tools and AWS cloud services.
The implementation covers CI/CD automation, containerization, security scanning, and Kubernetes deployment.
Inspired by Kastro Kiran V and implemented with hands-on execution.

🏗️ Architecture
Source Code: GitHub
CI/CD: Jenkins
Code Quality: SonarQube
Artifact Repo: Nexus
Containerization: Docker
Security: Trivy
Orchestration: Kubernetes (AWS EKS)

⚙️ Tech Stack
Category	Tools Used
Cloud	AWS (EKS, EC2, IAM)
CI/CD	Jenkins
Build Tool	Maven
Containerization	Docker
Orchestration	Kubernetes
Code Quality	SonarQube
Artifact Storage	Nexus
Security	Trivy

🔄 CI/CD Pipeline Flow
Code pushed to GitHub
Jenkins triggers pipeline
Maven build & test
File system scan (Trivy)
Code analysis (SonarQube)
Build artifact & publish to Nexus
Docker image build & push
Image security scan
Deployment to Kubernetes (EKS)

☁️ AWS Infrastructure Setup
Created IAM user with required permissions
Configured AWS CLI, kubectl, and eksctl
Created EKS cluster and node groups
Configured security groups and networking

🚀 Deployment
Application is deployed using:
Docker container (local testing)
Kubernetes deployment on AWS EKS

📸 Key Features
Automated CI/CD pipeline
Secure DevOps practices
Scalable Kubernetes deployment
Real-time monitoring-ready setup

📚 Learnings
CI/CD pipeline automation
Kubernetes cluster management
Docker & container lifecycle
DevSecOps integration
AWS infrastructure setup

🙌 Credits
Special thanks to:
Kastro Kiran V – for the original project guidance and learning reference

🔗 Repository
👉 https://github.com/SahilM1508/Ecommerce-App-Sahil

⭐ Support
If you found this project useful, feel free to ⭐ the repository!
