# Project 5: Global Content Delivery, Fast Everywhere

**AWS services:** S3 static hosting, CloudFront, Route 53 (optional), bucket policies

## Client brief
A media brand's landing page loads slowly for visitors overseas.

## Requirements
Tick each box in your own `submission/REPORT.md` as you complete it, and attach evidence for every item.

- [ ] S3 static website with versioning and a bucket policy
- [ ] Direct bucket access blocked, so content is served only through CloudFront
- [ ] Route 53 custom domain if the group has one, otherwise a documented design
- [ ] Latency measured before and after CloudFront, from at least two locations
- [ ] A cache invalidation demonstration

## Defend It
Answer this in your report, and be ready to defend it live in the presentation. Every member may be asked.

> What is cached at the edge and for how long, and how would you push an urgent fix to every user immediately?

## Key learning
Edge caching, origin protection, and content delivery performance.

## Cost watch
A registered domain and a hosted zone cost real money. They are optional, so document the design if you skip them.

## Evidence checklist
- Architecture diagram saved in `submission/diagrams/`
- One screenshot per requirement in `submission/screenshots/`, named like `req-03-multi-az-enabled.png`
- Code, Dockerfiles, policies, or templates saved in `submission/code/`
- Screenshot of resources deleted at the end
