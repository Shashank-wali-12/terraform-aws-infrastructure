# Terraform AWS Infrastructure

## Description
Provisioned AWS infrastructure using Terraform to deploy EC2 instances, configure VPC networking, and manage IAM policies.

## Tools Used
- Terraform
- AWS (EC2, VPC, IAM)

## Project Structure
- c1-variables.tf → Defines variables
- c2-variables.tf → Configuration inputs
- c3-security-group.tf → Security group rules
- c4-ec2-instance.tf → EC2 instance setup

## Features
- Infrastructure as Code (IaC)
- Automated resource provisioning
- Secure IAM configuration
- Scalable cloud infrastructure setup

## Commands
```bash
terraform init
terraform apply
