# Postgres MCP Server (fork)

A minimal fork of [awslabs/mcp](https://github.com/awslabs/mcp) containing only the
**Postgres MCP Server**. All other servers and monorepo tooling have been removed.

The server lives in [`src/postgres-mcp-server/`](src/postgres-mcp-server/) — see its
[README](src/postgres-mcp-server/README.md) for usage, configuration, and development.

## Development

```bash
cd src/postgres-mcp-server
uv sync
uv run pytest
```

Licensed under Apache-2.0 (see [LICENSE](LICENSE) / [NOTICE](NOTICE)).
