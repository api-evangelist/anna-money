# ANNA Money (anna-money)

ANNA Money is a UK digital business account and tax app for freelancers, startups, and small businesses, marketed as "the business account that does your taxes." It is a trading name of Absolutely No Nonsense Admin Ltd (company number 10149389, Cardiff), a subsidiary of ANNA Holdings Ltd, and is positioned as a challenger to the UK high-street banks.

ANNA is **not a bank**. It is an e-money proposition: its Mastercard and e-money services are issued by PayrNet Limited, authorised by the Financial Conduct Authority for electronic money service activities (FCA FRN 900594), and its Account Information Services are provided under agency of TrueLayer (FCA FRN 901096).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/anna-money/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/anna-money/refs/heads/main/apis.yml)

## Open Banking Posture

Within UK Open Banking (OBIE / PSD2), ANNA is a **consumer / third-party provider (TPP)**, not an account-holding **ASPSP** and not one of the nine CMA9 mandated banks. ANNA does **not** publish:

- a public developer / Open Banking portal (no `developer.anna.money`, `/developers`, `/api`, or `api.anna.money`);
- an OBIE **Open Data** API (ATMs / Branches / Product reference data) — no live Open Data endpoint was found;
- OBIE **Read/Write** APIs (Account & Transaction Information / Payment Initiation / Confirmation of Funds) of its own.

Instead, ANNA *consumes* Open Banking through TrueLayer's Data and Payments APIs to power external-account aggregation, automatic VAT calculation, and QR-code "pay by bank" collection.

## Tags

- Financial Services
- Banking
- Fintech
- Business Account
- Open Banking
- PSD2
- Account Information
- Payments
- E-Money
- United Kingdom
- SME

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

No first-party public APIs are documented. ANNA exposes no developer portal, Open Data API, or OBIE Read/Write API surface of its own, so the `apis` collection is intentionally empty. ANNA's product integrations (Stripe, Xero, Shopify, Amazon, etc.) and its Open Banking connectivity are delivered through third parties (notably TrueLayer) rather than an ANNA-published API.

## Common Properties

- [Website](https://www.anna.money/)
- [Blog](https://anna.money/blog/)
- [Pricing](https://anna.money/pricing/)
- [Terms of Service](https://anna.money/terms-and-conditions/)
- [Privacy Policy](https://anna.money/privacy-policy/)
- [GitHub Organization](https://github.com/anna-money)
- [LinkedIn](https://www.linkedin.com/company/annamoneyuk)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
