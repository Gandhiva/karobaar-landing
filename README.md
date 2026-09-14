# Karobaar landing

Vite + React + TanStack Router SPA, served as Cloudflare static assets.

- `karobaar.gandivalabs.com/` — product landing
- `karobaar.gandivalabs.com/privacy-policy` — complete existing privacy policy
- `gandivalabs.com/in` — Gandiva Labs company page

```sh
npm ci
npm run build
npm run deploy
```

The primary CTA is `tel:+918303807051`. The company domain uses Gandiva Labs branding; the product domain uses Karobaar branding. Four companies currently use the product internally; public launch and voice-agent integration are upcoming. Cloudflare custom domains and SPA fallback are configured in `wrangler.jsonc`.
