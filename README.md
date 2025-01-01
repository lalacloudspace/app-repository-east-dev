# AWS CodePipeline for Static Website Deployment

This repository contains an automated **3-stage AWS CodePipeline** that deploys a static website using **AWS S3**, **CloudFront**, **ACM**, and **Route 53**. 

## Pipeline Breakdown

1. **Source Stage**: Pulls code from **GitHub**.
2. **Build Stage**: Packages the CloudFormation template and uploads it to **S3**.
3. **Deploy Stage**: Deploys resources via **AWS CloudFormation**.

## Steps to Use

1. Fork or clone this repository.
2. Set up a new **AWS CodePipeline** with **GitHub** as the source.
3. Add **AWS CodeBuild** to build the CloudFormation template.
4. Add **AWS CloudFormation** to deploy the stack.

## Resources
- CloudFormation Template: `s3_static_web.yml`
- BuildSpec for CodeBuild: `buildspec.yml`

