# Terraform AWS Scaffold

## Purpose
Creates:
- S3 bucket for CI logs
- GitHub Actions OIDC provider
- IAM role for GitHub Actions

## Usage

cp terraform.tfvars.example terraform.tfvars
terraform init
terraform plan
terraform apply

## AWS prerequisites

Authenticate locally using AWS CLI or AWS SSO before running Terraform.
