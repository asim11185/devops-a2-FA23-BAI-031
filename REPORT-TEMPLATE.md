# DevOps Assignment 2 Report

## 1. Project overview
This project is a personal portfolio website made with HTML and CSS. It displays my name, roll number, introduction, and contact details. I stored the source code in GitHub and used Docker with Nginx to run the website in a container. GitHub Actions checks the website and publishes the Docker image to Docker Hub when changes are pushed to the main branch.

## 2. Evidence screenshots
Insert your own screenshots with captions:
1. GitHub commit history showing at least five meaningful commits.
2. `feature-endpoint` pull request showing it was merged.
3. Docker Hub `devops-a2` repository showing the `manual` and `latest` tags.
4. Failed GitHub Actions run (intentionally caused on a branch).
5. Successful GitHub Actions run.
6. Portfolio website running from Docker at `http://localhost:8080` with the browser address bar visible.

## 3. Webhook observations
Fill this table using the actual requests shown on webhook.site.

| Event | Value of the Event header | Value of the ref field (push only) | Your own observation |
|---|---|---|---|
| Ping | Fill from webhook.site | Not applicable | Sent by GitHub when the webhook is first created |
| Push | Fill from webhook.site | Fill actual branch ref | Sent when a commit is pushed |
| Pull request opened | Fill from webhook.site | Not applicable | Sent when a pull request is opened |

**Difference:** The webhook sends event information to an external URL (webhook.site) so that another service can receive it. GitHub Actions runs automated jobs, such as checking the HTML and building/pushing the Docker image, in response to repository events.

## 4. Problem faced and solution
Write about a real problem you personally faced. Include the exact error message and explain the steps you took to solve it. Do not invent an error; use one from your actual work.
