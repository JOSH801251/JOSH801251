[GITHUB_PROFILE_README.md](https://github.com/user-attachments/files/35207710/GITHUB_PROFILE_README.md)
<h1 align="center">Hi, I'm Joshva 👋</h1>

<h3 align="center">Application Support Engineer | Aspiring Cloud & DevOps Engineer</h3>

<p align="center">
  <a href="https://github.com/JOSH801251"><img src="https://img.shields.io/badge/GitHub-JOSH801251-181717?style=for-the-badge&logo=github" alt="GitHub profile"></a>
  <img src="https://img.shields.io/badge/Focus-Cloud%20%26%20DevOps-2563EB?style=for-the-badge" alt="Cloud and DevOps focus">
</p>

## About me

I work in application support and am building practical Cloud and DevOps engineering skills through hands-on projects and continuous learning.

My production-support experience includes:

- Monitoring production applications and Linux/Windows servers, reviewing logs and checking service health.
- Deploying application releases to IIS, performing application-pool operations and supporting rollbacks when required.
- Investigating incidents, troubleshooting APIs with Postman, coordinating with application teams and documenting findings in Jira.
- Using Grafana and operational reports/runbooks to support incident response and service reliability.

I am expanding this foundation with AWS, infrastructure as code, containers, Kubernetes, CI/CD automation and GitOps.

## Technology focus

| Area | Tools and technologies |
|---|---|
| Cloud | AWS – EC2, VPC, S3, RDS, IAM, CloudWatch |
| Infrastructure as Code | Terraform |
| CI/CD | Jenkins, GitHub Actions |
| Containers | Docker, Docker Hub |
| Orchestration | Kubernetes, Minikube, kind |
| Kubernetes configuration | Helm, Kustomize |
| GitOps | Argo CD |
| Monitoring | Grafana; learning Prometheus and alerting |
| Operating systems | Linux, Windows Server |
| Support and troubleshooting | IIS, Postman, Jira, log analysis, incident response |

## Featured projects

### 1. Online Boutique – Kubernetes, CI/CD and GitOps

[View repository](https://github.com/JOSH801251/online-boutique-eks)

- Uses GitHub Actions to build and publish container images for the Online Boutique microservices.
- Uses Kubernetes manifests and Kustomize overlays for the local Minikube deployment.
- Uses Argo CD for GitOps synchronization and demonstrated self-healing in the local cluster.
- Includes Terraform configuration for a future AWS EKS target; the AWS EKS environment is not currently deployed.

**Stack:** Docker, GitHub Actions, Docker Hub, Kubernetes, Kustomize, Argo CD, Terraform, AWS (target architecture).

### 2. Jenkins CI/CD – Docker and Kubernetes

[View repository](https://github.com/JOSH801251/End-to-End-CI-CD-Pipeline-with-Jenkins-Docker-Kubernetes)

- Builds an Nginx-based website image through a Jenkins Declarative Pipeline.
- Authenticates to Docker Hub using a Jenkins credential and publishes the image.
- Applies Kubernetes Deployment and NodePort Service manifests to the configured cluster.
- Demonstrates a local delivery workflow using Minikube.

**Stack:** Jenkins, Docker, Docker Hub, Kubernetes, Minikube, GitHub.

### 3. AWS Three-Tier Web Application Architecture

[View repository](https://github.com/JOSH801251/AWS-3-Tier-Application-Architecture)

- Documents a VPC design with public, private application and private database subnets.
- Covers an Application Load Balancer, EC2 application tier, Auto Scaling and Amazon RDS for MySQL.
- Includes IAM, Systems Manager, CloudWatch and SNS configuration walkthroughs with screenshots.
- This is a console-based learning implementation guide, not an automated Terraform deployment.

**Stack:** AWS VPC, EC2, ALB, Auto Scaling, RDS, IAM, Systems Manager, CloudWatch, SNS.

## Projects in progress

- [DevSecOps Pipeline](https://github.com/JOSH801251/End-to-End-DevSecOps-Pipeline) – architecture and implementation plan; automated scanning stages are not yet implemented.
- [Kubernetes Multi-Environment GitOps Platform](https://github.com/JOSH801251/kubernetes-Multi-Environment-GitOps-Platform) – initial scaffold; environment overlays and Argo CD deployment evidence are still to be added.

## Current learning focus

- AWS networking, IAM and EKS fundamentals.
- Terraform workflows, reusable infrastructure configuration and state management.
- Kubernetes deployment, troubleshooting and GitOps practices.
- Prometheus/Grafana monitoring, alerting and operational automation.
- Bash and PowerShell scripting for repeatable support and DevOps tasks.

---

<p align="center">
  <i>Build it, understand it, document it, and validate it.</i>
</p>
