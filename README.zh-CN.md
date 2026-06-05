<div align="center">

# speckit-skills

**Spec Kit spec-driven development workflow skills**

[![GitHub](https://img.shields.io/badge/github-full--statck--skills%2Fspeckit-skills-green.svg)](https://github.com/full-statck-skills/speckit-skills)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-兼容-purple.svg)](https://agentskills.io)

[English](./README.md) | 简体中文

[简介](#-简介) ·
[安装](#-安装) ·
[技能列表](#-技能列表) ·
[支持的智能体](#-支持的智能体) ·
[生态](#-生态)

</div>

---

## 📖 简介

**Spec Kit 技能** 是一组 AI 编码智能体技能，属于 [Full Stack Skills](https://github.com/partme-ai/full-stack-skills) 生态，由 [PartMe.AI](https://github.com/partme-ai) 维护。

本包包含 **13 个技能**。每个技能是一个独立的 `SKILL.md` 文件，AI 智能体按需加载。

## 📦 安装

```bash
npx skills add full-statck-skills/speckit-skills
```

或按需安装特定技能：

```bash
npx skills add full-statck-skills/speckit-skills --skill <skill-name>
```

## 🎯 技能列表 (13)

| 技能 | 描述 |
|------|------|
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

## 🤖 支持的智能体

适用于 [Claude Code](https://code.claude.com)、[Codex](https://developers.openai.com/codex)、[Cursor](https://cursor.com)、[OpenCode](https://opencode.ai)、[Gemini CLI](https://geminicli.com)、[GitHub Copilot](https://github.com/features/copilot)、[Windsurf](https://codeium.com/windsurf) 及 [70+ 其他智能体](https://agentskills.io/clients)。

## 🌐 生态

| 资源 | 链接 |
|------|------|
| **Full Stack Skills** | [github.com/partme-ai/full-stack-skills](https://github.com/partme-ai/full-stack-skills) |
| **全部技能组** | [github.com/full-statck-skills](https://github.com/full-statck-skills) |
| **Agent Skills 规范** | [agentskills.io](https://agentskills.io) |
| **Skills CLI** | [github.com/vercel-labs/skills](https://github.com/vercel-labs/skills) |

## 📄 许可证

Apache 2.0 — 详见 [LICENSE](LICENSE)。
