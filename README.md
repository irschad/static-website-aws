# Host a Static Website on AWS

## Overview
This project demonstrates how to host a static HTML web application on AWS, utilizing various AWS services for enhanced security, reliability, and scalability.

## Architecture
**Virtual Private Cloud (VPC)**: Configured with public and private subnets across two availability zones.
**Internet Gateway**: Deployed to enable connectivity between VPC instances and the internet.
**Security Groups**: Act as a network firewall.
**Availability Zones**: Utilization of two zones for reliability and fault tolerance.
**Public Subnets**: Used for NAT Gateway and Application Load Balancer.
**EC2 Instance Connect Endpoint**: For secure connections within subnets.
**Private Subnets**: Host web servers (EC2 instances) for security.
**NAT Gateway**: Provides internet access for instances in private subnets.
**EC2 Instances**: Hosting the website.
**Application Load Balancer & Auto Scaling Group**: Distributes traffic and manages EC2 instances.
**GitHub**: Stores web files for version control and collaboration.
**Certificate Manage**r: Secures application communications.
**Simple Notification Service (SNS)**: Alerts for activities within the Auto Scaling Group.
**Route 53**: Domain name registration and DNS setup.

## Conclusion
This setup ensures a scalable, secure, and fault-tolerant environment for hosting a static web application, leveraging AWS's robust infrastructure.
