# Hyguette Labs — Engineering Portfolio

**Engineering technology that solves problems that matter.**

This workspace is the engineering story of [Isimbi Hyguette](mailto:isimbihyguette07@gmail.com): six independently deployable systems, each solving a real operational problem, connected by a single portfolio site.

It is not a folder of CRUD tutorials. Each product has a named problem, a designed architecture, an API, a database, tests, and a path to production.

## The story

```
Agriculture  →  Transportation  →  Education  →  Healthcare  →  Multi-domain systems  →  Public identity
   AgriPulse        MoveFlow         LearnSphere     MediBridge         NexusOne            Portfolio
```

| Phase | Product | Domain | GitHub |
| --- | --- | --- | --- |
| 1 | [AgriPulse](./agriculture-platform) | Agriculture | https://github.com/Hyguette07/agripulse |
| 2 | [MoveFlow](./transport-platform) | Transportation | https://github.com/Hyguette07/moveflow |
| 3 | [LearnSphere](./education-platform) | Education | https://github.com/Hyguette07/learnsphere |
| 4 | [MediBridge](./health-platform) | Healthcare | https://github.com/Hyguette07/medibridge |
| 5 | [NexusOne](./advanced-project) | Emergency coordination | https://github.com/Hyguette07/nexusone |
| 6 | [Developer portfolio](./portfolio-website) | Identity | https://github.com/Hyguette07/developer-portfolio |

## Technology growth

The stack is intentional, not repetitive.

1. **Java 17 + Spring Boot** — security, JPA, REST, OpenAPI
2. **Next.js + TypeScript + Tailwind CSS** — production frontends
3. **PostgreSQL** — relational design, constraints, indexes
4. **Docker + GitHub Actions** — reproducible builds and CI
5. **Python FastAPI + Redis + WebSockets** — async, cache, real-time
6. **Architecture documentation** — diagrams, trade-offs, deployment

## Workspace

```
portfolio/
├── README.md
├── LICENSE
├── .gitignore
├── docs/                    # Cross-project engineering docs
├── architecture/            # Portfolio-level diagrams
├── screenshots/
├── github-profile/          # GitHub profile README (pin this on GitHub)
├── agriculture-platform/    # AgriPulse
├── transport-platform/      # MoveFlow
├── education-platform/      # LearnSphere
├── health-platform/         # MediBridge
├── advanced-project/        # NexusOne
└── portfolio-website/       # Public site
```

Each product is independently deployable and intended as its own Git repository.

GitHub repositories:

- https://github.com/Hyguette07/agripulse
- https://github.com/Hyguette07/moveflow
- https://github.com/Hyguette07/learnsphere
- https://github.com/Hyguette07/medibridge
- https://github.com/Hyguette07/nexusone
- https://github.com/Hyguette07/developer-portfolio
- Workspace: https://github.com/Hyguette07/hyguette-labs

## Status

| Product | Demo | GitHub |
| --- | --- | --- |
| AgriPulse | API 8081 · UI 3000 | [agripulse](https://github.com/Hyguette07/agripulse) |
| MoveFlow | API 8082 · UI 3002 | [moveflow](https://github.com/Hyguette07/moveflow) |
| LearnSphere | API 8083 · UI 3003 | [learnsphere](https://github.com/Hyguette07/learnsphere) |
| MediBridge | API 8084 · UI 3004 | [medibridge](https://github.com/Hyguette07/medibridge) |
| NexusOne | API 8085 · UI 3005 | [nexusone](https://github.com/Hyguette07/nexusone) |
| Portfolio site | UI 3000 | [developer-portfolio](https://github.com/Hyguette07/developer-portfolio) |

Local Java APIs use the `local` profile (H2). Seed password is `APP_SEED_PASSWORD` (default `ChangeMe123!`).

## How to work this workspace

Each product is its own git repository. Copy `.env.example` to `.env` before Docker or production runs.

**Never commit secrets.** Copy `.env.example` to `.env` in each project. JWT secrets, database passwords, and API keys stay local or in the host’s secret manager.

## Author

**Isimbi Hyguette**  
Software engineer — Hyguette Labs  
Email: isimbihyguette07@gmail.com

## License

MIT. See [LICENSE](./LICENSE).
