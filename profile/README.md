<p align="center">
    <img src="https://user-images.githubusercontent.com/244253/211920936-3280408e-5873-45e4-bc3c-b5a9f0bc1ad0.png#gh-light-mode-only" alt="Phase Two Logo" width="344px" height="auto" />
    <img src="https://user-images.githubusercontent.com/244253/211920950-dcc9ae85-d3b3-4029-a2dc-069c663d6ee9.png#gh-dark-mode-only" alt="Phase Two Logo" width="344px" height="auto" />
</p>

Tools to accelerate SaaS time-to-market and enterprise adoption. [Sign up for a free, hosted deployment](https://phasetwo.io/?utm_source=github&utm_medium=readme&utm_campaign=p2-inc). See the [announcement and demo video](https://phasetwo.io/blog/self-service/) and [dedicated cluster information](https://phasetwo.io/blog/dedicated-launch). :rocket:

[Phase Two](https://phasetwo.io) builds on top of [Keycloak](https://keycloak.org/), one of the most widely used open source identity and access management systems in the world. Our extensions bring multi-tenancy, audit logging, a self-service admin portal, and more to enhance Keycloak for SaaS and on-prem use cases. 

## Our extensions ![stars](https://img.shields.io/github/stars/p2-inc)
- [Organizations](https://github.com/p2-inc/keycloak-orgs) Simple multi-tenancy and role delegation via API.
- [Events](https://github.com/p2-inc/keycloak-events) Audit logging for compliance and webhooks for user and system activity notifications.
- [Magic Link](https://github.com/p2-inc/keycloak-magic-link) Passwordless authentication using links sent to email.
- [Themes](https://github.com/p2-inc/keycloak-themes) Easy login UI and email content customizations.
- [Admin UI](https://github.com/p2-inc/keycloak/tree/23.0.1_orgs_admin_ui) Keycloak Admin UI additions to administer our extensions directly from Keycloak.
- [Admin Portal](https://github.com/p2-inc/phasetwo-admin-portal) User self-management for their account and organizations.
- [IdP Wizards](https://github.com/p2-inc/idp-wizard) Identity Provider setup wizards for self-management of SSO admins and organizations.

## Our Docker images
- [Phase Two enhanced Keycloak](https://quay.io/repository/phasetwo/phasetwo-keycloak) Easy, drop-in replacement for Keycloak with all our extensions.
- [Keycloak on CockroachDB](https://quay.io/repository/phasetwo/keycloak-crdb) Our Keycloak fork that supports [CRDB](https://www.cockroachlabs.com/) for the "legacy" store.
  
## Tools
- [Keycloak theme templates](https://github.com/p2-inc/keycloak-theme-template) and free examples.
- [Framework examples](https://github.com/p2-inc/examples) for securing apps.
- [Java](https://github.com/p2-inc/phasetwo-java), [JS](https://github.com/p2-inc/phasetwo-js), [Python](https://github.com/p2-inc/phasetwo-python) Phase Two API libraries.
  
## Come visit!
- [Website](https://phasetwo.io)
- [Blog](https://phasetwo.io/blog)
- [Keycloak Guides](https://dev.to/phasetwo)
- [Documentation](https://phasetwo.io/docs/introduction)
- [APIs](https://phasetwo.io/api/phase-two-admin-rest-api)
- [Contact us](mailto:support@phasetwo.io)
