# CRA — Step-by-Step Playbook

The CRA makes cybersecurity a **market-access condition**: a product with digital elements
may only be made available in the EU if it meets the Annex I essential requirements and the
manufacturer has fulfilled its obligations. Work the steps below in order.

---

## Step 1 — Is your product in scope?

**In scope:** any **product with digital elements (PDE)** — hardware or software — whose
intended or reasonably foreseeable use includes a direct or indirect data connection to a
device or network, made available on the EU market.

**Out of scope / carved out (governed by sector law instead):**
- Medical devices (MDR/IVDR)
- Motor vehicles (type-approval framework)
- Aviation and marine equipment
- Products already covered by equivalent sectoral cybersecurity law
- **Non-commercial** open-source software (a lighter "open-source steward" regime applies
  to those who monetise or commercially support OSS)
- Pure SaaS is generally outside the CRA's product scope (but check NIS2 / DORA instead)

Output: a **product-in-scope register** listing each product, its connectivity, your role,
and any exemption claimed.

---

## Step 2 — Determine your role

| Role | Obligation weight |
|------|-------------------|
| **Manufacturer** | Heaviest — full essential requirements, conformity, reporting |
| **Importer** | Verify the manufacturer complied before placing on market |
| **Distributor** | Act with due care; don't make non-compliant products available |
| **Authorised representative** | Non-EU manufacturers must appoint one |
| **Open-source steward** | Lighter regime for those supporting OSS commercially |

---

## Step 3 — Classify the product

The conformity route depends on class:

- **Default class** — self-assessment permitted for the majority of products.
- **Important products (Annex III), Class I & II** — e.g. password managers, network
  management, VPNs, firewalls, microcontrollers, OS, routers. Class II requires stricter
  routes (harmonised standards or third-party assessment).
- **Critical products (Annex IV)** — e.g. hardware security modules, smartcard secure
  elements — may require **EU cybersecurity certification**.

> Reality check (mid-2026): harmonised standards and CRA-designated notified bodies were
> **not yet available**. For higher classes, the third-party route may be temporarily
> blocked — factor this into your 2027 plan.

---

## Step 4 — Meet the earliest deadline first: reporting readiness (11 Sep 2026)

Article 14 is the **first binding obligation** and it is operational, not paperwork.

From 11 Sep 2026 you must, via the ENISA **Single Reporting Platform**, report:
- **actively exploited vulnerabilities** in your PDE, and
- **severe incidents** affecting product security.

Cadence:
- [ ] **24 hours** — early warning from becoming aware
- [ ] **72 hours** — full notification
- [ ] **14 days** — final report after a corrective measure is available (vulnerabilities)
- [ ] **1 month** — final report (severe incidents)

Build now:
- [ ] A **detection + triage** process that can recognise "actively exploited" and "severe"
- [ ] Named owners and an on-call path that can hit a 24-hour clock
- [ ] A pre-drafted notification workflow → use
      [`templates/cra-incident-report.md`](../templates/cra-incident-report.md)
- [ ] Coordinated vulnerability disclosure (CVD) policy and a contact point

> Tip: remediating known exploited vulnerabilities *before* 11 Sep 2026 removes the duty to
> notify them — early patching lowers your future reporting load.

---

## Step 5 — Build toward full compliance (11 Dec 2027)

Essential requirements (Annex I) — design, develop, and produce PDEs to be secure:

- [ ] **Secure-by-design & by-default** configuration
- [ ] No known exploitable vulnerabilities at release
- [ ] Attack-surface minimisation; defence in depth
- [ ] Protect confidentiality/integrity (encryption where appropriate) and availability
- [ ] Access control and authentication
- [ ] **Security update mechanism** — timely, ideally automatic, free security patches
- [ ] **SBOM** (software bill of materials) and documented vulnerability handling
- [ ] Defined **support period** during which security updates are provided (guidance
      commonly points to ~5 years unless the expected use period is shorter)

Then:
- [ ] **Vulnerability handling** processes (Annex I Part II) operating throughout support
- [ ] **Technical documentation** (Annex VII)
- [ ] **Conformity assessment** appropriate to product class → **CE marking** → **EU
      declaration of conformity**

---

## Step 6 — Supply chain & contracts

- Map component suppliers whose security affects your ability to comply by Dec 2027;
  prioritise critical components.
- Update supplier contracts and due-diligence to flow down CRA obligations and SBOM/patch
  expectations.
- Track third-party and open-source components in the SBOM.

---

*Not legal advice. Product class and conformity route determine large parts of your
obligation set — confirm class against Annex III/IV and the current implementing acts.*
