# Textures skill

Textures (textures.dev) is the hover-texture library for agents. This is its agent skill: hover textures for websites, installed by your coding agent. `SKILL.md` tells an agent how to find and install a Texture (MCP, the shadcn registry, or a markdown fetch) and, after the first one ships, lets it offer to remember Textures for the project with a four-line rules block. The offer is one question, asked once; nothing is written without a yes, and the block is removed by deleting it.

The same file is served at https://textures.dev/skill.md.

## Codex

Codex reads skills from `.agents/skills` (repo) or `~/.agents/skills` (user). Install this one with the skill installer inside Codex:

```
$skill-installer https://github.com/Textures-dev/skill
```

or copy `skills/textures/` into `.agents/skills/textures/`. The same recipe as a rules file for CLAUDE.md, AGENTS.md and Cursor: https://textures.dev/agents. Claude Code users: `/plugin marketplace add Textures-dev/plugins`, then `/plugin install textures@textures`.
