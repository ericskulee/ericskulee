- **VulnOps Pipeline (Scan → Prioritize → SLA → Report)**  
  https://github.com/ericskulee/vulnops-pipeline


# Eric S. Kulee
**Cybersecurity | Vulnerability Management • GRC • IAM**  
Open to: **Vulnerability Analyst • SOC Analyst (Jr) • GRC Analyst • IAM Analyst • IT Support**

## Featured project (proof of work)
### ✅ VulnOps Pipeline (Scan → Prioritize → SLA → Executive + Technical Reports)
![VulnOps Pipeline](https://github.com/ericskulee/vulnops-pipeline/actions/workflows/vulnops.yml/badge.svg)

- Turns vulnerability findings + asset context into **risk-ranked priorities**
- Assigns **SLA days + due dates**
- Generates **Executive Summary** + **Technical Remediation** reports
- Runs in **GitHub Actions** (CI) with downloadable artifacts

Repo: https://github.com/ericskulee/vulnops-pipeline

---

## Focus areas
- **Vulnerability Management:** prioritization, remediation tracking, SLA policy, reporting
- **GRC:** control mapping, evidence collection, policy/process documentation
- **IAM:** RBAC concepts, access reviews, least privilege, joiner/mover/leaver workflows

## Skills & tools (pick what matches your target jobs)
- Frameworks: NIST CSF / NIST 800-53 concepts, CIS Controls, ISO 27001 concepts
- Security ops: triage, alert investigation basics, documentation, incident support
- Data/automation: Python basics, CSV pipelines, reporting, GitHub Actions
- Platforms (if applicable): Splunk / Elastic / Microsoft Sentinel, Qualys / Nessus

## What I’m building next
- **GRC Evidence Pack** (audit-ready control → evidence repo)
- **IAM JML Lab** (joiner/mover/leaver + access review workflow)

## Contact
- LinkedIn: <https://www.linkedin.com/in/eric-kulee/>
- Email: <ericskulee@gmail.com>


## Run it locally (optional)
**Requirements:** Python 3.11+

```bash
python src/generate_reports.py \
  --findings sample_data/scans/scan_findings.csv \
  --assets sample_data/assets.csv \
  --outdir outputs \
  --reportdir reports
