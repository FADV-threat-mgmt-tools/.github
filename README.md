# FADV Threat Management Tools

## Overview

Welcome to the **FADV Threat Management Tools** GitHub organization. This organization houses the tooling, automation, and shared workflows that support First Advantage's (FADV) threat management program. Our mission is to proactively identify, assess, and mitigate security threats across FADV's technology landscape, protecting customer data, business operations, and organizational assets.

---

## What Is Threat Management?

Threat management is the continuous, structured practice of discovering, analyzing, prioritizing, and responding to cybersecurity threats before they can cause harm. It encompasses the full threat lifecycle:

| Phase | Description |
|---|---|
| **Identify** | Discover assets, exposures, and potential attack vectors across the environment. |
| **Assess** | Evaluate the likelihood and impact of each threat using risk-based scoring (e.g., CVSS, EPSS). |
| **Prioritize** | Rank findings so that the highest-risk items receive immediate attention. |
| **Remediate** | Apply patches, configuration changes, or compensating controls to eliminate or reduce risk. |
| **Verify** | Confirm that remediations are effective and that no regression has occurred. |
| **Report** | Communicate risk posture, trend data, and compliance status to stakeholders. |

Effective threat management blends people, process, and technology—combining automated scanning and detection with expert human analysis and a well-defined response workflow.

---

## What We Do

The FADV Threat Management Tools team designs and maintains the engineering infrastructure that powers our security program. Our key areas of focus include:

### 🔍 Vulnerability Management
- Automated scanning of applications, containers, cloud infrastructure, and endpoints.
- Integration of scanner outputs (e.g., Qualys) into a unified findings pipeline.
- Risk scoring, deduplication, and SLA tracking for discovered vulnerabilities.

### 🛡️ Threat Intelligence
- Ingestion and normalization of threat intelligence feeds (CVE/NVD, CISA KEV, ISAC advisories).
- Enrichment of findings with exploit availability, active-exploitation data, and asset criticality.
- Alerting on newly disclosed critical vulnerabilities that affect FADV's technology stack.

### ⚙️ Security Automation & Tooling
- Reusable GitHub Actions workflows for SAST, SCA, container scanning, and secrets detection.
- Automated ticket creation and routing to owning teams in Jira/ServiceNow.
- Dashboards and metrics pipelines that surface real-time risk posture to leadership.

### 📋 Policy & Compliance Enablement
- Enforcement of secure-coding gates in CI/CD pipelines.
- Tracking of remediation SLAs in alignment with FADV security policy and regulatory requirements (PCI DSS, SOC 2, ISO 27001).
- Evidence collection and reporting to support audit activities.

### 🤝 Collaboration & Developer Enablement
- Providing engineering teams with self-service security tooling and clear remediation guidance.
- Running threat-modeling sessions for new and changing systems.
- Sharing threat intelligence and security advisories across development and operations teams.

---

## Repository Contents

This `.github` repository serves as the organizational home for:

- **Reusable GitHub Actions workflows** – shared CI/CD security scanning pipelines consumable by any repository in this organization.
- **Issue & PR templates** – standardized templates for vulnerability reports, security review requests, and feature proposals.
- **Organization-level community health files** – contributing guidelines, code of conduct, and security policy.

---

---

## Contact

For security issues, questions, or collaboration requests, please contact the FADV Threat Management Tools team through official internal channels or open an issue in the appropriate repository.
