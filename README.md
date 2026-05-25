# Conekta (conekta)
Conekta is a Mexico-based payment processor that lets businesses accept credit and debit cards, OXXO cash vouchers, SPEI bank transfers, Apple Pay, Google Pay, and Buy Now Pay Later through a single PCI-DSS Level 1 certified API. The platform serves the Mexican market with Spanish-language documentation, CNBV-aligned compliance, and full Orders, Charges, Customers, Subscriptions, Payment Links, Antifraud, Webhooks, Payouts, and Balances resources. Conekta publishes its OpenAPI 3.1 specification publicly under MIT license, ships official SDKs for PHP, Node.js, Python, Ruby, .NET, and Java, and offers mobile components for Android, iOS, Flutter, and React Native plus plugins for major e-commerce platforms.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/conekta/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Payments, Payment Processing, Cards, Cash, OXXO, SPEI, Mexico, Latin America, LATAM, Fintech, Subscriptions, Antifraud, Checkout, BNPL, 3D Secure

## Timestamps

- **Created:** 2026-05-24
- **Modified:** 2026-05-24

## Payment Methods

| Method | Rate | Notes |
|---|---|---|
| Cards (Visa / Mastercard / Amex) | 3.4% + $3.00 MXN + IVA | Debit and credit, domestic and international |
| OXXO cash voucher | 2.6% + $3.00 MXN + IVA | $5.40 MXN minimum; $7–$10 MXN POS surcharge |
| SPEI bank transfer | $12.50 MXN + IVA | Flat fee per transfer |
| BNPL (provider A / B) | 4% / 6% + IVA | On top of base rates |
| MSI (Meses Sin Intereses) | 3.5% — 26.5% + IVA | Varies by issuer and number of months |
| Apple Pay / Google Pay | Card rate | Tokenized via Checkout / mobile SDKs |

No setup or monthly platform fees — merchants only pay on successful charges. See [`plans/conekta-plans-pricing.yml`](plans/conekta-plans-pricing.yml).

## APIs

### Conekta API
Conekta's REST API for accepting online payments in Mexico — credit and debit cards (Visa, Mastercard, Amex), OXXO cash vouchers, SPEI bank transfers, Apple Pay, Google Pay, and Buy Now Pay Later. The 2.2.0 API covers Orders, Charges, Customers, Plans, Subscriptions, Payment Links, Webhooks, Tokens, Payment Methods, Antifraud whitelists/blacklists, Payout Orders, Transfers, Balances, Events, and Logs, secured with bearer auth and an Accept-Language header for localized Spanish-language responses.

**Human URL:** [https://developers.conekta.com/reference](https://developers.conekta.com/reference)
**Base URL:** `https://api.conekta.io`

- [Documentation — API Reference](https://developers.conekta.com/reference)
- [Documentation — Welcome](https://developers.conekta.com/docs/welcome)
- [Authentication](https://developers.conekta.com/reference/autenticación)
- [OpenAPI](openapi/conekta-api-openapi.yml)
- [JSON Schema — Order](json-schema/conekta-order-schema.json)
- [JSON Schema — Charge](json-schema/conekta-charge-schema.json)
- [JSON Schema — Customer](json-schema/conekta-customer-schema.json)
- [JSON-LD](json-ld/conekta-context.jsonld)
- [Spectral Rules](rules/conekta-rules.yml)
- [Naftiko Capability — Orders](capabilities/orders.yaml)
- [Naftiko Capability — Charges](capabilities/charges.yaml)
- [Naftiko Capability — Customers](capabilities/customers.yaml)
- [Naftiko Capability — Subscriptions](capabilities/subscriptions.yaml)
- [Naftiko Capability — Webhooks](capabilities/webhooks.yaml)
- [Naftiko Capability — Antifraud](capabilities/antifraud.yaml)
- [Naftiko Capability — Payment Links](capabilities/payment-links.yaml)
- [Naftiko Capability — Payout Orders](capabilities/payout-orders.yaml)

## SDKs and Components

| Repository | Language | Purpose |
|---|---|---|
| [conekta/openapi](https://github.com/conekta/openapi) | OpenAPI 3.1 | Canonical API specification (MIT) |
| [conekta/conekta-php](https://github.com/conekta/conekta-php) | PHP | Server SDK |
| [conekta/conekta-node](https://github.com/conekta/conekta-node) | Node.js / TypeScript | Server SDK |
| [conekta/conekta-python](https://github.com/conekta/conekta-python) | Python | Server SDK |
| [conekta/conekta-ruby](https://github.com/conekta/conekta-ruby) | Ruby | Server SDK |
| [conekta/conekta-.net](https://github.com/conekta/conekta-.net) | .NET (C#) | Server SDK |
| [conekta/conekta-java](https://github.com/conekta/conekta-java) | Java | Server SDK |
| [conekta/conekta-elements](https://github.com/conekta/conekta-elements) | Kotlin Multiplatform | Card tokenization UI |
| [conekta/conekta-elements-react-native](https://github.com/conekta/conekta-elements-react-native) | React Native | Mobile checkout component |
| [conekta/component-flutter](https://github.com/conekta/component-flutter) | Flutter / Dart | Mobile checkout component |
| [conekta/ct-woocommerce-plugin](https://github.com/conekta/ct-woocommerce-plugin) | PHP | WooCommerce integration |
| [conekta/customer-magento-plugin](https://github.com/conekta/customer-magento-plugin) | PHP | Magento integration |
| [conekta/mcp-server](https://github.com/conekta/mcp-server) | Python | Model Context Protocol server |

## Integration Surfaces

- **Checkout Component** — Conekta's recommended embedded JavaScript checkout
- **Direct API** — Server-to-server REST integration using bearer auth
- **Payment Links** — Hosted, shareable checkout URLs
- **Mobile SDKs** — Android, iOS, Flutter, React Native, Xamarin
- **E-commerce plugins** — Shopify, VTEX, Magento, WooCommerce, PrestaShop, Tiendanube

## Operational Artifacts

- [Plans / Pricing](plans/conekta-plans-pricing.yml) — API Commons Plans 0.1
- [Rate Limits](rate-limits/conekta-rate-limits.yml) — API Commons Rate Limits 0.1
- [FinOps](finops/conekta-finops.yml) — FinOps Framework / FOCUS-aligned
- [Vocabulary](vocabulary/conekta-vocabulary.yml) — Domain term glossary

## Examples

- [Create order — card](examples/conekta-create-order-card-example.json)
- [Create order — OXXO cash](examples/conekta-create-order-oxxo-example.json)
- [Create order — SPEI transfer](examples/conekta-create-order-spei-example.json)
- [Create webhook endpoint](examples/conekta-create-webhook-example.json)

## Maintainers

- **Kin Lane** — [apievangelist.com](https://apievangelist.com) — info@apievangelist.com
