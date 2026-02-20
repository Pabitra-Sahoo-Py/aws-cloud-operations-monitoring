# AWS Cloud Operations & Monitoring

## Project Overview
This project demonstrates a beginner-level AWS cloud operations workflow. 
The objective is to deploy a simple web application on an EC2 instance, monitor its health using CloudWatch, and handle incidents using documented operational procedures.

## Architecture
The architecture consists of a single Amazon EC2 instance hosted in the default VPC. 
Access is managed through an IAM user with limited permissions. 
CloudWatch is used to monitor instance health and performance metrics.

## AWS Services Used
- Amazon EC2
- AWS IAM
- Amazon CloudWatch

## Implementation Summary
- Created an IAM user to avoid using the root account
- Deployed a basic web application on an EC2 instance
- Configured CloudWatch monitoring for system health
- Created alarms to detect abnormal CPU utilization
- Simulated an incident and documented the resolution process

## Monitoring & Incident Management
CloudWatch metrics were used to monitor EC2 performance and availability. 
A CPU spike incident was simulated to validate alerting and incident response mechanisms.

## Operational Documentation
The following operational documents are included:
- IAM and EC2 setup documentation
- Monitoring configuration overview
- Incident simulation details
- Runbook for CPU-related alerts

## Key Learnings
- Importance of least-privilege access using IAM
- Basics of EC2 deployment and security group configuration
- Monitoring system health using CloudWatch
- Structured approach to incident detection and resolution
- Cost-awareness by stopping and cleaning up resources

## Project Status
Completed (Monitoring and incident handling implemented)
