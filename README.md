# University of Copenhagen

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

The University of Copenhagen (Københavns Universitet, UCPH), founded in 1479, is Denmark's oldest and largest university and one of the leading research institutions in the Nordic region. It operates no central developer portal, no REST API program and no open-data portal — api.ku.dk and developer.ku.dk do not resolve, and data.ku.dk redirects to the homepage. What it does operate, and what makes it unusually well-covered for this cohort, is a set of standards-based machine-readable surfaces on its own infrastructure: a complete OAI-PMH 2.0 repository at curis.ku.dk serving 440,535 research records across 7,430 sets in six metadata formats; a signed SAML 2.0 identity provider at id.ku.dk registered in the Danish WAYF federation; and thirteen Darwin Core Archive feeds published by the Natural History Museum of Denmark from specify-snm.science.ku.dk and harvested by GBIF. Its public research portal researchprofiles.ku.dk is by contrast an Elsevier Pure tenancy — it CNAMEs to ku.elsevierpure.com and its REST contract is Elsevier's, api-key gated — and is recorded here as a tenant relationship rather than as the university's own API. The only source code the institution publishes is the ku-kom GitHub account: 52 repositories of TYPO3 content elements and a Bootstrap styleguide that build the ku.dk web platform.

**Areas:** Education · Higher Education · University · Research · Denmark · Nordic · Open Source · Research Data · Research Repository · Identity Federation · OAI-PMH · Open Data

## University of Copenhagen on APIs.io

Everything profiled for University of Copenhagen is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/university-of-copenhagen/](https://apis.io/providers/university-of-copenhagen/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [University of Copenhagen SAML 2.0 Identity Provider](https://apis.io/apis/university-of-copenhagen/identity-federation/) — The university publishes a signed SAML 2.0 EntityDescriptor at https://id.ku.dk/nidp/saml2/metadata (200, 24,737 bytes, text/xml), entityID…
- [Natural History Museum of Denmark Darwin Core Archive Feeds](https://apis.io/apis/university-of-copenhagen/nhmd-darwin-core/) — The Natural History Museum of Denmark, a University of Copenhagen faculty museum, publishes thirteen Darwin Core Archive exports from the Faculty of…
- [Electronic Research Data Archive (ERDA) and SCIENCE HPC Center](https://apis.io/apis/university-of-copenhagen/erda/) — ERDA (erda.ku.dk, erda.dk, sid.erda.dk) is the university's research data archive, operated by the SCIENCE HPC Center at the Faculty of Science and skinned…
- [University of Copenhagen Course Catalogue](https://apis.io/apis/university-of-copenhagen/course-catalog/) — kurser.ku.dk is the university's course catalogue, on a Copenhagen hostname running on Arcanic infrastructure (courses.loadbalancer.arcanic.dk). It serves…
- [University of Copenhagen Research Portal (Elsevier Pure tenancy)](https://apis.io/apis/university-of-copenhagen/research-portal-pure/) — researchprofiles.ku.dk is the university's public research portal and the front end of CURIS. It is an Elsevier Pure tenancy, not Copenhagen's engineering:…
- [University of Copenhagen DataCite Membership (XIZZ)](https://apis.io/apis/university-of-copenhagen/datacite-xizz/) — The university is an active DataCite member — provider symbol XIZZ, memberType consortium_organization, isActive true — with two registered repositories:…
- [University of Copenhagen Web Platform Source (ku-kom)](https://apis.io/apis/university-of-copenhagen/ku-kom-github/) — github.com/ku-kom is the university's GitHub account — a User account rather than an Organization, named "University of Copenhagen" and linked to www.ku.dk…
- [University of Copenhagen OAI PMH API](https://apis.io/apis/university-of-copenhagen/university-of-copenhagen-oai-pmh-api/) — The six OAI-PMH 2.0 verbs, all dispatched from a single path by query parameter.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [University Of Copenhagen Context](https://apis.io/jsonld/university-of-copenhagen/university-of-copenhagen-context/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [University Of Copenhagen Authentication](https://apis.io/security/university-of-copenhagen/university-of-copenhagen-authentication/)
- [University Of Copenhagen Domain Security](https://apis.io/security/university-of-copenhagen/university-of-copenhagen-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [University Of Copenhagen Plans Pricing](https://apis.io/plans/university-of-copenhagen/university-of-copenhagen-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [University Of Copenhagen Rate Limits](https://apis.io/rate-limits/university-of-copenhagen/university-of-copenhagen-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [University Of Copenhagen Finops](https://apis.io/finops/university-of-copenhagen/university-of-copenhagen-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.ku.dk/en)
- [Blog](https://news.ku.dk/)
- [GitHub](https://github.com/ku-kom)

## API Evangelist rating

**Kin Score 20.4** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 22.3 |
| Contract governance | 8.3 |
| Operational transparency | 10.5 |
| Developer ergonomics | 23.8 |
| Access clarity | 5.3 |

**Agent readiness 20.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 24.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/university-of-copenhagen/](https://apis.io/providers/university-of-copenhagen/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of Copenhagen: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/university-of-copenhagen/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
