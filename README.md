# mannutech — Claude Code plugin marketplace

A [Claude Code plugin marketplace](https://code.claude.com/docs/en/plugins). Currently hosts one plugin: **ContextSpin** — live context in your Claude Code status bar (weather, Hacker News, AI research papers, dev articles, PRs awaiting review, CI failures, incidents, meetings), pulled from tools you already run.

![ContextSpin composing live merge requests beneath your own statusline](screenshots/statusline.svg)

## Add this marketplace

In Claude Code:

```
/plugin marketplace add mannutech/claude-plugins
/plugin install contextspin@mannutech
```

## Plugins

| Plugin | What it does |
|---|---|
| [`contextspin`](https://github.com/mannutech/contextspin-plugin) | Auto-configures a never-empty, live status bar. Wraps the [`contextspin`](https://www.npmjs.com/package/contextspin) npm package. |

## Don't want the marketplace?

ContextSpin installs in one line without any plugin:

```bash
curl -fsSL https://raw.githubusercontent.com/mannutech/contextspin/main/install.sh | bash
```

## License

MIT.
