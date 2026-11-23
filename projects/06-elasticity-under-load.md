# Project 6: Elasticity Under Fire, Load Testing and Auto Scaling

**AWS services:** EC2 launch templates, Auto Scaling, Application Load Balancer, CloudWatch

## Client brief
A ticketing platform expects a sudden flash-sale traffic spike.

## Requirements
Tick each box in your own `submission/REPORT.md` as you complete it, and attach evidence for every item.

- [ ] Application Load Balancer and an Auto Scaling group built from a launch template
- [ ] A target-tracking scaling policy
- [ ] A load test using Apache Bench or hey
- [ ] CloudWatch graphs with timestamps showing scale out, then scale in
- [ ] A written analysis of how long scaling took and why

## Defend It
Answer this in your report, and be ready to defend it live in the presentation. Every member may be asked.

> What delayed scaling in your test, and how would you tune the policy for a real flash sale?

## Key learning
Horizontal scaling behavior, scaling policy tuning, and proof of elasticity with metrics.

## Cost watch
Scaling out multiplies instance cost. Set a sensible maximum group size and delete the group afterwards.

## Evidence checklist
- Architecture diagram saved in `submission/diagrams/`
- One screenshot per requirement in `submission/screenshots/`, named like `req-03-multi-az-enabled.png`
- Code, Dockerfiles, policies, or templates saved in `submission/code/`
- Screenshot of resources deleted at the end
