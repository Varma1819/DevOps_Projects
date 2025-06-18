# 🛠️ DevOps Projects Portfolio

Welcome to my DevOps project portfolio! This monorepo contains hands-on projects that demonstrate my practical knowledge in DevOps tools, automation, CI/CD pipelines, cloud infrastructure, and compliance auditing.

---

## 📁 Included Projects

# 🚀 CI/CD Pipeline for Static Website Deployment

This project demonstrates how to set up a CI/CD pipeline using **GitHub Actions** to automatically deploy a static website to **GitHub Pages**.

## 🔧 Key Features

- Automated deployment triggered on push to `main` branch  
- Uses GitHub Actions for checkout, artifact handling, and deployment  
- Zero manual deployment steps – fully automated

## 🛠️ Technologies Used

- **GitHub Actions** – Workflow automation  
- **GitHub Pages** – Static site hosting  
- **YAML** – CI/CD pipeline configuration

## ⚙️ Workflow Summary

- Checkout the code
- Setup GitHub Pages environment
- Upload static files as an artifact
- Deploy to GitHub Pages automatically


---

# 🛡️ ShellSentinel: GitHub Access Audit & Compliance Automation

This project demonstrates how to automate GitHub collaborator audits and enforce access compliance using **Shell Scripting** on an **Ubuntu EC2 instance** as part of the *DevOps Learning Path by Abhishek Veeramalla*.

## 🔍 Key Features

- Audits GitHub repo collaborators and compares with a secure whitelist  
- Detects unauthorized users and logs detailed reports  
- Sends manual email alerts via Postfix & Gmail SMTP  
- Scheduled daily execution using Cron on Ubuntu server

## 🛠️ Technologies Used

- **Bash Shell Scripting** – Core logic and automation  
- **GitHub API** – Accessing collaborator and permission data  
- **Postfix + Gmail SMTP** – Email notifications  
- **Cron** – Task scheduling  
- **Ubuntu (EC2)** – Execution environment

## ⚙️ Workflow Summary

- Fetch current collaborators using GitHub API  
- Compare against a predefined whitelist  
- Log mismatches or unauthorized access  
- Send alerts via configured mail system  
- Run the script automatically every day via Cron

---

## 🙋‍♂️ Author

**Mantena Jaya Rakesh Varma**  
👨‍💻 DevOps & Cloud Engineer  
🔗 [GitHub Profile](https://github.com/Varma1819)

---

## 📌 Future Plans

- Dockerize the audit tool for container-based deployment  
- Add Kubernetes project (cluster setup + monitoring)  
- Implement centralized logging with ELK or Loki stack

---

> ⭐ If you find these projects helpful or interesting, feel free to star the repo or connect!

