# Project 2: Cloud-Native Microservices Platform

**AWS services:** Docker, Amazon ECR, EKS or Fargate, Application Load Balancer

## Client brief
An e-commerce team is breaking a monolith into independently deployable services.

## Requirements
Tick each box in your own `submission/REPORT.md` as you complete it, and attach evidence for every item.

- [ ] A Dockerfile for each service (frontend and API)
- [ ] Images stored in Amazon ECR with versioned tags
- [ ] Deployment on EKS or Fargate behind a load balancer
- [ ] Evidence of service-to-service communication
- [ ] A rolling update: release v2 of one service with no downtime

## Defend It
Answer this in your report, and be ready to defend it live in the presentation. Every member may be asked.

> Why containers instead of virtual machines for this workload, and what trade-off did you accept by choosing EKS or Fargate?

## Key learning
The build, ship, run container lifecycle and the operational model of microservices.

## Cost watch
An EKS cluster has an hourly control plane charge on top of worker costs. Delete the cluster as soon as you have your evidence.

## Evidence checklist
- Architecture diagram saved in `submission/diagrams/`
- One screenshot per requirement in `submission/screenshots/`, named like `req-03-multi-az-enabled.png`
- Code, Dockerfiles, policies, or templates saved in `submission/code/`
- Screenshot of resources deleted at the end
