# Project 4: Serverless REST API, Zero Servers, Pay per Request

**AWS services:** AWS Lambda (Python), API Gateway, DynamoDB, IAM, CloudWatch Logs

## Client brief
A startup wants an API with no idle cost and no patching burden.

## Requirements
Tick each box in your own `submission/REPORT.md` as you complete it, and attach evidence for every item.

- [ ] Python Lambda functions for create, read, update, and delete
- [ ] DynamoDB table as the data store
- [ ] API Gateway routes tested with sample requests
- [ ] A least-privilege IAM execution role for the functions
- [ ] CloudWatch Logs evidence, including one deliberately triggered error

## Defend It
Answer this in your report, and be ready to defend it live in the presentation. Every member may be asked.

> Under what conditions would this serverless design become slower or more expensive than a fleet of EC2 instances?

## Key learning
The serverless execution model, event-driven design, and consumption-based pricing.

## Cost watch
Usually the cheapest project. Still set a budget alert and delete the API and table afterwards.

## Evidence checklist
- Architecture diagram saved in `submission/diagrams/`
- One screenshot per requirement in `submission/screenshots/`, named like `req-03-multi-az-enabled.png`
- Code, Dockerfiles, policies, or templates saved in `submission/code/`
- Screenshot of resources deleted at the end
