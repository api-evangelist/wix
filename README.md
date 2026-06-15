# Wix (wix)

Wix is a cloud-based web development platform that allows users to create professional websites and online businesses. The Wix developer platform provides a comprehensive REST API, JavaScript SDK, and CLI for building custom apps, headless storefronts, and site extensions across eCommerce, CRM, bookings, blog, events, and more. Developers can customize Wix sites, build marketplace apps, and integrate Wix capabilities into any frontend.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/wix/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/wix/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- CMS
- eCommerce
- Headless
- Website Builder

## Timestamps

- **Created:** 2025-02-08
- **Modified:** 2026-05-30

## APIs

### Wix REST API

The Wix REST API provides full programmatic access to all Wix platform capabilities via standard HTTP REST endpoints. The API covers eCommerce (stores, orders, catalog, payments, gift cards), bookings, CRM (contacts, members, forms), content (blog, events, restaurants, portfolio), business management (analytics, automations, calendar, notifications, payments), and account-level management (sites, domains, resellers). Authentication uses OAuth 2.0.

- **Human URL:** [https://dev.wix.com/docs/rest](https://dev.wix.com/docs/rest)

#### Tags

- CMS
- CRM
- eCommerce
- REST

#### Properties

- [Documentation](https://dev.wix.com/docs/rest)
- [Authentication](https://dev.wix.com/docs/rest/articles/getting-started/api-authentication)
- [Postman Collection](collections/wix.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wix.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Wix JavaScript SDK

The Wix JavaScript SDK provides modular npm packages for accessing Wix business solutions and site data from JavaScript code. It supports Wix Sites, Wix Apps, and Wix Headless projects. Modules cover eCommerce, bookings, CRM, blog, events, stores, payments, and more.

- **Human URL:** [https://dev.wix.com/docs/sdk](https://dev.wix.com/docs/sdk)

#### Tags

- JavaScript
- Node.js
- SDK

#### Properties

- [Documentation](https://dev.wix.com/docs/sdk)
- [SDK](https://www.npmjs.com/org/wix)
- [Postman Collection](collections/wix.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wix.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Wix Headless

Wix Headless enables developers to use Wix business solutions as a backend while building custom frontends with any framework. It provides managed commerce, CRM, and content APIs accessible from any tech stack.

- **Human URL:** [https://dev.wix.com/docs/go-headless](https://dev.wix.com/docs/go-headless)

#### Tags

- Headless
- Commerce
- Frontend

#### Properties

- [Documentation](https://dev.wix.com/docs/go-headless)
- [Postman Collection](collections/wix.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wix.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Wix Webhooks

The Wix webhook surface delivers signed JWT events to subscriber URLs registered in the Wix Dev Center. Events cover Stores (products, inventory, collections, variants), eCommerce (cart, checkout, abandoned checkout, orders, order transactions), Bookings v2 (bookings, services, legacy resource/schedule/category notifications), Members and Badges, Contacts v4 (and labels/extended fields), Forms submissions, Pricing Plans (plan and order lifecycle), Events v3 (events, RSVP, orders, reservations, ticket definitions, guests, policies), Blog posts and drafts, Coupons, Loyalty Program accounts and program, and app instance lifecycle. Payloads are JWTs that decode into a common envelope (id, entityFqdn, slug, entityId, eventTime, originatedFrom, triggeredByAnonymizeRequest) plus an event-specific payload.

- **Human URL:** [https://dev.wix.com/docs/build-apps/develop-your-app/api-integrations/events-and-webhooks/about-webhooks](https://dev.wix.com/docs/build-apps/develop-your-app/api-integrations/events-and-webhooks/about-webhooks)

#### Tags

- Webhooks
- AsyncAPI
- Events

#### Properties

- [Documentation](https://dev.wix.com/docs/build-apps/develop-your-app/api-integrations/events-and-webhooks/about-webhooks)
- [Documentation](https://dev.wix.com/docs/rest/articles/getting-started/webhook-structure)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/wix/refs/heads/main/asyncapi/wix-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/wix.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/wix.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/wix-com)
- [Website](https://www.wix.com)
- [Developer Portal](https://dev.wix.com)
- [Documentation](https://dev.wix.com/docs)
- [Getting Started](https://dev.wix.com/docs/rest/articles/getting-started/introduction)
- [Sign Up](https://users.wix.com/signin)
- [Git Hub](https://github.com/wix)
- [Tools](https://github.com/wix/wix-mcp)
- [Blog](https://dev.wix.com/blog)
- [Support](https://support.wix.com)
- [Forum](https://www.wix.com/forum/corvid-tips-questions-and-answers)
- [GitHub Organization](https://github.com/wix)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Integrations](https://www.wix.com/marketplace)
- [M C P Server](https://github.com/wix/wix-mcp)
- [Agent Skill](https://github.com/wix/skills)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
