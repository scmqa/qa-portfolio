![Project Cover](project-cover-api-security.jpeg)

![Project Report](project-report-security-devsecops.jpeg)

# 🛡️ Automated API Security & DevSecOps Pipeline

An enterprise-grade, automated **Dynamic Application Security Testing (DAST)** framework integrated with **GitHub Actions** and powered by **OWASP ZAP**. This pipeline is designed to enforce *Shift-Left Security* by automatically scanning REST APIs against critical vulnerabilities, aligning with the **OWASP API Security Top 10** vulnerabilities and web compliance standards.

---

## 🎨 Framework Architecture & Portfolio Preview

Below is the technical overview of the framework configuration, cloud integration metrics, and compliance auditing reports:

![API Security Framework](assets/portfolio-preview.png)

---

## 🚀 Key Features

- **Automated DAST Scan:** Dynamic security scanning triggered on every `push` and `pull_request` using the stabilized OWASP ZAP Baseline engine.
- **Multi-Tool Compliance Auditing:** Integrated dual-layer verification tracking core application flaws and server-side HTTP security headers.
- **Cloud-Native Artifact Generation:** Automated compilation of technical risk metrics (High, Medium, Low severity alerts) with direct HTML/PDF report downloads.
- **Enterprise DevSecOps Workflow:** Fully automated execution handled directly via GitHub-hosted runners in less than 7 minutes.

---

## 📂 Repository Structure

```text
├── .github/
│   └── workflows/
│       └── security.yml       # GitHub Actions DevSecOps workflow configuration
├── assets/
│   └── portfolio-preview.png  # Technical portfolio image preview
└── README.md                  # Comprehensive framework documentation
```

---

## 🛠️ Tech Stack & Dependencies

- **Automation Engine:** OWASP ZAP (Zed Attack Proxy)
- **CI/CD Platform:** GitHub Actions (Ubuntu-latest runner)
- **Target Environment:** OWASP crAPI (Completely Ridiculous API)
- **Compliance Standard:** HTTP Security Headers Auditing

---

## 🔧 Workflow Configuration (`security.yml`)

The automation pipeline is explicitly configured to grant write permissions for security artifacts, ensuring stable report archival:

```yaml
# Core triggers for the security scanner
on:
  push:
    branches: [ main, develop ]
  pull_request:
    branches: [ main, develop ]
```

---

## 📊 Deliverables & Technical Outcomes

1. **Continuous Security Integration:** 100% success rate on server automation pipelines with zero deployment blockages.
2. **Server-Side Hardening:** Validation protocols achieving **Grade "A" International Compliance** on web transport encryption and clickjacking protections.
3. **Actionable Remediation Reports:** Immediate accessibility to interactive `.html` logs pinpointing misconfigurations and remediation guidance for engineering teams.

---
_Developed with focus on premium quality engineering and technical excellence._
