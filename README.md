# Project Zoe — Documentation

This repo holds the Mintlify documentation for [Project Zoe](https://projectzoe.org), an open-source church relationship management system (RMS).

The docs are automatically deployed to **[docs.projectzoe.org](https://docs.projectzoe.org)** on every push to `main`.

## What's covered

- Getting started and local setup
- Core concepts: multi-tenancy, group hierarchy, authentication
- Feature guides: people/CRM, groups, events, attendance, finance, reports, tasks
- Developer guides: server setup, client setup, database migrations, contributing
- API reference: authentication, contacts, groups, events

## Local preview

Install the Mintlify CLI and run a local preview:

```bash
npm i -g mint
mint dev
```

The preview runs at **http://localhost:3000**.

## Making changes

1. Edit or add `.mdx` files in this repo.
2. Update the `navigation` in `docs.json` if you add a new page.
3. Push to `main` — Mintlify deploys automatically.

## Related repos

- [project-zoe-server](https://github.com/kanzucodefoundation/project-zoe-server) — NestJS API
- [project-zoe-client](https://github.com/kanzucodefoundation/project-zoe-client) — React client
