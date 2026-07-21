# GitHub Actions Multi-Environment Deployment

A CI/CD project demonstrating secure multi-environment deployments using **GitHub Actions**, **GitHub Environments**, and **Azure Virtual Machines**.

## Features

- Automatic deployment to **Staging**
- Manual approval before **Production**
- Environment-specific GitHub Secrets
- SSH-based deployment to Azure VMs
- Deployment verification after each release

## Tech Stack

- GitHub Actions
- GitHub Environments & Secrets
- Azure Virtual Machines (Ubuntu)
- Nginx
- SSH

## Deployment Flow

```text
Code Push
    │
    ▼
GitHub Actions
    │
    ▼
Deploy to Staging
    │
    ▼
Manual Approval
    │
    ▼
Deploy to Production
```

## Repository Structure

```text
.
├── app/
│   └── index.html
├── .github/
│   └── workflows/
│       └── deploy.yml
└── README.md
```

## Skills Demonstrated

- CI/CD Pipeline Design
- Multi-Environment Deployments
- Secure Secret Management
- GitHub Environment Protection Rules
- Azure VM Deployment
- SSH Automation

---

