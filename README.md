# Terraform Project: Infrastructure Automation on AWS

This project is a **Terraform-based infrastructure automation** that provisions and manages cloud resources on **AWS**. It showcases how to define infrastructure as code (IaC) using Terraform to ensure consistent and repeatable cloud deployments.  

## Project Overview
- Automates the creation of AWS infrastructure using Terraform.  
- Provisions essential resources such as **EC2 instances**, **S3 buckets**, and **VPCs**.  
- Ensures a scalable and reliable infrastructure setup with minimal manual intervention.  

## Features
- Infrastructure as Code (IaC) with Terraform  
- Automated provisioning of AWS resources  
- Modular and reusable Terraform configurations  
- Version-controlled infrastructure  

## Technologies Used
- **Tool:** Terraform  
- **Cloud Provider:** AWS  
- **Languages:** HCL (HashiCorp Configuration Language)  

## Prerequisites
- Terraform installed (`v1.x or above`)  
- AWS CLI configured with necessary credentials  
- An active AWS account  

## Project Setup
1. **Clone the Repository:**  
   ```bash
   git clone https://github.com/your-repo/terraform-aws-project.git
   cd terraform-aws-project

2. **Initialize Terraform:**

   ```bash
   terraform init
3. **Plan the Infrastructure:**

   ```bash
   terraform plan
4. **Apply the Configuration:**

   ```bash
   terraform apply
Confirm with **yes** to provision the infrastructure.

5. **Verify the Resources:**
   Check the AWS Console to confirm the resources were created.
6. **Destroy the Infrastructure (Optional):**

   ```bash
   terraform destroy
# Project Structure

``` bash
terraform-aws-project/
│
├── main.tf           # Core Terraform configuration
├── variables.tf      # Input variables
├── outputs.tf        # Output definitions
├── provider.tf       # AWS provider configuration
├── README.md         # Project documentation
└── terraform.tfstate # Terraform state file (generated after apply)
```
# Resources Created
  - EC2 Instance: Virtual machine on AWS
  - S3 Bucket: Object storage for static files
  - VPC: Virtual Private Cloud for networking
# Future Improvements

  - Add more resources such as RDS and Lambda functions.
  - Implement Terraform modules for better organization and reusability.
  - Integrate with CI/CD pipelines for automated infrastructure deployment.
# Author
**Abhirup Mohapatra**

B.Tech in Electronics and Communication Engineering (Silicon University, Bhubaneswar)

DevOps enthusiast | Terraform & AWS practitioner
