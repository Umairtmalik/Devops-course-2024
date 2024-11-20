# DevOps Course 2024

## About This Repository
This repository is part of the DevOps Course 2024. It showcases my learning journey, contributions, and practical implementations of DevOps principles and tools.

## Blogs and Summaries
https://medium.com/@i210431/terraform-with-eks-a-seamless-approach-to-aws-kubernetes-deployment-ed5738fe741e

## summary
As organizations increasingly adopt Kubernetes for container orchestration, AWS Elastic Kubernetes Service (EKS) has become a popular choice for managing Kubernetes clusters in the cloud. Integrating Terraform, an infrastructure-as-code tool, simplifies and automates the deployment and management of EKS clusters, ensuring scalability, repeatability, and collaboration.

Why Use Terraform for EKS?
Terraform’s declarative approach offers:

Version control for infrastructure.
Consistency in deployments.
Controlled changes to infrastructure.
Easy collaboration on configurations.
Terraform integrates seamlessly with AWS, leveraging modules to simplify EKS cluster setup.

Key Steps for EKS Deployment:
Setup Terraform Project: Create a project directory and define infrastructure in a main.tf file.
Configure AWS Provider: Define the AWS region and credentials.
Define EKS Cluster: Use the Terraform EKS module to configure the cluster, VPC, subnets, and worker nodes.
Create IAM Roles: Define required IAM roles and policies for EKS functionality.
Output Key Info: Export cluster details like API endpoint and kubeconfig for easy access.
Deploy Infrastructure: Use terraform init, terraform plan, and terraform apply to create the cluster.
Accessing and Managing the Cluster:
Configure kubectl with the cluster’s kubeconfig.
Use kubectl to deploy workloads and manage the cluster.
Best Practices:
State Management: Store Terraform state remotely (e.g., AWS S3) for team collaboration.
Modularize Code: Separate configurations into reusable modules (e.g., VPC, EKS, IAM).
Secure Infrastructure: Use IAM policies, security groups, and ACLs.
Automate: Integrate Terraform with CI/CD pipelines for consistent deployments.
Conclusion:
Using Terraform to manage EKS clusters on AWS ensures efficient, repeatable, and scalable infrastructure deployments. By treating infrastructure as code, organizations can simplify complex cloud deployments and enhance collaboration.


## A Guide to My Learning and Contribution to DevOps
Learning Journey Overview
Over the past four months, I have undertaken a focused journey into DevOps, starting from scratch and gradually building expertise in the following areas:

Version Control with Git and GitHub:

Learned the fundamentals of Git for version control, branching, and collaboration.
Explored GitHub workflows, including pull requests, issues, and actions.
Continuous Integration and Continuous Deployment (CI/CD):

Set up CI/CD pipelines using Jenkins and GitHub Actions.
Automated build, test, and deployment processes to streamline software delivery.
Containerization with Docker:

Created Docker images and containers to encapsulate applications and dependencies.
Wrote Dockerfiles and optimized images for better performance.
Orchestration with Kubernetes:

Deployed containerized applications using Kubernetes.
Gained experience in working with YAML configurations for Pods, Deployments, and Services.
Infrastructure as Code (IaC):

Used Terraform to define and provision infrastructure on cloud platforms like AWS.
Applied best practices for modular and reusable infrastructure templates.
Monitoring and Logging:

Implemented monitoring tools like Prometheus and Grafana for application metrics.
Used ELK stack (Elasticsearch, Logstash, Kibana) for centralized logging.
Cloud Platforms:

Explored AWS and Azure, focusing on services like EC2, S3, Lambda, and Azure DevOps.
Key Contributions

GitHub Repositories:

DevOps-Sample-Project:
A repository showcasing a complete CI/CD pipeline setup, including Docker, Kubernetes, and Terraform.
Learning-DevOps:
A collection of my notes, exercises, and mini-projects from my four-month learning journey.
Open-Source Contributions:

Contributed to documentation and bug fixes in open-source projects related to CI/CD tooling.
This document provides a structured account of my progress and contributions, showcasing my readiness to apply DevOps practices in real-world scenarios.



## My Forked Sample Project

As part of my DevOps learning journey, I worked on a sample project to apply DevOps tooling and practices. 
The forked repository contains the following:
- CI/CD pipelines using GitHub Actions
- Dockerfile for containerization
- Kubernetes manifests for deployment
- Terraform scripts for infrastructure provisioning

You can find the full repository here: https://github.com/Umairtmalik/jenkins-pipeline-kubernetes

