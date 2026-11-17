# DevOps Assignment 2

Personal portfolio website built using HTML and CSS, served through Nginx in Docker.

## Files
- `index.html`: portfolio page
- `style.css`: page styling
- `Dockerfile`: builds the Nginx-based Docker image
- `.github/workflows/ci.yml`: checks the page, builds the image, and pushes it to Docker Hub on pushes to `main`

## Before submitting
1. Replace `YOUR_ROLL_NUMBER` in `index.html` and in `.github/workflows/ci.yml`.
2. Replace `YOUR_EMAIL_ADDRESS` and `YOUR_GITHUB_USERNAME` in `index.html`.
3. Create a public GitHub repository named `devops-a2-YOUR_ROLL_NUMBER`.
4. Create a Docker Hub repository named `devops-a2`.
5. Add GitHub Actions secrets named `DOCKERHUB_USERNAME` and `DOCKERHUB_TOKEN`.
6. Follow the assignment instructions for commits, feature branch, pull request, webhook, screenshots, and report.
