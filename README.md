# microservice-app
This repo is for hands-on deployment of microservice application using Kubernetes, Helm and Jenkins.

# Architecture Overview
Source Code Management - GitHub/GitLab (Microservices code & Helm charts) \
Continuous Integration (CI) - Jenkins automates build & testing
Containerization - Docker packages microservices
Artifact Repository - Amazon ECR/JFrog Artifactory for storing images
Continuous Deployment (CD) - Helm deploys to Kubernetes (Amazon EKS)
Monitoring & Logging - Prometheus, Grafana, and ELK
