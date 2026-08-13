# 🔍 Procure-to-Pay (P2P) / Vendor Onboarding / Continuous Control Monitoring (CCM) Audit

A data-driven internal audit case study evaluating Q2 procurement transactions using automated continuous control monitoring rules, benchmarked against COSO Internal Controls and ISO 31000 Enterprise Risk Management (ERM) frameworks.

---

## 📌 Audit Scope & Governance Frameworks
Conducted a 100% population audit across Q2 procurement transactions (20 records) using logical audit testing rules in Microsoft Excel (`IF`, `AND`, `COUNTIF`). Fieldwork was benchmarked against:
- **COSO Internal Control Framework:** Evaluated Delegation of Authority (DoA) thresholds, vendor onboarding status, and invoice verification controls.
- **ISO 31000 ERM Framework:** Assessed operational risk severity, fraud vulnerability, and single-source vendor concentration.

---

## 📊 Key Audit Findings & Metrics

Out of 20 audited orders, **50% passed clean**, while the remaining **50% exhibited control exceptions** across three key operational risks:

1. **Unapproved Vendor Disbursements (20.00% Failure Rate / 4 Exceptions)**
   - *COSO Alignment:* Information & Communication Breakdown
   - *Deficiency:* Payments disbursed to suppliers whose tax registrations and onboarding status were still marked "Pending".
2. **Delegation of Authority (DoA) Evasion via "Split POs" (20.00% Failure Rate / 4 Exceptions)**
   - *COSO Alignment:* Control Activities Failure
   - *Deficiency:* Consecutive same-day POs created under ₹100,000 (e.g., ₹60,000 + ₹65,000) to bypass mandatory Senior Director authorization.
3. **Duplicate Invoice Disbursements (10.00% Failure Rate / 2 Exceptions)**
   - *COSO Alignment:* Control Activities Failure
   - *Deficiency:* Processed two separate disbursements sharing identical invoice numbers, resulting in direct financial leakage.
4. **Single-Source Vendor Concentration (CRITICAL Risk)**
   - *ISO 31000 Alignment:* Business Continuity Risk
   - *Deficiency:* Over 50% of operational orders concentrated with just two primary suppliers.

---

## 🛠️ Complete Tools & Tech Stack Used
- **Audit Analytics:** Microsoft Excel (`.xlsx`) using logical formulas (`=IF`, `=AND`, `=COUNTIF`), Pivot Tables, and summary dashboards.
- **Governance Frameworks:** COSO Internal Control Framework and ISO 31000 ERM Framework.
- **Audit Deliverables:** Internal Audit Deficiency Memorandum authored for the Head of Internal Audit & Risk Committee.

---

## 📝 Audit Recommendations & Remediation Plan

1. **ERP Hard-Locks:** Reconfigure ERP workflows to automatically block invoice processing or payment generation for any supplier lacking an "Active & Approved" onboarding status.
2. **Automated Split PO Detection:** Deploy automated monitoring scripts to aggregate same-day, same-vendor purchase orders exceeding ₹100,000 and freeze them for audit review.
3. **Supply Chain Redundancy:** Establish secondary supply agreements for key operational inputs to mitigate single-vendor dependency.

---

