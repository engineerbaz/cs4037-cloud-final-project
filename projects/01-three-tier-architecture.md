# Project 1: Production-Ready Three-Tier Architecture

**AWS services:** VPC, EC2, Application Load Balancer, Auto Scaling, RDS Multi-AZ, Security Groups

## Client brief
A fintech startup is moving its customer portal to AWS and cannot afford a single point of failure.

## Requirements
Tick each box in your own `submission/REPORT.md` as you complete it, and attach evidence for every item.

- [ ] Custom VPC across two Availability Zones with public and private subnet tiers
- [ ] Internet-facing Application Load Balancer and an Auto Scaling group for the web tier
- [ ] Private application tier, and a Multi-AZ RDS database in isolated subnets
- [ ] Security Groups chained tier to tier on least-privilege rules
- [ ] Resilience test: terminate a web instance and show traffic continues uninterrupted

## Defend It
Answer this in your report, and be ready to defend it live in the presentation. Every member may be asked.

> Why does the database subnet have no route to the Internet Gateway, and what is the blast radius if the web tier is compromised?

## Key learning
Designing a layered, highly available architecture where networking, compute, and data work together.

## Cost watch
Load balancers, NAT Gateways, and Multi-AZ RDS are charged by the hour. Delete them as soon as your evidence is captured.

## Evidence checklist
- Architecture diagram saved in `submission/diagrams/`
- One screenshot per requirement in `submission/screenshots/`, named like `req-03-multi-az-enabled.png`
- Code, Dockerfiles, policies, or templates saved in `submission/code/`
- Screenshot of resources deleted at the end
