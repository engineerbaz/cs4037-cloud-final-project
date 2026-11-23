# Project 11: Self-Healing Observability and Automated Remediation

**AWS services:** CloudWatch (metrics, alarms, dashboards, Logs Insights), SNS, EventBridge, Lambda, EC2, Application Load Balancer

## Client brief
An operations team wants incidents detected in seconds and fixed without waking an engineer.

## Requirements
Tick each box in your own `submission/REPORT.md` as you complete it, and attach evidence for every item.

- [ ] An application on EC2 behind an Application Load Balancer
- [ ] A CloudWatch dashboard covering the four golden signals: latency, traffic, errors, and saturation
- [ ] Alarms with SNS notifications, and Logs Insights queries that find a root cause
- [ ] An EventBridge rule and Lambda function that automatically remediates when an alarm fires
- [ ] An injected failure, with measured time to detect (MTTD) and time to recover (MTTR)

## Defend It
Answer this in your report, and be ready to defend it live in the presentation. Every member may be asked.

> Which kinds of failure should never be auto-remediated, and why?

## Key learning
Observability, SRE practice, and incident automation.

## Cost watch
Low cost, but dashboards, alarms, and extra instances can add small charges. Delete them when you are done.

## Evidence checklist
- Architecture diagram saved in `submission/diagrams/`
- One screenshot per requirement in `submission/screenshots/`, named like `req-03-multi-az-enabled.png`
- Code, Dockerfiles, policies, or templates saved in `submission/code/`
- Screenshot of resources deleted at the end
