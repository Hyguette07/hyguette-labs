# AgriPulse project report

Status: **implemented locally** (Phases 2–3 of the portfolio plan).

Verified:

- Backend unit and integration tests: 7 passing (`mvn test`)
- Frontend pulse label test passing (`npx vitest run`)
- Auth: register, login, JWT, 401 without token
- Disease engine and rainfall irrigation advisory tests

Not yet: public cloud URLs, Git remotes (Git is not on PATH on this machine), Docker runtime (Docker CLI not installed).

Demo accounts (local seed): `farmer@agripulse.local`, `officer@agripulse.local`, `admin@agripulse.local` with `APP_SEED_PASSWORD`.
