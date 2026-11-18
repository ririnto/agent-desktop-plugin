# Agent Desktop MCP

Observe and control desktop applications through the upstream [Agent Desktop](https://github.com/vercel-labs/agent-desktop) MCP server.

## Runtime

Install Bun with `bunx` on PATH and Node.js 22.19+ on 22.x or 24.6+ on 24.x, or a newer supported major. The plugin runs `bunx agent-desktop mcp` with system certificate support.
Use `desktop_status` to check adapter health and `desktop_permissions` to see which OS permissions are available.

## Install

### Claude Code

```sh
claude plugin marketplace add ririnto/agent-desktop-plugin
claude plugin install agent-desktop-plugin@agent-desktop-plugin
```

### Codex

```sh
codex plugin marketplace add ririnto/agent-desktop-plugin
codex plugin add agent-desktop-plugin@agent-desktop-plugin
```

If you already use the Sinon marketplace in either client, install `agent-desktop-plugin@sinon`.

### Cursor

In **Customize**, choose **From GitHub Repository**, enter `https://github.com/ririnto/agent-desktop-plugin`, and install **Agent Desktop MCP**.
Start a new Agent conversation after installation.

Report vulnerabilities through [private vulnerability reporting](https://github.com/ririnto/agent-desktop-plugin/security/advisories/new).
