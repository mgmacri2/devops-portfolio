# 4-Month DevOps Portfolio + Certification Plan

---

## Month 1 — Foundations + Project MVP

**Main Goals:**
- Pick cloud provider for core infra (**recommend AWS for widest reach**).
- Set up GitHub repo, GitHub Actions pipeline skeleton.
- Complete **AWS Certified Cloud Practitioner** (fast win, strong resume signal).

**Actions:**
- **AWS Cloud Practitioner study (CLF-C02)** — 5–7 hrs total over the month.
  - Use AWS Skill Builder free course or freeCodeCamp video (~4 hrs).
  - Practice exam once per week.
- **Project**:
  - Create GitHub repo with `/backend`, `/frontend`, `/device-emulator`, `/infra` folders.
  - Write Python/Go device emulator that sends pH, chlorine, temp via REST or MQTT.
  - Stand up a basic FastAPI or Go backend locally (no cloud yet).
  - Create initial GitHub Actions workflow to run tests on push.

**Deliverable:**
- Local demo with dummy data visible in backend logs.
- GitHub repo with working CI (build + test stage).
- AWS Cloud Practitioner booked for end of month.

**Time Allocation (per week):**
- 3–5 hrs cert study
- 5–8 hrs coding

---

## Month 2 — Infrastructure + CI/CD

**Main Goals:**
- Learn Terraform and deploy basic infra (DB + compute).
- Complete **Terraform Associate cert** (validates IaC skills).
- Deploy backend to AWS (can be Lambda or ECS/Fargate for free-tier control).

**Actions:**
- **HashiCorp Certified: Terraform Associate** study — 6–8 hrs total.
  - Free resources: HashiCorp Learn, ExamPro Terraform free course.
  - Build your project infra as part of learning.
- **Project**:
  - Write Terraform to deploy DB (Postgres on RDS free tier).
  - Deploy backend to AWS Lambda via Terraform.
  - Update CI/CD pipeline to build Docker image, push to ECR, deploy automatically.

**Deliverable:**
- Backend reachable over HTTPS (API Gateway + Lambda).
- DB stores device readings.
- CI/CD auto-deploy on push to main.

**Time Allocation:**
- 3–4 hrs cert study
- 6–10 hrs project work

---

## Month 3 — Kubernetes + Monitoring

**Main Goals:**
- Deploy processing or dashboard component to Kubernetes.
- Integrate monitoring (Prometheus + Grafana).
- Skip CKA for now — instead, show Kubernetes skill via project.

**Actions:**
- **Project**:
  - Set up minimal EKS cluster (or GKE for free-tier node).
  - Deploy backend or worker pods that process IoT messages.
  - Add monitoring stack (Prometheus in-cluster, Grafana dashboard).
  - Extend GitHub Actions pipeline with `kubectl` deploy step.
- **Docs**:
  - Architecture diagram showing IoT → Cloud ingestion → Processing → Dashboard.
  - README update with deployment steps.

**Deliverable:**
- Live Kubernetes workload connected to AWS backend.
- Grafana dashboard visible with live metrics from emulated devices.

**Time Allocation:**
- 8–12 hrs project work (no cert focus this month).

---

## Month 4 — Frontend, Security, & Polish

**Main Goals:**
- Finish React dashboard.
- Add GitHub security scanning + IaC scanning.
- Optional: **GitHub Actions certification** (quick win).

**Actions:**
- **Project**:
  - Build React dashboard (Chart.js) showing real-time pH/chlorine/temp from DB.
  - Host frontend on GitHub Pages or Netlify (free).
  - Add Dependabot, Trivy scans to CI pipeline.
- **Cert**:
  - GitHub Actions Certification (1–2 weeks study, mostly practical).
  - Leverage your own pipeline as study material.
- **Docs**:
  - Final README with features, tech stack, diagrams, how to run locally.
  - Short demo video (~2 min) for LinkedIn/GitHub profile.

**Deliverable:**
- Fully functional Smart Pool Maintenance App (live demo link).
- AWS Cloud Practitioner + Terraform Associate + GitHub Actions certs in resume.
- LinkedIn post with demo video + repo link.

---

## End of 4 Months — What You Have

**Live Project:**
- IoT emulation, ingestion pipeline, cloud backend, DB, Kubernetes processing, monitoring, frontend dashboard.
- Fully automated CI/CD with Terraform infra provisioning + security scans.

**Certs:**
- AWS Cloud Practitioner (broad cloud knowledge)
- Terraform Associate (IaC expertise)
- GitHub Actions (CI/CD specialization)

**Portfolio Materials:**
- Public GitHub repo
- Live demo
- Architecture diagram
- Demo video for LinkedIn
- Blog post or README case study
