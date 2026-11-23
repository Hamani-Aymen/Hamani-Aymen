## Aymen Hamani

Full-stack engineer, TypeScript and Node. Based in El Eulma, Algeria.
Willing to relocate to Algiers.

**Most of my work is not here.** I build the ordering platform at a pharmaceutical
distributor, and it lives in private company repositories. What that work involves:

- **110 REST endpoints across 18 business domains** in TypeScript and Node: JWT auth,
  role-based access, request validation, PostgreSQL repositories and migrations
- **436 passing unit and integration tests** across 55 suites
- **Domain-driven design and a hexagonal architecture**: domain logic isolated from
  transport and persistence, so SAP, PostgreSQL and HTTP are adapters rather than
  assumptions baked through the codebase
- **GitHub Actions continuous delivery to six environments** across three production
  sites: type-check gate, atomic symlink releases, PM2 zero-downtime reload,
  health-checked deploys, and a rollback that refuses to fire when the database
  schema is ahead of the previous release
- **Prometheus, Grafana, Alertmanager**, health and readiness endpoints, structured
  logs with request IDs
- **SAP Business One Service Layer and SAP HANA XS** integrated into Node services
- **30 architecture decision records** and incident postmortems, because the reasoning
  matters more than the diff

**You can use the product instead of reading about it:**
[pharmainvest.dz/client](https://pharmainvest.dz/client), log in with username
`demo@pharmainvest.com` / password `demo123`. Also on
[Google Play](https://play.google.com/store/apps/details?id=com.pharma.investapp)
and the [App Store](https://apps.apple.com/app/pharma-invest-spa/id6749502347).
Mock checkout, so there is no live customer data behind it.

**Stack:** TypeScript, Node.js, Express (production); NestJS (private side project);
PostgreSQL, Angular, Flutter/Dart, Docker, NGINX, PM2, Prometheus, GitHub Actions.

[LinkedIn](https://www.linkedin.com/in/aymen-hamani-214506233/) ·
hamaniaymen123@gmail.com
```

## Follow-ups

- **DDD and hexagonal architecture are confirmed real** by the owner (2026-09-02) and defensible in interview, so they are claimed here. **They are missing from the Storyous CV**, which is already submitted and cannot be changed. Add them to the next CV build and use them as an interview asset: an engineer who asks "how do you structure a Node service" gets a concrete answer instead of a general one.
- The bio line on the profile itself already reads "Software Engineer @PharmaInvest-SPA | Backend Software Engineer | Node.js & TypeScript | DDD & Hexagonal Architecture", which is consistent with the above.
- Be ready to walk through one ADR that shows the port/adapter boundary. The SAP integration is the strongest example, since it is the clearest case of an external system that had to stay an adapter.
