# Postmeister

A modular, AI-native social media scheduling platform, starting with Facebook Pages.

## Project status

Planning stage. Application code and deployment are not implemented yet.

Read the [implementation plan](docs/implementation-plan.md) for architecture, security, publishing reliability, milestones, acceptance criteria, and costs.

## Planned stack

- Next.js and TypeScript frontend
- NestJS API and worker on Google Cloud Run
- Cloud Tasks and Cloud Scheduler with a PostgreSQL transactional outbox
- Supabase PostgreSQL and Auth for MVP, with database portability to Cloud SQL or RDS
- Private object storage behind provider adapters
- Official Meta Pages API, revision-bound approvals, and AI provider adapters
- OpenTelemetry and Grafana Cloud

## Delivery

Track the six staged milestones in GitHub Issues. Implementation starts with the Meta feasibility and infrastructure decisions in M0.

## Security and licensing

Never commit credentials, tokens, database exports, or real environment files. Use placeholders in configuration examples and managed secret storage for deployments.

The repository is public. An open-source license has not yet been selected; resolve licensing before distributing or reusing project code.
