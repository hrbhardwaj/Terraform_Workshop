# Terraform_Workshop
How to provisioned the cloud resources with Configuration file .

## ECS - Fargate 
In this Terraform script file does the following:

*  Creates a VPC with two public subnets in different availability zones.
*  Creates an ECS cluster.
*  Creates an IAM role and policy for ECS tasks, allowing specific ECS actions.
*  Attaches the IAM policy to the IAM role.
*  Defines an ECS task definition with your container image and configuration.
*  Creates an ECS service that runs the task using Fargate launch type in the specified subnets and security group.
