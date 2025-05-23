Setup deployment for: $ARGUMENTS

CI/CD:
- Test, lint, security scan
- Build optimized artifacts
- Deploy staging → production
- Include rollback strategy

Container:
- Multi-stage Dockerfile (<100MB)
- Health checks & secrets handling
- docker-compose for dev
- K8s manifests if needed

Production checklist:
- Zero-downtime strategy
- DB migrations planned
- Monitoring & alerts
- Rollback tested