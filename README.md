# Cross-Border Cybersecurity Governance and ISO/IEC 27001 Compliance Architectures (China vs. Australia)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Institution: UQ EECS](https://img.shields.io/badge/Institution-The_University_of_Queensland-purple.svg)](https://eecs.uq.edu.au/)
[![Program: Master of Cyber Security](https://img.shields.io/badge/Degree-Master_of_Cyber_Security-blue.svg)]()

This repository contains the primary empirical datasets, quantitative coding matrices, qualitative thematic evidence ledgers, and audit logs supporting the Master of Cyber Security Capstone Dissertation at **The University of Queensland (School of EECS)**:

> **Thesis Title:** *Scope Ring-Fencing and Corporate Cybersecurity Maturity: An Empirical Examination of ISO/IEC 27001 Compliance Architectures Across China and Australia*  
> **Author:** Jiaan Wang  
> **Course Code:** CYBR7902  
> **Academic Cut-off Date:** October 2026  

---

## 📁 Repository Structure & Dataset Architecture

The primary empirical workbook (`ISO27001_50_companies_full_audit_2026-09-15.xlsx`) comprises **11 interconnected sub-sheets** detailing the lifecycle of the 50-cohort empirical audit (25 mainland China / HK-China and 25 Australia):

| Sub-sheet Name | Dimensions | Description / Purpose | Thesis Placement |
| :--- | :--- | :--- | :--- |
| **`Final Audited Dataset`** | 50 × 10 | Primary baseline directory (Identifiers, Country, Sector, ISO Status, Registrar CB, Scope Summary, Boundary Type, Validity). | Reproduced in **Thesis Appendix Table A.1** |
| **`Audit Matrix`** | 50 × 22 | Comprehensive 22-column working audit log, including granular registrar accreditations and internal verification notes. | Archived (Online Repository) |
| **`Coding Matrix`** | 50 × 14 | Machine-readable discrete numerical coding matrix (`0, 1, 2, 4, 9`) for statistical replication (Fisher's exact test). | Archived (Online Repository) |
| **`Evidence Ledger`** | 58 × 9 | 58 traceable evidentiary records with direct regulatory and corporate disclosure URLs. | Archived (Online Repository) |
| **`RQ2 Evidence Matrix`** | 12 × 11 | Structured qualitative thematic corpus extracts (CMI, Kingdee, Hikvision, Alibaba Cloud, Telstra, Macquarie, etc.). | Archived (Online Repository) |
| **`RQ2 Synthesis`** | 9 × 4 | Thematic proposition validation assessing signaling theory versus geopolitical ring-fencing. | Chapter 5 / Online Repository |
| **`RQ1 Statistics`** | 26 × 4 | Tabulated frequency distributions, contingency panels, and Fisher's exact test calculations ($p=0.6169$). | Chapter 5 (Tables 5.1–5.4) |
| **`Change Log`** | 31 × 5 | Complete audit trail documenting 31 baseline scope and entity alignment corrections (e.g., Optus, NEXTDC). | Archived (Online Repository) |
| **`Audit Summary`** | 19 × 4 | Methodological summary of strict evidence thresholds and classification counts. | Chapter 4 & 5 |
| **`README - Audit Rules`** | 12 × 2 | Operational coding definitions for Evidence Tiers (A–D) and Scope Evidence Levels (0–2). | Chapter 4 Methodology |
| **`README`** | 12 × 1 | Original metadata and reconstruction protocol notes. | Archived (Online Repository) |

---

## 🔍 Evidence Hierarchy & Coding Protocol

To mitigate "Visibility Bias" and eliminate unverified corporate marketing claims, all 50 cohorts were classified using strict evidentiary safeguards:

* **Tier A (Highest Evidentiary Weight):** Verified certificate entries directly obtained from accredited national/international registrar directories (e.g., CNCA, JAS-ANZ, BSI, SGS, Intertek SAI Global).
* **Tier B (First-Party Verifiable Disclosure):** Formal corporate disclosures, ESG annual reports, or Trust Center whitepapers containing specific certificate IDs, accredited CB identifiers, and demarcated scope statements.
* **Tier C (Generic Commercial Claim):** Marketing assertions or product badges lacking formal scope boundaries or accreditation credentials.
* **Tier D (Unverifiable / Missing Public Record):** Absence of publicly accessible qualifying certificate records (coded as *Indeterminate/Missing*, strictly separated from negative certification).

---

## 📊 Replication Protocol

The quantitative boundary comparisons and contingency testing reported in the dissertation can be replicated directly using `Coding Matrix`:
* **Population Eligibility:** Scope Analysis Population (`Scope Analysis Population = 1`, $N = 22$).
* **Contingency Dimensions:** Broad Scope (Codes 4–5) vs. Bounded Scope (Codes 1–3) across Australia ($n=11$) and China ($n=9$).
* **Statistical Independence Test:** Two-sided Fisher's exact test yielding $\text{Odds Ratio} = 0.4444, p = 0.6169$.

---

## ⚖️ Citation & License

This repository and dataset are distributed under the **MIT License**. You are free to use, modify, and distribute the materials for academic and research purposes, provided that the original attribution is maintained.

If referencing this dataset in academic research, please cite as follows:

```bibtex
@mastersthesis{wang2026scope,
  author       = {Jiaan Wang},
  title        = {Scope Ring-Fencing and Corporate Cybersecurity Maturity: An Empirical Examination of ISO/IEC 27001 Compliance Architectures Across China and Australia},
  school       = {School of Electrical Engineering and Computer Science, The University of Queensland},
  year         = {2026},
  month        = {October},
  type         = {Master of Cyber Security Capstone Dissertation},
  note         = {Replication dataset available at: [https://github.com/](https://github.com/)[Your-Username]/iso27001-cross-border-audit}
}
