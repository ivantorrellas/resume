---
layout: default
title: Ivan Torrellas · DevSecOps Platform Engineering Lead
---

# Ivan Torrellas
**DevSecOps Platform Engineering Lead · Builder who grows engineering teams**  
Dubai, UAE · Open to relocation  
[LinkedIn](https://www.linkedin.com/in/ivantorrellas) · [GitHub](https://github.com/ivantorrellas) · [X](https://x.com/IvanTorrellas) · [Credly](https://www.credly.com/users/ivantorrellas/badges)

### Summary
Engineer and tech lead with 20+ years in software and infrastructure, including 13 years running my own IT consultancy. At Emirates Group I designed the reusable EKS Terraform modules behind 110+ EKS clusters and the GitLab Runners platform that now runs 800K+ CI/CD jobs a month. I cut its compute cost ~65% and migrated it from AWS Bahrain to Ireland in 30 minutes when regional conflict hit. Today I'm Tech Lead for Managed Kubernetes Governance. Alongside the engineering, I grow the teams around me: at Globant I helped grow the Cloud team from 5 to 50+ engineers in one year, and at Emirates I've interviewed and onboarded 25+ Senior DevOps engineers. AWS Certified Solutions Architect – Professional.

### Community, Hiring & Mentoring
- **Globant, Colombia (self-initiated):** helped grow the Cloud team from 5 to 50+ engineers in one year through tech talks and recruiting events in Bogotá and Medellín (70+ attendees), interviews, and new-hire training.
- **Emirates Group:** interviewed and onboarded 25+ Senior DevOps engineers; mentor 3 colleagues on technical growth and promotion readiness.
- **Founder (2003–2016):** built and led small technical teams for clients in banking, hospitality, and retail.

### Experience

**Emirates Group IT — Apr 2021–Present & Jan 2019–Sep 2020**  
**Senior Technical DevOps Engineer · Tech Lead, Managed Kubernetes Governance**  
- Designed the reusable EKS Terraform modules behind 110+ EKS clusters, provided by my team as the standard across IT. Invited by AWS to present them; declined in line with company policy.
- Chose to run GitLab Runners on EKS and designed the architecture on a private cluster inside the company network. The platform runs 800K+ CI/CD jobs a month, autoscaling from near zero to 19K+ concurrent pods with Karpenter and custom pre-warming controllers, at ~98% job success.
- Cut CI/CD runner compute cost ~65% through Karpenter autoscaling, right-sizing, and a Reserved/Spot purchasing strategy.
- Designed a node pre-warming system: two Helm-deployed controllers working with Karpenter (one clears startup taints, one scales up and marks warmed capacity on a weekday schedule), so CI jobs start on ready nodes instead of waiting for cold EC2 boots. Least-privilege RBAC; Linux and Windows node pools.
- Built the reusable Terraform module teams use to self-serve GitLab Runners on EKS: runner registration, IRSA, Vault-managed pull secrets, and a declarative API that generates the runner config.
- Migrated the CI/CD runner platform from AWS Bahrain to Ireland in 30 minutes when regional conflict hit, keeping delivery running for engineering teams.
- Led the reusable IaC components (Terraform, Helm, HashiCorp Vault, AWS integration) for the Bitbucket → GitLab move.
- Built a Terraform blue/green module that shifts Route 53 traffic with feature flags, used for my team's releases.
- 2019–2020: designed and built Jenkins as a Service as code. Any department could get its own Jenkins instance through a pull request and a YAML declaration, as part of the centralized enterprise CI/CD platform (pipelines-as-code, immutable Docker builds, Blue/Green).
- Shaped the team: interviewed and onboarded 25+ Senior DevOps engineers; mentor 3 colleagues on technical growth and promotion readiness.

**Independent DevOps Contractor — FinTech clients (confidential) — Sep 2020–Apr 2021**  
- Kubernetes (GKE) platforms as code with Terraform, Helm, Helmfile, and Ansible; GitLab deployed in Kubernetes with GitLab CI/CD pipelines-as-code.
- Highly available PostgreSQL in Kubernetes with automatic failover; rootless image builds with Kaniko.
- Serverless AWS environments and secure partner networking as code (Terraform, Bash).

**Globant, Colombia · Jun 2016 - Dec 2018**
**DevOps Engineer SSR → SSR Advanced (Jun 2017) → Senior DevOps Engineer & Tech Lead (Apr 2018)**  
- Promoted twice in under two years.
- Led AWS/GCP delivery for agile client teams; CI/CD, IaC, and DevOps practice adoption.
- Grew the Cloud team from 5 to 50+ engineers in one year. On my own initiative, I ran tech talks and recruiting events in Bogotá and Medellín (one drew 70+ attendees), sat in interviews, and led a group of teammates who trained every new hire.

**Founder & Principal Consultant · SOTEX C.A. (2033-2005), TIT C.A. (2006-2016)**
- Ran my own IT consultancy for 13 years: built and led small technical teams and owned network, virtualization, and cloud environments for clients in banking, hospitality, and retail. Client references available on request.

### Certifications
- AWS Certified Solutions Architect – Professional (Feb 2025, valid through Feb 2028) — [verify](https://cp.certmetrics.com/amazon/en/public/verify/credential/c742653a10504e15ba8f0a45293011d1)
- Certified GitLab Duo (AI) Associate (Feb 2026) — [Credly](https://www.credly.com/users/ivantorrellas/badges)

### Technical Expertise
**Kubernetes & Platform:** Amazon EKS · GKE · Karpenter · Helm / Helmfile · GitOps · HashiCorp Vault / RBAC · Observability  
**Cloud:** AWS (EKS, EC2, Lambda, RDS, VPC) · GCP (GKE, Compute Engine, Cloud SQL, BigQuery)  
**CI/CD & Automation:** GitLab CI/CD & Runners · Jenkins · Terraform · Ansible · Docker / OCI · Nexus · Blue/Green  
**Practices:** DevSecOps · IaC · Hybrid cloud · SRE partnership · Agile/Scrum

[Recommendations on LinkedIn](https://www.linkedin.com/in/ivantorrellas)
