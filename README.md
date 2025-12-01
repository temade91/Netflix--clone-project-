# Netflix Clone - Project

This project demonstrates a **Netflix Clone** application deployed on **Azure Kubernetes Service (AKS)** with a **GitHub Actions CI/CD pipeline**. Docker images are built, pushed to DockerHub, and deployed automatically to AKS based on branch (master → production, release → development).

---

## Features

- Automated **build, push, and deployment** using GitHub Actions
- Supports **multi-environment deployments** (dev and prod)
- Containerized application with Docker
- Kubernetes manifests for **deployment** and **service**
- Azure integration with AKS

---

## Requirements

- Docker installed locally
- **kubectl** CLI
- **Azure CLI** installed and configured
- GitHub Secrets:
  - `DOCKERHUB_USERNAME`
  - `DOCKERHUB_TOKEN`
  - `AZURE_CREDENTIALS` (service principal JSON)
- AKS cluster created with required namespaces

---



