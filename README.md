# Website Project Toolkit

A reusable, white-label quick-start kit for web/app projects: capture a client's requirements, then auto-generate a build-team design note (with UI wireframes for every screen). Both files are self-contained HTML — no dependencies, work offline.

## Contents

| File | Version | For | Purpose |
|------|---------|-----|---------|
| `Website-Project-Questionnaire.html` | v0.1.0 | Client | Step-by-step questionnaire (adapts to project type), shows plain-language tax/legal must-haves, saves a "Project Brief" file the client emails back. |
| `Design-Note-Generator.html` | v0.2.0 | Project team | Reads the client's answers and produces a tailored design note — architecture, data model, fulfillment, inventory/ERP, payments, compliance, roadmap, **screen inventory + low-fi wireframe mockups**, and **client sign-off gates**. |

## How they connect

```
Client fills Questionnaire → saves Project Brief (.html, with answers embedded)
   → emails it back → team opens it in the Design Note Generator → design note + mockups
```

The questionnaire embeds answers as hidden JSON (`<script id="wpq-data">`). The generator reads that file (or pasted JSON, or this-browser localStorage `wpq_v1`).

## Usage

1. Send `Website-Project-Questionnaire.html` to the client (or host it). They fill it and email back the saved brief.
2. Open `Design-Note-Generator.html`, upload the brief, click **Generate**.
3. Export the design note (HTML / PDF / Markdown) and review wireframes with the client at the early sign-off gate.

## Notes

- White-label and neutral — reusable for any client.
- Design rules mirror the BeyondGorgeous v2 architecture (modular, marketplace-ready, ERP inventory, India-first compliance, mockup-first sign-off).
- Both tools are versioned in-file; bump the version on edits and keep them in sync as the design approach matures.

🤖 Generated with [Claude Code](https://claude.com/claude-code)
