# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

M-todo-Mantis is the central knowledge and operations repository for **Método Mantis** — a consulting practice that transforms businesses through systems, automation, and AI. There is no application code, build system, or test suite. All content is Markdown documentation.

The core principle: *Las personas no escalan. Los sistemas sí.* (People don't scale. Systems do.)

## Repository structure

```
IA/Asistentes/        ← AI assistant prompt files (the main deliverable)
Documentacion/        ← Strategic docs: vision, roadmap, stack, estado actual
Clientes/             ← Client records and engagements
Proyectos/            ← Project deliverables
Automatizaciones/     ← n8n workflows and automation specs
Plantillas/           ← Reusable templates
Sistemas/             ← Infrastructure and policy docs
Contenido/            ← Content production assets
Recursos/             ← Reference materials
Backup/               ← Archive
```

Most subdirectories are intentionally empty scaffolding awaiting content.

## AI assistant system (`IA/Asistentes/`)

Six specialized assistant prompt files define the full consulting lifecycle:

| File | Role | When used |
|------|------|-----------|
| `Estratega-Mantis.md` | Strategy & governance (transversal reference) | Always |
| `Ventas-Mantis.md` | Lead prospecting → diagnosis handoff | Phase 0 |
| `Diagnostico-Mantis.md` | Business audit, bottleneck analysis, ROI | Phase 1 |
| `Propuesta-Mantis.md` | Converting diagnosis into a winning proposal | Phase 2 |
| `Arquitecto-Mantis.md` | Technical blueprint and sprint roadmap | Phase 3 |
| `Automatizador-Mantis.md` | Build and deploy per blueprint | Phase 4 |

The flow is linear with a feedback loop on lost deals:
```
Ventas → Diagnostico → Propuesta → Arquitecto → Automatizador
                                        ↑ (feedback if lost)
```

`Estratega-Mantis.md` defines the methodology all other assistants follow: Observe → Interpret → Project → Decide → Execute → Measure → Adjust. Always read it first when modifying other assistant files.

## Technology stack (per `Documentacion/README-MANTIS.md`)

- **Automation**: n8n, APIs, webhooks
- **AI**: Claude, ChatGPT (strategic reasoning); Claude Code (building)
- **Knowledge management**: Obsidian, NotebookLM
- **Visualization**: Miro, Canva
- **Operations**: Google Calendar, Google Drive
- **Content**: OBS, DaVinci Resolve, CapCut → YouTube, Instagram, TikTok

## Current status

Infrastructure phase (as of 2026-06-28): identity and folder structure are committed; most subdirectories are empty containers. No automation workflows exist yet. Priority items per `Documentacion/ESTADO-ACTUAL.md`:

1. Templates in `Proyectos/Plantillas/` (Discovery, Plan, Checklist)
2. Operational prompts in `IA/Prompts/`
3. First n8n workflow (lead capture → notification → CRM)
4. Obsidian vault setup as system memory

## Conventions

- All documentation is in Spanish unless specified otherwise.
- Filenames use Title-Case-With-Hyphens (e.g., `Estratega-Mantis.md`).
- Markdown is the only file format in use.
- No credentials or API keys belong in this repository; external integrations are documented by reference only.
