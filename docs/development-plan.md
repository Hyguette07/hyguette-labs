# Development plan

Work incrementally. A phase is finished only when the product runs, tests pass for the features that exist, and documentation matches the code.

## Phase 1 — Workspace

- [x] Create `portfolio/` layout
- [x] Root README, LICENSE, `.gitignore`
- [ ] Local Git repositories (requires Git on PATH)
- [ ] Remote GitHub repositories (requires authenticated `gh`, not an account password)

## Phase 2 — AgriPulse (complete product)

Design, then implement:

1. Architecture
2. Database
3. API contracts
4. Frontend map
5. AuthZ model
6. Backend + frontend + tests

## Phase 3 — AgriPulse hardening

Tests, Docker, CI, deployment notes.

## Phases 4–9

MoveFlow, LearnSphere, MediBridge — same quality bar, growing domain complexity, not a copy-paste of AgriPulse.

## Phase 10 — NexusOne

Different stack: FastAPI, Redis, WebSockets, workers.

## Phases 11–12 — Portfolio site

Public identity, project pages, links to repos and live demos.

## GitHub authentication (important)

GitHub **does not accept account passwords** for Git or the API.

Use one of:

- SSH key
- Fine-grained or classic Personal Access Token
- `gh auth login`

If a password was ever pasted into chat, email, or a ticket: **change it immediately**. Do not store it in this repo.
