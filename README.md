<div align="center">

# speckit-skills

**Spec Kit spec-driven development workflow skills**

[![GitHub](https://img.shields.io/badge/github-full--statck--skills%2Fspeckit-skills-green.svg)](https://github.com/full-statck-skills/speckit-skills)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Compatible-purple.svg)](https://agentskills.io)

English | [简体中文](./README.zh-CN.md)

[Introduction](#-introduction) ·
[Install](#-install) ·
[Skills](#-skills) ·
[Supported Agents](#-supported-agents) ·
[Ecosystem](#-ecosystem)

</div>

---

## 📖 Introduction

**Spec Kit Skills** is a curated collection of Agent Skills for AI coding agents, part of the [Full Stack Skills](https://github.com/partme-ai/full-stack-skills) ecosystem maintained by [PartMe.AI](https://github.com/partme-ai).

This package includes **13 skills**. Each skill is a self-contained `SKILL.md` file that AI agents load on-demand.

## 📦 Install

```bash
npx skills add full-statck-skills/speckit-skills
```

Or install specific skills:

```bash
npx skills add full-statck-skills/speckit-skills --skill <skill-name>
```

## 🎯 Skills (13)

| Skill | Description |
|-------|-------------|
| `speckit-analyze` | Perform a non-destructive cross-artifact consistency and quality analysis across spec.md, plan.md, and tasks.md after... |
| `speckit-baseline` | Generate feature specifications by analyzing existing source code. |
| `speckit-check` | Run `specify check` to verify that Spec Kit required tools (git, claude, gemini, code, cursor-agent, windsurf, qwen, ... |
| `speckit-checklist` | Generate a custom checklist for the current feature based on user requirements. |
| `speckit-clarify` | Identify underspecified areas in the current feature spec by asking up to 5 highly targeted clarification questions a... |
| `speckit-constitution` | Create or update the project constitution from interactive or provided principle inputs, ensuring all dependent templ... |
| `speckit-implement` | Execute the implementation plan by processing and executing all tasks defined in tasks.md |
| `speckit-initial` | Run `specify init` in the current or target directory to bootstrap a Spec Kit project (pull .specify/ and slash comma... |
| `speckit-install` | Install the Specify CLI on the host machine (uv tool install or uvx one-time); supports multiple OS, persistent or on... |
| `speckit-plan` | Execute the implementation planning workflow using the plan template to generate design artifacts. |
| `speckit-specify` | Create or update a feature specification from a natural language feature description. |
| `speckit-tasks` | Generate an actionable, dependency-ordered tasks.md for the feature based on available design artifacts. |
| `speckit-taskstoissues` | Convert existing tasks into actionable, dependency-ordered GitHub issues for the feature based on available design ar... |

## 🤖 Supported Agents

Works with [Claude Code](https://code.claude.com), [Codex](https://developers.openai.com/codex), [Cursor](https://cursor.com), [OpenCode](https://opencode.ai), [Gemini CLI](https://geminicli.com), [GitHub Copilot](https://github.com/features/copilot), [Windsurf](https://codeium.com/windsurf), and [70+ others](https://agentskills.io/clients).

### Claude Code Installation

**Option 1: npx skills CLI (Recommended)**

```bash
npx skills add full-statck-skills/speckit-skills
```

**Option 2: Manual Installation**

```bash
git clone https://github.com/full-statck-skills/speckit-skills.git
cp -r speckit-skills/skills/* .claude/skills/
```

For more details, see the [Claude Code Skills Guide](https://code.claude.com/docs/en/skills) and [Agent Skills Spec](https://agentskills.io/).

## 🌐 Ecosystem

| Resource | Link |
|----------|------|
| **Full Stack Skills** | [github.com/partme-ai/full-stack-skills](https://github.com/partme-ai/full-stack-skills) |
| **All Skill Groups** | [github.com/full-statck-skills](https://github.com/full-statck-skills) |
| **Agent Skills Spec** | [agentskills.io](https://agentskills.io) |
| **Skills CLI** | [github.com/vercel-labs/skills](https://github.com/vercel-labs/skills) |

## 📄 License

Apache 2.0 — see [LICENSE](LICENSE).
