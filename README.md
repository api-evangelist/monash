# Monash University

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

Monash University is a public research university in Melbourne, Australia, and a member of the Group of Eight. Its genuinely institution-operated programmable footprint is small but real, and it is not where a company's would be. Its three institution-operated surfaces all belong to Monash eResearch and all resolve into Monash's own APNIC address space: the Cloud Resource Allocation and Management System (CRAMS) portal, a public documentation site for the M3/MASSIVE HPC estate, and a Shibboleth service provider federated through the Australian Access Federation. None of the three publishes an open specification, so Monash's only evidenced domain-standard conformance (SAML, Shibboleth) rests on that one federation entry. The Monash-branded identity provider at idp.monash.edu.au looks like the strongest contract here and is not Monash's: it CNAMEs to idp-cname.aaf.edu.au on Amazon address space, making it a tenant of AAF's fully managed Rapid IdP. Everything else that looks like a Monash API is a vendor platform running under a Monash hostname: the Bridges research repository is Figshare (bridges.monash.edu is a CNAME to figshare.com), research.monash.edu is Elsevier Pure, the Handbook course catalog runs on CourseLoop, and library discovery is Ex Libris Primo. Those are recorded here as tenant relationships, not as Monash contracts. No central institutional developer portal, no open data portal, and no institution-operated OAI-PMH endpoint were found.

**Areas:** Education · Higher Education · University · Research · Australia · Group of Eight · Identity Federation · Research Computing · Research Repository · Course Catalog

## Monash University on APIs.io

Everything profiled for Monash University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/monash/](https://apis.io/providers/monash/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [Monash University Identity Provider (AAF Rapid IdP tenant)](https://apis.io/apis/monash/idp/) — Monash's federated login, published as a signed SAML 2.0 EntityDescriptor at https://idp.monash.edu.au/idp/shibboleth (HTTP 200, application/xml). Declares…
- [Monash eResearch Center HPC ID (SAML Service Provider)](https://apis.io/apis/monash/eresearch-hpc-sp/) — A second Monash-operated SAML service provider, entityID https://hpc.erc.monash.edu.au/shibboleth, registered in the Australian Access Federation under…
- [CRAMS API (Cloud Resource Allocation and Management System)](https://apis.io/apis/monash/crams/) — Monash eResearch operates the Cloud Resource Allocation and Management System (CRAMS), an institutional portal for managing research cloud resource…
- [Monash eResearch Documentation (M3 / MASSIVE)](https://apis.io/apis/monash/eresearch-docs/) — Public documentation for the compute, storage, application and training services Monash eResearch runs, including the M3 and MonARCH HPC clusters.…
- [Bridges — Monash Research Repository (Figshare tenant)](https://apis.io/apis/monash/bridges/) — Monash's institutional research data repository, "Bridges", operating on the Figshare platform. bridges.monash.edu and monash.figshare.com both resolve as…
- [Monash Research Portal (Elsevier Pure tenant)](https://apis.io/apis/monash/pure/) — Monash's research outputs, profiles and publication metadata portal, running on Elsevier Pure. research.monash.edu resolves as a CNAME chain to…
- [Monash University Handbook (CourseLoop tenant)](https://apis.io/apis/monash/handbook/) — The official Monash course, unit and area-of-study catalog. The site is a Next.js application on Monash's own hostname, but its runtime configuration…
- [Monash Library Discovery (Ex Libris Primo tenant)](https://apis.io/apis/monash/library-discovery/) — Monash Library's discovery layer. search.lib.monash.edu redirects to monash.primo.exlibrisgroup.com/discovery/search?vid=61MONASH_AU:MONUI — a…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Monash Agentic Access](https://apis.io/agentic-access/monash/monash-agentic-access/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Monash University Research Repository (figshare) Vocabulary](https://apis.io/vocabularies/monash/monash-vocabulary/)

#### Collections (10)

Postman and Open Collection request collections.

- [Figshare altmetric API](https://apis.io/collections/monash/open-monash-altmetric-api/)
- [Figshare altmetric articles API](https://apis.io/collections/monash/open-monash-articles-api/)
- [Figshare altmetric authors API](https://apis.io/collections/monash/open-monash-authors-api/)
- [Figshare altmetric collections API](https://apis.io/collections/monash/open-monash-collections-api/)
- [Figshare altmetric institutions API](https://apis.io/collections/monash/open-monash-institutions-api/)
- [Figshare altmetric oauth API](https://apis.io/collections/monash/open-monash-oauth-api/)
- [Figshare altmetric other API](https://apis.io/collections/monash/open-monash-other-api/)
- [Figshare altmetric profiles API](https://apis.io/collections/monash/open-monash-profiles-api/)
- [Figshare altmetric projects API](https://apis.io/collections/monash/open-monash-projects-api/)
- [Figshare altmetric symplectic API](https://apis.io/collections/monash/open-monash-symplectic-api/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Monash Domain Security](https://apis.io/security/monash/monash-domain-security/)
- [Monash Trust Center](https://apis.io/security/monash/monash-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Monash Plans Pricing](https://apis.io/plans/monash/monash-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Monash Rate Limits](https://apis.io/rate-limits/monash/monash-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Monash Finops](https://apis.io/finops/monash/monash-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.monash.edu/)

## API Evangelist rating

**Kin Score 13.7** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 4.4 |
| Contract governance | 0.0 |
| Operational transparency | 10.5 |
| Developer ergonomics | 9.5 |
| Access clarity | 13.2 |

**Agent readiness 2.4** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 15.7** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/monash/](https://apis.io/providers/monash/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Monash University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/monash/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
