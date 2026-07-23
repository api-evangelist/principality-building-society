# Principality Building Society (principality-building-society)

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
