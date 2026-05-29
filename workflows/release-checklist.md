# Workflow: Release Checklist

## Safe Launch Checklist
- [ ] Run full project linting and syntax compilation.
- [ ] Execute local unit and integration tests.
- [ ] Inspect environment file templates to verify no new secret variables are missing.
- [ ] Perform a bundle size review to detect bloated dependencies.
- [ ] Create a database backup checkpoint if running database migrations.
- [ ] Validate standard rollback procedures in the hosting platform.
