# GH Deployment Workflow

A minimal static website deployed with GitHub Actions to GitHub Pages.

## Overview
This project is a simple example of automating deployment for a static site. When changes are pushed to the `main` branch, the workflow publishes the site to GitHub Pages automatically.

## Project Structure
- `index.html` — the homepage content
- `.github/workflows/deploy.yml` — deployment workflow configuration

## Deployment
1. Push changes to the `main` branch.
2. GitHub Actions runs the deployment workflow.
3. The site is published to GitHub Pages.

## Local Preview
You can preview the page locally by opening `index.html` in a browser or serving the folder with a simple local web server.

Example:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

Project Idea: https://roadmap.sh/projects/github-actions-deployment-workflow
