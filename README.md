# AWS Text-to-Speech CI/CD Pipeline

## Overview

This project demonstrates the deployment of a Text-to-Speech (TTS) web application using AWS cloud services and DevOps practices. The application is containerized using Docker and deployed on an AWS EC2 instance through an automated Jenkins CI/CD pipeline.

## Features

* Convert text into speech through a web interface
* Automated CI/CD deployment using Jenkins
* Docker-based containerization
* Secure AWS cloud infrastructure
* CloudWatch monitoring and SNS alerting
* S3-based backup and artifact storage

## Architecture

GitHub → Jenkins → Docker → AWS EC2 → Web Application

AWS Infrastructure:

* VPC
* Public Subnet
* Route Table
* Internet Gateway
* Security Groups
* IAM
* EC2
* S3
* CloudWatch
* SNS

## Tech Stack

* AWS (EC2, VPC, IAM, S3, CloudWatch, SNS)
* Docker
* Jenkins
* Git
* GitHub
* AWS CLI
* HTML
* CSS
* JavaScript

## CI/CD Workflow

1. Developer pushes code to GitHub.
2. Jenkins pulls the latest code.
3. Docker image is built automatically.
4. Existing container is stopped.
5. New container is deployed.
6. Updated application becomes available.

## Security Features

* IAM-based access control
* Security Group firewall rules
* Network isolation using VPC and Subnets
* Controlled inbound traffic on required ports

## Monitoring and Alerting

* CloudWatch metrics monitoring
* CPU utilization tracking
* SNS email notifications
* Infrastructure health monitoring

## Project Outcomes

* Automated software deployment
* Improved deployment reliability
* Reduced manual deployment effort
* Enhanced monitoring and observability
* Secure cloud infrastructure implementation

## Future Enhancements

* Kubernetes deployment
* Terraform-based Infrastructure as Code
* Auto Scaling Groups
* Application Load Balancer
* Multi-region deployment

## Author

Ankur Choudhary
