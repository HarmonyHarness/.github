# Harmony

Harmony is an open-source, native UI-first, local-first AI development harness meant to replace scattered Codex, Claude Code, Cursor, and OpenCode-style workflows with one governed project runtime.

It is built around a simple idea: the coding agent is not the product. The runtime around the agent is what makes AI-assisted development reliable.

Harmony gives developers a single operating system for AI-assisted software work by turning project context into durable artifacts:

- project constitutions
- staged development pipelines
- model-routing policies
- permission rules
- cost-aware execution
- validation gates
- cross-model reviews
- audit logs

The goal is to replace the tool-chaos layer: the repeated prompting, context rebuilding, permission guessing, manual model picking, disconnected reviews, and expensive agent loops. Existing models and tools can still become execution backends, but Harmony owns the workflow, policy, memory, routing, and acceptance gates.

Harmony is planned as a strictly Rust-based native application. No Node, Bun, or JavaScript runtime should be required for the core product.

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

The first milestone is a native local-first UI that opens a project, creates its project brain, runs an adversarial review pass, generates a project constitution, and turns the result into structured work for agents.

The first version should prove that a project can carry its own memory, decisions, review history, and operating rules without depending on fragile chat history.

Harmony starts as a practical native local UI for one developer, then grows into a serious runtime for safer, cheaper, more reproducible agentic software development. Automation surfaces can exist later, but they are not the primary product.
