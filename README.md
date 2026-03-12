# habit-tracker-api
A backend service where users create habits, log daily completions, and generate progress summaries.

This API was built to help me understand serverless backend engineering and to be able to create a clean system architecture. The project also uses TypeScript and raw SQL to add structure and help me maintain it.

Within this architecture, I use the following:
# API Gateway
-HTTP routing

# Lambda (Node.js 18.x runtime + TypeScript)
- compute for each endpoint

# Amazon RDS PostgreSQL 
- relational database

# AWS Secrets Manager 
- DB credentials

# AWS EventBridge 
- scheduled daily summary job

# AWS CloudWatch 
- logs and metrics

# Terraform 
- infrastructure as code

# GitHub Actions 
- CI/CD pipeline



