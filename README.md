# Banking Demo GitOps

Argo CD desired state for development, UAT, and production-like environments.

- Development auto-syncs.
- UAT and production require manual sync.
- Secrets are created outside Git.
- Images are pulled from JFrog using immutable commit tags.
