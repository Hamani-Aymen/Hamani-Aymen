## Aymen Hamani

Full-stack engineer, TypeScript and Node. Based in El Eulma, Algeria.

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
