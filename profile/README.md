# CloudOps Automator

![cloud](https://github.com/VbhvCloud/.github/assets/49318838/f7ac5382-e34d-4bfb-bebe-0e489b45cdeb)


# AWS Infrastructure & Web Application Suite

This suite comprises a collection of repositories that together facilitate the deployment of a secure, scalable, and highly available web application on AWS. Leveraging Terraform for infrastructure automation, AWS Lambda for serverless operations, and Django for web application development, this project provides an end-to-end solution for modern cloud-native application deployment and management.

## Key Features

- **Automated AWS Infrastructure**: Utilizes Terraform to provision VPCs, subnets, EC2 instances, databases, and more, ensuring a repeatable and secure infrastructure setup.
- **Serverless Email Notification System**: An AWS Lambda function integrates with Mailgun to send emails and tracks these activities using DynamoDB, triggered by SNS topics for real-time event handling.
- **Django RESTful API**: A Django-based backend offers a RESTful API for user and product management, supporting operations such as registration, login, and CRUD operations for product data, with AWS S3 integration for file storage.
- **Security and Scalability**: Includes configurations for autoscaling, load balancing, security groups, and IAM roles to ensure application scalability and security.
- **Comprehensive Deployment Scripts**: Provides scripts for deploying the Lambda function, managing database migrations, and automating AWS infrastructure setup and teardown.
- **Monitoring and Logging**: The Monitoring and Logging directory contains configurations for monitoring application health and performance using AWS CloudWatch. CloudWatch is integrated with CloudWatch Logs for centralized log management and analysis, enabling effective monitoring and troubleshooting.

## Components

1. **Terraform Configuration**: Sets up the required AWS infrastructure, including networking, compute, and database resources, along with security configurations and an S3 bucket for storage.
2. **Lambda Function for Email Notifications**: Sends email notifications using Mailgun and logs the event in a DynamoDB table, orchestrated by SNS.
3. **Django Web Application**: Implements a RESTful API for managing user data, with endpoints for registration, login, and user details, alongside product management functionalities.

## Getting Started

To deploy this suite:

1. Ensure prerequisites such as AWS CLI, Terraform, and Python are installed.
2. Clone the respective repositories for infrastructure setup, Lambda function, and the Django application.
3. Follow the setup instructions in each component's README for configuration and deployment.

## Use Cases

- **Rapid Deployment**: Quickly stand up a new web application environment with all necessary cloud infrastructure.
- **Event-Driven Email Notifications**: Automate email sending for user actions or system alerts.
- **Web Application Backend**: Deploy a scalable and secure backend for handling user and product data.


Feel free to explore each directory to gain insights into the CloudOps Automator and leverage its capabilities for efficient cloud infrastructure management and deployment. If you have any questions or need assistance, please don't hesitate to reach out to the project maintainers. Happy automating!

