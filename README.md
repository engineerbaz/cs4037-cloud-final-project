# CS4037 Introduction to Cloud Computing: Final Project

This repository is a template. Each group creates its own copy, completes one assigned project on AWS, documents it here, and submits the link on Google Classroom.

## How to start
1. **One member** opens this template on GitHub and clicks **Use this template**, then **Create a new repository**.
2. Name it `cs4037-group-XX` (replace XX with your group number) and set it to **Private**.
3. Under **Settings, Collaborators**, add every group member and the instructor (`engineerbaz`). Profile is https://github.com/engineerbaz/ 
4. Every member clones the repo and works on their own branch.
5. Read your assigned brief in `projects/`, then build and document it.

## What to submit
Everything lives in the `submission/` folder:

| Item | Location |
|---|---|
| Report (the main document) | `submission/REPORT.md` |
| Screenshots | `submission/screenshots/` |
| Architecture diagrams | `submission/diagrams/` |
| Code, Dockerfiles, policies, templates | `submission/code/` |

Then paste your repository link into the Google Classroom assignment before the deadline set there.

## Working as a group
- Every member must make commits under their own GitHub account. Commit history is part of the assessment.
- Use short branches and open a pull request into `main` for each piece of work. Another member reviews it.
- Write clear commit messages, for example `Add Multi-AZ failover screenshots and timing`.
- Each member owns one section of the report and writes their name against it in the team table.

## Naming rule
Every AWS resource you create must start with your group number, for example `grp07-vpc`, `grp07-alb`. Your screenshots must show these names. This is how evidence is matched to your group.

## Presentation
Present from this repo in class: about 10 minutes plus 3 minutes of questions. Every member presents a part, and any member may be asked to explain the Defend It question.

## Security rules, read before your first commit
- Never commit AWS access keys, secret keys, `.pem` files, passwords, or `.env` files. The `.gitignore` blocks common ones, but you are responsible.
- If a key is ever committed, treat it as compromised. Delete the key in IAM straight away, then tell your instructor. Removing it from the repo is not enough.
- Blur or crop your AWS account ID and any email addresses in screenshots.

## Cost rules
- Set an AWS budget alert before you build anything.
- Run the project in one member's account.
- Delete all resources after you capture your evidence, and include proof in the report.

See `docs/PRE-SUBMISSION-CHECKLIST.md` before you submit.
