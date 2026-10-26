# Principality Building Society (principality-building-society)

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

Principality Building Society is the largest building society in Wales and the sixth largest in the United Kingdom, founded in 1860 and headquartered in Cardiff. It is a mutual, owned by and run for the benefit of its members rather than shareholders, with total assets of more than £11 billion and around 71 branches and agencies. Its products are savings, residential mortgages and investments, plus a commercial lending division. It does not offer current or payment accounts. It is authorised by the Prudential Regulation Authority and regulated by the FCA and PRA, and is a member of the Building Societies Association.

Principality is **not** one of the CMA9 banks mandated to deliver UK Open Banking, and because it holds no payment accounts it is outside the scope of the PSD2 / OBIE Read/Write standard. As of this profile it publishes no public developer portal and no confirmed OBIE Open Data endpoint. The Open Banking APIs listed below are represented as the shared OBIE standard for reference only, not as Principality-operated contracts.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/principality-building-society/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/principality-building-society/refs/heads/main/apis.yml)

## Tags

- Financial Services
- Banking
- Building Society
- Savings
- Mortgages
- Open Banking
- Open Data
- PSD2
- OBIE
- United Kingdom
- Wales
- Mutual

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

### OBIE Open Data API (Shared Standard - Unverified for Principality)

The UK Open Banking Implementation Entity (OBIE) Open Data API standard - public, unauthenticated reference data covering Branches, ATMs, Personal Current Accounts, Business Current Accounts, Unsecured SME Loans and Commercial Credit Cards. No live Principality Open Data host was confirmed; the harvested OpenAPI is the OBIE standard (Open Data API v1.3), not a Principality contract.

- **Human URL:** [https://openbankinguk.github.io/opendata-api-docs-pub/v2.4.0/](https://openbankinguk.github.io/opendata-api-docs-pub/v2.4.0/)

#### Tags

- Open Data
- Branches
- ATMs
- Reference Data

#### Properties

- [OpenAPI](openapi/obie-open-data-swagger.json)
- [Documentation](https://openbankinguk.github.io/knowledge-base-pub/standards/open-data.html)
- [API Reference](https://openbankinguk.github.io/opendata-api-docs-pub/v2.4.0/)
- [Source Code](https://github.com/OpenBankingUK/opendata-api-spec-compiled)

### OBIE Account & Transaction Information API (AIS - Standard, Out of Scope)

The OBIE Read/Write Account and Transaction Information (AISP) standard, FAPI-secured with OAuth2/OIDC, mutual-TLS and PSD2 strong customer authentication. Represented as the documented OBIE standard only - Principality offers no current or payment accounts and publishes no ASPSP developer portal.

- **Human URL:** [https://github.com/OpenBankingUK/read-write-api-specs](https://github.com/OpenBankingUK/read-write-api-specs)

#### Tags

- Account Information
- AIS
- PSD2
- FAPI

#### Properties

- [Documentation](https://github.com/OpenBankingUK/read-write-api-specs)
- [API Reference](https://openbankinguk.github.io/read-write-api-site3/)

### OBIE Payment Initiation API (PIS - Standard, Out of Scope)

The OBIE Read/Write Payment Initiation (PISP) standard, FAPI-secured with OAuth2/OIDC, mutual-TLS and PSD2 strong customer authentication. Represented as the documented OBIE standard only - Principality holds no payment accounts and operates no PISP endpoint.

- **Human URL:** [https://github.com/OpenBankingUK/read-write-api-specs](https://github.com/OpenBankingUK/read-write-api-specs)

#### Tags

- Payment Initiation
- PIS
- PSD2
- FAPI

#### Properties

- [Documentation](https://github.com/OpenBankingUK/read-write-api-specs)
- [API Reference](https://openbankinguk.github.io/read-write-api-site3/)

### OBIE Confirmation of Funds API (CBPII - Standard, Out of Scope)

The OBIE Read/Write Confirmation of Funds (CBPII) standard, FAPI-secured with OAuth2/OIDC, mutual-TLS and PSD2 strong customer authentication. Represented as the documented OBIE standard only - Principality offers no payment accounts and provides no CBPII endpoint.

- **Human URL:** [https://github.com/OpenBankingUK/read-write-api-specs](https://github.com/OpenBankingUK/read-write-api-specs)

#### Tags

- Confirmation of Funds
- CBPII
- PSD2
- FAPI

#### Properties

- [Documentation](https://github.com/OpenBankingUK/read-write-api-specs)
- [API Reference](https://openbankinguk.github.io/read-write-api-site3/)

## Common Properties

- [Website](https://www.principality.co.uk/)
- [About](https://www.principality.co.uk/home/about-us)
- [News](https://www.principality.co.uk/home/about-us/principality-news)
- [Support](https://www.principality.co.uk/home/contact-us/help-and-support)
- [Terms of Service](https://www.principality.co.uk/home/terms-of-use)
- [Privacy Policy](https://www.principality.co.uk/home/terms-of-use/privacy-and-security)
- [LinkedIn](https://www.linkedin.com/company/principality-building-society/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
