# WIN Capital Strategy
GitHub/Vercel-compatible static prototype, structured for later WordPress migration.
Open `index.html` for the homepage.
Pages: Home, Framework, Roadmap™, Resources, About, Strategy Session.
Pexels-hosted placeholder photography is used on the About/team page; replace with approved team images for production and verify applicable image licensing.
The strategy form is a front-end preview and must be connected to a real booking/form service before launch.

## Cloudflare Workers preview

This package is configured for Cloudflare's current Worker-based deployment flow.
- `wrangler.toml` tells Wrangler to serve the static site files from the repository root.
- Build command: leave blank.
- Deploy command: `npx wrangler deploy`.
- Path: `/`.
- No environment variables are required for this preview.
- This preview does not connect or change the production `thewealthyinvest.com` domain.
