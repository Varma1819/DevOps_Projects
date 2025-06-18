# 🚀 CI/CD Pipeline for Static Website Deployment using GitHub Actions

This project demonstrates how to set up a **CI/CD pipeline** to automatically deploy a static website to **GitHub Pages** using **GitHub Actions**.

## 📌 Project Overview

Every time a change is pushed to the `main` branch, the GitHub Actions workflow is triggered. It checks out the code, uploads the static site as an artifact, and deploys it directly to GitHub Pages — without any manual intervention.

This setup follows DevOps best practices for automation, speed, and consistency.

---

## 🧑‍💻 Technologies Used

- **GitHub Actions** – For automating deployment on every code push
- **GitHub Pages** – To host the static website
- **YAML** – For defining CI/CD workflow
- **Git** – For version control and deployment triggers
- **Bash (optional)** – For scripting automation steps

---

## ⚙️ CI/CD Workflow Explained

The `.github/workflows/deploy.yml` file contains the deployment workflow:

```yaml
on:
  push:
    branches:
      - main

jobs:
  deploy:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: actions/configure-pages@v4
      - uses: actions/upload-pages-artifact@v3
        with:
          path: '.'
      - uses: actions/deploy-pages@v4
