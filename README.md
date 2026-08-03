# Cyber Resilience Act — Step-by-Step Compliance Guide
Practitioner reference for the EU Cyber Resilience Act — built around the 11 Sep 2026 reporting deadline, with a 24h/72h clock calculator.

> **The current, practitioner-facing reference for the CRA** — built around the 11 Sep 2026 reporting deadline, dated, and free.

![Last reviewed](https://img.shields.io/badge/last%20reviewed-Aug%202026-1B9E86) ![First deadline](https://img.shields.io/badge/Art%2014%20reporting-11%20Sep%202026-F5A623) ![Licence](https://img.shields.io/badge/docs-CC%20BY%204.0-34C4A8)

**Last reviewed: August 2026** · see [CHANGELOG](CHANGELOG.md)

A practitioner's reference for the **Cyber Resilience Act — Regulation (EU) 2024/2847** — the
EU's product-cybersecurity law for **products with digital elements (PDE)**. Built to be
*current*: the first hard deadline (vulnerability & incident reporting) lands **11 September
2026**, and this guide is organised around getting you there.

If your product also contains AI, read the companion **[EU AI Act Compliance
Guide](https://github.com/SMIIT-CyberAI-UK/eu-ai-act-compliance-guide)** — the two overlap, and
[`docs/connects-to-ai-act.md`](docs/connects-to-ai-act.md) maps where.

> Maintained under the [SMIIT CyberAI](www.smiitcyberai.com) banner.
> **Not legal advice.** The Official Journal text is the only authoritative source.

---

## Timeline at a glance

| Date | What happens |
|------|--------------|
| 10 Dec 2024 | Regulation entered into force |
| 11 Jun 2026 | Conformity assessment body notification rules apply |
| **11 Sep 2026** | **Article 14 reporting** — actively exploited vulnerabilities + severe incidents |
| **11 Dec 2027** | **Full application** — essential requirements, conformity, CE marking |

Full sourced version: [`docs/00-timeline.md`](docs/00-timeline.md)

---

## Grab-and-go

- **[Interactive CRA Navigator](tools/index.html)** — deadline countdowns, a scope & product-
  class classifier, a **24h/72h reporting-clock calculator**, and a penalty reckoner.
- **[Quick reference — one page](docs/reference/quick-reference.md)**
- **[Am I in scope?](docs/reference/who-does-this-apply-to.md)**
- **[Penalties](docs/reference/penalties.md)** · **[FAQ & myths](docs/reference/faq-myths.md)** · **[Glossary](docs/reference/glossary.md)**
- **[Incident reporting clocks](docs/reference/incident-reporting-clocks.md)** (multi-regime)

> Publish the tool: enable **GitHub Pages**, then visit `/tools/`.

---

## How to use this guide

1. **[Am I in scope?](docs/reference/who-does-this-apply-to.md)** — is your product a PDE?
2. **[Scope & product classes](docs/scope-and-product-classes.md)** — default / important / critical.
3. **[Hit the first deadline](docs/reporting-article-14.md)** — reporting readiness by 11 Sep 2026.
4. **[Build the technical baseline](docs/vulnerability-handling-sbom.md)** — SBOM, secure updates, vuln handling.
5. **[Conformity & CE marking](docs/conformity-and-ce-marking.md)** — for full application (11 Dec 2027).
6. Follow the **[step-by-step playbook](docs/step-by-step.md)** end to end.
7. Jump to your **[industry annex](docs/industries/)**; run the **[readiness checklist](checklists/readiness-checklist.md)**.

---

## Contents

```
docs/
  00-timeline.md              Master dated timeline (+ related AI Act dates)
  step-by-step.md             Scope → class → reporting → conformity
  scope-and-product-classes.md  What's a PDE; default / important / critical classes
  reporting-article-14.md     The 11 Sep 2026 obligation: 24h/72h/final report
  vulnerability-handling-sbom.md  SBOM, secure updates, support period, CVD
  conformity-and-ce-marking.md  Conformity routes → CE marking → declaration
  connects-to-ai-act.md       Where the CRA meets the AI Act (+ ISO / NIS2 / DORA)
  reference/                  quick-reference · who-does-this-apply-to · penalties
                              faq-myths · glossary · incident-reporting-clocks
  industries/                 manufacturing-iiot · software-saas · consumer-iot
                              automotive-ecosystem · connected-health · public-sector
tools/index.html              Interactive CRA Navigator (with reporting-clock calculator)
checklists/readiness-checklist.md
templates/cra-incident-report.md
```

## Contributing
See [`CONTRIBUTING.md`](CONTRIBUTING.md). Cite the Official Journal or an official
Commission/ENISA source.

## Licence
Docs under **CC BY 4.0** — attribute to SMIIT CyberAI and link back.
