# How the CRA Connects to the AI Act (and ISO / NIS2 / DORA)

If your connected product contains AI, the **EU AI Act** applies alongside the CRA — and you can
satisfy much of both from one set of controls. Full detail lives in the companion **EU AI Act
Compliance Guide**; here's the CRA view.

## The shared surface
A connected product can be **both** a CRA product with digital elements *and* an AI Act
high-risk system.

- **CRA Annex I** essential cybersecurity requirements overlap heavily with **AI Act Art 15**
  (accuracy, robustness, **cybersecurity** of high-risk AI). Design once; evidence against both.
- Where AI is a **safety component** of a CRA/Annex-I product, coordinate the two conformity
  assessments into **one** technical file and CE-marking exercise.
- CRA **Art 14 reporting** and AI Act **Art 73 serious-incident reporting** can share one
  detection-and-triage pipeline.

| Concern | CRA | AI Act |
|---------|-----|--------|
| Product cybersecurity | Annex I essential requirements | Art 15 (high-risk) |
| Documentation | Annex VII | Art 11 + Annex IV |
| Incidents | Art 14 reporting | Art 72–73 |
| Conformity + CE | Annex VIII | Art 43 |

## Standards that bridge both
- **ISO/IEC 27001 / 27002** — infosec management → CRA vuln handling, NIS2.
- **ISO/IEC 15408 (Common Criteria)** — product security evaluation → CRA higher classes.
- **ISO/IEC 42001** — AI management system → AI Act governance.
- **ETSI EN 303 645** — consumer-IoT baseline → CRA for connected consumer PDEs.

## Adjacent regimes
- **NIS2**: entity-level cybersecurity + 24h incident reporting — designed to share reporting
  logic with the CRA. Don't build two disconnected pipelines.
- **DORA** (finance): ICT risk + incident reporting.
- **GDPR**: personal-data breaches add a 72h clock.

## One incident, many clocks
See [`reference/incident-reporting-clocks.md`](reference/incident-reporting-clocks.md).

**→ Full AI Act classification, high-risk obligations and transparency rules:** companion
**EU AI Act Compliance Guide**.
