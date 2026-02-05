# Production-style-AWS-setup
highly available, production-ready AWS VPC architecture designed for secure web applications.

 ![Image Alt](https://docs.aws.amazon.com/images/vpc/latest/userguide/images/vpc-example-private-subnets.png)
 
Services:
 
VPC,Subnets(private and public),Internet Gateway,Nat Gateway,Route Tables,EC2(Bastion Host),Application Load Balancer,Target Group
Security Groups

Implementation Steps (Manual AWS Console)

-Created a custom VPC with CIDR block

-Created public and private subnets across two Availability Zones

-Attached an Internet Gateway to the VPC

-Configured route tables for public and private subnets

-Deployed NAT Gateway in a public subnet

-Launched EC2 instances in private subnets

-Created an Application Load Balancer in public subnets

-Configured Target Groups and health checks

-Attached Security Groups with controlled inbound/outbound rules

-Verified application access via ALB DNS


