# mcp-s-icons

Static icon assets served via Cloudflare Pages CDN.

## Structure

```
connectors/          # Connector icons (light theme)
connectors-dark/     # Connector icons (dark theme)
ai-hosts/            # AI agent/client icons (light theme)
ai-hosts-dark/       # AI agent/client icons (dark theme)
sso-providers/       # SSO provider icons
```

## Usage

Icons are served at:
```
https://<your-pages-domain>/connectors/{id}.svg
https://<your-pages-domain>/connectors-dark/{id}.svg
https://<your-pages-domain>/ai-hosts/{slug}.svg
https://<your-pages-domain>/ai-hosts-dark/{slug}.svg
https://<your-pages-domain>/sso-providers/{provider}.svg
```

## Adding new icons

1. Add the SVG file to the appropriate folder (both light and dark variants)
2. Commit and push — Cloudflare Pages deploys automatically

## Deployment

Connect this repo to a Cloudflare Pages project (no build command, publish directory: `/`).
# icons
