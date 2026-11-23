# Project 9: Backup and Disaster Recovery Drill

**AWS services:** EBS snapshots, S3 versioning, RDS snapshots, cross-Region copy

## Client brief
A regulator requires proof that the business can recover from losing its primary environment.

## Requirements
Tick each box in your own `submission/REPORT.md` as you complete it, and attach evidence for every item.

- [ ] Backups across compute, storage, and database (EBS snapshots, S3 versioning, RDS snapshot)
- [ ] A cross-Region copy of at least one backup
- [ ] A simulated resource loss followed by a timed recovery
- [ ] Measured RTO and RPO documented from the drill
- [ ] A recommended DR strategy (backup and restore, pilot light, or warm standby) with its cost trade-off

## Defend It
Answer this in your report, and be ready to defend it live in the presentation. Every member may be asked.

> Is your measured RTO acceptable for a bank, and what would it cost to reduce it?

## Key learning
Resilience planning, RTO and RPO, and the cost of recovery speed.

## Cost watch
Copies in a second Region add storage and transfer charges. Delete the copies in both Regions afterwards.

## Evidence checklist
- Architecture diagram saved in `submission/diagrams/`
- One screenshot per requirement in `submission/screenshots/`, named like `req-03-multi-az-enabled.png`
- Code, Dockerfiles, policies, or templates saved in `submission/code/`
- Screenshot of resources deleted at the end
