---
title: "Workshop"
date: 2026-11-03
weight: 4
chapter: false
pre: " <b> 4. </b> "
---

# Hướng dẫn chi tiết Xây dựng Serverless & Event-Driven Game Backend trên AWS

#### Tổng quan bài Thực hành (Workshop)

Nội dung phần Workshop được cấu trúc thành các chương chính từ **5.1** đến **5.6** và các bài thực hành chi tiết **5.x.y** dưới đây:

> [!NOTE]
> * **Link Source Code**: [https://github.com/Nothingtoread/fighting-game/tree/main](https://github.com/Nothingtoread/fighting-game/tree/main)

---

#### Danh sách các chương thực hành:

1. [4.1. Chuẩn bị môi trường & Chọn Region](5.1-prerequiste/)
2. [4.2. Khởi tạo Amazon Cognito & DynamoDB Tables](5.2-cognito-dynamodb/)
   * [4.2.1. Khởi tạo Amazon Cognito User Pool](5.2-cognito-dynamodb/5.2.1-cognito-user-pool/)
   * [4.2.2. Khởi tạo Amazon Cognito Identity Pool](5.2-cognito-dynamodb/5.2.2-cognito-identity-pool/)
   * [4.2.3. Khởi tạo các bảng Amazon DynamoDB](5.2-cognito-dynamodb/5.2.3-dynamodb-tables/)
3. [4.3. Xây dựng Lambda Matchmaker & API Gateway REST API](5.3-matchmaker-api/)
   * [4.3.1. Khởi tạo hàm AWS Lambda Matchmaker](5.3-matchmaker-api/5.3.1-lambda-matchmaker/)
   * [4.3.2. Cấu hình Amazon API Gateway REST API](5.3-matchmaker-api/5.3.2-api-gateway/)
4. [4.4. Cấu hình EC2 Spot Fleet, Launch Template & GitOps CodeDeploy](5.4-ec2-fleet-gitops/)
   * [4.4.1. EC2 Game Server mẫu & Đóng gói AMI](5.4-ec2-fleet-gitops/5.4.1-ec2-ami/)
   * [4.4.2. Launch Template & Auto Scaling Group Warm Pool](5.4-ec2-fleet-gitops/5.4.2-spot-launch-template/)
   * [4.4.3. Amazon S3 Bucket & Static Website Hosting](5.4-ec2-fleet-gitops/5.4.3-s3-website/)
   * [4.4.4. GitHub OIDC & AWS CodeDeploy GitOps Pipeline](5.4-ec2-fleet-gitops/5.4.4-github-codedeploy/)
5. [4.5. Xử lý Asynchronous Analytics với DynamoDB Streams & Lambda](5.5-async-analytics/)
   * [4.5.1. Kích hoạt DynamoDB Streams](5.5-async-analytics/5.5.1-dynamodb-streams/)
   * [4.5.2. Tạo & Kết nối MatchAnalytic Lambda](5.5-async-analytics/5.5.2-match-analytic-lambda/)
6. [4.6. Dọn dẹp tài nguyên](5.6-cleanup/)
   * [4.6.1. Dọn dẹp Amazon Cognito](5.6-cleanup/5.6.1-cognito-cleanup/)
   * [4.6.2. Dọn dẹp Amazon DynamoDB](5.6-cleanup/5.6.2-dynamodb-cleanup/)
   * [4.6.3. Dọn dẹp AWS Lambda Functions](5.6-cleanup/5.6.3-lambda-cleanup/)
   * [4.6.4. Dọn dẹp Amazon API Gateway](5.6-cleanup/5.6.4-api-gateway-cleanup/)
   * [4.6.5. Dọn dẹp CloudFront & AWS WAF](5.6-cleanup/5.6.5-cloudfront-waf-cleanup/)
