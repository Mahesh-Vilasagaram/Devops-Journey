# AWS End-to-End Production Architecture Project

## Architecture Overview
This project demonstrates a highly available and scalable web application hosted on AWS using production best practices.

## Services Used
- VPC with public and private subnets
- Internet Gateway and NAT Gateway
- Application Load Balancer
- Auto Scaling Group
- EC2 with IAM Role
- Security Groups

## Architecture Flow
User → ALB → EC2 (Auto Scaling) → NAT → Internet

## Key Highlights
- High availability across multiple AZs
- Secure architecture using private subnets
- Auto scaling based on CPU utilization
- Health checks and self-healing instances

## Interview Talking Points
- Designed secure and scalable AWS infrastructure
- Implemented least privilege using Security Groups and IAM
- Used automation via EC2 user data

