# Agent Quickstart

- Run tooling from repository root; banner templates live under `templates/`.
- `npm run dev` spins a local preview; avoid `npm run build` during active agent sessions ([OpenAI Codex](https://developers.openai.com/codex/cloud)).
- Claude Code reads project memory from `CLAUDE.md` and picks up custom slash commands/sub-agents from `.claude/` ([Claude Code docs](https://github.com/ericbuess/claude-code-docs/blob/main/docs/memory.md)).
- Cursor consumes `.cursorrules` at the root for project-specific rules ([Cursor docs](https://github.com/getcursor/docs/blob/main/context/rules-for-ai.mdx)).
- All templates must respect Google DV360, Adform, and Xandr HTML5 clickTag standards located in the repo rules.

