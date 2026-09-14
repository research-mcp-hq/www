# researchmcp.dev — Cloudflare Pages stub

**Owner:** Growth (copy) · Code & PRs (repo wire) · Deploy (DNS + Pages)

## Deploy
1. Cloudflare Pages project from this folder (or `research-mcp-hq/www` after Code moves it).
2. Build: none — static `index.html`.
3. Custom domain: `researchmcp.dev` (+ `www` redirect optional).
4. After live: Growth swaps websiteUrl on Registry / X / listings (hold until Deploy says DNS green).

## Do not
- Point Smithery `websiteUrl` here until HTTPS resolves.
- Put API on this domain in v1 (API stays `research-mcp-mhh.fly.dev`).

## Cloudflare deploy settings

If the dashboard requires a deploy command (Workers & Pages create flow):

- **Build command:** leave empty (or `exit 0`)
- **Deploy command:** `npx wrangler deploy`
- **Root directory:** `/` or empty
- Do **not** put `/` in the build or deploy command fields

`wrangler.toml` serves this folder as static assets under project name `researchmcp`.
