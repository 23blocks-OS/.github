<p align="center">
  <img src="https://img.shields.io/badge/23blocks-Open%20Source-blue?style=for-the-badge" alt="23blocks Open Source">
</p>

<h2 align="center">Building the infrastructure for autonomous AI agents</h2>

<p align="center">
  <a href="https://ai-maestro.23blocks.com">AI Maestro Docs</a> &middot;
  <a href="https://23blocks.com">23blocks.com</a> &middot;
  <a href="https://github.com/23blocks-OS/ai-maestro/discussions">Community</a>
</p>

---

## AI Maestro — AI Agent Orchestration Platform

**AI Maestro** is an open-source platform for orchestrating AI coding agents. Give Claude Code, Aider, and Cursor agents superpowers: persistent memory, code graph queries, agent-to-agent messaging, and skills systems. Manage multiple agents across multiple machines from one dashboard.

<table>
<tr>
<td width="50%">

### Core Platform

<a href="https://github.com/23blocks-OS/ai-maestro">
<img src="https://img.shields.io/github/stars/23blocks-OS/ai-maestro?style=flat&label=ai-maestro&color=blue" alt="ai-maestro stars">
</a>

The orchestration engine. Skills system, memory search, code graph queries, agent-to-agent messaging, multi-machine support. Next.js dashboard + CLI.

**[Get Started →](https://github.com/23blocks-OS/ai-maestro)**

</td>
<td width="50%">

### Messaging Gateways

<a href="https://github.com/23blocks-OS/aimaestro-gateways">
<img src="https://img.shields.io/github/stars/23blocks-OS/aimaestro-gateways?style=flat&label=aimaestro-gateways&color=blue" alt="aimaestro-gateways stars">
</a>

Connect AI agents to **Discord, Slack, Email & WhatsApp**. Built-in prompt injection defense (34 patterns), trust-based content security, timing-safe auth.

**[Explore Gateways →](https://github.com/23blocks-OS/aimaestro-gateways)**

</td>
</tr>
</table>

### How They Work Together

```
  Discord    Slack    Email    WhatsApp        You (CLI/Dashboard)
     |         |        |         |                    |
     v         v        v         v                    v
  ┌─────────────────────────────────────┐    ┌──────────────────┐
  │      AI Maestro Gateways           │    │   AI Maestro     │
  │  Content Security · Agent Routing  │───>│   Dashboard      │
  └────────────────┬────────────────────┘    └────────┬─────────┘
                   │                                  │
                   v                                  v
          ┌──────────────────────────────────────────────────┐
          │              AI Maestro Agent Network             │
          │                                                  │
          │  Claude Code · Aider · Cursor · Custom Agents    │
          │  Memory · Skills · Code Graph · Messaging        │
          └──────────────────────────────────────────────────┘
```

**AI Maestro** manages the agents. **Gateways** connect them to the world. Users message through any platform, the gateway secures and routes it to the right agent, and the agent responds back through the same channel.

### Ecosystem

| Repository | Description |
|-----------|-------------|
| **[ai-maestro](https://github.com/23blocks-OS/ai-maestro)** | Core platform — agent orchestration, skills, memory, dashboard |
| **[aimaestro-gateways](https://github.com/23blocks-OS/aimaestro-gateways)** | Discord, Slack, Email & WhatsApp gateways with content security |
| **[ai-maestro-plugins](https://github.com/23blocks-OS/ai-maestro-plugins)** | Official plugins for Claude Code agents |
| **[frontend-sdk](https://github.com/23blocks-OS/frontend-sdk)** | TypeScript SDK for 23blocks BaaS — React hooks + Angular services |

## Contributing

We welcome contributions across all repos. Each project has its own `CONTRIBUTING.md` with setup instructions. Start with the [AI Maestro discussions](https://github.com/23blocks-OS/ai-maestro/discussions) to connect with the community.

---

<p align="center">
  <a href="https://ai-maestro.23blocks.com">Documentation</a> &middot;
  <a href="https://23blocks.com">Website</a> &middot;
  Boulder, CO
</p>
