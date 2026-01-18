# TextBurst

Monorepo scaffold for TextBurst — a bulk SMS + payments platform using Termii (SMS) and Palmpay (payments).

What’s included
- frontend/: Next.js + TypeScript admin UI (contacts, composer, campaigns)
- backend/: Node.js API (skeleton services for Termii + Palmpay)
- worker/: job worker using Redis/Bull for sending SMS and retries
- docker-compose.yml for local Postgres + Redis + services
- .env.example with required env vars
- CI workflow skeleton

Next steps
1. Create an empty GitHub repo `GrayHat-John/textburst` (public).
2. Tell me when it exists and I will push the initial scaffold.
3. Add secrets (Termii + Palmpay) to GitHub Secrets or your server environment per .env.example.

Security
- Do NOT share API keys in chat. Use GitHub Secrets or your host’s secret manager.
