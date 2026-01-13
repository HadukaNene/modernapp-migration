# Runbook: Roll Back a Deployment

## When to use this runbook
Use this when a new deployment causes errors, performance issues, or customer impact.

## Steps
1. Identify the last known good version.
2. Use Azure deployment history to redeploy the previous version.
3. Confirm rollback success using health checks.
4. Notify stakeholders.
5. Open a GitHub issue to investigate the failed deployment.

## Expected outcome
ModernApp returns to a stable version with minimal downtime.
