# Provision an EKS Cluster with Terraform CI/CD on AWS

# Notes: 
- Set up Credentials in Github, 
- Set up workspace in Terraform Cloud. 

# Set up workspaces in versions.tf

```terraform
required_version = ">= 0.14"
  backend "remote" {
    organization = ""  

    workspaces {
      name = ""
    }
```
