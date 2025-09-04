# Cloud-Native 2048 Game Deployment on AWS EKS

This project demonstrates the deployment of the classic **2048 game** on a **cloud-native architecture** using **Amazon EKS (Elastic Kubernetes Service)** and **AWS Fargate**. It highlights Kubernetes deployment practices, serverless compute, and infrastructure automation with Helm.

## Features
- **Containerized 2048 Game** packaged for Kubernetes deployment.
- **EKS with AWS Fargate** for serverless, scalable, and managed compute.
- **Helm-based ALB provisioning** for automated load balancing and seamless access.
- **IAM Role-based Access Control (RBAC)** and **OIDC integration** for secure infrastructure management.

## Architecture
1. The 2048 game is containerized and pushed to a container registry.
2. Kubernetes manifests and Helm charts provision:
   - EKS Cluster
   - Fargate Profile
   - Application Load Balancer (ALB)
   - RBAC roles and policies
3. Users access the game securely via the ALB endpoint.

## Deployment Steps
1. **Create EKS Cluster** with Fargate profiles.
2. **Set up ALB Controller** using Helm charts.
3. **Deploy the 2048 Game** using `kubectl` or Helm.
4. **Access the Game** from the ALB DNS URL.

## Screenshots
- EKS Cluster running on AWS
- Fargate nodes deployed successfully
- ALB integrated and routing traffic
- Game running live

## Skills Demonstrated
- Kubernetes Deployment (EKS + Fargate)
- Infrastructure as Code with Helm & YAML
- AWS Cloud Services (EKS, ALB, IAM, VPC)
- DevOps Best Practices (automation, scalability, security)

---
