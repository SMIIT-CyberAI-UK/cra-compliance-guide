# CRA — Product Classes & Conformity Routes

The conformity route depends on how the product is classified.

## Classes
- **Default (unclassified) products** — the large majority. **Self-assessment** (internal
  control) is permitted against the essential requirements.
- **Important products — Annex III**
  - **Class I** (e.g. password managers, VPNs, network management, some IoT) — self-assessment
    **if** harmonised standards are applied; otherwise third-party.
  - **Class II** (e.g. operating systems, firewalls, microcontrollers, routers) — stricter:
    harmonised standards or **third-party** conformity assessment.
- **Critical products — Annex IV** (e.g. hardware security modules, smartcard secure elements)
  — may require **EU cybersecurity certification**.

## Conformity steps (target 11 Dec 2027)
1. Determine class and applicable route.
2. Meet **Annex I** essential requirements (secure-by-design, no known exploitable vulns,
   access control, secure updates, SBOM, vulnerability handling over the support period).
3. Compile **Annex VII technical documentation**.
4. Run the conformity assessment (self or notified body).
5. Draw up the **EU declaration of conformity**; affix **CE marking**.

## State-of-play blockers (mid-2026)
- **No CRA-designated notified bodies** yet listed in NANDO.
- **No CRA harmonised standard** yet in the Official Journal; CEN/CENELEC still drafting.
- ENISA reporting platform in testing toward 11 Sep 2026.

**Implication:** for Class II / critical products, the third-party route may be temporarily
unavailable. Do the internal work now (SBOM, secure-update mechanism, vuln handling,
documentation) so you're ready the moment standards and bodies land — and hit the **11 Sep
2026 reporting** obligation on time regardless.

*Not legal advice — class lists are summarised; confirm against Annex III/IV and implementing
acts.*
