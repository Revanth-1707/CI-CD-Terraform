
CI/CD Pipeline with Terraform, AWS, Jenkins, Ansible, and Docker
This project demonstrates an enhanced CI/CD pipeline for deploying a web application using GitHub, Jenkins, Ansible, Docker, Terraform, and AWS. The pipeline now includes scalable infrastructure provisioning and automated deployments.

🚀 What’s New?
Jenkins: Automates code fetching, building, and Dockerization.

Ansible: Ensures smooth deployment across worker nodes.

Docker: Runs the application efficiently inside containers.

Terraform: Provisions AWS EC2 instances and configures an Application Load Balancer (ALB) for seamless traffic distribution.

💡 Challenge Faced & Solution
🔐 Terraform AWS Authentication Issue

Problem: Managing AWS access and secret keys securely while provisioning infrastructure.

Solution:

Configured environment variables for secure access.

Used Jenkins’ built-in credential management to handle sensitive data securely.

This approach eliminated the need for hardcoding credentials and enhanced the overall security of the pipeline.

🛠️ Tools & Technologies Used
Version Control: GitHub

CI/CD Automation: Jenkins

Configuration Management: Ansible

Containerization: Docker

Infrastructure as Code (IaC): Terraform

Cloud Provider: AWS (EC2, ALB)

Feel free to customize the content further to suit your style! 😊
