# Incident Reporting Clocks — One Incident, Many Deadlines

The trap nobody plans for: a single security incident can start **three or four separate
reporting clocks at once**, to different authorities, on different timers. Miss one and the
fine tiers stack. Keep this table where your on-call team can see it.

| Regime | Trigger | First clock | Then | Report to |
|--------|---------|-------------|------|-----------|
| **CRA (Art 14)** | Actively exploited vulnerability or severe incident in a product with digital elements | **24 h** early warning | 72 h full notification → final report (14 days / 1 month) | ENISA Single Reporting Platform |
| **NIS2** | Significant incident (essential/important entity) | **24 h** early warning | 72 h notification → final report 1 month | National CSIRT / competent authority |
| **GDPR (Art 33)** | Personal-data breach | **72 h** notification | — | Supervisory authority (DPA) |
| **AI Act (Art 73)** | Serious incident involving a high-risk AI system | **~15 days** (shorter for death/widespread) | follow-up | Market surveillance authority / AI Office |
| **DORA** (financial entities) | Major ICT-related incident | initial → intermediate → final | per RTS timelines | Competent authority (via EBA/ESMA/EIOPA) |

**Design one pipeline, route many ways.** Build a single detection-and-triage function that
classifies an event once, then fans out notifications on each applicable timer. The 24-hour
clocks (CRA, NIS2) set the pace — architect for those.

> A financial entity hit by a breach of an AI-driven, connected product could owe CRA (24h),
> NIS2 (24h), GDPR (72h), AI Act (15d) **and** DORA reports for the same event. That is not
> hypothetical; it is the default for regulated, connected AI.

*Timelines summarise the regimes; confirm exact triggers and cut-offs against each text and
its implementing/RTS acts.*
