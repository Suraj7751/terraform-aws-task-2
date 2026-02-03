# TASK-2: AWS Infrastructure using Terraform

## Overview
This task demonstrates the use of Terraform to define and manage
AWS infrastructure using Infrastructure as Code (IaC).

---

## What is Terraform?
Terraform is an open-source Infrastructure as Code tool that allows
users to define cloud infrastructure using declarative configuration files.

---

## What is AWS?
Amazon Web Services (AWS) is a cloud computing platform that provides
services such as compute, storage, networking, and security.

---

## AWS Services Used
- EC2 (Elastic Compute Cloud)
- IAM (Identity and Access Management)
- S3 (theoretical understanding)

---

## Project Structure
terraform-aws-task-2/
├── main.tf
├── provider.tf
├── variables.tf
├── outputs.tf
└── README.md


---

## Terraform Configuration Explanation

### Provider Configuration
The AWS provider is configured with a specific region to allow Terraform
to interact with AWS services.

### EC2 Instance
An EC2 instance is defined using Terraform to demonstrate resource creation.
The instance type used is `t2.micro`, suitable for free-tier usage.

---

## Terraform Workflow
1. `terraform init` – Initialize the project
2. `terraform plan` – Preview infrastructure changes
3. `terraform apply` – Create infrastructure
4. `terraform destroy` – Remove infrastructure

---

## Notes
Actual deployment requires valid AWS credentials.
This task focuses on understanding Terraform syntax and AWS integration.

---

## Conclusion
This task helps in understanding how Terraform can be used with AWS
to manage infrastructure in a scalable and repeatable way.

