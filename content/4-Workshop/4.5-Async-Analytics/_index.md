---
title: "Asynchronous Analytics"
date: 2026-11-03
weight: 5
chapter: false
pre: " <b> 4.5. </b> "
aliases:
  - /4-workshop/5.1-serverless-game-backend/4.1.5-async-analytics/
  - /4-workshop/5.1-Serverless-Game-Backend/4.1.5-async-analytics/
---

# 4.5. Asynchronous Post-Match Analytics with DynamoDB Streams

In this section, we will enable **DynamoDB Streams** on the DynamoDB tables and implement the **MatchAnalytic Lambda** function to capture post-match logs, metrics, and player statistics asynchronously (Asynchronous Event Processing), isolating analytics tasks from the core matchmaking path.

---

### Detailed Modules:

* **[4.5.1. Enabling DynamoDB Streams](5.5.1-dynamodb-streams/)**
* **[4.5.2. Creating & Connecting MatchAnalytic Lambda](5.5.2-match-analytic-lambda/)**
