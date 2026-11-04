# Production-Grade AWS Infrastructure with Terraform

## 1. Project Overview

This project demonstrates the design and implementation of secure,
scalable, and highly available AWS infrastructure using Terraform.

## 2. Business Scenario

A fictional SaaS startup needs cloud infrastructure to host its
web application and relational database.

The infrastructure must support:
- High availability across two Availability Zones
- Secure network segmentation
- Automated application scaling
- Private database access
- Infrastructure as Code
- Monitoring and operational visibility

## 3. Architecture Components

- Amazon VPC
- Public and private subnets
- Internet Gateway
- NAT Gateway
- Application Load Balancer
- EC2 Auto Scaling Group
- Amazon RDS
- IAM roles and policies
- Security Groups
- Amazon CloudWatch

## 4. Infrastructure Principles

- Least-privilege access
- Private-by-default application and database tiers
- Multi-AZ architecture
- Reusable Terraform modules
- Environment separation
- Cost awareness

## 5. Validation

Terraform formatting, initialization, validation, and automated
checks will be performed locally.

No live AWS deployment is included in this portfolio version.

## 6. Project Status

In progress.
