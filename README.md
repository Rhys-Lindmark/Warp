# Warp

[Open the factory](https://ai.rhyslindmark.com/warp) · [Dashboard](https://platform.warp.dev/q3JLYzeswNuT47rYZz0Qyj/dashboard)

Warp software factory connected to **Rhys-Lindmark/Warp**. The dashboard requires your Warp account and team access.

## Configuration

- Team: rhyslindmark's Team
- Factory: Warp
- Agents: Foreman, Triage, Spec, Implement, Review
- Model: Warp's automatic model selection (`auto-genius`)
- Optional Slack and issue-tracker integrations: not connected
- Factory definition: Warp-managed; this repository is the factory's working repository, not its definition repository

## Send work

Open the dashboard, start a new chat, select **Warp**, and describe a small change with clear acceptance criteria. Review the resulting pull request and validation before merging.

## Use from Codex

Factory MCP is registered as `warp-factory` on the setup computer. For a different computer:

```sh
codex mcp add warp-factory --url https://app.warp.dev/api/v1/mcp/factory
codex mcp login warp-factory
```

Complete the browser authorization. Keep credentials in the client's credential store, outside this repository. If tools are unavailable after adding the server, restart Codex and reopen the same chat.

Ask your connected coding agent to send work to the **Warp** factory. The factory ID is `q3JLYzeswNuT47rYZz0Qyj`.

[Factory MCP documentation](https://docs.warp.dev/factories/factory-mcp/) · [Warp quickstart](https://docs.warp.dev/factories/quickstart/)
