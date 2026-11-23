# Project 8: Storage Tiering and Data Lifecycle Strategy

**AWS services:** S3 (classes, versioning, lifecycle), EBS snapshots, EFS, S3 Glacier

## Client brief
A media company's data is growing fast, and it must cut storage cost without losing anything.

## Requirements
Tick each box in your own `submission/REPORT.md` as you complete it, and attach evidence for every item.

- [ ] S3 lifecycle policy moving data across storage classes, with justified timings
- [ ] Versioning enabled, and an overwritten or deleted object recovered
- [ ] An EBS volume snapshotted and restored in a different Availability Zone
- [ ] EFS mounted on two EC2 instances, with a file written on one and visible on the other
- [ ] A comparison table of when to use each storage option

## Defend It
Answer this in your report, and be ready to defend it live in the presentation. Every member may be asked.

> Take one dataset and justify its access pattern, retention period, and tiering plan from a cost point of view.

## Key learning
Matching storage type and class to access patterns and compliance needs.

## Cost watch
Keep test data small. Delete snapshots, volumes, and file systems when you are done.

## Evidence checklist
- Architecture diagram saved in `submission/diagrams/`
- One screenshot per requirement in `submission/screenshots/`, named like `req-03-multi-az-enabled.png`
- Code, Dockerfiles, policies, or templates saved in `submission/code/`
- Screenshot of resources deleted at the end
