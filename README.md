# ANNA Money (anna-money)

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
