# FACE Knowledge Base Template

> Powered by the [Framework for AI Context in Enterprise](https://abq.institute) by ABQ Institute.

## What is this?

This is a ready-to-use knowledge base template built on the **Framework for AI Context in Enterprise (FACE)**. It includes:

- ✅ The standard 5-layer KB structure (company, departments, products, projects, agents)
- ✅ AI skill files for Claude Code, Cursor, Gemini CLI, GitHub Copilot — auto-loaded when you open an agent in this folder
- ✅ A guided setup flow: the agent walks you through `kb-config.yaml` configuration automatically

## How to Use

1. Click **"Use this template"** on GitHub → create your organisation's KB repo
2. Clone the repo locally
3. Open your AI tool (Claude Code, Cursor, Gemini, Copilot) in the repo root
4. The agent detects this is an FACE KB and guides you through the 4-question setup
5. Done — your KB is live

## Structure

| Folder | Purpose |
|--------|---------|
| `0-meta/` | KB configuration (`kb-config.yaml`) |
| `1-company/` | Organisation-wide: mission, values, policies, strategy |
| `2-departments/` | Per department: processes, team context, responsibilities |
| `3-products/` | Per product: specs, architecture, decisions, roadmap |
| `4-projects/` | Per project: scope, timelines, deliverables, retrospectives |
| `5-agents/` | Agent configurations and skill assignments |

## After Setup

Once `kb-config.yaml` is configured:
- Delete `CLAUDE.md` setup instructions and replace with ongoing KB operations instructions (the agent will guide you)
- Or keep them — the agent auto-detects whether setup is complete and switches modes

## Learn More

- [FACE Documentation](https://abq.institute/face)
- [ABQ Institute](https://abq.institute)

---

*Template maintained by [ABQ Institute](https://abq.institute)*
