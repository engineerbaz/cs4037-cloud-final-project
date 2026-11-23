# Project 10: CI/CD Pipeline for a Containerized Application

**AWS services:** GitHub Actions, Docker, Amazon ECR, ECS Fargate or EKS, IAM OIDC

## Client brief
A development team wants every merged code change built, tested, and deployed automatically.

## Requirements
Tick each box in your own `submission/REPORT.md` as you complete it, and attach evidence for every item.

- [ ] A small application with a Dockerfile in the repo
- [ ] A GitHub Actions workflow that builds and tests on every push
- [ ] Images pushed to Amazon ECR, tagged with the commit SHA
- [ ] Automatic deployment to ECS Fargate or EKS on merge to `main`
- [ ] AWS authentication through an OIDC role, not stored access keys
- [ ] Evidence that a failing test blocks deployment, and a rollback to the previous image

## Defend It
Answer this in your report, and be ready to defend it live in the presentation. Every member may be asked.

> Why are long-lived access keys in a CI pipeline a security risk, and how does OIDC reduce that risk?

## Key learning
CI/CD, pipeline security, immutable image tags, and rollback.

## Cost watch
Fargate tasks, EKS clusters, and load balancers are charged by the hour, and private repositories have a monthly limit on free GitHub Actions minutes. Keep workflows lean and delete the deployment afterwards.

## Note
GitHub reads workflow files only from `.github/workflows/` at the root of the repo, so put your workflow there. Copy it into `submission/code/` as well so it appears with your evidence. Never place AWS access keys in repository secrets. Use an OIDC role.

## Evidence checklist
- Architecture diagram saved in `submission/diagrams/`
- One screenshot per requirement in `submission/screenshots/`, named like `req-03-multi-az-enabled.png`
- Code, Dockerfiles, policies, or templates saved in `submission/code/`
- Screenshot of resources deleted at the end
