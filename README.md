# Reusable Workflows

Centralized reusable GitHub Actions workflows for project-poc-org.

## 📦 Available Workflows

### docker-build-push.yml

**Usage:**
```yaml
uses: project-poc-org/reusable-workflows/.github/workflows/docker-build-push.yml@v1.0.0
with:
  app-name: api-backend
  app-version: 1.0.0
secrets:
  AWS_ACCESS_KEY_ID: ${{ secrets.AWS_ACCESS_KEY_ID }}
  AWS_SECRET_ACCESS_KEY: ${{ secrets.AWS_SECRET_ACCESS_KEY }}
  AWS_REGION: ${{ secrets.AWS_REGION }}
```

See full documentation in the repository.
