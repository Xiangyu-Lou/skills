# Skills Collection

A curated collection of skills for AI agents and vibe coding tools (Claude Code, Cursor, etc.).

## What is a Skill?

Skills are reusable prompt templates that extend what AI coding tools can do. When invoked, a skill expands into a full, structured prompt — turning a short slash command into a complex, repeatable workflow.

## Structure

```
skills/
├── README.md
└── <skill-name>.md   # each skill is a single markdown file
```

Each skill file follows this format:

```markdown
---
name: skill-name
description: One-line description of what the skill does
---

<skill content / prompt template>
```

## Usage

### Claude Code

Copy a skill file into your project's `.claude/` directory (or `~/.claude/` for global use), then invoke it with:

```
/skill-name
```

### Other Tools

Most skills are plain markdown prompt templates — paste them directly into your tool's system prompt or custom instructions section.

## Skills

| Skill | Description |
|-------|-------------|
| *(more coming soon)* | |

## Contributing

Found a useful skill or wrote one yourself? PRs are welcome.

1. One skill per file
2. Keep the frontmatter format consistent
3. Include a brief description of when and why to use it

## License

MIT
