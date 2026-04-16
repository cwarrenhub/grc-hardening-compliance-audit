# 🔐 GRC Hardening Compliance Audit (CIS Aligned)

## 📌 Overview

This project demonstrates a full-cycle Governance, Risk, and Compliance (GRC) assessment across Windows and Linux environments, aligned with CIS Benchmarks.

The engagement simulates a real-world security audit by identifying control gaps, mapping risks, and implementing remediation strategies to improve system security posture.

---

## 🎯 Objectives

* Assess system configurations against CIS hardening standards
* Identify control failures and security gaps
* Map findings to a structured risk register
* Execute remediation and validate control effectiveness
* Produce audit-ready documentation and evidence

---

## 🧱 Scope

* Windows 11 security configuration (CIS-aligned)
* Kali Linux hardening validation
* Firewall configuration:

  * Microsoft Defender Firewall
  * UFW (Linux)
* SSH access control enforcement

---

## 🔍 Key Findings

* ❌ Weak password policy (minimum length = 0)
* ❌ Firewall configuration not validated across profiles
* ❌ SSH root login improperly configured
* ⚠️ Directory listing exposure risk (web control review)

---

## 🛠️ Remediation Actions

* ✅ Enforced minimum password length and policy controls
* ✅ Verified firewall activation across Domain, Private, and Public profiles
* ✅ Disabled SSH root login (PermitRootLogin no)
* ✅ Enabled and validated UFW firewall in Linux
* ✅ Conducted evidence sanitization for secure documentation

---

## 📈 Outcome (Business Impact)

* 🔺 Improved control effectiveness from ~50% → 90%+
* 🔻 Reduced critical and high-risk exposure
* 🔐 Strengthened system hardening aligned with CIS standards
* 📊 Demonstrated audit-ready GRC workflow and documentation

---

## 📊 Risk & Compliance Artifacts
---

## 📂 Project Files

* 📊 [Download Compliance Workbook](./GRC_Hardening_Compliance_Audit.xlsx)
* 📄 [Benchmark Selection & Applicability Statement](./Benchmark_Selection_Applicability_Statement.pdf)

> These documents contain full control validation, risk scoring, remediation tracking, and supporting audit evidence.

* Compliance Assessment Workbook

  * Control validation (Pass/Fail)
  * Evidence tracking (EV-### format)

* Risk Register

  * Likelihood × Impact scoring
  * Risk prioritization

* Remediation Plan

  * Ownership assignment
  * Target tracking

* Dashboard

  * KPI metrics (pass rate, risk distribution, remediation status)

---

## 📎 Supporting Documentation

* Benchmark Selection & Applicability Statement
* Evidence Appendix (embedded in Excel workbook)

---

## 🧠 Skills Demonstrated

* GRC Risk Assessment
* CIS Benchmark Mapping
* Control Testing & Validation
* Windows & Linux Hardening
* Audit Documentation & Evidence Handling

---

## 🧑‍💻 Author

Cortney Warren
