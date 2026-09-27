# AzureFlow — Professional Azure CI/CD Learning Dashboard

AzureFlow is a **self-contained, interactive DevOps learning website** built around an Azure CI/CD architecture.

## What this project demonstrates

The website explains and visually simulates:

**GitHub / Source → Azure Pipelines → Build → Test → Docker → Azure Container Registry → Environments → Approval → Azure App Service → Monitoring**

Microsoft describes Azure Pipelines as a CI/CD service that automates build, test and deployment. Pipeline stages can have dependencies, conditions and approval checks; Azure environments provide deployment history and traceability. Azure's App Service container workflow can build/publish a Docker image to ACR and deploy that image to App Service.

## Features

### Learning
- What CI/CD means
- Continuous Integration vs Continuous Delivery
- Why Azure is useful in this workflow
- Visual end-to-end pipeline model
- DevOps concept lessons

### Pipeline
- Source trigger
- Build & test
- Containerization
- Azure Container Registry
- Azure App Service
- Stage/status visualization
- YAML examples

### Professional dashboard
- Build history
- Deployment health
- Environment cards
- Pipeline run simulation
- Execution logs
- Monitoring metrics
- Deployment history
- Production release gates
- Approval check simulation
- Rollback simulation
- Commit/artifact traceability examples

### UI / UX
- Responsive layout
- Mobile navigation
- Scroll reveal animations
- Hover interactions
- Pipeline status badges
- Interactive YAML tabs
- Modal pipeline logs
- Toast notifications
- Professional dark cloud/DevOps visual style

## Run

No installation is required.

1. Download and extract the ZIP.
2. Open `index.html`.
3. It will run directly in Chrome.

## GitHub

Upload `index.html` and `README.md` to a GitHub repository.

For a live static deployment, enable GitHub Pages from the repository settings.

## Important distinction

This is an **interactive front-end simulation**, not a real Azure deployment. The Run Pipeline, approval and rollback controls demonstrate the concepts locally.

To make the project actually deploy applications, you would connect:
- an Azure DevOps project
- a real Git repository
- an Azure service connection
- a real Azure Container Registry
- a real Azure App Service
- a real `azure-pipelines.yml`
- optional staging/production environments and approval checks

## Suggested real pipeline stages

1. Build
2. Test
3. Docker Build
4. Push Image to ACR
5. Deploy to Staging
6. Smoke Test
7. Production Approval
8. Deploy to Production
9. Health Check
10. Rollback path

## Official references

Microsoft Learn:
- Azure Pipelines: https://learn.microsoft.com/azure/devops/pipelines/
- App Service with Azure Pipelines: https://learn.microsoft.com/azure/app-service/deploy-azure-pipelines
- Custom container to App Service: https://learn.microsoft.com/azure/devops/pipelines/apps/cd/deploy-docker-webapp
- Azure Pipelines stages: https://learn.microsoft.com/azure/devops/pipelines/process/stages
- Azure Pipelines environments: https://learn.microsoft.com/azure/devops/pipelines/process/environments
- Azure Container Registry: https://learn.microsoft.com/azure/container-registry/container-registry-intro
