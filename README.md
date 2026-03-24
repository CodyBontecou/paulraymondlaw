# The Law Office of Paul J. Raymond, LLC

Website for Paul J. Raymond's general practice law firm in Buena Vista, Colorado.

## Stack

- Static HTML/CSS/JS — no build step
- Hosted on [Cloudflare Pages](https://pages.cloudflare.com/)
- Auto-deployed on every push to `main`

## Development

Open `index.html` directly in a browser, or serve locally:

```bash
npx serve .
```

## Deployment

Pushes to `main` automatically deploy to Cloudflare Pages via GitHub Actions.

Requires two repository secrets:
- `CLOUDFLARE_API_TOKEN` — API token with Cloudflare Pages edit permissions
- `CLOUDFLARE_ACCOUNT_ID` — `e4265f322e6380ee832b83ad45e3e8c0`
