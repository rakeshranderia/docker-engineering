# Docker Engineering

Hands-on Docker engineering covering container images, registries, CI/CD and application packaging.

This repository contains practical Docker implementations and working examples developed while building and testing container-based workflows.

## Project Links

- **Docker Hub:** https://hub.docker.com/r/rakeshranderia/docker-hello
- **GitHub:** https://github.com/rakeshranderia/docker-engineering
- **Website:** https://rakeshranderia.com.au/projects/docker-engineering/
- **DEV article:** https://dev.to/rakeshranderia/docker-publishing-with-github-actions-a-practical-end-to-end-setup-39g4
- **CodePen visual:** https://codepen.io/rakeshranderia/pen/YPZvRGm

---

## Current Implementation

### Docker Hello

The first implementation packages a simple static web application using the lightweight `nginx:alpine` base image.

It demonstrates the core Docker lifecycle:

```text
Dockerfile
    ↓
Docker Image
    ↓
Container
    ↓
Docker Hub Registry
```
