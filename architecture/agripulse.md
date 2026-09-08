# AgriPulse — portfolio-level view

See the product architecture in `agriculture-platform/docs/architecture.md`.

```
Farmer / Officer / Admin
        │
        ▼
Next.js (AgriPulse UI)
        │ JWT REST
        ▼
Spring Boot API  ── Open-Meteo
        │
        ▼
PostgreSQL (prod) / H2 (local demo)
```

Memorable capability: **Pulse Score** + weather-aware irrigation advice.
