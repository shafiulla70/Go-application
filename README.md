# Go-application
Go · Docker · Kubernetes (EKS) · Helm · GitHub Actions · ArgoCD · AWS | GitHub Built a complete DevOps pipeline for a Go web application with containerization. Containerized the application using Docker multi-stage builds. Automated CI/CD with GitHub Actions and managed deployment to AWS EKS using ArgoCD. 

## DevOpsify the Golang Web Application
The main goal of this project is to implement DevOps practices in the Go web application. The project is a simple website written in Golang. It uses the net/http package to serve HTTP requests.

### Project Overview
This project involves the following DevOps practices:

Creating Dockerfile (Multi-stage build)
Containerization
Continuous Integration (CI)
Continuous Deployment (CD)
GitOps with ArgoCD and AWS EKS
Prerequisites
Golang
Docker
AWS CLI
EKS CTL
Kubectl
Helm
ArgoCD

### Steps to Implement DevOps Practices
1. Creating Dockerfile (Multi-stage build)
The Dockerfile is used to build a Docker image containing the Go web application and its dependencies. A Multi-stage build reduces the size of the final Docker image and enhances security by removing unnecessary files and packages.

2. Containerization
Containerization is the process of packaging an application and its dependencies into a container. Docker is used to containerize the Go web application.

Build, Run, and Push Docker Image
3. Continuous Integration (CI)
CI automates the integration of code changes into a shared repository. GitHub Actions is used to implement CI for the Go web application.

4. Continuous Deployment (CD)
CD automates the deployment of code changes to a production environment. ArgoCD is used to implement CD for the Go web application.

5. GitOps with ArgoCD and AWS EKS
The ArgoCD application deploys the Go web application to a Kubernetes cluster and keeps it in sync with the Git repository.

