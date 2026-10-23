# Dawit Bayou Kassie

Solutions architect and full-stack engineer in Addis Ababa, Ethiopia. Three-plus years building production systems: multi-tenant SaaS, enterprise internal platforms and central identity. Strongest in Node.js, NestJS, TypeScript and PostgreSQL.

I like systems where correctness is checkable: rules enforced in the database, a test that proves each guarantee, and runbooks an operations team can follow.

**Portfolio and resume:** [dawitbkportfolio.vercel.app](https://dawitbkportfolio.vercel.app) · [LinkedIn](https://www.linkedin.com/in/dawit-b-kassie) · dawitbk01@gmail.com

## What I work on

- **At work:** architecture and delivery of a group's internal platform: a custom OpenID Connect single sign-on service with back-channel logout, a document and records system, a guest management system, offline-signed licensing and signed releases. More than 3,000 automated tests across the three systems. The source is private, so each has a public showcase with the write-up, screenshots and a live demo (below).
- **In the open:** the repositories below.

## Platform showcases (source private, access on request)

| Showcase | What it is |
| --- | --- |
| [sso-showcase](https://github.com/DawitBK/sso-showcase) | Custom OpenID Connect identity provider with an admin console and app launcher. |
| [dms-showcase](https://github.com/DawitBK/dms-showcase) | Multi-tenant document and records platform: approvals, e-signing, retention, correspondence. |
| [gms-showcase](https://github.com/DawitBK/gms-showcase) | Visitor and access-management platform: approvals, escalation, door-access credentials. |

Try them with the sandbox administrator login on the [portfolio](https://dawitbkportfolio.vercel.app/#demos).

## Open-source projects

| Project | What it is |
| --- | --- |
| [retail-os](https://github.com/DawitBK/retail-os) | Point of sale, weighted-average inventory and double-entry accounting where the stock and the books cannot disagree. |
| [jobpilot](https://github.com/DawitBK/jobpilot) | Multi-tenant job-search platform with row-level security, a transparent matching engine and a hash-chained audit trail. |
| [martronics](https://github.com/DawitBK/martronics) | E-commerce platform: catalog, cart, orders and payments ([live](https://martronics.vercel.app)). |
| [library-management-system](https://github.com/DawitBK/library-management-system) | Library back office and public catalogue: lending, holds, fines, reports ([live](https://library-management-system-lyart-pi.vercel.app)). |
| [workspace](https://github.com/DawitBK/workspace) | Control repo for a developer machine: manifest, read-only doctor and clean-up with undo. |

The first four share a stack: NestJS 12, Drizzle, PostgreSQL 18, Zod contracts that generate the OpenAPI document, Next.js 16 and Vitest.
