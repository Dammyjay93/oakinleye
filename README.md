<h1 align="center">oakinleye</h1>

<h4 align="center">Claude Code plugins by <a href="https://github.com/Dammyjay93" target="_blank">Damola Akinleye</a></h4>

<p align="center">
  <a href="https://github.com/Dammyjay93/oakinleye/releases">
    <img src="https://img.shields.io/github/v/release/Dammyjay93/oakinleye" alt="Release">
  </a>
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License">
  </a>
</p>

<p align="center">
  Plugins for project management and design engineering.
</p>

---

## Quick Start

```
/plugin marketplace add Dammyjay93/oakinleye
```

Then install what you need:

```
/plugin install claudepm
/plugin install design-engineer
```

Restart Claude Code after installing.

---

## Plugins

### [claudepm](https://github.com/Dammyjay93/claudepm)

**Context that persists.**

Stop re-explaining your project every session. PRDs, epics, tasks, and decisions that carry forward — so Claude knows what you're building and what's next.

| Command | What it does |
|---------|--------------|
| `/claudepm` | Smart dispatcher |
| `/claudepm plan` | Create a project from conversation |
| `/claudepm start` | Begin working on a task |
| `/claudepm done` | Mark task complete |
| `/claudepm save` | Save session notes |
| `/claudepm status` | Show current state |

---

### [design-engineer](https://github.com/Dammyjay93/claude-design-engineer)

**Design decisions that stick.**

When you build UI, choices get made — colors, spacing, depth, typography. This plugin helps you make those choices intentionally, records them, and keeps future work consistent.

| Command | What it does |
|---------|--------------|
| `/design-engineer` | Smart dispatcher |
| `/design-engineer status` | Show your design system state |
| `/design-engineer audit <path>` | Check code against your system |
| `/design-engineer extract` | Extract patterns from existing code |

---

## Updating

```
/plugin marketplace update oakinleye
```

Restart Claude Code after updating.

---

## License

MIT License. See [LICENSE](LICENSE) for details.
