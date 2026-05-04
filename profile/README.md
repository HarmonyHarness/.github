# Harmony

Harmony is an open-source, local-first AI development harness for coordinating models, agents, tools, permissions, reviews, and project memory.

It is built around a simple idea: the model is not the product. The system around the model is what makes AI-assisted development reliable.

Harmony helps developers keep multi-agent work structured by turning project context into durable artifacts:

- project constitutions
- staged development pipelines
- model-routing policies
- permission rules
- MCP and Skill governance
- cost-aware execution
- validation gates
- cross-model reviews
- audit logs

The goal is not to replace Codex, Claude Code, Cursor, OpenCode, MCP servers, or model providers. The goal is to give them a shared project brain so they can work together without losing context, drifting from decisions, or burning expensive model calls on work a cheaper model could safely handle.

## Core Principles

- Artifacts over chat history.
- Provider-neutral by design.
- Cheap models do labor, stronger models review judgment.
- The harness owns permissions, not the model.
- Review before trust.
- Local-first before cloud-first.
- Build for real developer workflows, not demo theater.

## Current Focus

The first milestone is a CLI that initializes a `.harmony/` project brain, runs an adversarial council pass, generates a project constitution, and exports structured prompts and tasks for external agents.

Minimum useful output:

```txt
.harmony/
  project.yaml
  constitution.md
  council/verdict.yaml
  rules/
  stages/
  tasks/
  prompts/
  reviews/
```

Harmony starts as a practical local tool for one developer, then grows into a serious runtime for safer, cheaper, more reproducible agentic software development.
