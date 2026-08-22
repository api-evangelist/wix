# Wix (wix)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
