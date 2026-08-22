# Monash University (monash)

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

Monash University is a public research university in Melbourne, Australia, and a member of the Group of Eight, ranked #42 in the QS World University Rankings 2025. This repository catalogs Monash's public, machine-readable footprint as an [APIs.json](https://apisjson.org) profile.

Re-profiled **2026-08-19** under the university pipeline, which settles **who operates each surface** before saving anything. A university is a federation of buyers, not a producer, and Monash is a clean example: of eight surfaces catalogued here, **three are institution-operated and five are tenant relationships on platforms Monash does not run**.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/monash/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=monash-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party
- University — Public Research University

## Tags

Education, Higher Education, University, Research, Australia, Group of Eight, Identity Federation, Research Computing, Research Repository, Course Catalog

## Operator attribution

Operator was settled by **IP ownership**, not hostname. A Monash hostname is not evidence that Monash runs the thing behind it.

| Surface | Host | Operator | Basis |
|---|---|---|---|
| CRAMS | crams-api.erc.monash.edu | **institution** | 118.138.238.174 — MONASHUNI-NET3 (APNIC) |
| eResearch docs (M3/MASSIVE) | docs.erc.monash.edu | **institution** | 130.194.250.205 — MONASHUNI-AU (APNIC) |
| eResearch HPC ID (SAML SP) | hpc.erc.monash.edu.au | **institution** | 118.138.238.241 — MONASHUNI-NET3 (APNIC) |
| Identity Provider | idp.monash.edu.au | tenant | CNAMEs to `idp-cname.aaf.edu.au`, resolves to Amazon (AT-88-Z) — AAF **Rapid IdP** managed service |
| Bridges research repository | bridges.monash.edu | tenant | CNAME to `figshare.com` |
| Research portal | research.monash.edu | tenant | CNAME to `monash.elsevierpure.com` |
| Handbook (course catalog) | handbook.monash.edu | tenant | `API_DOMAIN` = `api-ap-southeast-2.prod.courseloop.com` |
| Library discovery | search.lib.monash.edu | tenant | 302 to `monash.primo.exlibrisgroup.com` |

## APIs

**Institution-operated** — real surfaces, none of which publishes an open specification:

- **CRAMS (Cloud Resource Allocation and Management System)** — Monash eResearch's research cloud allocation portal. HTTP 200 with a real Django application shell; `/api/`, `/swagger/` and `/docs/` all 404.
  - Portal: https://crams-api.erc.monash.edu/
- **Monash eResearch Documentation (M3 / MASSIVE)** — compute, storage, applications and training docs for the M3 and MonARCH HPC clusters. `massive.org.au` redirects here.
  - Docs: https://docs.erc.monash.edu/
- **Monash eResearch Center HPC ID** — a Shibboleth SAML service provider registered in the Australian Access Federation under Organization "Monash University". Monash's only evidenced education-regime domain-standard conformance (SAML, Shibboleth) rests on this one entry.
  - AAF aggregate: https://md.aaf.edu.au/aaf-metadata.xml

**Tenant relationships** — real institutional facts; the contracts belong to the platform, not to Monash, and are deliberately not saved here:

- **Monash Identity Provider** — signed SAML 2.0 metadata, the most complete machine-readable contract in this profile, served from AAF's fully managed Rapid IdP. https://idp.monash.edu.au/idp/shibboleth
- **Bridges** — Monash's research data repository on Figshare. https://bridges.monash.edu/
- **Monash Research Portal** — Elsevier Pure. https://research.monash.edu/
- **Monash Handbook** — course/unit catalog on CourseLoop. https://handbook.monash.edu/
- **Library Discovery** — Ex Libris Primo, view code `61MONASH_AU:MONUI`. https://search.lib.monash.edu/

## Identity Federation

- [identity-federation/monash-identity-federation.yml](identity-federation/monash-identity-federation.yml) — all five AAF entities naming Monash, each with an operator verdict
- [identity-federation/monash-idp-saml-metadata.xml](identity-federation/monash-idp-saml-metadata.xml) — the fetched SAML 2.0 EntityDescriptor

## Conformance

- [conformance/monash-conformance.yml](conformance/monash-conformance.yml) — `education` regime standards. 2 conformant (saml, shibboleth, institution-operated), 2 tenant-operated only, 3 vendor-operated, 7 not found.

## Security

- [security/monash-domain-security.yml](security/monash-domain-security.yml)
- [security/monash-trust-center.yml](security/monash-trust-center.yml)

## Plans

- [plans/monash-plans-pricing.yml](plans/monash-plans-pricing.yml)

## Rate Limits

- [rate-limits/monash-rate-limits.yml](rate-limits/monash-rate-limits.yml)

## FinOps

- [finops/monash-finops.yml](finops/monash-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-19

## Common Properties

- Website: https://www.monash.edu/
- Identity Federation: [identity-federation/monash-identity-federation.yml](identity-federation/monash-identity-federation.yml)
- Research Computing: https://docs.erc.monash.edu/
- Research Repository: https://bridges.monash.edu/
- Library Catalog: https://search.lib.monash.edu/
- Course Catalog: https://handbook.monash.edu/
- AI Policy: https://www.monash.edu/ai/tools-training-and-resources/ai-policies-and-guidelines
- Research: https://research.monash.edu/
- GitHub: https://github.com/monash-university
- Source Code: https://github.com/MonashStudentInnovation
- LinkedIn: https://www.linkedin.com/school/monash-university/

## Notes

All cataloged URLs were probed on 2026-08-19 and no endpoints were fabricated.

**What changed in this re-profile.** The June 2026 pass attributed a Figshare contract to Monash, saved as ten tag-split OpenAPIs plus derived schemas, examples, rules, vocabulary, scopes and an agentic-access profile. That same Figshare contract was attributed to 24 other universities, and the eight top-scoring universities in the catalog were all scoring the identical document. Those artifacts have been removed. Monash's Figshare relationship is retained as a **tenant** surface, because it is a real institutional fact — but the contract scores against Figshare, where it belongs.

**The IdP is the interesting case.** `idp.monash.edu.au` publishes exactly what a strong institutional surface should look like: signed SAML 2.0 metadata, application/xml, own hostname, own certificate name, `shibmd:Scope monash.edu.au`, registered in a national federation. It was recorded as institution-operated on that evidence, and then reversed within the same run when DNS showed it CNAMEd to `idp-cname.aaf.edu.au` and whois put the IPs in Amazon's AT-88-Z. AAF's Rapid IdP is a fully managed identity provider that AAF says more than half its member organisations now use. `idp.unimelb.edu.au` shows the same shape; `idp.uq.edu.au` resolves into UQ's own address space, so the pattern discriminates.

**Blocked surfaces.** `www.monash.edu` returns HTTP 403 with `cf-mitigated: challenge` to non-browser clients — a Cloudflare managed challenge. It is live for browsers; the block is a limitation of our probe, not a finding about Monash. `bridges.monash.edu` returns HTTP 202 with `x-amzn-waf-action: challenge`.

**Absences that are real.** `data.monash.edu`, `api.monash.edu` and `developer.monash.edu` do not resolve. No open data portal, no institution-operated OAI-PMH endpoint, and no central developer portal were found. The `monash-university` GitHub org exists but has zero public repositories; `MonashStudentInnovation` has six. `TheBetterHandbookAPI` is community-built and not an official Monash service.

## Maintainers

- Kin Lane — kin@apievangelist.com
