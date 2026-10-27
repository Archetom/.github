# Archetom

**Open-source CRM and Java application foundations.**

Reusable Java types, DDD project scaffolding, and a CRM with a dedicated backend and web application.

[简体中文](https://github.com/Archetom) · [All repositories](https://github.com/orgs/Archetom/repositories)

## Atom CRM

Customer and sales management with team collaboration. The backend and frontend build independently and share an OpenAPI contract.

| Project | Purpose | Stack |
| --- | --- | --- |
| [atom-crm](https://github.com/Archetom/atom-crm) | Customers, sales, contracts, receivables, tasks, approvals, reporting, and tenant-scoped access control | Java · Spring Boot |
| [atom-crm-web](https://github.com/Archetom/atom-crm-web) | Companion web interface for desktop and mobile | React · TypeScript · Ant Design |

[Quick start](https://github.com/Archetom/atom-crm/blob/main/README.en.md#quick-start) · [Backend deployment](https://github.com/Archetom/atom-crm/blob/main/docs/deployment.md) · [Frontend deployment](https://github.com/Archetom/atom-crm-web/blob/main/docs/deployment.md) · [API reference](https://github.com/Archetom/atom-crm/blob/main/docs/api-reference.md)

## Java foundations

| Project | Purpose |
| --- | --- |
| [Atom-Archetype](https://github.com/Archetom/Atom-Archetype) | Generate a DDD-oriented, multi-module Java project with persistence, authentication, transactions, and testing foundations |
| [Atom-Common](https://github.com/Archetom/Atom-Common) | Standalone shared types for error codes, error context, results, pagination, and lightweight timing; no Spring dependency |

Start with **Atom-Archetype** for a new Java service, or use **Atom-Common** for shared types. To run the CRM, follow the paired **atom-crm** and **atom-crm-web** guides. Each repository documents its own versions, requirements, and license.

## Contributing

Use the relevant repository's Issues for bug reports and feature discussions, and Pull Requests for code and documentation improvements.

- [Backend contribution guide](https://github.com/Archetom/atom-crm/blob/main/CONTRIBUTING.md)
- [Frontend contribution guide](https://github.com/Archetom/atom-crm-web/blob/main/CONTRIBUTING.md)
- Report vulnerabilities privately according to the relevant security policy: [backend](https://github.com/Archetom/atom-crm/blob/main/SECURITY.md) · [frontend](https://github.com/Archetom/atom-crm-web/blob/main/SECURITY.md).
