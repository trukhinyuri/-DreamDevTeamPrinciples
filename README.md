# The DreamTeam Principles
*Created by **YURIY TRUKHIN** — v 6.0 (AI Era Edition, March 2026)*

> *v5.0 was quantum-era. v6.0 is post-AI. The physics of delivery have changed — again. The principles that made us great stay. The ones that assumed humans are the only builders don't.*

We are the team that will make our company **No. 1**. We operate as a high-frequency organism, valuing **Radical Visibility** and **Cognitive Flow** above all else. We don't spell out rules that'll get you fired. We set **incredibly high standards** (Talent Density) and hire exceptional people who value autonomy.

What changed: **AI agents are now first-class team members.** The bottleneck is no longer implementation speed — it's **Vision, Judgment, and Coordination Overhead.** Every principle below is written for a world where a single engineer with AI can outpace yesterday's squad.

---

## The Three Laws of Post-AI Infrastructure

**1. Coordination is the enemy.** Every standup, ticket, handoff, and sync is energy spent NOT building. We minimize it ruthlessly. The formula N(N-1)/2 is our nemesis: a team of 4 = 6 channels, a team of 8 = 28, a team of 17 = 136. We operate in cells of 3 = 3 channels.

**2. Speed creates stability.** We never drop a task until it's done — but we prioritize **speed** because fast iteration finds bugs faster, delivers value sooner, and learns quicker than slow perfection. Bursty iteration beats careful planning. Ship, measure, fix.

**3. Knowledge lives in artifacts, not heads.** If it's in someone's head, it dies when they're on vacation. Solution docs, runbooks, AI-generated documentation — these are the real "team members" that never leave. AI makes this cheap. We make it mandatory.

---

## Cell Topology (Consent > Consensus)

We don't blur responsibility. We manage **Cognitive Load**, not people. We organize around **domains**, not tiers.

### The Cell

The cell is our atomic unit: **3 humans + AI agent fleet**, aligned to one infrastructure domain. Small enough to eliminate coordination tax. Large enough to avoid bus factor = 1. Every cell operates autonomously within boundaries set by the Director.

| Role | What It Means |
|------|---------------|
| **Product Engineer (PE)** | The cell's architect-builder. Owns the "why" AND the "how" — in infrastructure, they're inseparable. Sets systemic vision. Builds MVPs. Runs AI agents. Has no HR power, only the **Authority of Competence.** |
| **Technical Engineer (TE)** | Domain expert and executor. Leads tasks when they own context (floating leadership). Operates their own AI agent fleet. Creates solution docs that outlive them. **Single person per epic.** |
| **AI Agents** | First-class team members. Domain-specific harnesses, MCP servers, agentic workflows. They don't replace judgment — they multiply it. Every routine task that a human does twice should become an agent's job. |

### Floating Leadership

Context determines who leads, not title. The person who understands the problem best drives the Design phase. The PE ensures systemic coherence. A junior TE with deep knowledge of a subsystem leads that subsystem's work — the PE validates and connects it to the bigger picture.

> *"Without explicitly establishing this principle, people default to 'the lead decides everything, we wait.' — We don't wait."*

### The Support Layer

| Role | What It Means |
|------|---------------|
| **Technical Program Manager** | Cross-cell coherence. Incident Commander for P0/P1. Architecture Decision Records. Career development. **Not a bottleneck** — cells don't need permission to execute. |
| **Service Delivery Lead** | The **Shield** that absorbs operational entropy so domain cells can focus on Build. Transforms reactive ticket-processing into self-service platform. |
| **Director** | Gets "hanged" if the internal platform fails to support the cells. Steers long-term strategy to reduce cognitive load. Absorbs chaos from the business. Stands before the board and says **"I am to blame"** — but privately demands accountability through data. |

### No Bosses; Only Consent

We do not wait for *Consensus* (everyone agrees) — that breeds mediocrity. We operate on **Consent**: *"Is this safe to try?"* If there is no paramount objection — no evidence of immediate harm — we execute.

**The Arbitrator Protocol** still holds: if two people jam (normal in distributed systems), call in an arbitrator — not a "boss", but the person with the deepest domain competence.

> *"An arbitrator might choose something you don't like. Suck it up and commit."*

**Bubble-up Escalation:** Decisions happen at the **Cell** level (where the infrastructure lives). Escalate only to unblock:

1. Cell PE decides within domain
2. TPM resolves cross-cell conflicts
3. Director addresses strategic scope

Then it **bubbles back down**. Consent lets us be smarter (and faster) than our competitor's smartest bureaucracy.

---

## Direction → Design → Delivery

We don't do Spec → Design → Grooming → Dev → PR Review → QA → Rework. That's the old way — fragmentation and delay.

**Direction:** The Director (or business need, or cell initiative) sets the goal. Not the implementation plan — the **goal**.

**Design:** The context owner — whoever knows the problem best — independently investigates and shapes the solution doc. They don't bring in the partner until they have a clear picture. Bringing someone in too early creates "joint wandering that kills speed."

**Delivery:** The cell builds, iterates, deploys together. The PE works in parallel on adjacent workstreams. AI agents handle execution at scale.

### Build + Run: Two Modes, Same Cell

Infrastructure can't "fail fast" on production. We must Build new capabilities AND Run production systems. These aren't different teams — they're two states of the same cell.

- **Build** is the default. Direction → Design → Delivery.
- **Run** interrupts Build only for P0/P1. The cell switches to incident mode, resolves, writes postmortem, returns to Build.
- **The goal:** Shift from 30/70 (Build/Run) to 60/40. Every automation we build in Build mode reduces future Run load.

---

## AI-First: Not a Tool, the Operating Model

This isn't about "using AI sometimes." AI agents are how we work, period.

**What's not okay:** Writing infrastructure code by hand. Copy-pasting to/from ChatGPT. Reading hundreds of lines in code reviews manually. Splitting features into small tasks for the team.

**What's okay:** Steering AI agents through Cursor or Claude Code. Using AI to explain, probe, investigate during reviews. Single person per epic with AI assistance.

**Where we should be:** Creating agentic harnesses — agents running for hours or days unattended. Automated OpenNebula management. Automated Ceph capacity planning. Automated compliance checks. Automated access provisioning. Multiple epics running simultaneously.

> *"Your job is to create context for the AI, so that it does work for you. Your domain expertise, your knowledge — that's what feeds the machine."*

**Every engineer operates an AI agent fleet.** If you're not using AI for your work daily, you're operating at 1x while the world moves at 10-50x. We invest in subscriptions, API tokens, and tooling so nobody hits limits.

---

## Radical Visibility

We reject "Green/Red" status reports — they are lies. We operate with an **Open Order Book.**

- We show the raw data: blockers, queue sizes, Build/Run ratio, the specific "why" behind every decision.
- **Demos over reports.** Biweekly, every cell shows working results. No slides. Working systems.
- **Solution docs are transparent.** Every design decision is documented and accessible. If you need context on why something was built this way, read the doc — don't schedule a meeting.
- **AI Daily Reports** summarize cell activity automatically. No manual weekly status reports.
- **Transparency is the antidote to politics.** If the data is visible, shadow agendas die.

---

## Who's the Most Important?

All **Engineers** who are in the "Flow." Above them are only our users (who pay our salaries) and the production systems (which serve those users). **Management exists solely to serve as a support function for Engineering.** If a manager isn't removing a blocker, absorbing stress (The Shield), or creating strategic clarity — they are overhead.

In the AI era, this extends: **the best engineer is the one who multiplies their impact through AI agents.** Not the one who types fastest, but the one with the best judgment about what to build and the skill to orchestrate agents to build it.

---

## Vital Signs

Forget "Lines of Code." We watch:

### Delivery Health (evolved DORA)
1. **OKR Completion Rate** — Are we shipping what matters? (Target: >75%)
2. **Build/Run Ratio** — Are we building the future or firefighting the past? (Target: 60/40)
3. **Cycle Time** — Request to delivery. Days, not weeks.
4. **Change Failure Rate** — Don't break it often.

### Operational Health
5. **L2 Interruptions/Day** — Can engineers focus? (Target: ≤35/day)
6. **Hero Bottleneck Events** — Is any one person a single point of failure? (Target: <3/quarter)
7. **P0/P1 Incident Count** — Is the platform stable? (Target: <20/quarter)
8. **GSR Ticket Volume** — Is self-service working? (Target: -50% quarter over quarter)

### AI Adoption
9. **Active AI Users** — Is every engineer leveraging AI? (Target: 100%)
10. **Mean Time to Verification (MTTV)** — How fast can we validate AI output? (Lower is better)

> *Achieving big targets without breaking things secures the company's future. Speed and Stability are friends, not enemies.*

---

## The "Keeper" Standard

We are a **Pro Team**, not a family. **The Test:** *"If a team member told you they were leaving for a competitor, would you fight hard to keep them?"* If the answer is **No** — we give them a generous severance and say goodbye immediately.

In the AI era, the bar is higher: **a Keeper is someone who multiplies their impact through AI, shares their learnings, creates skills and harnesses for others, and lifts the whole cell's velocity.** A 1x engineer in a 10x world is a drag on Talent Density.

> *"The one who will survive are the one who changes fastest to adapt for the situation. The fittest doesn't mean strongest or fastest — it means those that adapt the best for the change."*

---

## Toxicity Is Evil! (But Silence is Worse)

- **Psychological Safety != Comfort.** It means it is safe to take risks, safe to speak up, safe to say "I don't know how to do this with AI yet."
- **Radical Candor:** We care personally, so we **challenge directly**. Ruinous empathy is a fireable offense. But so is cruelty disguised as feedback.
- **Public Liability, Private Correction:** If infrastructure breaks, the Cell/PE takes the blame publicly. Inside, we fix the process instantly.
- Any junior can tell a PE they are wrong — but must argue with data (or a well-reasoned solution doc).
- We drop honorifics. **Respect is the default.**
- **"It doesn't work" is not acceptable.** Come with concrete examples. Come with what you tried. Come with what you need help with. We will figure it out together — but defeatism is not tolerated.

---

## The Rules of the Cell

1. **No priorities via DM.** If it's not P0/P1, it waits for Leads Sync. DMs create shadow priority queues that kill focus.
2. **One person per epic.** Collaboration happens at Design validation and Delivery review — not as a committee running the same task.
3. **Solution doc before code.** Design is cheap. Rebuilding is expensive even with AI. Think first, build fast.
4. **Automate the second time.** First time you do something manually, fine. Second time, build the automation (or the AI skill). Third time should be zero-touch.
5. **Own your on-call.** The cell that builds it, runs it. Not because we're cruel — because the Platform (Cell Service Delivery) makes running it easy.
6. **Demo, don't report.** Show the working system. If you can't demo it, it's not done.
7. **Unlearn constantly.** Whatever worked last year might not work now. Challenge your assumptions. The cost of code change is near zero — the cost of wrong assumptions is infinite.

---

## The Prime Directive

> **Build systems that make humans unnecessary for routine work** — so humans can focus on the work that makes them irreplaceable: vision, judgment, creative problem-solving, and caring about the people who use what we build.

Know why you earned your salary today. Systems this complex — and a **Dream Team** — can be built only together. With AI.

---

**P.S.** What happens for breaking the rules?

Nothing dramatic. Rules are written — and updated — collectively based on data. **Pull Requests welcome.** But remember: in a cell of 3, there's nowhere to hide. Your teammates see everything. That's not surveillance — it's trust at close range.

*This document is a living artifact. Like our infrastructure, it's never "done" — it's continuously deployed.*
