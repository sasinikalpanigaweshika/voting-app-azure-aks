
## Microservices

| Service | Language | Description |
|---------|----------|-------------|
| vote | Python | Frontend voting app |
| redis | Redis | Message queue |
| worker | .NET | Processes votes |
| db | PostgreSQL | Stores votes |
| result | Node.js | Shows live results |

## What I Built

- Deployed 5 microservices on Azure Kubernetes Service (AKS)
- Azure DevOps CI pipeline builds and pushes Docker images to ACR
- ArgoCD GitOps automatically deploys from Azure Repos to AKS
- All pods running: Healthy + Synced

## Tech Stack

AKS | ACR | Azure DevOps | ArgoCD | Docker | Kubernetes | Python | Node.js | .NET | Redis | PostgreSQL

## Terraform Infrastructure

Full infrastructure as code:
https://github.com/sasinikalpanigaweshika/voting-app-terraform-infra
EOF

