# 01 — Docker Basics

## Objective

Establish a working Docker environment and understand the basic lifecycle:

**Dockerfile → Image → Container → Registry**

This exercise also publishes the first public image to Docker Hub and proves that it can be pulled back and run independently.

---

## Environment

- Windows workstation
- Docker Desktop
- Docker Hub account: `rakeshranderia`
- Public Docker Hub repository: `rakeshranderia/docker-hello`

---

## Core Concepts

### Dockerfile

A Dockerfile is the set of instructions used to build an image.

Example:

```dockerfile
FROM nginx:alpine

COPY index.html /usr/share/nginx/html/index.html

EXPOSE 80