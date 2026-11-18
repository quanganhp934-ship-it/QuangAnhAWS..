---
title: "Amazon Cognito & DynamoDB Setup"
date: 2026-11-03
weight: 2
chapter: false
pre: " <b> 4.2. </b> "
aliases:
  - /4-workshop/4.1-serverless-game-backend/4.1.2-cognito-dynamodb/
  - /4-workshop/4.1-Serverless-Game-Backend/4.1.2-cognito-dynamodb/
---

# 4.2. Amazon Cognito & DynamoDB Setup

In this section, we will configure an **Amazon Cognito User Pool & Identity Pool** to handle player authentication and authorize S3 asset downloads. Then, we will create two **Amazon DynamoDB** tables: one for the matchmaking queue (`MatchmakingQueue`) and another for live matches (`ActiveMatches`).

---

### Detailed Modules:

* **[4.2.1. Provisioning Amazon Cognito User Pool](4.2.1-cognito-user-pool/)**
* **[4.2.2. Provisioning Amazon Cognito Identity Pool](4.2.2-cognito-identity-pool/)**
* **[4.2.3. Provisioning Amazon DynamoDB Tables](4.2.3-dynamodb-tables/)**
