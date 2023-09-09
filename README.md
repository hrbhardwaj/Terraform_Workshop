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

## Elastic - Beanstalk
In this Terraform script file does the following:

*  Configures the AWS provider for the desired region.
*  Creates an Elastic Beanstalk application named "my-example-app."
*  Creates an Elastic Beanstalk environment named "my-example-environment" and associates it with the application.
*  Specifies a platform for the environment using solution_stack_name. Be sure to select a suitable platform based on your application's 
    requirements.
*  Configures various settings for the environment, including instance type, memory limit, and environment type. Customize these settings to match 
    your application's needs.
*  Tags the environment with a name for easier identification. 

## Script 1 

 In this file creation of EC2 Instance with (autoscale,launch config,loadbalancer)
 
* Defines the AWS provider and region
* Creates a Launch Configuration with user data to set up a simple web server.
* Defines a security group and inbound rules for the EC2 instances.
* Sets up an Auto Scaling Group with a minimum and maximum size, desired capacity, and EC2 instance placement in specific subnets.
* Creates an Application Load Balancer (ALB).
* Configures the ALB listener and target group.
* Attaches the Auto Scaling Group to the ALB target group.

## Script 2 

This Script for Creating S3 Bucket in AWS

## Script 3 

This Script is for creating VPC with Subnets 

## Script 4 

This is Script for RDS Database Instance:

## Script 5 

This Script for  IAM User and Policy:
