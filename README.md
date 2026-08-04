# Conekta (conekta)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Conekta is a Mexico-based payment processor that lets businesses accept credit and debit cards, OXXO cash vouchers, SPEI bank transfers, Apple Pay, Google Pay, and Buy Now Pay Later through a single PCI-DSS Level 1 certified API. The platform serves the Mexican market with Spanish-language documentation, CNBV-aligned compliance, and full Orders, Charges, Customers, Subscriptions, Payment Links, Antifraud, Webhooks, Payouts, and Balances resources. Conekta publishes its OpenAPI 3.1 specification publicly under MIT license, ships official SDKs for PHP, Node.js, Python, Ruby, .NET, and Java, and offers mobile components for Android, iOS, Flutter, and React Native plus plugins for major e-commerce platforms.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/conekta/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/conekta/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Payments
- Payment Processing
- Cards
- Cash
- OXXO
- SPEI
- Mexico
- Latin America
- LATAM
- Fintech
- Subscriptions
- Antifraud
- Checkout
- BNPL
- 3D Secure

## Timestamps

- **Created:** 2026-05-24T00:00:00.000Z
- **Modified:** 2026-05-24

## APIs

### Conekta API

Conekta's REST API for accepting online payments in Mexico — credit and debit cards (Visa, Mastercard, Amex), OXXO cash vouchers, SPEI bank transfers, Apple Pay, Google Pay, and Buy Now Pay Later. The 2.2.0 API covers Orders, Charges, Customers, Plans, Subscriptions, Payment Links, Webhooks, Tokens, Payment Methods, Antifraud whitelists/blacklists, Payout Orders, Transfers, Balances, Events, and Logs, secured with bearer auth and an Accept-Language header for localized Spanish-language responses.

- **Human URL:** [https://developers.conekta.com/reference](https://developers.conekta.com/reference)
- **Base URL:** `https://api.conekta.io`

#### Tags

- Payments
- Cards
- Cash
- OXXO
- SPEI
- Mexico
- Latin America
- Subscriptions
- Antifraud
- Webhooks

#### Properties

- [Documentation](https://developers.conekta.com/reference)
- [Documentation](https://developers.conekta.com/docs/welcome)
- [Authentication](https://developers.conekta.com/reference/autenticación)
- [OpenAPI](openapi/conekta-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/conekta-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/conekta-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/conekta-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/conekta-charge-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/conekta-customer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/conekta-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/conekta-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

## Common Properties

- [Portal](https://www.conekta.com)
- [Documentation](https://developers.conekta.com)
- [Getting Started](https://developers.conekta.com/docs/welcome)
- [Getting Started](https://developers.conekta.com/docs/inicio-rápido-pagos-únicos-con-component)
- [Documentation](https://developers.conekta.com/reference)
- [Authentication](https://developers.conekta.com/reference/autenticación)
- [Errors](https://developers.conekta.com/reference/errores)
- [Errors](https://developers.conekta.com/docs/códigos-de-error-http)
- [Documentation](https://developers.conekta.com/docs/eventos-conekta)
- [Documentation](https://developers.conekta.com/docs/configurar-un-webhook)
- [Documentation](https://developers.conekta.com/docs/autenticación-webhooks)
- [Documentation](https://developers.conekta.com/docs/reintentos-de-notificación)
- [Changelog](https://developers.conekta.com/changelog/versión-220)
- [Changelog](https://developers.conekta.com/changelog/version-21)
- [GitHub Organization](https://github.com/conekta)
- [OpenAPI](https://github.com/conekta/openapi) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Tool](https://github.com/conekta/mcp-server)
- [SDK](https://github.com/conekta/conekta-php)
- [SDK](https://github.com/conekta/conekta-node)
- [SDK](https://github.com/conekta/conekta-python)
- [SDK](https://github.com/conekta/conekta-ruby)
- [SDK](https://github.com/conekta/conekta-.net)
- [SDK](https://github.com/conekta/conekta-java)
- [SDK](https://github.com/conekta/conekta-elements)
- [SDK](https://github.com/conekta/conekta-elements-react-native)
- [SDK](https://github.com/conekta/component-flutter)
- [SDK](https://developers.conekta.com/android)
- [SDK](https://developers.conekta.com/ios-skd)
- [SDK](https://developers.conekta.com/checkout-tokenizer-sdk)
- [SDK](https://developers.conekta.com/xamarin)
- [Plugins](https://github.com/conekta/ct-woocommerce-plugin)
- [Plugins](https://github.com/conekta/customer-magento-plugin)
- [Sign Up](https://panel.conekta.com)
- [Pricing](https://www.conekta.com/precios)
- [Plans](plans/conekta-plans-pricing.yml)
- [Rate Limits](rate-limits/conekta-rate-limits.yml)
- [Fin Ops](finops/conekta-finops.yml)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
