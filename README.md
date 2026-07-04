# AWS EC2 Instance Management

## Project Overview

This project demonstrates the deployment, configuration, monitoring, and scaling of an Amazon EC2 instance deployed in a public subnet within an Amazon VPC.

The environment includes Security Group configuration, EC2 instance monitoring, Amazon EBS volume modification, instance resizing, termination protection, and validation of an Apache web server over HTTP.

## Architecture Components

- Amazon EC2
- Amazon EBS
- Security Groups
- Amazon VPC
- Public Subnet
- Apache Web Server

## Architecture

tbd...

## Skills Demonstrated

- Amazon EC2
- Amazon EBS
- EC2 Instance Management
- Security Groups
- EC2 Instance Monitoring
- EC2 Instance Scaling

## Implementation Steps

1. Launched an Amazon EC2 web server with termination protection enabled.
2. Reviewed the EC2 instance configuration, networking, and storage settings.
3. Configured Security Group inbound rules to allow HTTP traffic.
4. Validated web server accessibility through the public IPv4 address.
5. Monitored the instance health using EC2 Status Checks.
6. Resized the EC2 instance from t3.micro to t3.small.
7. Modified the attached Amazon EBS volume.
8. Tested termination protection before deleting the instance.
9. Successfully terminated the EC2 instance after disabling termination protection.

## What I Learned

- Amazon EC2 fundamentals
- Security Group configuration
- EC2 monitoring and status checks
- Instance resizing
- Amazon EBS volume modification
- Termination protection

## Possible Improvements

- Associate an IAM Role with the EC2 instance following least privilege principles.
- Deploy the instance behind an Application Load Balancer.

## Project Files

- Architecture Diagram
- EC2 Instance Configuration
- Web Server Validation
- EC2 Instance Resize
- EC2 Status Checks
- Termination Protection
- Security Group Configuration
