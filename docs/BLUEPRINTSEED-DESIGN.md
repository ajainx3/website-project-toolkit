# BlueprintSeed — Product Design Document

> Vision, design, and roadmap for **BlueprintSeed** — the tool that turns client requirements into a build blueprint.
> Living document, versioned in Git. Update the history table on each meaningful edit.

---

## Document control

| Version | Date | Summary |
|---------|------|---------|
| 0.1.0 | 2026-06-28 | Initial product design: vision, problem, how it works, the moat, principles, current capabilities, and a staged future roadmap (v0.2 → enterprise). |

**Status legend:** 🟢 done · 🟡 in progress / next · 🔵 future · ⚪ open question.

---

## 1. Vision

> **BlueprintSeed turns a client's plain-language requirements into a complete, opinionated build blueprint — architecture, scope, screens, compliance, and roadmap — in minutes, so any team can start a project with senior-architect rigour.**

The long-term ambition: become the fastest, most trustworthy way to go from **"idea" to "plan"** for web, app, and software projects — used from solo studios up to enterprise solutioning and pre-sales teams.

The name captures the model: you plant a small **seed** (the requirements) and it grows into the **blueprint**.

---

## 2. The problem

Scoping a new software project is slow, inconsistent, and trapped in senior people's heads:

- **Discovery is manual and repetitive** — every project re-asks the same questions.
- **Quality depends on who's in the room** — a junior scopes differently from a principal architect.
- **Critical things get missed** — compliance, edge screens, inventory rules, payment realities — and surface late, when they're expensive.
- **Clients can't picture the result early**, so changes land after the build, not before.
- **The output isn't reusable** — notes live in someone's doc, not as structured context a team (or an AI) can build on.

BlueprintSeed compresses that into a guided intake plus an instant, opinionated blueprint.

---

## 3. What BlueprintSeed is (today)

A two-part, dependency-free toolkit:

1. **Intake questionnaire** *(client-facing)* — a friendly, adaptive form that captures requirements in plain language and saves a portable brief.
2. **BlueprintSeed generator** *(team-facing)* — reads those answers and produces a tailored blueprint: architecture, data model, fulfillment, inventory, payments, **compliance**, **roadmap**, a **screen inventory with wireframe mockups**, and **client sign-off gates**. Exports HTML / PDF / Markdown.

```
Requirements (seed)  →  BlueprintSeed  →  Build blueprint + UI mockups (+ AI-ready context)
```

---

## 4. The asset & moat

**Forms are cheap; the encoded judgement is the moat.** BlueprintSeed's real value is its **rules engine** — the accumulated mapping of *"a requirement implies this architecture / compliance need / screen / risk."* That's the kind of judgement a senior architect carries in their head; BlueprintSeed makes it **reusable, consistent, and instant.**

Two reinforcing differentiators on top:
- **It draws the screens** (mockups), so alignment happens early and visually.
- **It emits AI-ready context**, so the blueprint can seed brainstorming or a downstream LLM run.

Every version that deepens and validates the rule library makes the asset more valuable and harder to copy.

---

## 5. Product principles

- **Opinionated, not blank.** It recommends, it doesn't just collect.
- **Plain language for clients, depth for the team.** Never show architecture jargon to the buyer.
- **Mockup-first.** Every screen is drawn up front, before expensive build.
- **Compliance is not optional.** Tax, privacy, and sector rules are surfaced automatically.
- **Portable by default.** Runs offline today; the knowledge is meant to outlive any single UI.
- **Versioned knowledge.** The rule library is the product — it is tracked and grows.

---

## 6. Current capabilities (v0.2.0)

- 🟢 Adaptive intake questionnaire (e-commerce + general websites), auto-save, plain-language must-haves.
- 🟢 Blueprint generator: architecture, data model, ingestion, fulfillment, inventory/ERP, payments, notifications, tax, SEO, AI support, compliance, tailored roadmap, open questions.
- 🟢 Screen inventory + low-fidelity wireframe mockups for every screen.
- 🟢 Client sign-off gates.
- 🟢 Exports: HTML, Print/PDF, Markdown (AI-pasteable).
- 🟢 Self-contained, offline, white-label.

---

## 7. Future roadmap

A staged path from today's offline tool to a product corporates could adopt. Horizons are directional, not committed dates.

| Version | Theme | Key deliverables |
|---------|-------|------------------|
| **v0.2** 🟢 | Working toolkit | Questionnaire + generator with rules, mockups, sign-off gates, exports |
| **v0.3** 🟡 | Knowledge as data | Separate the rule library from the UI into a versioned data file; broaden sectors; a polished **"AI context pack"** export tuned for LLM hand-off |
| **v0.4** 🔵 | Depth & fidelity | More project types, richer rules, a larger wireframe library, branded PDF output, estimation hints |
| **v1.0** 🔵 | Hosted SaaS | Accounts, saved projects, shareable links, branded client-intake portals, blueprint history |
| **v2.0** 🔵 | AI-augmented | LLM fills gaps, drafts higher-fidelity mockups, suggests questions, estimates effort/cost — with guardrails |
| **v3.0** 🔵 | Integrations & enterprise | Push to Jira/Linear/Figma/Notion & proposal tools; team templates, governance, SSO, analytics |

### Narrative
- **Near term (v0.3–0.4)** is about making the *knowledge* the asset — pull the rules out of the HTML into structured, versioned data so it can power any front-end later, and sharpen the AI-context output (the most modern, in-demand feature).
- **Mid term (v1.0)** turns it into a real product: hosted, multi-user, shareable — the point at which agencies pay for it.
- **Long term (v2.0–v3.0)** is the corporate ceiling: AI-augmented solutioning that plugs into the tools enterprise teams already use, with the security and governance they require.

---

## 8. Branding & naming notes

- **Name:** BlueprintSeed — *"plant the brief, grow the build."*
- **Status:** the exact name appears unused as a product; brandable and ownable as a compound.
- ⚠️ **Watch-out:** the "Blueprint" root is crowded in software (incl. enterprise incumbents), which has implications for **trademark** (same class) and **SEO**. The distinctive "Seed" half mitigates this.
- ⚪ **Before heavy branding investment:** verify `blueprintseed.com` / `.io` / `.app` (registrar WHOIS) and run a trademark search (USPTO / IP India). Consider whether a shorter "Seed" sub-brand emerges over time.

---

## 9. Open questions & next steps

| # | Question / step | Status |
|---|-----------------|--------|
| 1 | Pull the rule library out of the UI into versioned data | 🟡 next (v0.3) |
| 2 | Design the "AI context pack" export format | 🟡 next |
| 3 | Verify domain + trademark availability | ⚪ to do |
| 4 | Decide hosting/SaaS stack when we reach v1.0 | 🔵 later |
| 5 | Pricing & target segment (studios → agencies → enterprise) | ⚪ open |
| 6 | Should the questionnaire become a branded "BlueprintSeed Intake"? | ⚪ open |

---

<p align="center"><sub>BlueprintSeed · product design v0.1.0 · part of the <a href="../README.md">Website Project Toolkit</a></sub></p>
