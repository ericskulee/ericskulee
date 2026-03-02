# Eric S. Kulee
**Cybersecurity | Vulnerability Management • GRC • IAM**  
Open to: **Vulnerability Analyst • Cyber Risk Analyst • GRC Analyst • IAM Analyst • SOC Analyst (Jr)**

---

## Featured proof of work (start here)

### ✅ VulnOps Pipeline (Scan → Normalize → Prioritize → SLA → Executive + Technical Reports)
![VulnOps Pipeline](https://github.com/ericskulee/vulnops-pipeline/actions/workflows/vulnops.yml/badge.svg)

- Turns vulnerability findings + asset context into **risk-ranked priorities**
- Assigns **SLA days + due dates**
- Generates **Executive Summary** + **Technical Remediation** reports
- Runs in **GitHub Actions** (CI) with downloadable artifacts

Repo: https://github.com/ericskulee/vulnops-pipeline

---

### ✅ Vulnerability Management Labs (Evidence Packs)
Hands-on labs with evidence (reports + screenshots + summaries) organized for recruiter review.

Evidence hub: https://github.com/ericskulee/cybersecurity-vulnerability-management  
Labs Index: https://github.com/ericskulee/cybersecurity-vulnerability-management/tree/main/labs

**Nessus Lab — Credentialed Scan (Ubuntu “TargetJuice”)**
- Lab page: https://github.com/ericskulee/cybersecurity-vulnerability-management/tree/main/labs/nessus/ubuntu-targetjuice-credentialed-2026-01-25
- Report (PDF): https://github.com/ericskulee/cybersecurity-vulnerability-management/blob/main/labs/nessus/ubuntu-targetjuice-credentialed-2026-01-25/reports/nessus-ubuntu-targetjuice-credentialed-scan_qizp96.pdf

**Entra ID IAM Lab — Least Privilege for Vulnerability Management**
- Lab page: https://github.com/ericskulee/cybersecurity-vulnerability-management/tree/main/labs/iam/entra-least-privilege-vm-2026-03-01

---

## Focus areas
- **Vulnerability Management:** scanning, prioritization, remediation tracking, SLA policy, reporting, validation
- **GRC:** control mapping, evidence collection, policy/process documentation
- **IAM:** RBAC concepts, access reviews, least privilege, joiner/mover/leaver workflows

## Skills & tools
- Frameworks: NIST CSF / NIST 800-53 (concepts), CIS Controls, ISO 27001 (concepts)
- VM tools: **Nessus**, Qualys (familiar; building lab next), remediation validation workflows
- Security ops: triage, alert investigation basics, documentation, incident support
- Data/automation: Python (basics), CSV pipelines, reporting, GitHub Actions
- SIEM (if used): Splunk / Elastic / Microsoft Sentinel

## What I’m building next
- **Qualys-style VM lab** (metrics + remediation aging + validation rescan)
- **GRC Evidence Pack** (audit-ready control → evidence repo)
- **Additional VM evidence packs** (repeatable lab structure + cleaner reporting)

## Contact
- LinkedIn: https://www.linkedin.com/in/eric-kulee/
- Email: ericskulee@gmail.com

## Run VulnOps locally (optional)
**Requirements:** Python 3.11+

```bash
python src/generate_reports.py \
  --findings sample_data/scans/scan_findings.csv \
  --assets sample_data/assets.csv \
  --outdir outputs \
  --reportdir reports
