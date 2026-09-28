# AWS 3-Tier Java Application

A three-tier application practice project demonstrating how a Java web application can be structured and prepared for AWS deployment.

## Architecture

**Users → Application Load Balancer → Web/Application tier → RDS database**

Core AWS and DevOps concepts covered:

- VPC and subnet architecture
- EC2
- Application Load Balancer
- Auto Scaling
- Amazon RDS / MySQL
- Nginx
- Apache Tomcat
- Java + Maven
- Infrastructure as Code with Terraform
- Monitoring and security

## Application Layers

- Presentation / web layer
- Application layer
- Database layer

## DevOps Workflow

1. Build Java application with Maven
2. Package the application
3. Provision infrastructure
4. Configure web/application servers
5. Connect application tier to RDS
6. Validate application through the load balancer

## Deployment Status

This is a learning/practice implementation. No AWS deployment is claimed unless explicitly documented with real evidence.

## Source / Attribution

The architecture and learning material were studied from the DevOps-Projects community repository and adapted for practice.