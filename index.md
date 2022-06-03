# PiBS - Advanced IaC & DevOps with Terraform

# AWS CloudFormation

[https://youtu.be/eOBq__h4OJ4](https://youtu.be/eOBq__h4OJ4)

[https://youtu.be/6R44BADNJA8](https://youtu.be/6R44BADNJA8)

[https://youtu.be/1h-GPXQrLZw](https://youtu.be/1h-GPXQrLZw)

[https://youtu.be/GP-wknHzPpI](https://youtu.be/GP-wknHzPpI)

[https://youtu.be/KXUsyApAI3Y](https://youtu.be/KXUsyApAI3Y)

# Terraform

## Videos

[https://youtu.be/h970ZBgKINg](https://youtu.be/h970ZBgKINg)

[https://youtu.be/l5k1ai_GBDE](https://youtu.be/l5k1ai_GBDE)

[https://youtu.be/SLB_c_ayRMo](https://youtu.be/SLB_c_ayRMo)

## Hands-on tutorials

[Get Started - AWS | Terraform - HashiCorp Learn](https://learn.hashicorp.com/collections/terraform/aws-get-started)

[Use the Command Line Interface | Terraform - HashiCorp Learn](https://learn.hashicorp.com/collections/terraform/cli)

[Write Terraform Configuration | Terraform - HashiCorp Learn](https://learn.hashicorp.com/collections/terraform/configuration-language)

[Manage Terraform State | Terraform - HashiCorp Learn](https://learn.hashicorp.com/collections/terraform/state)

[Reuse Configuration with Modules | Terraform - HashiCorp Learn](https://learn.hashicorp.com/collections/terraform/modules)

[Provision Infrastructure | Terraform - HashiCorp Learn](https://learn.hashicorp.com/collections/terraform/provision)

# Source control & CodeCommit

## Git basics

[https://youtu.be/USjZcfj8yxE](https://youtu.be/USjZcfj8yxE)

## Git + Github

[https://youtu.be/RGOj5yH7evk](https://youtu.be/RGOj5yH7evk)

## Git advanced

[https://youtu.be/Uszj_k0DGsg](https://youtu.be/Uszj_k0DGsg)

[https://youtu.be/qsTthZi23VE](https://youtu.be/qsTthZi23VE)

## CodeCommit: the AWS way to git

[https://youtu.be/46PRLMW8otg](https://youtu.be/46PRLMW8otg)

[https://youtu.be/teXiG9C57Jk](https://youtu.be/teXiG9C57Jk)

# CI/CD : what does it mean?

[https://youtu.be/scEDHsr3APg](https://youtu.be/scEDHsr3APg)

[https://youtu.be/1er2cjUq1UI](https://youtu.be/1er2cjUq1UI)

[https://youtu.be/2TTU5BB-k9U](https://youtu.be/2TTU5BB-k9U)

[https://youtu.be/LNLKZ4Rvk8w](https://youtu.be/LNLKZ4Rvk8w)

[https://youtu.be/RYQbmjLgubM](https://youtu.be/RYQbmjLgubM)

# CI/CD with AWS: Code* tools

## Overview

[https://youtu.be/tQcF6SqWCoY](https://youtu.be/tQcF6SqWCoY)

[https://youtu.be/kaZOF4EEPqk](https://youtu.be/kaZOF4EEPqk)

[https://youtu.be/Tvz5rREeLkA](https://youtu.be/Tvz5rREeLkA)

## Pipeline for containerised apps

[https://youtu.be/jJ4WgX2aOcs](https://youtu.be/jJ4WgX2aOcs)

[https://youtu.be/00qQaoC-5ig](https://youtu.be/00qQaoC-5ig)

## CodeDeploy

[https://youtu.be/A4NSyUbAEkw](https://youtu.be/A4NSyUbAEkw)

## Local build with CodeBuild

[https://youtu.be/N3pW4ZCeCxA](https://youtu.be/N3pW4ZCeCxA)

## Advanced topics

[https://youtu.be/YGSJMpNTSaA](https://youtu.be/YGSJMpNTSaA)

## End-to-end example: deploying a .net application with code* tools

[https://youtu.be/4SB1t1yW9aE](https://youtu.be/4SB1t1yW9aE)

[https://youtu.be/5NSRjb_1pOI](https://youtu.be/5NSRjb_1pOI)

[https://youtu.be/NCXzTgjUOQo](https://youtu.be/NCXzTgjUOQo)

# Exercise

1. Create a CI/CD pipeline using Terraform
2. Create another CI/CD pipeline using CloudFormation
3. Choose an application that you’ve already developed and deploy it using one of the CI/CD pipelines you’ve created in 1. or 2. Build jobs will be based on CodeBuild. Host code in a git repository. Use CodeDeploy when is possible.
    
    Target for deployments:
    
    - On EC2
    - On a serverless platform (ECS/Fargate or Lambda). In case of containers, they have to be hosted in ECR.
    - On your local machine using CodeBuild agent (just the build part is enough)
4. Prepare a demo to show how to deploy updates to the app live via `git push + CI/CD`