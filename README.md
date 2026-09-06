# Obinna Obika — Cloud & Infrastructure Engineer

<p align="center">
  <strong>Cloud & Infrastructure Engineering · DevOps · SRE · Platform Engineering · DevSecOps</strong>
</p>

<p align="center">
  Designing reliable, secure, automated infrastructure and the platforms that help engineering teams ship with confidence.
</p>

<p align="center">
  <a href="https://github.com/obinna-obika-devops"><img src="https://img.shields.io/badge/GitHub-Profile-181717?logo=github" alt="GitHub"></a>
  <a href="https://github.com/obinna-obika-devops?tab=repositories"><img src="https://img.shields.io/badge/Projects-Portfolio-2ea44f" alt="Projects"></a>
  <a href="https://github.com/obinna-obika-devops/bilolo"><img src="https://img.shields.io/badge/Portfolio-Bilolo-0969da" alt="Portfolio"></a>
</p>

## About

I build cloud and infrastructure engineering solutions around **automation, reliability, security, scalability, and operational excellence**.

My portfolio focuses on the full engineering lifecycle:

- ☁️ **Cloud:** AWS, Azure, cloud architecture, networking, IAM
- ⚙️ **Infrastructure as Code:** Terraform, reusable modules, environment management
- 🚀 **DevOps:** CI/CD, GitOps, deployment automation, release workflows
- ☸️ **Kubernetes:** platform engineering, workloads, RBAC, policies, reliability
- 🛠️ **SRE:** SLOs, SLIs, error budgets, observability, incident response, DR
- 🔐 **DevSecOps:** supply-chain security, SBOMs, image security, policy-as-code
- 💰 **FinOps:** cost governance, allocation, forecasting, anomaly detection, rightsizing
- 🌐 **Networking:** VPC architecture, segmentation, connectivity, DNS, security controls
- 🤖 **Automation:** Python tooling, event-driven remediation, infrastructure operations

> **Engineering principle:** automate repeatable work, make failure observable, reduce blast radius, and design systems that are easier to operate.

## Featured Engineering Work

### 🏗️ Cloud & Platform Engineering

| Project | Focus |
|---|---|
| [cloud-platform-engineering](https://github.com/obinna-obika-devops/cloud-platform-engineering) | AWS, Kubernetes, Terraform, GitOps, self-service platform engineering |
| [platform-engineering-portal](https://github.com/obinna-obika-devops/platform-engineering-portal) | Developer portal, service catalog, golden paths, self-service workflows |
| [kubernetes-platform-operator](https://github.com/obinna-obika-devops/kubernetes-platform-operator) | Kubernetes operator patterns, reconciliation, CRDs, remediation |

### 🛡️ Reliability & Security

| Project | Focus |
|---|---|
| [sre-reliability-engineering-lab](https://github.com/obinna-obika-devops/sre-reliability-engineering-lab) | SLOs, observability, incident response, chaos engineering, DR |
| [devsecops-supply-chain-security](https://github.com/obinna-obika-devops/devsecops-supply-chain-security) | SBOM, signing, provenance, vulnerability management, admission controls |
| [cloud-zero-trust-security](https://github.com/obinna-obika-devops/cloud-zero-trust-security) | IAM, Zero Trust, Kubernetes security, network segmentation, policy-as-code |

### ☁️ Infrastructure, Networking & Cloud Operations

| Project | Focus |
|---|---|
| [cloud-networking-engineering](https://github.com/obinna-obika-devops/cloud-networking-engineering) | VPC architecture, Terraform networking, segmentation, connectivity |
| [infrastructure-gitops-engineering](https://github.com/obinna-obika-devops/infrastructure-gitops-engineering) | Infrastructure GitOps, drift detection, promotion, policy gates |
| [cloud-automation-engineering](https://github.com/obinna-obika-devops/cloud-automation-engineering) | Event-driven automation, Python tooling, remediation, AWS operations |
| [cloud-finops-cost-optimization](https://github.com/obinna-obika-devops/cloud-finops-cost-optimization) | Cost governance, forecasting, anomaly detection, rightsizing |
| [cloud-migration-engineering](https://github.com/obinna-obika-devops/cloud-migration-engineering) | Discovery, dependency mapping, 6R assessment, migration planning |
| [multi-cloud-platform-engineering](https://github.com/obinna-obika-devops/multi-cloud-platform-engineering) | AWS/Azure abstractions, platform architecture, cloud tradeoffs |

### 🧩 Portfolio Foundation

[bilolo](https://github.com/obinna-obika-devops/bilolo) brings the broader engineering themes together into a coherent cloud and infrastructure portfolio.

## Engineering Stack

**Cloud**  
AWS · Azure

**Infrastructure**  
Terraform · Kubernetes · Helm · Docker · Linux

**DevOps & GitOps**  
GitHub Actions · Argo CD · GitOps · CI/CD

**Programming & Automation**  
Python · Bash · YAML

**Observability & SRE**  
Prometheus · Grafana · OpenTelemetry · SLOs · Error Budgets · Incident Response

**Security**  
Trivy · Gitleaks · Checkov · Kyverno · OPA/Rego · Cosign · SBOM · Zero Trust

**Operations**  
Networking · IAM · Disaster Recovery · Chaos Engineering · FinOps · Cloud Automation

## How I Approach Infrastructure

```text
                    ┌──────────────────────┐
                    │      Developers      │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │   Developer Platform │
                    │  Golden Paths / APIs │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │       GitHub         │
                    │   Source / GitOps    │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │       CI/CD          │
                    │ Test / Build / Scan  │
                    └──────────┬───────────┘
                               │
                    ┌──────────▼───────────┐
                    │      Terraform       │
                    │ Infrastructure as    │
                    │        Code          │
                    └──────────┬───────────┘
                               │
                 ┌─────────────┴─────────────┐
                 ▼                           ▼
          ┌─────────────┐             ┌─────────────┐
          │     AWS     │             │    Azure    │
          └──────┬──────┘             └──────┬──────┘
                 │                           │
                 └─────────────┬─────────────┘
                               ▼
                    ┌──────────────────────┐
                    │     Kubernetes       │
                    │   Platform / Apps    │
                    └──────────┬───────────┘
                               │
             ┌─────────────────┼─────────────────┐
             ▼                 ▼                 ▼
       ┌───────────┐     ┌───────────┐     ┌───────────┐
       │Observability│   │ Security  │     │  FinOps   │
       │ SRE / SLOs │   │  Policies  │     │ Efficiency │
       └─────┬─────┘     └─────┬─────┘     └─────┬─────┘
             └─────────────────┼─────────────────┘
                               ▼
                    ┌──────────────────────┐
                    │ Automation &         │
                    │ Automated Remediation│
                    └──────────────────────┘
```

## What You'll Find in My Repositories

- Infrastructure-as-code and reusable Terraform patterns
- Kubernetes platform and workload patterns
- CI/CD and GitOps workflows
- Security and supply-chain controls
- SRE practices and operational runbooks
- Network and cloud architecture references
- FinOps and cloud efficiency automation
- Migration planning and readiness tooling
- Tests, validation, policy gates, and documentation
- Architecture decisions and engineering tradeoffs

These repositories are **portfolio/reference implementations** designed to demonstrate engineering practices and architecture. They do not represent claims of production deployment or customer environments unless explicitly stated in a repository.

## Engineering Mindset

```text
Reliability       → Design for failure
Automation        → Eliminate repetitive toil
Security          → Reduce blast radius
Observability     → Know what the system is doing
Infrastructure    → Treat it as code
Delivery          → Make changes repeatable and reversible
Operations        → Document, measure, improve
Cost              → Engineer for efficiency
```

## Currently Building Toward

- More advanced internal developer platform capabilities
- Deeper Kubernetes automation and operator patterns
- Multi-cloud infrastructure abstractions
- Production-oriented SRE and reliability practices
- Secure software supply-chain automation
- Cloud networking and infrastructure operations
- Automated cloud governance and remediation

## Connect

- **GitHub:** [@obinna-obika-devops](https://github.com/obinna-obika-devops)
- **Portfolio:** [bilolo](https://github.com/obinna-obika-devops/bilolo)

---

<p align="center">
  <strong>Cloud Infrastructure · DevOps · SRE · Platform Engineering · DevSecOps</strong>
</p>
