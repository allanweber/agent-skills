# agent-skills

Reusable Claude Code skills and agents: plan a feature with an interview, implement the plan with worker agents, review it, audit it, and write build-in-public posts.

## Contents

- `.claude/skills/`: the skills. See [.claude/skills/README.md](.claude/skills/README.md) for the workflow.
- `.claude/agents/`: the worker and reviewer agents.
- `examples/cartogra/project.md`: a filled example.

## Use in a project

1. Copy `.claude/skills` and `.claude/agents` into the `.claude/` folder of the project.
2. Run `/project-setup`. It writes `.claude/project.md` and `AGENTS.md`, and adds `@AGENTS.md` to `CLAUDE.md`.
