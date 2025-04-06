# EKS-Terraform

This repository contains Terraform configurations for deploying an Amazon EKS (Elastic Kubernetes Service) cluster.

**Files Overview**

**main.tf** – Defines the Terraform configuration, including providers and resources for EKS deployment.

**variables.tf** – Declares input variables for customization of the infrastructure.

**outputs.tf** – Specifies the output values, such as the EKS cluster name and endpoint.

**Usage**

**Initialize Terraform:**
```
terraform init
```
**Plan the infrastructure changes:**
```
terraform plan
```
**Apply the changes to deploy the EKS cluster:**
```
terraform apply -auto-approve
```
**Destroy the infrastructure if needed:**
```
terraform destroy -auto-approve
```
**Prerequisites**

Terraform installed

AWS CLI configured

IAM permissions to create AWS resources

# License

This project is licensed under the MIT License.
