# End-to-End CI/CD and GitOps Deployment of Voting Microservices on Azure

## Project Overview
Deployed a cloud native microservices voting platform on Azure Kubernetes Service (AKS) using Azure DevOps CI/CD and ArgoCD GitOps.

## Architecture
- **Vote app** (Python) — voting frontend
- **Result app** (Node.js) — results dashboard
- **Worker** (.NET) — processes votes
- **Redis** — message queue
- **PostgreSQL** — persistent storage

## Technologies Used
- Azure Kubernetes Service (AKS)
- Azure Container Registry (ACR)
- Azure DevOps CI/CD Pipeline
- ArgoCD (GitOps)
- Docker
- Kubernetes
- Python, Node.js, .NET

## What I Built
- Deployed all 5 microservices on AKS
- Set up Azure DevOps CI pipeline to build and push Docker images to ACR
- Implemented GitOps with ArgoCD for automated deployments
- All pods running successfully on Kubernetes

## GitHub
https://github.com/sasinikalpanigaweshika/voting-app-azure-aks
