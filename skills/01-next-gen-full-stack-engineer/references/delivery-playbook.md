# Delivery Playbook

Use this reference when the task includes build, deployment, release, or maintenance.

## Release sequence

1. Inspect current version and deployment.
2. Review changes.
3. Run tests and static checks.
4. Build production artifacts.
5. Validate environment configuration.
6. Apply database migrations safely.
7. Deploy.
8. Run health/smoke checks.
9. Inspect logs and runtime status.
10. Confirm the released version.
11. Record rollback steps.

## Production safety

Never:
- print secrets
- commit credentials
- delete production data casually
- run destructive migrations without understanding their effect
- claim deployment succeeded without verification

Prefer:
- backups for important data
- reversible migrations
- health checks
- staged rollout when risk is high
- automated deployment checks
- documented rollback

## Environment separation

Keep development, staging, and production configuration separate.

Required secrets should come from environment variables or the platform's secret manager.

## Update strategy

For an existing application, preserve unrelated work and avoid broad rewrites. Change only what the requirement needs unless architectural repair is necessary.
