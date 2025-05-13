# My Node.js CI/CD Task

This is my solution for the DevOps internship Task 1: Automating a Node.js app deployment using GitHub Actions.

## What I Did
- Built a simple Node.js app.
- Dockerized it with a `Dockerfile`.
- Set up a CI/CD pipeline to push it to DockerHub.

## How It Works
1. Push code to the `main` branch.
2. GitHub Actions builds the Docker image.
3. The image is pushed to `mani628/nodejs-demo-app:latest`.

## Files
- `index.js`: The Node.js application.
- `Dockerfile`: Docker configuration.
- `.github/workflows/main.yml`: CI/CD pipeline.

## How to Test
Run this on any machine with Docker:
```bash
docker pull mani628/nodejs-demo-app:latest
docker run -d -p 3000:3000 mani628/nodejs-demo-app:latest
