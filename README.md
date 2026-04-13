<p align="center">
  <img src="https://img.shields.io/badge/Open%20to%20Work-DevOps%20%7C%20SRE%20%7C%20Cloud%20Engineer-brightgreen?style=for-the-badge&logo=checkmarx&logoColor=white" />
</p>

> **Available for new opportunities** — DevOps / SRE / Cloud Engineer roles
> Pan India (Remote · On-site · Hybrid) · Notice period: 15 days · [hmandloi346@gmail.com](mailto:hmandloi346@gmail.com)

---

<h1 align="center">Hi, I'm Himanshu Mandloi</h1>
<h3 align="center">DevOps Engineer · AWS EKS · Terraform · ArgoCD · Prometheus</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=himanshumandloi307&label=Profile%20Views&color=blueviolet&style=flat-square" />
  <img src="https://img.shields.io/badge/AWS-Cloud%20Practitioner-FF9900?style=flat-square&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS%20SAA-In%20Progress-FF9900?style=flat-square&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/Location-Pan%20India-blueviolet?style=flat-square&logo=googlemaps&logoColor=white" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?lines=DevOps+Engineer+%7C+Sole+Owner+%40+Zevo360;AWS+EKS+%7C+Terraform+%7C+ArgoCD;GitOps+%7C+Prometheus+%7C+Grafana;40%25+Faster+Deployments+%7C+99%25+Uptime;Open+to+Pan+India+%7C+Remote+%7C+Hybrid&center=true&width=700&height=45&color=7F3ACE">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg" alt="contribution snake" />
</p>

---

## About Me

I'm a DevOps Engineer and the **sole DevOps owner** at Zevo360 Technologies — a parenting mobile app serving real users in production. I manage the entire infrastructure end-to-end: from Terraform provisioning and EKS cluster management to CI/CD pipelines, GitOps deployments, and observability.

- **Currently at:** Zevo360 Technologies Pvt. Ltd. — DevOps Engineer (sole owner)
- **Stack:** AWS EKS · Terraform · ArgoCD · Helm · Prometheus · Grafana · Jenkins · GitHub Actions · Docker
- **Certs:** AWS Cloud Practitioner ✓ · AWS Solutions Architect Associate (target Q2 2026)
- **Open to:** Pan India — Remote · On-site · Hybrid · Any location

---

## Impact at Zevo360

> Running production infrastructure solo for a live parenting app — end-to-end ownership across 15+ microservices.

| Metric | Before | After | Result |
|--------|--------|-------|--------|
| Deployment time | Baseline | Optimized pipelines | **40% faster** |
| System uptime | Variable | EKS + ALB + monitoring | **99%+ maintained** |
| Mean time to recovery (MTTR) | Slow manual triage | Prometheus alerts + runbooks | **50% reduction** |
| Microservices on EKS | — | ArgoCD GitOps | **15+ managed** |

---

## Featured Project — zero-to-eks

> **Production-grade AWS EKS cluster — zero to running, fully automated**

```
GitHub Actions (CI/CD)
        │
        ▼
  ┌─────────────────────────────────────────────┐
  │                  AWS Cloud                  │
  │                                             │
  │  ┌──────────────────────────────────────┐   │
  │  │           VPC (Terraform)            │   │
  │  │                                      │   │
  │  │   Public Subnet    Private Subnet    │   │
  │  │   ┌──────────┐    ┌──────────────┐  │   │
  │  │   │   ALB    │    │  EKS Cluster │  │   │
  │  │   └────┬─────┘    │              │  │   │
  │  │        │          │  ┌─────────┐ │  │   │
  │  │        └─────────►│  │  Pods   │ │  │   │
  │  │                   │  └────┬────┘ │  │   │
  │  │                   └───────┼──────┘  │   │
  │  └───────────────────────────┼─────────┘   │
  │                              │             │
  │   S3 (Terraform state)       │             │
  │   DynamoDB (state lock)      │             │
  └──────────────────────────────┼─────────────┘
                                 │
                    ┌────────────┼────────────┐
                    ▼            ▼            ▼
                 ArgoCD      Prometheus    Grafana
               (GitOps)    (Monitoring)  (Dashboards)
```

| What | How |
|------|-----|
| Infrastructure | Terraform modules — VPC + EKS (`terraform-aws-modules`, AWS provider `~> 5.0`) |
| State management | S3 remote backend + DynamoDB locking |
| GitOps | ArgoCD — app definitions live in Git, auto-synced to cluster |
| Monitoring | Prometheus + Grafana via `kube-prometheus-stack` Helm chart |
| CI/CD | GitHub Actions — lint → plan → apply on merge |
| Sample workload | Nginx app deployed via custom Helm chart |

👉 [github.com/HimanshuMandloi307/zero-to-eks](https://github.com/HimanshuMandloi307/zero-to-eks)

---

## What I Build & Operate

- End-to-end CI/CD pipelines — Jenkins + GitHub Actions, from commit to production
- AWS infrastructure as code — VPC, EKS, ECS, ECR, ALB, WAF, Route53, IAM via Terraform
- GitOps workflows — ArgoCD managing 15+ microservices on EKS
- Observability stacks — Prometheus + Grafana + CloudWatch dashboards and alerting
- Container orchestration — Kubernetes (EKS), Helm chart authoring and management
- Config management — Ansible playbooks for server provisioning

---

## Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,kubernetes,terraform,docker,ansible,jenkins,githubactions,helm,git,bash,linux,grafana,prometheus,mysql,mongodb&theme=dark" />
</p>

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=HimanshuMandloi307&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=HimanshuMandloi307&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=HimanshuMandloi307&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" width="36%" />
</p>

---

## GitHub Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=himanshumandloi307&theme=onedark&no-frame=true&row=1&column=6" />
</p>

---

## Connect

<p align="center">
  <a href="https://linkedin.com/in/himanshu-mandloi-046971175">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:hmandloi346@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/HimanshuMandloi307/zero-to-eks">
    <img src="https://img.shields.io/badge/zero--to--eks-Project-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

<p align="center">
  <b>Open to DevOps / SRE / Cloud Engineer roles — Pan India</b><br>
  <a href="mailto:hmandloi346@gmail.com">hmandloi346@gmail.com</a> · 15-day notice period · Indore (open to remote & relocation anywhere in India)
</p>
