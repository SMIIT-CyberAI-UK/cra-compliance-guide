# CRA — Vulnerability & Incident Reporting (Article 14)

**The first binding CRA obligation — live 11 September 2026.** It is *operational*, not
paperwork: you must be able to detect, assess, and report against tight clocks via the ENISA
**Single Reporting Platform**.

## What you must report
- **Actively exploited vulnerabilities** in your product with digital elements.
- **Severe incidents** having an impact on the security of the product.

## The clocks
| Stage | Deadline |
|-------|----------|
| Early warning | **24 hours** of becoming aware |
| Full notification | **72 hours** of becoming aware |
| Final report — actively exploited vulnerability | within **14 days** of a corrective measure being available |
| Final report — severe incident | within **1 month** |

## Build this before 11 Sep 2026
- [ ] **Detection & triage** that can recognise "actively exploited" and "severe."
- [ ] **Named owners** and an on-call path that can meet a **24-hour** clock (nights/weekends).
- [ ] A **pre-drafted notification workflow** → use [`../templates/cra-incident-report.md`](../templates/cra-incident-report.md).
- [ ] A **coordinated vulnerability disclosure (CVD)** policy and a contact point.
- [ ] Access/test credentials for the **ENISA Single Reporting Platform**.

## Practical notes
- **Patch early:** remediating a known exploited vulnerability *before* the deadline removes the
  duty to notify it — early fixing lowers your reporting load.
- The 24-hour clock is the hardest engineering constraint in the whole CRA. Architect for it.
- One event can also trigger **NIS2, GDPR, AI Act and DORA** reports — see
  [`reference/incident-reporting-clocks.md`](reference/incident-reporting-clocks.md).

*Not legal advice — confirm exact triggers and cut-offs against Art 14 and ENISA guidance.*
