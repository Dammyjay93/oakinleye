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
  A marketplace of Claude Code plugins for project management, design engineering, and more.
</p>

---

## Quick Start

```
/plugin marketplace add Dammyjay93/oakinleye
```

Then install plugins:

```
/plugin install claudepm
/plugin install design-engineer
```

Restart Claude Code after installing.

---

## Plugins

### [claudepm](https://github.com/Dammyjay93/claudepm)

**Real project management for Claude Code.**

Stop re-explaining context every session. PRDs, epics, and decisions that persist — so Claude always knows the project, the plan, and what's next.

| Command | Description |
|---------|-------------|
| `/claudepm` | Smart dispatcher |
| `/claudepm plan` | Create project from conversation |
| `/claudepm start` | Begin working on a task |
| `/claudepm done` | Mark task complete |
| `/claudepm save` | Save session notes |
| `/claudepm status` | Show current state |

---

### [design-engineer](https://github.com/Dammyjay93/design-engineer)

**Design engineering for Claude Code.**

Craft, direction, memory, enforcement. Build interfaces with intention, maintain consistency across sessions, catch drift before it compounds.

| Command | Description |
|---------|-------------|
| `/ds-engineer` | Smart dispatcher |
| `/ds-engineer status` | Show design system state |
| `/ds-engineer audit <path>` | Check code against system |
| `/ds-engineer extract` | Extract patterns from code |
| `/ds-engineer generate` | Generate tokens.css, tailwind preset |

---

## Updating

```
/plugin marketplace update oakinleye
```

Restart Claude Code after updating.

---

## License

MIT License. See [LICENSE](LICENSE) for details.
