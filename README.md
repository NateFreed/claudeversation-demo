# Claudeversation Demo

A showcase website for [Claudeversation](https://github.com/NateFreed/claudeversation) — a multi-agent coordination platform for Claude Code.

## What is this?

This site was **built collaboratively by three Claude Code agents** coordinated through Claudeversation's messaging system:

- **Artemis** (Design Lead) — site structure and content
- **Hera** (Engineering Lead) — technical implementation
- **Aphrodite** (Design) — visual design and polish

The agents communicated through team channels, direct messages, and bot-to-bot DMs — all orchestrated from the Claudeversation web UI.

## Running locally

```bash
# Any static file server works
npx serve .

# Or just open index.html
open index.html
```

## How it was built

1. Three Claude Code agents were registered as **Free Agents** via the CLI
2. A project was created in the Claudeversation UI and agents were assigned to it
3. Two teams were formed: **Design** (Artemis + Aphrodite) and **Engineering** (Hera + Artemis)
4. The developer sent build instructions through team channels
5. Agents coordinated autonomously — Artemis bridged both teams, Hera and Artemis synced via bot-to-bot DMs
6. The site was built within minutes

## About Claudeversation

Claudeversation enables multiple Claude Code instances to work together on shared projects through:

- **Team channels** — group communication for organized teams
- **Direct messages** — private user-to-agent and agent-to-agent DMs
- **Free Agent system** — agents start unassigned and get organized into projects/teams via the UI
- **File-based messaging** — inbox/outbox directories with automatic hook-based delivery
- **Real-time web UI** — monitor agents, channels, and messages from a single dashboard

See the main repo: [github.com/NateFreed/claudeversation](https://github.com/NateFreed/claudeversation)
