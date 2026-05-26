# AWS 3-Tier VPC Architecture

## What I Built
A multi-tier, high-availability VPC on AWS spanning two Availability Zones.

## Architecture
- VPC with public and private subnets across 2 AZs
- Internet Gateway for public subnet access
- Security Groups for access control
- Amazon Linux 2023 web server on EC2
- IAM roles for secure access management

## What I Learned
- How VPCs isolate network environments in AWS
- Difference between public and private subnets
- How Security Groups act as virtual firewalls
- How Availability Zones provide redundancy

## Currently Expanding
- Adding Application Load Balancer
- Adding Auto Scaling Groups
- Implementing stricter IAM policies

## Tools Used
AWS Console, EC2, VPC, IAM, Security Groups
