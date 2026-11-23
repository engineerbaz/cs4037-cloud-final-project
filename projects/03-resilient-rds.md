# Project 3: Resilient Relational Database, Surviving an AZ Outage

**AWS services:** RDS (Multi-AZ, Read Replica), VPC, Security Groups, snapshots

## Client brief
A bank lost three hours of service to an Availability Zone outage and wants proof it will not happen again.

## Requirements
Tick each box in your own `submission/REPORT.md` as you complete it, and attach evidence for every item.

- [ ] RDS instance in private subnets, reachable only from the application's Security Group
- [ ] Multi-AZ enabled, plus one Read Replica serving reporting queries
- [ ] A forced failover, with before and after evidence including the measured downtime
- [ ] Automated backups, and a snapshot restored into a new instance

## Defend It
Answer this in your report, and be ready to defend it live in the presentation. Every member may be asked.

> Why is a Read Replica not a substitute for Multi-AZ, and which workloads would you route to the replica?

## Key learning
High availability versus read scalability, and managed database operations.

## Cost watch
Multi-AZ and replicas run extra database instances. Delete them, and any manual snapshots, when you are done.

## Evidence checklist
- Architecture diagram saved in `submission/diagrams/`
- One screenshot per requirement in `submission/screenshots/`, named like `req-03-multi-az-enabled.png`
- Code, Dockerfiles, policies, or templates saved in `submission/code/`
- Screenshot of resources deleted at the end
