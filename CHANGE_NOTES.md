Change Notes: DreamTeam Principles (v 5.0 → v 6.0)

**Release Date:** March 23, 2026
**Author:** YURIY TRUKHIN

We are moving from "Quantum Technocracy" (v5.0) to **"Post-AI Cell Architecture."**
In v6.0, the focus shifts from managing Cognitive Load in a Leaf-Spine network to **maximizing impact through AI-augmented autonomous cells.** We acknowledge that AI has fundamentally changed the economics of delivery: the bottleneck is no longer implementation speed but coordination overhead and judgment quality. The team architecture changes from Leaf-Spine to **Domain-Aligned Cells** (3 humans + AI agent fleet).

---

### 1. New Foundation: The Three Laws of Post-AI Infrastructure
* **New in v6.0:** Three foundational laws replace the implicit principles of v5.0.
  1. Coordination is the enemy (N(N-1)/2)
  2. Speed creates stability (preserved from v5.0)
  3. Knowledge lives in artifacts, not heads

**Reason for Change:**
AI has made implementation cheap. The new constraint is coordination overhead — every sync, handoff, and meeting now costs more than the work itself. These three laws encode this reality as first principles.

---

### 2. Topology: Leaf-Spine → Domain-Aligned Cells
* **Was (v 5.0):** Leaf-Spine Network (Stream Engineers as Leafs, Platform & Leadership as Spine).
* **Now (v 6.0):** **Cell Topology** — 3 humans + AI agent fleet per domain cell.

**Reason for Change:**
The Leaf-Spine model assumed individual Stream Engineers as the atomic unit. In the AI era, the atomic unit is a **cell of 3 + AI agents** — small enough to eliminate coordination tax (3 channels vs 136), large enough to avoid bus factor = 1. Cells are domain-aligned (IaaS+Network, PaaS+Observability, Automation+Data, Service Delivery) matching Conway's Law.

---

### 3. New Roles: PE, TE, AI Agents
* **Was:** Stream Engineer, Tech Lead, Owner (The Shield), Director.
* **Now:** **Product Engineer (PE)**, **Technical Engineer (TE)**, **AI Agents**, TPM, Service Delivery Lead, Director.

**Reason for Change:**
The PE combines Product Sponsor ("why") and Principal Engineer ("how") — in infrastructure with narrow domain expertise, these are inseparable. The TE operates autonomously with AI agents (single person per epic). AI Agents are elevated to first-class team members. The Shield role is preserved in the Service Delivery Lead. The Director role is preserved. Tech Lead evolves into TPM (cross-cell coherence).

---

### 4. New Concept: Floating Leadership
* **New in v6.0:** Context determines who leads, not title.

**Reason for Change:**
In a trio, the person who understands the problem best should drive the Design phase, regardless of their formal role. This prevents the "lead decides everything, we wait" anti-pattern and maximizes domain expertise utilization.

---

### 5. Operating Model: Direction → Design → Delivery
* **Was:** Implicit; relied on Consent for decision-making.
* **Now:** Explicit **Direction → Design → Delivery** pipeline with Build + Run modes.

**Reason for Change:**
Infrastructure teams must simultaneously Build new capabilities AND Run production systems. The old Spec→Design→Grooming→Dev→QA→Rework pipeline is dead. The new pipeline eliminates handoffs: one person designs (with validation), the cell delivers. Build/Run modes are states of the same cell, not different teams.

---

### 6. AI-First Operating Model
* **New in v6.0:** Entire section dedicated to AI as the operating model.

**Reason for Change:**
AI adoption is no longer optional. Manual code writing, copy-paste to ChatGPT, line-by-line code reviews, splitting features into small tasks for teams — all obsolete. Engineers operate AI agent fleets. Agentic harnesses run for hours unattended. This is the reality as of March 2026 and the expectation from company leadership.

---

### 7. Metrics: DORA → 10 Vital Signs
* **Was (v 5.0):** 4 DORA Metrics.
* **Now (v 6.0):** **10 Vital Signs** across three categories.

**Reason for Change:**
DORA metrics alone don't capture the AI-era reality. We add:
- **OKR Completion Rate** — are we shipping what matters?
- **Build/Run Ratio** — are we building the future or firefighting?
- **L2 Interruptions/Day** — can engineers maintain flow?
- **Hero Bottleneck Events** — is any person a single point of failure?
- **GSR Ticket Volume** — is self-service working?
- **Active AI Users** — is everyone leveraging AI?
- **MTTV (Mean Time to Verification)** — how fast can we validate AI output?

---

### 8. Keeper Standard: Elevated for AI Era
* **Was:** Would you fight to keep them?
* **Now:** Same test, **plus**: a Keeper multiplies impact through AI, shares learnings, creates harnesses for others.

**Reason for Change:**
A 1x engineer in a 10x world is a drag on Talent Density. The bar is higher: adaptability and AI fluency are now part of what makes someone a Keeper.

---

### 9. New: Rules of the Cell
* **New in v6.0:** 7 explicit operating rules for cell members.

**Reason for Change:**
Autonomous cells need guardrails, not management. The rules encode hard-won lessons: no DM priorities, one person per epic, solution doc before code, automate the second time, own your on-call, demo don't report, unlearn constantly.

---

### 10. Culture: "It doesn't work" is not acceptable
* **Added to Toxicity section.**

**Reason for Change:**
In the AI era, defeatism ("AI doesn't work for our use case") is as toxic as the old "that's not my job." Come with concrete examples and specific blockers — we solve them together. But blanket rejection of new tools is not tolerated.

---

### 11. Prime Directive: Evolved
* **Was:** "Don't do stupid stuff."
* **Now:** "Build systems that make humans unnecessary for routine work — so humans can focus on vision, judgment, and creative problem-solving."

**Reason for Change:**
The old directive was about avoiding harm. The new one is about actively building toward a future where human time is spent only on irreplaceable human contributions. AI handles the rest.

---

### Summary of Changes Table

| Area | Version 5.0 (Old) | Version 6.0 (New) |
|:---|:---|:---|
| **Philosophy** | Cognitive Flow, Consent, Talent Density | **AI-First Cells**, Consent, **Coordination is the Enemy** |
| **Structure** | Leaf-Spine (Network Topology) | **Domain-Aligned Cells** (3 humans + AI agents) |
| **Atomic Unit** | Stream Engineer (individual) | **Cell** (PE + 2 TEs + AI fleet) |
| **Leadership** | Tech Lead (Bar Raiser) | **Floating Leadership** (context-driven) + TPM |
| **Manager Role** | Stability Interface / The Shield | **Service Delivery Lead** (Shield) + **TPM** (Coherence) |
| **Operating Model** | Implicit (Consent-based) | **Direction → Design → Delivery** with Build/Run modes |
| **AI** | Not addressed | **First-class team members**; agentic harnesses mandatory |
| **Metrics** | 4 DORA Metrics | **10 Vital Signs** (Delivery + Operational + AI Adoption) |
| **Keeper Test** | Would you fight to keep them? | Same + **AI multiplication** required |
| **Prime Directive** | Don't do stupid stuff | **Build systems that make humans unnecessary for routine** |

> *"v5.0 didn't need industrial-era management for quantum-era problems. v6.0 doesn't need quantum-era management for post-AI problems."*

---

### Previous Change Notes

<details>
<summary>v 4.1.2 → v 5.0 (Dec 15, 2025)</summary>

We abandoned the "industrial era" paradigm (where people are cogs and success depends on heroism) in favor of "Quantum Technocracy." In v5.0, the focus shifted from hunting for "rock stars" to managing Cognitive Load and creating Flow. We acknowledged that modern systems are too complex for a single mind, so the team architecture changed from hierarchical to networked (Leaf-Spine).

1. **Decision Making:** Consensus → Consent (Sociocracy)
2. **Topology:** Hierarchy → Leaf-Spine Network Structure
3. **Leader's Role:** Owner → "The Shield" (Stability Interface)
4. **Transparency:** Green/Red reports → Open Order Book (Radical Visibility)
5. **Culture & HR:** "Family" → Pro Team with Keeper Test
6. **Metrics:** Vague goals → DORA Metrics

</details>
