# Day 94 â€” February 21, 2026

## ðŸ” Deep Dive â€” Security Services (Post-Cert Review)

**Day Number:** 94 of 100
**Date:** February 21, 2026

---

## Security Services Summary

| Service | Purpose |
|---------|---------|
| **KMS** | Managed encryption keys, envelope encryption |
| **Secrets Manager** | Store, rotate, and retrieve secrets automatically |
| **Parameter Store** | Config values and secrets (lighter alternative to Secrets Manager) |
| **IAM** | Identity and access control for all AWS resources |
| **Cognito** | User authentication for web/mobile apps |
| **GuardDuty** | Threat detection using ML and logs |
| **Macie** | Sensitive data discovery in S3 |
| **Inspector** | Automated security assessment for EC2 & containers |
| **WAF** | Filter malicious web traffic at the application layer |
| **Shield** | DDoS protection (Standard: free, Advanced: paid) |
| **Security Hub** | Aggregated view of security findings across services |
| **CloudTrail** | Audit log of all API calls in your account |
| **Config** | Track resource configuration changes over time |

---

## Key Exam Differentiators

- **Secrets Manager vs Parameter Store**: Secrets Manager auto-rotates; Parameter Store is cheaper for static config
- **WAF vs Shield**: WAF = layer 7 (HTTP), Shield = layer 3/4 (DDoS)
- **GuardDuty vs Inspector**: GuardDuty = threat detection from logs; Inspector = vulnerability scanning

---

*[â† Day 93](./day-93.md) | [â†’ Day 95](./day-95.md) | [100 Days of AWS](../README.md)*
