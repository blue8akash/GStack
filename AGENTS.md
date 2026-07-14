# AGENTS.md

This is the model-neutral entrypoint for AI agents working in this project.

## Start Here

Read these first:

1. `AGENTS.md`
2. `.agents/README.md`
3. `README.md`
4. The nearest workflow, tracker, or playbook file for the task

## Project Mission

TODO: Describe what this project is for.

## Repo Map

TODO: List the main folders and what belongs in each one.

| Path | Purpose |
|---|---|
| `src/` | TODO |
| `docs/` | TODO |
| `tests/` | TODO |

## Non-Negotiables

- **Use internal contracts for non-trivial work** - define what must be true at completion before treating a task as done.
- Preserve project structure.
- Read local instructions before editing.
- Do not edit unrelated files.
- Do not invent evidence, data, APIs, or requirements.
- Stop when a human gate is explicitly marked.
- Report changed files and remaining gaps.

## Common Workflows

- Use `.agents/commands/` for explicit repeatable tasks.
- Use `.agents/skills/` for reusable workflow knowledge.
- Use `.agents/skills/internal-contracts/` to define success criteria and verification for meaningful tasks.
- Use `.agents/subagents/` for specialist roles.
- Use `.agents/hooks/` for deterministic guardrails.
