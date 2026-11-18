---
title: "EC2 Spot Fleet & GitOps CodeDeploy"
date: 2026-11-03
weight: 4
chapter: false
pre: " <b> 4.4. </b> "
aliases:
  - /4-workshop/4.1-serverless-game-backend/4.1.4-ec2-fleet-gitops/
  - /4-workshop/4.1-Serverless-Game-Backend/4.1.4-ec2-fleet-gitops/
---

# 5.4. Provisioning EC2 Spot Fleet, Launch Template & GitOps CodeDeploy

In this section, we will create a sample **Amazon EC2 (Ubuntu 24.04 LTS)** Game Server, bake a custom AMI, set up a **Launch Template** for an EC2 Spot Fleet with an **ASG Warm Pool**, configure **S3 Static Website Hosting**, and implement a **GitOps CI/CD pipeline** using **GitHub OIDC** and **AWS CodeDeploy**.

---

### Detailed Modules:

* **[4.4.1. Sample EC2 Game Server & Baking AMI](4.4.1-ec2-ami/)**
* **[4.4.2. Launch Template & Auto Scaling Group Warm Pool](4.4.2-spot-launch-template/)**
* **[4.4.3. Amazon S3 Bucket & Static Website Hosting](4.4.3-s3-website/)**
* **[4.4.4. GitHub OIDC & AWS CodeDeploy GitOps Pipeline](4.4.4-github-codedeploy/)**
