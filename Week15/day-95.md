# Day 95 â€” February 22, 2026

## ðŸ—„ï¸ Deep Dive â€” Databases (Post-Cert Review)

**Day Number:** 95 of 100
**Date:** February 22, 2026

---

## AWS Database Services Summary

| Service | Type | Best For |
|---------|------|----------|
| **RDS** | Relational (MySQL, Postgres, Oracle, SQL Server, MariaDB) | Traditional relational workloads |
| **Aurora** | Relational (MySQL/Postgres compatible) | High performance, cloud-native relational DB |
| **DynamoDB** | NoSQL (key-value + document) | Millisecond latency at any scale |
| **ElastiCache** | In-memory (Redis / Memcached) | Caching, session storage, leaderboards |
| **Redshift** | Data warehouse | OLAP analytics at petabyte scale |
| **Neptune** | Graph database | Social networks, fraud detection, knowledge graphs |
| **DocumentDB** | MongoDB-compatible | Document workloads |
| **Timestream** | Time-series | IoT, monitoring, metrics |

---

## Key Differentiators

- **RDS Multi-AZ** = High availability (synchronous replica, automatic failover)
- **RDS Read Replicas** = Scalability (asynchronous, readable, can be cross-region)
- **Aurora** = 6-way replication across 3 AZs by default, up to 15 read replicas
- **DynamoDB DAX** = In-memory cache for DynamoDB (microsecond reads)

---

*[â† Day 94](./day-94.md) | [â†’ Day 96](./day-96.md) | [100 Days of AWS](../README.md)*
