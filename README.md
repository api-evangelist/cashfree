# Cashfree Payments (cashfree)

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

Cashfree Payments is an Indian payment gateway and banking platform providing REST APIs for payment links, subscriptions, payouts, refunds, QR codes, and banking payouts across UPI, credit and debit cards, net banking, and international payment methods. It serves over one million businesses with RBI authorisation as a Payment Aggregator and Prepaid Payment Instrument provider.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cashfree/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cashfree/refs/heads/main/apis.yml)

## Tags

- Payments
- Payouts
- UPI
- India
- Payment Gateway
- Subscriptions
- Refunds
- QR Codes
- Net Banking
- Identity Verification

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Cashfree Payment Gateway API

REST API for creating and managing payment orders, processing transactions across UPI, cards, net banking, wallets, and international payment methods, and handling refunds, settlements, and disputes.

- **Human URL:** [https://www.cashfree.com/docs/api-reference/overview](https://www.cashfree.com/docs/api-reference/overview)
- **Base URL:** `https://api.cashfree.com`

#### Tags

- Payments
- Orders
- Refunds
- Settlements
- UPI
- Cards
- Net Banking

#### Properties

- [Documentation](https://www.cashfree.com/docs/api-reference/overview)
- [Authentication](https://www.cashfree.com/docs)
- [OpenAPI](openapi/openapi-payment-gateway.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Cashfree Payouts API

REST API for automating fund transfers to beneficiaries — vendors, employees, refund recipients, loan disbursements, and insurance claims. Supports batch payouts, beneficiary management, and connected banking.

- **Human URL:** [https://www.cashfree.com/docs](https://www.cashfree.com/docs)
- **Base URL:** `https://payout-api.cashfree.com`

#### Tags

- Payouts
- Transfers
- Beneficiaries
- Batch Payouts

#### Properties

- [Documentation](https://www.cashfree.com/docs)
- [OpenAPI](openapi/openapi-payouts.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Cashfree Subscriptions API

API for creating and managing recurring payment mandates using UPI AutoPay and eNACH, including subscription plans, customer mandates, and automated billing cycles.

- **Human URL:** [https://www.cashfree.com/docs](https://www.cashfree.com/docs)
- **Base URL:** `https://api.cashfree.com`

#### Tags

- Subscriptions
- Recurring Payments
- UPI AutoPay
- eNACH

#### Properties

- [Documentation](https://www.cashfree.com/docs)

### Cashfree Secure ID (Verification) API

Identity verification and KYC API supporting PAN, Aadhaar, bank account, GST, passport, driving licence verification, face match, and video KYC for onboarding and compliance workflows.

- **Human URL:** [https://www.cashfree.com/docs](https://www.cashfree.com/docs)
- **Base URL:** `https://api.cashfree.com`

#### Tags

- Identity Verification
- KYC
- Aadhaar
- PAN
- Bank Account Verification

#### Properties

- [Documentation](https://www.cashfree.com/docs)
- [OpenAPI](openapi/openapi-verification.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Cashfree Platforms API

API for marketplace and SaaS platform operators to onboard sub-merchants, split payments, manage settlements to multiple vendors, and operate escrow arrangements.

- **Human URL:** [https://www.cashfree.com/docs](https://www.cashfree.com/docs)
- **Base URL:** `https://api.cashfree.com`

#### Tags

- Marketplaces
- Split Payments
- Merchant Onboarding
- Escrow

#### Properties

- [Documentation](https://www.cashfree.com/docs)

## Common Properties

- [Website](https://www.cashfree.com/)
- [Documentation](https://www.cashfree.com/docs)
- [Git Hub Org](https://github.com/cashfree)
- [LinkedIn](https://in.linkedin.com/company/cashfree)
- [Blog](https://www.cashfree.com/blog/)
- [Pricing](https://www.cashfree.com/payment-gateway-charges/)
- [Status Page](https://status.cashfree.com/)
- [X (Twitter)](https://x.com/gocashfree)
- [Dev Portal](https://www.cashfree.com/devstudio)
- [Support](https://www.cashfree.com/support/)
- [Contact](https://www.cashfree.com/contact-us/)
- [Plans](plans/cashfree-plans-pricing.yml)
- [Rate Limits](rate-limits/cashfree-rate-limits.yml)
- [Fin Ops](finops/cashfree-finops.yml)
- [Vocabulary](vocabulary/cashfree-vocabulary.json)
- [JSON Schema](json-schema/cashfree-payment-gateway-schemas.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cashfree-payouts-schemas.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cashfree-verification-schemas.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/cashfree-provider.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
