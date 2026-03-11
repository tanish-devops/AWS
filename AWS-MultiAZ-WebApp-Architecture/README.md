#overview

So the project is basically creating an architecture for high availability, scalability, and security in AWS for running a web app....

AWS Services used in it:
1. VPC
2. EC2
3. S3
4. RDS
5. AMAZON CLOUDWATCH
6. AUTO SCALING GROUP
7. SNS
8. ELB
9. ROUTE 53

How I created all:

1. VPC - we have to create a custom VPC for our webapp... so while creating VPC we need to keep a few things in our mind -- 1 that we must connect the  endpoint with S3 and RDS services..-- 2) we have to create two(as per your requirement) AZs with private and public subnets and create aseparatee route table for private subnets --3) also look for a NAT gateway to connect to private subnets for internet access...
