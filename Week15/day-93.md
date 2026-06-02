# Day 93 â€” February 20, 2026

## ðŸŒ Deep Dive â€” VPC & Networking (Post-Cert Review)

**Day Number:** 93 of 100
**Date:** February 20, 2026

---

## Why Revisit Networking?

VPC and networking concepts are the backbone of AWS architecture.
Even post-certification, reviewing these ensures the knowledge sticks for real-world use.

---

## Key VPC Concepts Reviewed

- **Subnets** â€” Public vs private, CIDR block planning
- **Route Tables** â€” Controlling traffic flow within VPC
- **Internet Gateway** â€” Enables public internet access for public subnets
- **NAT Gateway** â€” Allows private subnet instances to reach internet (outbound only)
- **VPC Peering** â€” Direct connectivity between two VPCs (non-transitive)
- **Transit Gateway** â€” Hub-and-spoke connectivity for multiple VPCs
- **VPC Endpoints** â€” Private access to AWS services without internet
- **PrivateLink** â€” Expose services privately across VPCs

---

## Exam Insight

The most common trap: VPC peering is **non-transitive**.
If VPC A peers with B, and B peers with C â€” A cannot reach C through B.
Use Transit Gateway for transitive routing.

---

*[â† Day 92](./day-92.md) | [â†’ Day 94](./day-94.md) | [100 Days of AWS](../README.md)*
