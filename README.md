# AI-Sandbox-test

## Container image

The `cuda12.1` image is available from GitHub Container Registry:

```sh
docker pull ghcr.io/advcom-of-cpp/cpp-ai-sandbox:cuda12.1
```

To migrate another Docker Hub tag, run **Migrate container image** from the
Actions tab and provide the tag to copy. The workflow preserves the source
image manifest and publishes it under the repository's GHCR namespace.
