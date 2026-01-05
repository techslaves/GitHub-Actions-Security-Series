# 🎥 GitHub Actions Security – Full Video Series

## **1: GitHub Actions Security – Threat Landscape & Basics**

### 📘 Content

- What GitHub Actions is (runner, workflow, job, step)
- CI/CD attack surface
- Common CI/CD attacks:
    - Credential leakage
    - Malicious PRs
    - Dependency confusion
    - Runner compromise
- Shared vs self-hosted runners
- Real-world CI/CD breach examples

### 🎬 Demo

- Simple insecure workflow example
- Show how secrets can leak via logs

## **2: GitHub Actions Authentication & Authorization Model**

### 📘 Content

- GitHub identities:
    - `GITHUB_TOKEN`
    - Personal Access Tokens (PATs)
    - GitHub App tokens
- Default permissions of `GITHUB_TOKEN`
- `permissions:` key in workflows
- - Repository, org, and environment-level permissions

### 🎬 Demo

- Compare default vs least-privilege token permissions
- Break a workflow by over-restricting permissions (learning moment)