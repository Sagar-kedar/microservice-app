# microservice-app
This repo is for hands-on deployment of microservice application using Kubernetes, Helm and Jenkins.

# Architecture Overview
**Source Code Management** - GitHub/GitLab (Microservices code & Helm charts) \
**Continuous Integration (CI)** - Jenkins automates build & testing \
**Containerization** - Docker packages microservices \
**Artifact Repository** - Amazon ECR for storing images \
**Continuous Deployment (CD)** - Helm deploys to Kubernetes (Amazon EKS) \
**Monitoring & Logging** - Prometheus, Grafana \

# Step-by-Step Implementation

## 1. Set Up Kubernetes Cluster (Amazon EKS)
* Create an EKS cluster using AWS UI
* Verify cluster: \
`` `aws eks --region us-east-1 update-kubeconfig --name myapp-cluster` 
kubectl get nodes ``

