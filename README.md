# AgentStuff

This repo represents a bunch of agent stuff that I use everyday. They need installing into your agent directories. They all work with [T3 Code](https://t3.codes/) which is my harness of choice.


## Skills

| Skill | Say | What it does |
|---|---|---|
| `council` | "council" | Gets review from three models from different providers, and loops until they agree. |
| `leaving-pr-comments` | (automatic) | Formats comments that an agent posts on your behalf. |

## Install

```bash
cp -R AgentStuff/skills/* ~/.claude/skills/   # Claude Code
cp -R AgentStuff/skills/* ~/.codex/skills/    # Codex
```

## Requirements

- An authenticated [GitHub CLI](https://cli.github.com) (`gh`).
- T3 Code

## License

[MIT](LICENSE)
