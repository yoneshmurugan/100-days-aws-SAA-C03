# Day 96 â€” February 23, 2026

## âš¡ Deep Dive â€” Serverless & Compute (Post-Cert Review)

**Day Number:** 96 of 100
**Date:** February 23, 2026

---

## Serverless Services Summary

| Service | Purpose |
|---------|---------|
| **Lambda** | Run code without managing servers (event-driven) |
| **API Gateway** | Build REST, HTTP, and WebSocket APIs |
| **SQS** | Message queue â€” decouples producers and consumers |
| **SNS** | Pub/Sub â€” fan-out notifications to multiple subscribers |
| **EventBridge** | Event bus â€” route events between AWS services and SaaS apps |
| **Step Functions** | Orchestrate multi-step workflows with state machines |
| **Fargate** | Serverless containers (no EC2 management) |

---

## Compute Options Comparison

| Option | Use Case |
|--------|----------|
| **EC2** | Full control, persistent workloads |
| **Lambda** | Event-driven, short-duration tasks (<15 min) |
| **ECS on EC2** | Containerized apps with EC2 control |
| **ECS on Fargate** | Serverless containers |
| **EKS** | Kubernetes workloads on AWS |
| **Elastic Beanstalk** | PaaS â€” deploy apps without managing infrastructure |

---

## Lambda Limits to Remember

- Max execution timeout: **15 minutes**
- Max memory: **10 GB**
- Max deployment package: **50 MB (zipped)** / 250 MB (unzipped)
- Concurrency: default **1000 per region**

---

*[â† Day 95](./day-95.md) | [â†’ Day 97](./day-97.md) | [100 Days of AWS](../README.md)*
