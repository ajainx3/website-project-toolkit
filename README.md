<p align="center">
  <img src="assets/banner.svg" alt="BlueprintSeed" width="100%">
</p>

<h1 align="center">BlueprintSeed</h1>

<p align="center">
  A reusable, white-label quick-start for web &amp; app projects: capture a client's requirements, then auto-generate a build blueprint — complete with UI wireframes for every screen.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/type-white--label%20template-4f46e5" alt="White-label">
  <img src="https://img.shields.io/badge/dependencies-none-16a34a" alt="No dependencies">
  <img src="https://img.shields.io/badge/runs-offline%20in%20any%20browser-0d9488" alt="Offline">
</p>

---

## What it is

Two self-contained HTML files that turn a messy, error-prone kick-off into a repeatable, professional process:

1. **BlueprintSeed Intake** — captures *what* they need, in plain language.
2. **BlueprintSeed** — turns those answers into *how we'll build it*: architecture, scope, compliance, roadmap, and screen mockups — for the project team.

No installs, no accounts, no internet required. Open in any browser.

## How it works

```mermaid
flowchart LR
  A["🧾 Client fills<br/>Intake"] --> B["💾 Saves a<br/>Project Brief"]
  B --> C["📧 Emails it back"]
  C --> D["⚙️ BlueprintSeed"]
  D --> E["📐 Blueprint +<br/>UI mockups"]
```

The questionnaire embeds the answers invisibly in the saved file; the generator reads that file and produces the note — nothing is re-typed.

## The two tools

| Tool | For | What it does |
|------|-----|--------------|
| 📝 **[BlueprintSeed-Intake.html](BlueprintSeed-Intake.html)** | The client | A friendly, step-by-step wizard that adapts to the project type, auto-saves progress, and shows plain-language tax/legal must-haves based on the answers. Exports a *Project Brief* to email back. |
| ⚙️ **[BlueprintSeed.html](BlueprintSeed.html)** | The project team | Reads the client's answers and generates a tailored **blueprint**: architecture, data model, fulfillment, inventory, payments, **compliance**, **roadmap**, a **screen inventory with wireframe mockups**, and **client sign-off gates**. Exports HTML / PDF / Markdown. → see the **[BlueprintSeed vision &amp; roadmap](docs/BLUEPRINTSEED-DESIGN.md)** |

## Why it matters

- **Fewer surprises.** Scope and must-haves are explicit before a line of code.
- **Mockup-first.** Every screen is wireframed up front — clients react and approve early, when changes are cheap.
- **Compliance built in.** Tax, privacy, and sector rules are flagged automatically from the answers.
- **Repeatable.** The same solid foundation for every new client.

## Try it

1. Download or clone this repo.
2. Open **`BlueprintSeed-Intake.html`**, fill a few steps, and save your answers.
3. Open **`BlueprintSeed.html`**, load that file, and click **Generate**.

## Notes

- White-label and neutral — brand it per engagement.
- The built-in design rules reflect a production-grade reference architecture (modular, marketplace-ready, ERP-grade inventory, India-first compliance, mockup-first sign-off).
- Both tools are versioned in-file and evolve as the approach matures.

---

<p align="center"><sub>Built by ajainx3 · 🤖 with <a href="https://claude.com/claude-code">Claude Code</a></sub></p>
