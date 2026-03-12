# icons

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
https://icons.webrix.workers.dev/connectors/{id}.svg
https://icons.webrix.workers.dev/connectors-dark/{id}.svg
https://icons.webrix.workers.dev/ai-hosts/{slug}.svg
https://icons.webrix.workers.dev/ai-hosts-dark/{slug}.svg
https://icons.webrix.workers.dev/sso-providers/{provider}.svg
```

## Adding new icons

1. Add the SVG file to the appropriate folder (both light and dark variants)
2. Commit and push — Cloudflare Pages deploys automatically
