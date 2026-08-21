# Architecture Playbook

Use this reference when the project is large enough that architecture decisions need more detail.

## Default decision order

1. Clarify the product outcome.
2. Identify clients: web, mobile, desktop, game, API, or multiple.
3. Identify data requirements.
4. Identify real-time requirements.
5. Identify scale and reliability requirements.
6. Identify external integrations.
7. Choose the simplest architecture that satisfies those requirements.

## Preferred progression

Start with a monolith or modular monolith unless there is a concrete reason for distributed services.

Introduce separate services only when there is a clear boundary such as:
- independent scaling
- independent deployment
- strong ownership boundary
- isolated workload
- infrastructure requirement
- reliability boundary

## Production concerns

For production systems consider:
- authentication and authorization
- database migrations
- backups
- observability
- health checks
- rate limiting
- caching
- queues/background jobs
- object storage
- CDN
- secret management
- CI/CD
- rollback

## Multi-platform products

For products with web + mobile + desktop:
- share API contracts and domain rules where practical
- avoid duplicating business logic unnecessarily
- keep platform-specific UI separate
- define compatibility/versioning strategy

For games:
- separate gameplay state from presentation where practical
- treat assets, input, save data, networking, and frame performance as first-class concerns
