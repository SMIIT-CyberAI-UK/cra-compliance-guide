
<div align="center">
<img width="900" alt="Cyber Resilience Act Compliance Guide" src="https://github.com/user-attachments/assets/6e225262-81fc-4db5-b936-57917343ca0b" />
</div>

# Cyber Resilience Act — Step-by-Step Compliance Guide

**The current, practitioner-facing reference for the EU Cyber Resilience Act.**



Built around the 11 September 2026 reporting deadline · dated · maintained · free

[![Last reviewed](https://img.shields.io/badge/last%20reviewed-Aug%202026-1B9E86)](CHANGELOG.md)
[![First deadline](https://img.shields.io/badge/Art%2014%20reporting-11%20Sep%202026-F5A623)](docs/reporting-article-14.md)
[![Licence](https://img.shields.io/badge/docs-CC%20BY%204.0-34C4A8)](LICENSE)
[![Not legal advice](https://img.shields.io/badge/status-not%20legal%20advice-lightgrey)](#disclaimer)

**[▶ Open the Interactive Navigator](https://smiit-cyberai-uk.github.io/cra-compliance-guide/tools/)** · [Timeline](docs/00-timeline.md) · [Am I in scope?](docs/reference/who-does-this-apply-to.md) · [FAQ](docs/reference/faq-myths.md)

*Maintained under the [SMIIT CyberAI](https://www.smiitcyberai.com) banner.*

</div>

---

## Why this exists

The Cyber Resilience Act — **Regulation (EU) 2024/2847** — is the EU's first horizontal law setting mandatory cybersecurity requirements for **products with digital elements** (hardware and software placed on the EU market). Most coverage circles the **11 December 2027** full-application date. But the obligation that bites *first* is **vulnerability and incident reporting on 11 September 2026** — an operational, 24-hour-clock duty, not paperwork.

This guide is organised around getting you to that first deadline, then to full compliance — and it's built to be **current, not comprehensive-but-stale**, for the people who actually ship product: security engineers, product owners, compliance leads, and the assessors reviewing them.

**What makes it different from the other guides out there:**

- **Deadline-first** — sequenced around 11 Sep 2026 reporting readiness, then the 11 Dec 2027 baseline.
- **Honest about the state of play** — as of mid-2026 there are no CRA notified bodies and no harmonised standards yet, so parts of the conformity route are blocked. The guide says so and sequences around it.
- **Interactive** — a navigator with a **24h / 72h reporting-clock calculator**: enter when you became aware of an incident, get your deadlines back.

---

## Timeline at a glance

| Date | What happens |
|------|--------------|
| 10 Dec 2024 | Regulation entered into force |
| 11 Jun 2026 | Conformity assessment body notification rules apply |
| **11 Sep 2026** | **Article 14 reporting** — actively exploited vulnerabilities + severe incidents |
| **11 Dec 2027** | **Full application** — essential requirements, conformity, CE marking |

> Full sourced version, penalty tiers, and the mid-2026 state-of-play → **[`docs/00-timeline.md`](docs/00-timeline.md)**

---

## Start here

1. **Am I in scope?** — is your product a "product with digital elements"? → [applicability router](docs/reference/who-does-this-apply-to.md)
2. **Which class?** — default / important / critical → [scope & product classes](docs/scope-and-product-classes.md)
3. **Hit the first deadline** — reporting readiness by 11 Sep 2026 → [Article 14 reporting](docs/reporting-article-14.md)
4. **Build the technical baseline** — SBOM, secure updates, vulnerability handling → [technical baseline](docs/vulnerability-handling-sbom.md)
5. **Conformity & CE marking** — for full application → [conformity & CE marking](docs/conformity-and-ce-marking.md)
6. **Follow the playbook** end to end → [step-by-step](docs/step-by-step.md)
7. **Prove it** — run the [readiness checklist](checklists/readiness-checklist.md); use the [incident report template](templates/cra-incident-report.md)

---

## Interactive Navigator

**[smiit-cyberai-uk.github.io/cra-compliance-guide/tools](https://smiit-cyberai-uk.github.io/cra-compliance-guide/tools/)**

A single-page tool that:

- **counts down** live to every CRA deadline,
- runs a **scope & product-class classifier** (in scope? default / important / critical?),
- includes a **24h / 72h reporting-clock calculator** — enter the moment you became aware of an incident and it returns your Article 14 deadlines, and
- **sizes your exposure** with a penalty reckoner.

Runs entirely client-side — no data leaves the browser.

---

## What's inside

<details>
<summary><strong>Full repository map</strong></summary>

```
docs/
  00-timeline.md              Master dated timeline (+ related AI Act dates)
  step-by-step.md             Scope → class → reporting → conformity
  scope-and-product-classes.md  What's a PDE; default / important / critical
  reporting-article-14.md     The 11 Sep 2026 obligation: 24h / 72h / final report
  vulnerability-handling-sbom.md  SBOM, secure updates, support period, CVD
  conformity-and-ce-marking.md  Conformity routes → CE marking → declaration
  connects-to-ai-act.md       Where the CRA meets the AI Act (+ ISO / NIS2 / DORA)
  reference/
    quick-reference.md          One-page cheat sheet
    who-does-this-apply-to.md   60-second scope router
    penalties.md                Ready-reckoner
    faq-myths.md                Myth-busting
    glossary.md                 Every term and acronym
    incident-reporting-clocks.md  One incident, many deadlines
  industries/
    manufacturing-iiot · software-saas · consumer-iot
    automotive-ecosystem · connected-health · public-sector
tools/index.html              Interactive CRA Navigator (reporting-clock calculator)
checklists/readiness-checklist.md
templates/cra-incident-report.md
```

</details>

**Grouped by what you need:**

- **Playbooks** — [step-by-step](docs/step-by-step.md), [scope & product classes](docs/scope-and-product-classes.md), [Article 14 reporting](docs/reporting-article-14.md), [technical baseline (SBOM etc.)](docs/vulnerability-handling-sbom.md), [conformity & CE marking](docs/conformity-and-ce-marking.md)
- **Reference** — [quick reference](docs/reference/quick-reference.md), [penalties](docs/reference/penalties.md), [FAQ](docs/reference/faq-myths.md), [glossary](docs/reference/glossary.md), [scope router](docs/reference/who-does-this-apply-to.md), [incident-reporting clocks](docs/reference/incident-reporting-clocks.md)
- **By industry** — [manufacturing / IIoT](docs/industries/manufacturing-iiot.md), [software / SaaS](docs/industries/software-saas.md), [consumer IoT](docs/industries/consumer-iot.md), [automotive ecosystem](docs/industries/automotive-ecosystem.md), [connected health](docs/industries/connected-health.md), [public sector](docs/industries/public-sector.md)
- **Templates & checklists** — [CRA incident report](templates/cra-incident-report.md), [readiness checklist](checklists/readiness-checklist.md)

---

## Companion guide — the EU AI Act

Does your product contain AI? A connected product with an AI component is often in scope of **both** regulations. The companion repo covers the AI Act end to end:

**→ [EU AI Act Compliance Guide](https://github.com/SMIIT-CyberAI-UK/eu-ai-act-compliance-guide)**

Where they overlap — shared cybersecurity controls, one technical file, one incident pipeline — is mapped in **[`docs/connects-to-ai-act.md`](docs/connects-to-ai-act.md)**.

---

## Maintenance & currency

- **Last reviewed: August 2026.**
- Changes are logged in **[CHANGELOG.md](CHANGELOG.md)**.
- Corrections and additions welcome as pull requests — see **[CONTRIBUTING.md](CONTRIBUTING.md)**. Cite the Official Journal or an official Commission / ENISA source, and update the state-of-play notes as notified bodies and harmonised standards land.

---

<a id="disclaimer"></a>
## Disclaimer & licence

**Not legal advice.** This repository helps you build and sequence a compliance programme; it does not replace qualified legal counsel or a notified body. The official text in the *Official Journal of the European Union* is the only authoritative source.

Documentation is licensed under **[CC BY 4.0](LICENSE)** — share and adapt with attribution to **SMIIT CyberAI** and a link back.
