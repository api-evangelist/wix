# Wix GraphQL API

The Wix GraphQL API exposes the full Wix platform as a single unified GraphQL schema, providing an alternative to the REST API for querying and mutating Wix site data. It is well-suited for applications with complex data requirements that need to combine multiple queries into a single request, retrieve only specific fields from larger objects, or reduce round-trips to the server. The API covers all core Wix domains including blog, bookings, CRM contacts, data collections, eCommerce (carts, checkouts, orders), events, members, pricing plans, stores (products, collections, inventory), business tools, auth management, and redirects.

Authentication is handled via the same OAuth 2.0 mechanism used by the Wix REST API. Requests must include either an API key (`Authorization: <API_KEY>`) or a bearer access token (`Authorization: Bearer <ACCESS_TOKEN>`) along with a `Content-Type: application/json` header. Site owners must grant the required permissions to your application through the Wix Dev Center before your app can access their data via GraphQL. The Wix JavaScript SDK also exposes a `graphql()` helper method on the initialized client, which accepts a GraphQL query or mutation string and returns a Promise resolving to the result, with optional support for type inference via GraphQL Code Generator.

The API is organized into domain-namespaced query and mutation fields (for example, `blogPostsV3Posts`, `ecomOrdersV1`, `crmContactsV4Contact`, `dataItemsV2DataItems`), each reflecting the versioned service that backs it. As of 2025, the API is in **Developer Preview** and may be subject to breaking changes. Webhooks are not available through the GraphQL layer; use the REST webhook surface instead.

**Endpoint:** `https://www.wixapis.com/graphql`

**Documentation:** https://dev.wix.com/docs/sdk/articles/work-with-the-sdk/wix-graph-ql-api

**References:**
- Documentation: https://dev.wix.com/docs/sdk/articles/work-with-the-sdk/wix-graph-ql-api
- Documentation: https://dev.wix.com/docs/build-apps/develop-your-app/api-integrations/graph-ql
- GettingStarted: https://dev.wix.com/docs/sdk/articles/set-up-a-client/wix-graph-ql-api
- APIReference: https://www.wix.com/graphql-public-server/docs/
