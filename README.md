# Agentmemory MCP

Paid remote MCP for persistent AI agent memory, analytics, checkout, and search-readiness.

## Connect

- Website: https://agentmemory.space/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://agentmemory.space/mcp
- Server card: https://agentmemory.space/.well-known/mcp/server-card.json
- Official Registry name: `space.agentmemory/agentmemory-mcp`

This is a hosted Streamable HTTP MCP server. It requires an Authorization bearer token issued after checkout and token claim.

## What It Does

Agentmemory MCP exposes a fixed, read-only tool surface for AI agent memory. It is designed for agent workflows that need a hosted MCP endpoint with explicit auth, public discovery metadata, and clear data boundaries.

## Authentication

Send the paid MCP token as:

```http
Authorization: Bearer <token>
```

The token is issued by the product checkout and MCP token claim flow. Do not put tokens in issues, pull requests, logs, or screenshots.

## Files

- [server.json](./server.json) - MCP Registry descriptor.
- [Usage guide](./docs/usage.md) - setup and request examples.
- [Security notes](./docs/security.md) - auth, data boundaries, and safe-use expectations.
- [llms.txt](./llms.txt) - short machine-readable discovery summary.

## Related Project

- [OpenHuman Online](https://openhuman.online/?utm_source=github&utm_medium=readme&utm_campaign=openhuman_public_repos&utm_content=agentmemory_mcp) helps teams keep MCP rollout notes, source context, and approval memory inspectable for human-reviewed workflows.

## Status

This public repository is a docs-only distribution package for directory review and MCP discovery. The hosted server runs at https://agentmemory.space/mcp.
