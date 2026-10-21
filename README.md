# Docker Engineering

Hands-on Docker engineering covering image builds, registries, CI/CD, networking, security, optimisation and application packaging.

> **Status:** Active development  
> **Started:** October 2026

---

## Purpose

This repository is a practical collection of Docker engineering exercises, reusable patterns and working examples.

The focus is on understanding how containers operate in real environments rather than simply learning individual Docker commands.

Areas covered will include:

- image creation and optimisation;
- container lifecycle management;
- Docker Hub and container registries;
- persistent storage and volumes;
- container networking;
- environment variables and configuration;
- Docker Compose;
- health checks and resilience;
- image security and vulnerability scanning;
- GitHub Actions CI/CD;
- automated image publishing;
- tagging and release management;
- troubleshooting and operational practices.

The repository will grow as each capability is built and tested.

---

## Current Architecture

```text
Source Code
    |
    v
Dockerfile
    |
    v
Docker Image
    |
    v
Container
    |
    v
Local Application
    |
    v
Docker Hub Registry