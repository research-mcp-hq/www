# researchmcp.dev

Static landing for [Research MCP](https://github.com/research-mcp-hq/research-mcp).

## Cloudflare Workers & Pages settings

- **Root directory:** empty
- **Build command:** empty
- **Deploy command:** `npx wrangler deploy`
- Assets live in `public/` only (see `wrangler.toml`) — do **not** set assets to repo root.

After deploy: Custom domains → `researchmcp.dev`.

## Routes

- `/` — pitch, happy/FAIL examples, buy, install
- `/docs/` — contract summary + schema links
- `/docs/tools/` — when to call / when not
- `/pricing/` — packs + meters + Stripe Payment Links
- `/changelog/`, `/legal/`
- `/llms.txt`, `/llms-full.txt`
- `/.well-known/mcp/server-card.json`
