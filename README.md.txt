# AWS 2-Tier Web Architecture

## Project Overview

Designed and implemented a scalable and secure 2-Tier Web Architecture on AWS. The architecture separates the web/application layer from the database layer and uses AWS services for load balancing, auto-scaling, secure database connectivity, and monitoring.

## Architecture Diagram

![AWS 2-Tier Web Architecture](diagrams/aws-2-tier-architecture.png)

## Key Features

- Designed and implemented a scalable 2-Tier web architecture.
- Configured load balancing using Application Load Balancer (ALB).
- Configured Auto Scaling for EC2 instances.
- Implemented secure database connectivity using Amazon RDS.
- Set up monitoring and alerting using Amazon CloudWatch.
- Used Amazon VPC and Security Groups for network security.

## AWS Services Used

- Amazon VPC
- Amazon EC2
- Application Load Balancer (ALB)
- EC2 Auto Scaling
- Amazon RDS
- Amazon CloudWatch
- IAM
- Security Groups

## Architecture Components

### Web/Application Tier

Amazon EC2 instances host the web/application layer. An Application Load Balancer distributes incoming traffic across the EC2 instances.

### Load Balancing

The Application Load Balancer distributes incoming requests across multiple EC2 instances to improve availability and traffic handling.

### Auto Scaling

EC2 Auto Scaling automatically adjusts the number of instances based on application demand.

### Database Tier

Amazon RDS provides the managed relational database layer. Database access is configured securely from the application tier.

### Monitoring

Amazon CloudWatch monitors AWS resources and application metrics and can be configured to generate alerts.

## Technologies Used

- AWS
- Amazon EC2
- Amazon VPC
- Application Load Balancer
- Auto Scaling
- Amazon RDS
- Amazon CloudWatch
- IAM
- Linux

## Learning Outcomes

- Understanding of AWS 2-Tier architecture
- Load balancing and traffic distribution
- EC2 Auto Scaling
- Secure RDS connectivity
- AWS networking and security
- CloudWatch monitoring and alerting
- High availability and scalability concepts