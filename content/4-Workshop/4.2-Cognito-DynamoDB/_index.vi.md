---
title: "Khởi tạo Cognito & DynamoDB"
date: 2026-11-03
weight: 2
chapter: false
pre: " <b> 4.2. </b> "
aliases:
  - /4-workshop/4.1-serverless-game-backend/4.1.2-cognito-dynamodb/
  - /4-workshop/4.1-Serverless-Game-Backend/4.1.2-cognito-dynamodb/
---

# 4.2. Khởi tạo Amazon Cognito & DynamoDB Tables

Trong chương này, chúng ta sẽ cấu hình **Amazon Cognito User Pool & Identity Pool** để xử lý xác thực người chơi và cấp phát quyền tải asset/patch từ S3. Sau đó, chúng ta sẽ tạo 2 bảng **Amazon DynamoDB** để phục vụ hàng đợi ghép trận (`MatchmakingQueue`) và các trận đấu đang hoạt động (`ActiveMatches`).

---

### Danh sách các bài học chi tiết:

* **[4.2.1. Khởi tạo Amazon Cognito User Pool](4.2.1-cognito-user-pool/)**
* **[4.2.2. Khởi tạo Amazon Cognito Identity Pool](4.2.2-cognito-identity-pool/)**
* **[4.2.3. Khởi tạo các bảng Amazon DynamoDB](4.2.3-dynamodb-tables/)**
