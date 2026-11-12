# Haulwyn site

The public product homepage for Haulwyn, moving company software, served by GitHub Pages at https://haulwyn.com. Only the marketing homepage lives here. The app and all project docs stay in the private haulwyn-os repo.

## Status

- Live. https://haulwyn.com verified responding on November 11, 2026.
- Last change: October 21, 2026 (demo requests connected to the Haulwyn support inbox).
- This repository is PUBLIC. Everything committed here is visible to anyone.

## Tech stack and how to run

- One static `index.html` plus `CNAME`. No build step.
- Run locally: `python3 -m http.server 8080` and open http://localhost:8080.
- Pushing to main publishes to the live site through GitHub Pages. Treat every merge as a production deploy.

## Done

- Product homepage and demo request form wired to the support inbox.

## Next 3 most important tasks (inferred)

1. Confirm the demo request form delivers to the support inbox (test with the Founder's approval, since it sends a message).
2. Keep homepage claims in line with what the Haulwyn app actually does today.
3. Add basic SEO details (description, social preview image) if missing.

## Standing rules (apply to every change)

- Never use em dashes anywhere in any copy, code comments, docs or commit messages.
- Never write a bare "Bay Area". Always name the specific place.
- Customer messages for this business are signed by the business support team, never in the Founder's personal voice. Brand signing rules for the Founder's other businesses live in the private haulwyn-os repo, not here.
- Every change must be committed to this GitHub repository.
- Never commit secrets: no .env files, API keys, tokens, private keys, passwords or service role keys. This repository is PUBLIC.
- Anything that deploys to production, changes DNS, spends money, or sends customer messages needs the Founder's explicit approval first.
