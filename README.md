# WordPress Deployment on AWS EC2 with Amazon RDS

## Project Overview
This project demonstrates the deployment of a WordPress website on AWS using an EC2 instance as the web server and Amazon RDS MySQL as the database.

The objective was to understand how cloud infrastructure, web servers, application software, and managed databases work together to host a dynamic website.

## AWS Services Used
- **Amazon EC2:** Hosts the WordPress application.
- **Amazon RDS (MySQL):** Stores WordPress website data.
- **Amazon VPC:** Provides the network environment.
- **Security Groups:** Controls inbound and outbound traffic.

## Technologies Used
- Linux (Amazon Linux)
- Apache HTTP Server
- PHP
- WordPress
- MySQL / MariaDB client

## Architecture

Browser → EC2 (Apache + PHP + WordPress) → Amazon RDS (MySQL)

## Implementation Steps
1. Launched an EC2 instance using Amazon Linux.
2. Configured security groups to allow required traffic.
3. Installed and configured Apache and PHP.
4. Created an Amazon RDS MySQL database.
5. Configured WordPress to connect to the RDS database.
6. Deployed WordPress on the EC2 instance.
7. Accessed the website through the EC2 public IPv4 address.

## Challenges and Learnings
- Configuring security groups for SSH and HTTP access.
- Connecting an EC2 instance to Amazon RDS.
- Configuring WordPress database credentials.
- Troubleshooting website access after an EC2 public IP change.
- Understanding the interaction between web servers, applications, and databases.

## Project Outcome
Successfully deployed a WordPress website on AWS EC2 with Amazon RDS MySQL as its backend database.

## Key Learnings
Gained practical experience with AWS compute, database services, Linux administration, web server configuration, and cloud-hosted application deployment.
