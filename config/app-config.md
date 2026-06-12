# NovaTech — App Configuration Reference

This document describes the environment variables used by NovaTech applications.

## Required Variables

| Variable | Description | Example |
|----------|-------------|--------|
| NOVATECH_API_KEY | Main API authentication key | nt-xxxx-xxxx |
| DATABASE_URL | PostgreSQL connection string | postgresql://host:port/db |
| SECRET_TOKEN | Internal service token | (auto-generated) |
| AWS_ACCESS_KEY | AWS IAM access key | AKIA... |
| AWS_SECRET_KEY | AWS IAM secret key | (never share) |

## Important

- Never hardcode these values in application code
- Always use environment variables
- Rotate keys every 90 days
- If a key is ever exposed, rotate it immediately and notify your team lead