# Hyguette Labs — Engineering Portfolio

**Engineering technology that solves problems that matter.**

This workspace is the engineering story of [Isimbi Hyguette](mailto:isimbihyguette07@gmail.com): six independently deployable systems, each solving a real operational problem, connected by a single portfolio site.

It is not a folder of CRUD tutorials. Each product has a named problem, a designed architecture, an API, a database, tests, and a path to production.

## The story

```
Agriculture  →  Transportation  →  Education  →  Healthcare  →  Multi-domain systems  →  Public identity
   AgriPulse        MoveFlow         LearnSphere     MediBridge         NexusOne            Portfolio
```

| Phase | Product | Domain | What makes it memorable |
| --- | --- | --- | --- |
| 1 | [AgriPulse](./agriculture-platform) | Agriculture | Weather-aware **Pulse Score** and advisory engine for smallholder farms |
| 2 | [MoveFlow](./transport-platform) | Transportation | Delay-aware trip intelligence and digital tickets |
| 3 | [LearnSphere](./education-platform) | Education | Performance-based study recommendations, not just course catalogs |
| 4 | [MediBridge](./health-platform) | Healthcare | Privacy-first appointment coordination with audit logging |
| 5 | [NexusOne](./advanced-project) | Emergency coordination | Real-time multi-domain dispatch (FastAPI, Redis, WebSockets) |
| 6 | [Developer portfolio](./portfolio-website) | Identity | The public narrative that ties the systems together |

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

Suggested GitHub repositories:

- `agripulse`
- `moveflow`
- `learnsphere`
- `medibridge`
- `nexusone`
- `developer-portfolio`

## How to work this workspace

Build in the order documented in [docs/development-plan.md](./docs/development-plan.md). Do not start five backends at once.

**Never commit secrets.** Copy `.env.example` to `.env` in each project. JWT secrets, database passwords, and API keys stay local or in the host’s secret manager.

## Author

**Isimbi Hyguette**  
Software engineer — Hyguette Labs  
Email: isimbihyguette07@gmail.com

## License

MIT. See [LICENSE](./LICENSE).
