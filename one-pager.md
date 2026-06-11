> **Word Layout Note (Slalom template).** The Slalom Word template's Heading 1 style auto-inserts a page break and consumes massive vertical space; Heading 2 is also large. **Do NOT apply the template's H1/H2 styles to the one-pager section markers below** — that's what produced the two-page result on the first paste.
>
> Style mapping when transferring to Word:
> - **Title block** (Slalom AI SDLC Solution + subtitle): use the template's stacked two-color title treatment (black title word, blue subtitle stacked beneath) — *not* preceded by an H1 (which would page-break).
> - **Section markers** (How it works / Representative outputs / Slalom's AI delivery footprint / Recommended path forward / What we need from Nelnet): use **bold Body Text run-ins** at the start of each block (e.g., "**How it works.** The platform layers AI execution..."), NOT H2 headings.
> - **Bullet lists**: List Bullet 1 (default 10pt body bullets).
> - **Navigation table**: Table Slalom style with the blue header bar.
> - **TODO callout**: optionally use the template's Call-Out Box style (blue box, page 5 / page 11 of the template).
>
> If transferring to Word produces >1 page, the fix is **style adjustment**, not content cuts. Verify the section markers are bold body-text run-ins, not H2.

---

# Slalom AI SDLC Solution
### Response to Workstream 3 — an AI-First Delivery Lifecycle ready to configure for Nelnet NDS IT Delivery

Slalom brings Nelnet an AI-First Delivery Lifecycle in use by current enterprise client teams to deliver business-critical initiatives — phase definitions, gate logic, role frameworks, and evidence patterns. The AI SDLC platform is its working implementation: AI workflows, an enterprise context layer that accumulates organizational knowledge, and configurable governance gates. We don't propose a new lifecycle for Nelnet to design; we configure a complete AI platform to Nelnet's existing SDLC vocabulary, gates, ceremonies, and roles.

## How it works

The lifecycle overlays the SDLC Nelnet already runs and spans the full delivery cycle — product inception, design, architecture, build and test, release and deployment, operations, and governance. AI generates the work product of each stage, a peer-reviewer agent validates it before anyone sees it, and the named role owns every gate. Three architectural properties let it operate safely at scale: multi-reviewer validation of every AI output before human eyes see it; audit evidence — decision logs, traceability matrices, peer-review records, quality reports — emitted as a byproduct of delivery rather than assembled after the fact; and profile-driven tailoring that applies NIST controls to federal-facing initiatives, consumer-financial controls to commercial systems, and isolated controls to restricted environments.

**Outcomes for the business.** Faster cycle time between a new contract requirement and its implementation. Broader compliance coverage — FISMA, consumer-financial, federal program requirements — expanding the portfolio your teams can support and bid for with confidence. Defect reduction lowering operational support costs. And as adoption deepens at Nelnet — context layer accumulating organizational knowledge, governance patterns refining, prompts stabilizing — the quality and consistency of outputs grow with it. Each Nelnet initiative inherits the cumulative benefits of the AIDLC.

## Representative outputs

Anonymized samples appear in the appendix.

- **Decision log** with cumulative implications and category traces
- **Requirements decomposition plan** with feature/epic/story/dev-package hierarchy
- **Traceability JSON** mapping features through dev packages
- **Quality report** with gap analysis and verification gates
- **Peer-review artifacts** from multi-agent validation
- **CMMI evidence bundle** mapping practice areas to workflow artifacts

The 60-minute working session will highlight the platform's workflows and agents — and the outputs they produce — on a representative anonymized initiative.

## Slalom's AI delivery footprint

Slalom's broader AI delivery practice spans Fortune-50 enterprise rollouts, regulated-environment modernizations, and large-scale transformation programs. The AI-First Delivery Lifecycle proposed here is its leading edge — backed by the practice's operating-model experience, regulated-environment fluency, and at-scale change management.

## Recommended path forward

- **Setup** — Survey Nelnet's current SDLC structure — vocabulary, gates, ceremonies, roles, regulatory profile — to inform tailoring and configuration. Co-design the change-communications plan: stakeholder landscape, comms cadence, and readiness signals for Pilot launch. Identify a pilot candidate.
- **Pilot** — One real initiative delivered through the lifecycle. Coaching alongside a Nelnet pod. Real artifacts, real gates, real evidence. Go/no-go on scale.
- **Scale** — Replicate the playbook across teams. Stewardship and a center of excellence stand up to own the AIDLC's evolution at Nelnet. Metrics framework drives where to invest next.

## What we need from Nelnet

- A pilot initiative candidate with real scope and a real timeline
- Access to relevant documentation and SMEs for context capture
- A cross-IT steering committee with authority to approve the process, roles, and governance changes the engagement will require
- SME availability across the engagement
- A change-management or communications lead with access to the stakeholder landscape — we co-design the plan and provide the structure; Nelnet's team owns the organizational delivery

---

**Navigation**

| Section | RFI items covered |
|---|---|
| §1 The Shift | Offering & Differentiators · Outcome 1 |
| §2 Our AI-First Delivery Lifecycle | Offering · Approach · Deliverables A & C · Outcome 1 · Full lifecycle coverage |
| §3 How It Stays Safe | Governance, Risk & Auditability · Heterogeneous environments · Deliverable A gates |
| §4 How It Scales | Approach · Outcomes 2–5 · Deliverables B, C, D, E, F |
| §5 How It Integrates | Parallel Modernization |
| §6 How We Engage | Team · Experience · Commercial · Risks |

---

## Open Questions for the Lead

1. **"Hundreds of team members' work in the context layer"** — verified at telecom client? Pattern language per the anonymization rule, but the magnitude should be defensible. If "hundreds" overstates, fall back to "many teams' work."
2. **Mini-map shape** — currently a navigation strip. If the Word layout has room, consider a small 2-column table (narrative section → RFI items/criteria/deliverables) instead. Defer to design pass.
3. **"What we need from Nelnet" specifics** — items listed are first-pass. Confirm "senior sponsor with the authority to honor workflow gates" is the right register (vs. "executive sponsor," "champion," etc.).
4. **TODO callout visibility in final** — the bolded TODO block is intentionally visible so it survives revision cycles. To be resolved before submission (not displayed to Nelnet).

## Decisions I Made During Drafting

1. **Voice = B (tighter sales-deck cadence).** Headline-driven, scannable, navigation-aware. Distinct from §1's narrative register.
2. **Lead with "enterprise-ready AI SDLC platform."** Mirrors RFI's "AI-First Delivery Lifecycle" as the outcome the platform produces. Two terms with distinct jobs.
3. **Removed "In production today" header.** Read as marketing-speak and defensive ("why specify today?"). Replaced with "Slalom's AI delivery footprint" — layered synthesis where the platform is the leading edge of broader Slalom AI delivery practice.
4. **Hierarchical proof structure** — broader Slalom AI delivery practice frames the platform, not the other way around. Avoids the bifurcated "platform deployments vs. adjacent AI delivery" awkwardness while preserving the working-notes anti-conflation rule.
5. **Quantified Artifact 1 metrics deferred to §6.** The cover one-pager doesn't need to perform numbers; pattern language carries breadth, §6 Relevant Experience has space for the quantified outcomes.
6. **No "approximately 400 team members" reference.** Working-notes rule: 400 figure can appear once in §4 or §6, not on the cover.
7. **No specific scale numbers for the anchor engagement.** Pattern language only ("dozens of IT teams," "hundreds of team members' work in the context layer").
8. **TODO callout left inline.** Honest about the proof-bolstering work remaining; visible enough that the next revision pass cannot miss it.
9. **Setup → Pilot → Scale framing.** Aligns with Phase 0 Q2 commercial posture (fixed-fee pilot + T&M scale) and the §1 closing.
10. **Navigation strip at bottom = mini-map (rubric technique #6).** Compact form per the user's earlier checkpoint decision.

## Rubric Coverage Self-Check

| Criterion | One-pager coverage | Where |
|---|---|---|
| Specificity & Credibility of Proposed Outputs | **Strong** — concrete artifact list under Representative outputs | Representative outputs |
| Credibility & Scale of Enablement / Adoption Approach | Moderate — Setup → Pilot → Scale path; compounding-context referenced | Our approach + Recommended path forward |
| Practicality & Usability of the Lifecycle | Moderate — Phases A–J + configuration framing | Our approach |
| Governance & Risk Maturity | Moderate — multi-agent review + workflow-emitted evidence | Our approach |
| Metrics Framework | Light — implied; detailed in §4 | Quality report mention |
| CMMI Integration (Streamlined, Not Additive) | Light — CMMI evidence bundle named; detailed in §3 | Representative outputs |
| Heterogeneous Environment Experience | Moderate — NIST/consumer-fin/Direct tailoring named | Our approach |
| Delivery Structure & Role Framework | Light — detailed in §4 | Implied only |

**RFI §8.2 mandatory elements (one-pager-specific):**

| Required element | Coverage |
|---|---|
| Core approach | ✅ Our approach section |
| Sample artifacts / representative outputs | ✅ Representative outputs section |
| Recommended path forward | ✅ Recommended path forward section |
| What we need from Nelnet to succeed | ✅ What we need from Nelnet section |

**Mini-map (rubric technique #6):** ✅ Navigation strip at bottom

**Win-theme anchoring:**

- WT1 — Running, not reimagined: **Primary** (opening claim + Slalom's AI delivery footprint)
- WT2 — Compounding context: **Primary** (Our approach paragraph)
- WT3 — Governance architectural: **Preview** (multi-agent review, workflow-emitted evidence)
- WT4 — Tailored at the gate: **Preview** (NIST / consumer-fin / Direct tailoring named)
- WT5 — Modernization as fuel: Not addressed on the cover
- WT6 — Architecting around AI failure modes: Not addressed on the cover by design
- WT7 — Financial outcomes: **Preview** (bold run-in sentence at close of Our approach)
