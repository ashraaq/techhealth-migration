# techhealth-migration to AWS CDK Infrastructure (TypeScript)
This project provisions a VPC with public/private subnets, an EC2 instance, an RDS instance, and required IAM roles using AWS CDK (TypeScript).

# Architecture:
VPC (2 AZs)
1 Public + 1 Private subnet per AZ
EC2 in public subnet
RDS in private subnet
Security groups for EC2/RDS
IAM roles & policies

<img width="850" height="772" alt="Screenshot 2025-08-26 at 12 42 46 PM" src="https://github.com/user-attachments/assets/e54f0426-45fd-4cf6-9788-6d5383edd588" />
