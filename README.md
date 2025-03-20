# Azure Task Manager: Cloud-Native Deployment 🚀

## 📌 Overview
This project showcases the **deployment of a containerized Task Manager application** on **Microsoft Azure**, following DevOps best practices. It mirrors an **AWS ECS-based setup** but leverages **Azure Container Apps** for hosting and **Terraform for infrastructure provisioning**.  

The goal was to **package, build, and deploy** the application while implementing **CI/CD, security, and scalability**.  

**This README provides an overview of the deployment process, highlighting key decisions, trade-offs, and implementation details.** 

---

## 🔑 Key Features  
- **Containerized App Deployment** using **Azure Container Apps**  
- **Infrastructure as Code (IaC)** with **Terraform**  
- **Container Image Management** using **Azure Container Registry (ACR)**  
- **CI/CD Automation** with **GitHub Actions**  
- **Secure HTTPS Routing** using **Azure Front Door / Application Gateway**  

---

## 📖 Directory Structure  
```sh
azure-task-manager/
│── app/                     # Application source code & Dockerfile
│── terraform/                # Terraform configuration for infrastructure
│── .github/workflows/        # CI/CD pipeline setup
│── docs/                     # Documentation & architecture diagrams
│── README.md                 # Project documentation
```

## 🛠 Prerequisites  
Before deploying the **Azure Task Manager**, ensure you have the following installed and configured:

### ✅ Required Tools  
- **Azure CLI** – Install from [Microsoft Docs](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli)  
- **Terraform (latest stable version)** – Install from [Terraform Docs](https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli)  
- **Docker** – Required for containerizing the application  
- **GitHub Actions or Azure DevOps** – For CI/CD pipeline automation  
- **Azure Subscription** – Must have **Contributor** or **Owner** permissions  
- **Azure Container Registry (ACR)** – To store and manage container images  
- **Azure Container Apps** – Ensure it's available in your region  
