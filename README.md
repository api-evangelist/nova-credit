# Nova Credit

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

Nova Credit is a fintech consumer-credit-data platform that gives lenders and financial institutions a single API to access unified consumer credit data from more than 26 sources — international credit bureaus, bank-transaction aggregators, payroll systems, and automated document data. Its products (Credit Passport, Cash Atlas, Income Navigator, and Eligibility Compass) let institutions underwrite qualified newcomers and thin-file applicants with translated international credit history, run cashflow-based underwriting from bank data, automate income verification with fraud detection, and speed income/asset verification for affordable housing. The developer platform exposes REST APIs over api.novacredit.com with a dedicated sandbox host, HTTP Basic to short-lived Bearer authentication, JWE-encrypted report payloads, hosted NovaConnect consent webviews, webhooks, SCIM and SSO.

**Areas:** Company · Credit Data · Consumer Credit · Credit Bureau · Income Verification · Underwriting · Fintech · Financial Services · Lending · Cash Flow Underwriting · Identity

## Nova Credit on APIs.io

Everything profiled for Nova Credit is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/nova-credit/](https://apis.io/providers/nova-credit/)** — or go straight to one of the APIs or properties below.

### APIs (1)

- [Nova Credit Platform API](https://apis.io/apis/nova-credit/nova-credit-platform-api/) — Unified REST API surface across Nova Credit's products (Credit Passport v4, Cash Atlas v2, Income Navigator v2, Eligibility Compass v1). Server-side clients…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Nova Credit Webhooks](https://apis.io/asyncapis/nova-credit/nova-credit-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [nova-credit](https://apis.io/servers/nova-credit/nova-credit/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Nova Credit Authentication](https://apis.io/security/nova-credit/nova-credit-authentication/)
- [Nova Credit Domain Security](https://apis.io/security/nova-credit/nova-credit-domain-security/)
- [Nova Credit Trust Center](https://apis.io/security/nova-credit/nova-credit-trust-center/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.novacredit.com)
- [Documentation](https://docs.novacredit.com)
- [Getting started](https://docs.novacredit.com/credit-passport-quickstart)
- [API reference](https://docs.novacredit.com/credit-passport/v4)
- [Support](https://www.novacredit.com/contact)
- [Blog](https://www.novacredit.com/corporate-blog)
- [Terms of service](https://www.novacredit.com/terms)
- [Privacy policy](https://www.novacredit.com/privacy)
- [GitHub](https://github.com/novacredit)

## API Evangelist rating

**Kin Score 39.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 39.0 |
| Contract governance | 18.2 |
| Operational transparency | 10.5 |
| Developer ergonomics | 57.1 |
| Access clarity | 28.9 |

**Agent readiness 22.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 26.3** — Insurance

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/nova-credit/](https://apis.io/providers/nova-credit/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Nova Credit: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/nova-credit/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
