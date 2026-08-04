# Stifel Financial

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

Stifel Financial is a financial services holding company whose subsidiaries provide securities brokerage, investment banking, trading, investment advisory, and related financial services to individual investors, corporations, and government entities. Stifel bank accounts are accessible via open banking data aggregators including Plaid and Finicity (Mastercard) for third-party financial applications.

**URL:** [https://raw.githubusercontent.com/api-evangelist/stifel-financial/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/stifel-financial/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Fortune 500:** Yes

## Tags

- Finance
- Wealth Management
- Investment Banking
- Open Banking
- Financial Services

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-02

## APIs

### Stifel Bank Finicity Integration

Stifel Bank account data accessible via Finicity (Mastercard) open banking aggregation API.

**Human URL:** [https://fintable.io/coverage/banks/United%20States/4445_stifel](https://fintable.io/coverage/banks/United%20States/4445_stifel)

### Stifel Bank Plaid Integration

Stifel Trust Company account data accessible via Plaid open banking aggregation API.

**Human URL:** [https://fintable.io/coverage/banks/United%20States/31584_stifel-trust-company-client-point](https://fintable.io/coverage/banks/United%20States/31584_stifel-trust-company-client-point)

### Stifel Wealth Tracker

Client-facing portfolio management portal for monitoring investment accounts.

**Human URL:** [https://www.stifel.com/Tracker/Support/Overview](https://www.stifel.com/Tracker/Support/Overview)

## JSON-LD

| Context | Description |
|---|---|
| [stifel-financial-context.jsonld](json-ld/stifel-financial-context.jsonld) | JSON-LD context mapping Stifel financial account vocabulary to schema.org |

## Vocabulary

| Vocabulary | Description |
|---|---|
| [stifel-financial-vocabulary.yml](vocabulary/stifel-financial-vocabulary.yml) | Domain vocabulary for wealth management and open banking |

## Notes

Stifel Financial does not maintain a public developer API portal. Account data is accessible to authorized third-party applications through open banking aggregators:

- **Finicity (Mastercard Open Banking)**: [developer.mastercard.com/open-banking-us/documentation](https://developer.mastercard.com/open-banking-us/documentation/)
- **Plaid**: [plaid.com/docs](https://plaid.com/docs/)

## Common Properties

- [Website](https://www.stifel.com)
- [Technology](https://www.choosestifel.com/technology/)
- [Open Banking Tracker](https://www.openbankingtracker.com/provider/stifel-bank-personal/apis)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
