# Did You Ask Copilot?

A tiny satirical-but-serious page (in the spirit of [nohello.net](https://nohello.net)) reminding
teammates to ask their AI assistant before rubber-ducking a coworker.

Live at: `aka.ms/didyouaskcopilot` or wherever this repo's GitHub Pages site ends up.

## Deployment

This repo deploys automatically to GitHub Pages via `.github/workflows/pages.yml` on every push to `main`.

One-time setup in the repo:

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment → Source**, select **GitHub Actions**.
4. Push to `main` (or run the workflow manually) to trigger the first deploy.

No build step — it's a single static `index.html`.
