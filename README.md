# Cloud VAPT Playground — Project & Source Code

One-stop repo to deploy a safe, isolated cloud Vulnerability Assessment & Penetration Testing playground on AWS (Free-tier friendly), including IaC (Terraform), vulnerable apps (Docker Compose), scanning automation, exploitation helpers, reporting templates, and cleanup scripts.

> Warning: Use this only on accounts, networks and targets you own or have explicit permission to test. Do NOT deploy on third-party accounts or production networks.

---

## What you get in this project

1. Project overview & architecture
2. Files included (Terraform, Docker Compose, scanning & recon scripts, report templates)
3. `terraform/` — Terraform config to provision a single EC2 instance + security group + optional S3 for reports
4. `docker/` — `docker-compose.yml` to run Juice Shop + DVWA + vulnerable API
5. `scripts/` — automation scripts: deploy, scan, gather, generate-report, cleanup
6. `reports/` — markdown report template & example
7. Step-by-step README for deployment and security hardening

---

See the repo files for full content and usage instructions.
