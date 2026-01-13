# Runbook: High Error Rate Incident

## Symptoms
- Error rate > 2%
- Spikes in 500 or 400 errors
- Checkout failures

## Steps
1. Confirm error rate in Azure Application Insights.
2. Check logs for recent exceptions.
3. Identify recent deployments.
4. Restart the service if needed.
5. Roll back if errors persist.
6. Document the incident.

## Expected outcome
Error rate returns to normal levels.
