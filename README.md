# Obinna Obika

### DevOps Engineer · Cloud Infrastructure · Platform Engineering · Site Reliability Engineering

I design and automate cloud platforms with a focus on **reliability, repeatability, security, observability, and developer experience**. My work centers on Infrastructure as Code, Kubernetes, CI/CD, GitOps, cloud operations, and the engineering practices required to operate platforms safely.

**Cloud:** Azure · AWS · GCP  
**Infrastructure:** Terraform · Kubernetes · Docker · Helm · Linux  
**Delivery:** GitHub Actions · Jenkins · Argo CD · GitOps  
**Automation:** Python · Bash  
**Observability:** Prometheus · Grafana · OpenTelemetry · CloudWatch  
**Engineering:** SRE · Platform Engineering · DevSecOps · IAM/RBAC · Networking · Disaster Recovery

> Build repeatable systems. Make changes observable and reversible. Automate operational toil. Design for failure before failure happens.

## Selected Engineering Work

### Cloud Platform Engineering
[`cloud-platform-engineering`](https://github.com/obinna-obika-devops/cloud-platform-engineering)

Production-style internal developer platform architecture using Terraform, Kubernetes/EKS, Helm, GitHub Actions and Argo CD. Includes workload isolation, policy controls, observability, SLOs, incident response and disaster-recovery practices.

### Infrastructure GitOps
[`infrastructure-gitops-engineering`](https://github.com/obinna-obika-devops/infrastructure-gitops-engineering)

Infrastructure change-management model built around Git as the source of truth, Terraform environment promotion, policy gates, continuous reconciliation, drift detection and rollback planning.

### Platform Engineering Portal
[`platform-engineering-portal`](https://github.com/obinna-obika-devops/platform-engineering-portal)

Self-service platform concepts implemented with Python/FastAPI, service catalogs, golden paths, policy-aware provisioning and GitOps/Terraform integration points.

### SRE & Reliability Engineering
[`sre-reliability-engineering-lab`](https://github.com/obinna-obika-devops/sre-reliability-engineering-lab)

Reliability engineering environment covering SLIs/SLOs, error budgets, Prometheus/Grafana observability, Kubernetes reliability controls, controlled failure injection, incident response and safe remediation automation.

### DevSecOps & Software Supply Chain
[`devsecops-supply-chain-security`](https://github.com/obinna-obika-devops/devsecops-supply-chain-security)

Defense-in-depth software delivery controls spanning source, dependencies, IaC, containers and Kubernetes, including SBOM/provenance, Cosign signing, policy-as-code and admission controls.

### Cloud FinOps
[`cloud-finops-cost-optimization`](https://github.com/obinna-obika-devops/cloud-finops-cost-optimization)

Cloud cost engineering patterns for allocation, budgets, forecasting, anomaly detection, rightsizing and policy automation using synthetic billing data and Terraform examples.

## Engineering Approach

```text
Developer Change
      │
      ▼
 Version Control
      │
      ▼
Test → Validate → Security Gates → Build
      │
      ├──────────────► Infrastructure as Code
      │
      ▼
    GitOps
      │
      ▼
 Kubernetes / Cloud Platform
      │
 ┌────┼─────────────┐
 ▼    ▼             ▼
SRE  Security   Observability
 │     │             │
 └─────┴──────┬──────┘
              ▼
      Automated Operations
```

My platform work follows a few consistent principles: infrastructure changes are versioned and validated; delivery paths are automated; access follows least privilege; workloads expose meaningful telemetry; reliability is measured through service objectives; and operational procedures are documented alongside the systems they support.

## Additional Work

[`multi-cloud-platform-engineering`](https://github.com/obinna-obika-devops/multi-cloud-platform-engineering) · [`cloud-automation-engineering`](https://github.com/obinna-obika-devops/cloud-automation-engineering) · [`cloud-networking-engineering`](https://github.com/obinna-obika-devops/cloud-networking-engineering) · [`cloud-zero-trust-security`](https://github.com/obinna-obika-devops/cloud-zero-trust-security) · [`cloud-migration-engineering`](https://github.com/obinna-obika-devops/cloud-migration-engineering) · [`kubernetes-platform-operator`](https://github.com/obinna-obika-devops/kubernetes-platform-operator)

## About These Repositories

The repositories contain reference implementations and engineering labs used to develop and demonstrate cloud, DevOps, platform and reliability engineering patterns. Where synthetic data or non-deployed infrastructure is used, the individual project documents that scope explicitly.

---

**Obinna Obika** · DevOps · Cloud · Platform Engineering · SRE
