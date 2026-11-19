---
title: "Workshop"
date: 2026-11-03
weight: 4
chapter: false
pre: " <b> 4. </b> "
---

# Step-by-Step Guide: Building a Serverless & Auto-Scaling Online Game Arena On AWS

#### Workshop Overview

The Workshop modules are structured under main chapters **4.1** through **4.6** and sub-modules **4.x.y** below:

---

#### Agenda:

1. [4.1. Prerequisites & Region Setup](4.1-prerequiste/)
2. [4.2. Amazon Cognito & DynamoDB Setup](4.2-cognito-dynamodb/)
   * [4.2.1. Provisioning Amazon Cognito User Pool](4.2-cognito-dynamodb/4.2.1-cognito-user-pool/)
   * [4.2.2. Provisioning Amazon Cognito Identity Pool](4.2-cognito-dynamodb/4.2.2-cognito-identity-pool/)
   * [4.2.3. Provisioning Amazon DynamoDB Tables](4.2-cognito-dynamodb/4.2.3-dynamodb-tables/)
3. [4.3. Lambda Matchmaker & API Gateway REST API Deployment](4.3-matchmaker-api/)
   * [4.3.1. Provisioning AWS Lambda Matchmaker](4.3-matchmaker-api/4.3.1-lambda-matchmaker/)
   * [4.3.2. Provisioning Amazon API Gateway REST API](4.3-matchmaker-api/4.3.2-api-gateway/)
4. [4.4. EC2 Spot Fleet, Launch Template & GitOps CodeDeploy Setup](4.4-ec2-fleet-gitops/)
   * [4.4.1. Sample EC2 Game Server & Baking AMI](4.4-ec2-fleet-gitops/4.4.1-ec2-ami/)
   * [4.4.2. Launch Template & Auto Scaling Group Warm Pool](4.4-ec2-fleet-gitops/4.4.2-spot-launch-template/)
   * [4.4.3. Amazon S3 Bucket & Static Website Hosting](4.4-ec2-fleet-gitops/4.4.3-s3-website/)
   * [4.4.4. GitHub OIDC & AWS CodeDeploy GitOps Pipeline](4.4-ec2-fleet-gitops/4.4.4-github-codedeploy/)
5. [4.5. Asynchronous Analytics with DynamoDB Streams & Lambda](4.5-async-analytics/)
   * [4.5.1. Enabling DynamoDB Streams](4.5-async-analytics/4.5.1-dynamodb-streams/)
   * [4.5.2. Creating & Connecting MatchAnalytic Lambda](4.5-async-analytics/4.5.2-match-analytic-lambda/)
6. [4.6. Resource Cleanup](4.6-cleanup/)
   * [4.6.1. Cleaning up Amazon Cognito](4.6-cleanup/4.6.1-cognito-cleanup/)
   * [4.6.2. Cleaning up Amazon DynamoDB](4.6-cleanup/4.6.2-dynamodb-cleanup/)
   * [4.6.3. Cleaning up AWS Lambda Functions](4.6-cleanup/4.6.3-lambda-cleanup/)
   * [4.6.4. Cleaning up Amazon API Gateway](4.6-cleanup/4.6.4-api-gateway-cleanup/)
   * [4.6.5. Cleaning up CloudFront & AWS WAF](4.6-cleanup/4.6.5-cloudfront-waf-cleanup/)
