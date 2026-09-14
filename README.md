# researchmcp.dev

Static landing for [Research MCP](https://github.com/research-mcp-hq/research-mcp).

## Cloudflare Workers & Pages settings

- **Root directory:** empty
- **Build command:** empty
- **Deploy command:** `npx wrangler deploy`
- Assets live in `public/` only (see `wrangler.toml`) — do **not** set assets to repo root (that uploads `node_modules`).

After deploy: Custom domains → `researchmcp.dev`.
