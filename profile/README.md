# Harmony

Harmony is an open-source, UI-first, local-first AI development harness meant to replace scattered Codex, Claude Code, Cursor, and OpenCode-style workflows with one governed project runtime.

It is built around a simple idea: the coding agent is not the product. The runtime around the agent is what makes AI-assisted development reliable.

Harmony gives developers a single operating system for AI-assisted software work by turning project context into durable artifacts:

- project constitutions
- staged development pipelines
- model-routing policies
- permission rules
- MCP and Skill governance
- cost-aware execution
- validation gates
- cross-model reviews
- audit logs

The goal is to replace the tool-chaos layer: the repeated prompting, context rebuilding, permission guessing, manual model picking, disconnected reviews, and expensive agent loops. Existing models, APIs, CLIs, and MCP servers can still become execution backends, but Harmony owns the workflow, policy, memory, routing, and acceptance gates.

## Core Principles

- Artifacts over chat history.
- Provider-neutral by design.
- Cheap models do labor, stronger models review judgment.
- The harness owns permissions, not the model.
- Review before trust.
- Local-first before cloud-first.
- Replace fragmented agent workflows with one governed runtime.
- Build for real developer workflows, not demo theater.

## Current Focus

The first milestone is a local-first UI that opens a repo, initializes a `.harmony/` project brain, runs an adversarial council pass, generates a project constitution, and exports structured prompts and tasks for external agents.

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

Harmony starts as a practical local UI for one developer, then grows into a serious runtime for safer, cheaper, more reproducible agentic software development. CLI/headless automation can exist later, but it is not the primary product surface.
