<p align="center">
    <img src="https://user-images.githubusercontent.com/244253/211920936-3280408e-5873-45e4-bc3c-b5a9f0bc1ad0.png#gh-light-mode-only" alt="Phase Two Logo" width="344px" height="auto" />
    <img src="https://user-images.githubusercontent.com/244253/211920950-dcc9ae85-d3b3-4029-a2dc-069c663d6ee9.png#gh-dark-mode-only" alt="Phase Two Logo" width="344px" height="auto" />
</p>

<p align="center"><b>Hosted Keycloak, plus the extensions that make it work for SaaS.</b></p>

<p align="center">
  <a href="https://phasetwo.io/?utm_source=github&utm_medium=profile&utm_campaign=p2-inc">Website</a> •
  <a href="https://phasetwo.io/docs/introduction">Docs</a> •
  <a href="https://phasetwo.io/pricing/?utm_source=github&utm_medium=profile&utm_campaign=p2-inc">Pricing</a> •
  <a href="https://phasetwo.io/blog">Blog</a> •
  <a href="mailto:support@phasetwo.io">Contact</a>
</p>

[Phase Two](https://phasetwo.io/?utm_source=github&utm_medium=profile&utm_campaign=p2-inc) builds on [Keycloak](https://keycloak.org/), one of the most widely used open source identity and access management systems in the world. Our open source extensions add multi-tenancy, passwordless login, audit logging and webhooks, a self-service admin portal, and more — and we run all of it for you as a managed service.

> [!TIP]
> **Try Phase Two free for 30 days.** Every Starter cluster includes a 30-day free trial with all of our extensions built in. [Start your trial →](https://phasetwo.io/pricing/?utm_source=github&utm_medium=profile&utm_campaign=p2-inc)

## 🤖 Build with AI agents

[Keycloak Skills](https://github.com/p2-inc/keycloak-skills) teach Claude Code, Cursor and Codex how to configure Keycloak and Phase Two: passwordless login (magic link, email OTP, passkeys), organization-restricted login, corporate SSO by email domain, social and enterprise identity providers, and cluster provisioning. They connect to our hosted MCP server, so your agent can check its work against your live deployment.

```sh
claude plugin marketplace add p2-inc/keycloak-skills
claude plugin install phasetwo@keycloak-skills
```

The plugin connects the MCP server for you. To connect just the MCP server:

```sh
claude mcp add --transport http keycloak https://mcp.phasetwo.io/mcp
```

[Read the launch post →](https://phasetwo.io/blog/keycloak-skills-mcp-launch)

## 🧩 Our extensions ![stars](https://img.shields.io/github/stars/p2-inc)

**Multi-tenancy and SSO**
- [Organizations](https://github.com/p2-inc/keycloak-orgs) — Single-realm multi-tenancy and role delegation via API.
- [IdP Wizards](https://github.com/p2-inc/idp-wizard) — Identity provider setup wizards so organization admins can configure their own SSO.
- [Admin Portal](https://github.com/p2-inc/phasetwo-admin-portal) — User self-management for their account and organizations.

**Authentication**
- [Magic Link](https://github.com/p2-inc/keycloak-magic-link) — Passwordless authentication with links sent by email, plus email OTP.
- [Atomic Auth Flows](https://github.com/p2-inc/keycloak-atomic-auth-flows) — Config as code to safely update authentication flows.

**Events and email**
- [Events](https://github.com/p2-inc/keycloak-events) — Audit logging for compliance and webhooks for user and system activity.
- [Transactional Email](https://github.com/p2-inc/keycloak-transactional-email) — Send Keycloak's email through a transactional email provider.

**Look and feel**
- [Themes](https://github.com/p2-inc/keycloak-themes) — Easy login UI and email customization, plus Admin UI additions for managing our extensions directly from Keycloak.

**Operations**
- [Redis Cache](https://github.com/p2-inc/keycloak-redis-cache) — Replace Keycloak's Infinispan distributed caches with Redis or Valkey.
- [KMS](https://github.com/p2-inc/keycloak-kms) — Keep realm signing keys in a cloud KMS instead of in the database.

**Migration**
- [User Migration](https://github.com/p2-inc/keycloak-user-migration) — Migrate users from legacy systems as they log in.
- [WorkOS Migrator](https://github.com/p2-inc/workos-keycloak-migrator) — Move from WorkOS to Keycloak.

## 🐳 Run it yourself

- [Phase Two enhanced Keycloak](https://quay.io/repository/phasetwo/phasetwo-keycloak) — Drop-in replacement for Keycloak with all our extensions ([source](https://github.com/p2-inc/phasetwo-containers)).
- [Keycloak on CockroachDB](https://quay.io/repository/phasetwo/keycloak-crdb) — Our Keycloak fork with [CockroachDB](https://www.cockroachlabs.com/) support.
- [Terraform provider](https://registry.terraform.io/providers/p2-inc/phasetwo/latest) — Manage Phase Two hosted clusters and realms as code ([source](https://github.com/p2-inc/terraform-provider-phasetwo)).

## 🛠️ Tools

- [Java](https://github.com/p2-inc/phasetwo-java), [JS](https://github.com/p2-inc/phasetwo-js) and [Python](https://github.com/p2-inc/phasetwo-python) Phase Two API libraries.
- [Keycloak theme template](https://github.com/p2-inc/keycloak-theme-template), [email theme template](https://github.com/p2-inc/keycloak-email-theme-template) and [shadcn Keycloakify starter](https://github.com/p2-inc/keycloakify-starter-shadcn).
- [Framework examples](https://github.com/p2-inc/examples) for securing apps.

## 👋 Come visit

- [Website](https://phasetwo.io/?utm_source=github&utm_medium=profile&utm_campaign=p2-inc)
- [Documentation](https://phasetwo.io/docs/introduction)
- [APIs](https://phasetwo.io/api/phase-two-admin-rest-api)
- [Blog](https://phasetwo.io/blog)
- [Keycloak guides](https://dev.to/phasetwo)
- [Contact us](mailto:support@phasetwo.io)
