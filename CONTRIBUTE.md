# Prepare new release

If a new version of the workflow should be published.

1. Create a new release in GitHub and give it an appropriate semantic versioning name
2. let the `v1` tag point to the new version

```bash
git tag v1 <newly-created-version>
git push origin v1
```
