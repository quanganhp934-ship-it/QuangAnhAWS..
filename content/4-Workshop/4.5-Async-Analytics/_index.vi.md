---
title: "Asynchronous Analytics"
date: 2026-11-03
weight: 5
chapter: false
pre: " <b> 4.5. </b> "
aliases:
  - /4-workshop/4.1-serverless-game-backend/4.1.5-async-analytics/
  - /4-workshop/4.1-Serverless-Game-Backend/4.1.5-async-analytics/
---

# 4.5. Xử lý Asynchronous Analytics với DynamoDB Streams & Lambda

Trong chương này, chúng ta sẽ cấu hình **DynamoDB Streams** trên bảng DynamoDB và viết hàm **MatchAnalytic Lambda** để thu thập log, xử lý thống kê và phân tích kết quả sau trận đấu một cách hoàn toàn bất đồng bộ (Asynchronous Event Processing), không gây bất kỳ độ trễ nào cho luồng ghép trận.

---

### Danh sách các bài học chi tiết:

* **[4.5.1. Kích hoạt DynamoDB Streams](5.5.1-dynamodb-streams/)**
* **[4.5.2. Tạo & Kết nối MatchAnalytic Lambda](5.5.2-match-analytic-lambda/)**
