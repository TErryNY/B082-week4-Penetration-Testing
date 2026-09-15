# 🏥 Mediroza General Hospital — Penetration Testing Report (Week 4)

## 📋 Overview

This repository/document set contains the Week 4 authorized penetration testing
report for **Mediroza General Hospital**, produced as part of the
**Cybersecurity Int. B082A** course (Instructor: Waqas Karim, CCIE) under the
**NetworkWalks** training program.

The engagement was a **controlled black-box web application assessment**
carried out exclusively within an authorized training environment. All
activity, evidence, and findings described in this report relate solely to the
approved target and are documented for educational purposes.

> 🎓 **This project is for educational and training use only.** No technique,
> tool, or finding described here should be applied to any system without
> explicit, written authorization from its owner.

## 👤 Prepared By

| Field | Detail |
|---|---|
| Pen Tester | Terry Nyambe |
| Course / Engagement | Cybersecurity Int. B082A — Waqas Karim, CCIE |
| Assessment Type | Authorized Black-Box Penetration Test |
| Client / Target | Mediroza General Hospital — https://medirozahospital.com |
| Authorization | Written permission granted for the controlled training environment |
| Date | 15th September 2026 |
| Classification | **CONFIDENTIAL** |

## 🎯 Scope

- **Target:** `https://medirozahospital.com`
- **Model:** Black-box web application penetration test
- **In scope:** Public site, patient portal authentication, robots.txt discovery, patient-report area, legacy `/old/` resources, exposed database backup material
- **Out of scope:** Denial-of-service activity, social engineering, destructive modification, and any system outside the approved target

## 🗂️ Report Structure

| Section | Contents |
|---|---|
| 1 | Liability and Authorization Statement |
| 2 | Executive Summary |
| 3 | Scope, Rules and Methodology |
| 5.1 – 5.2 | Reconnaissance and patient portal authentication review |
| 5.3 | robots.txt discovery of sensitive paths |
| 5.4 – 5.5 | Patient report area access and controlled PDF retrieval |
| 5.6 – 5.8 | PDF hash extraction, password recovery, and verification |
| 5.9 – 5.10 | Legacy resource review and database backup exposure |
| 5.11 – 5.12 | Employee salary and shareholder information exposure review |

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Web Browser / Firefox | Manual navigation, authentication review, portal validation |
| robots.txt Review | Passive discovery of disallowed/hidden paths |
| curl | Direct HTTP request/response inspection |
| SQL Injection Testing | Authentication input-handling assessment |
| Browser Developer Tools | Page source and login-form inspection |
| Networkwalks Hash Calculator (online) | PDF encryption hash extraction |
| Networkwalks Password Cracker (online) | Dictionary-based password recovery testing |
| Text / Database Analysis Utilities | Legacy backup review without altering evidence |
| Claude | Converting raw SQL data into readable tables during analysis |

## 📸 Evidence Policy

Only screenshots actually captured by the pentester during the engagement are
embedded in the report as visual evidence. Any project stage without a
supplied screenshot is documented in detailed narrative form instead —
no substitute or fabricated images are used.

## 🔒 Sensitive Data Handling

In line with responsible disclosure practice, the following are **intentionally
withheld or redacted** from the public report:

- Exact patient data and pathology report contents
- Recovered document passwords and extracted hash values
- Employee salary figures and names
- Shareholder/ownership records

Findings involving this data are described at the category and impact level
only. Full evidence is retained privately for the authorized client or
instructor.

## ⚠️ Disclaimer

This report and all associated files are provided strictly for educational
purposes within an authorized training environment. Reproducing, adapting, or
applying any part of this material against real, non-consenting systems is
prohibited and may be unlawful.
