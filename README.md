# University of Copenhagen (university-of-copenhagen)

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

The University of Copenhagen (Københavns Universitet, UCPH), founded in 1479, is Denmark's oldest and largest university and one of the leading research institutions in the Nordic region. This repository catalogs the institution's public developer and API footprint as an APIs.json provider profile.

UCPH operates **no central developer portal, no REST API program and no open-data portal** — `api.ku.dk` and `developer.ku.dk` do not resolve, and `data.ku.dk` redirects to the homepage. What it does operate is a set of standards-based machine-readable surfaces on its own infrastructure: a complete OAI-PMH 2.0 repository at `curis.ku.dk`, a signed SAML 2.0 identity provider at `id.ku.dk` registered in the Danish WAYF federation, and thirteen Darwin Core Archive feeds published by the Natural History Museum of Denmark from `specify-snm.science.ku.dk` and harvested by GBIF.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-copenhagen/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-copenhagen-api-evangelist&utm_content=repo

## Type

- university / Public Research University — Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Denmark, Nordic, Open Source, Research Data, Research Repository, Identity Federation, OAI-PMH, Open Data, Research Computing, Course Catalog, Biodiversity

## Who operates what

A university is a federation of buyers, not a producer, so every surface below carries an `x-operator` saying **who runs the thing**, not merely where we fetched it.

### Institution-operated

- **CURIS OAI-PMH Repository Interface** — `https://curis.ku.dk/ws/oai`. Complete, unauthenticated OAI-PMH 2.0. All six verbs answer 200. `verb=Identify` names the repository "University of Copenhagen", adminEmail `curis@adm.ku.dk`, owner org unit "KU Forskning og Informationssikkerhed". Six metadata formats, 7,430 sets, 440,535 records in `oai_dc` over `openaire_cris_publications`. Declares OpenAIRE CERIF compatibility 1.1.1. Host resolves to 130.226.237.49, a University of Copenhagen address. Spec: [openapi/university-of-copenhagen-curis-oai-pmh-openapi.yml](openapi/university-of-copenhagen-curis-oai-pmh-openapi.yml)
- **SAML 2.0 Identity Provider** — `https://id.ku.dk/nidp/saml2/metadata`, a signed EntityDescriptor served at 200. Three ku.dk SAML entities are registered in WAYF, Denmark's national federation and eduGAIN participant.
- **NHMD Darwin Core Archive feeds** — thirteen collection exports served from `specify-snm.science.ku.dk` and harvested by GBIF. The only bulk open-data downloads the university serves from a host it operates.
- **ERDA + SCIENCE HPC Center** — `erda.ku.dk` and `hpc.ku.dk`. Real research-computing surfaces with no machine-readable contract; data moves over WebDAVS/SFTP/FTPS.
- **Course catalogue** — `kurser.ku.dk`. Human-readable pages plus a 471KB `sitemap.xml`. No JSON API; `?format=json` returns the same HTML.
- **ku-kom on GitHub** — 52 public repositories of TYPO3 content elements and a Bootstrap styleguide that build the ku.dk web platform. Source code, not a callable service.

### Tenant (their data, a vendor's contract)

- **Research Portal, `researchprofiles.ku.dk`** — an **Elsevier Pure tenancy**, not Copenhagen's engineering. The hostname CNAMEs `researchprofiles.ku.dk` → `ku.elsevierpure.com` → `eu.prod.elsevierpure.com` → Cloudflare, and the REST contract at `/ws/api/524/openapi.yaml` is Elsevier's document, returned 401 without an api-key. **No Pure specification is saved under this slug.** The institution's own harvesting interface over the same data is the CURIS OAI-PMH entry above.
- **DataCite membership (XIZZ)** — an active consortium organization with two registered repositories, `xizz.curis` and `dk.ku`. An account on a shared platform; no DataCite contract is saved here.

## Standards conformance (Kin Score `education` regime)

Confirmed by probe, with evidence in [conformance/university-of-copenhagen-conformance.yml](conformance/university-of-copenhagen-conformance.yml): **oai-pmh**, **saml**, **orcid**, **datacite**; **crossref** partial (Copenhagen republishes publisher-minted DOIs but mints its own via DataCite). Not found and not claimed: shibboleth, scim, lti, oneroster, ed-fi, caliper, qti.

## Artifacts

- OpenAPI: [openapi/university-of-copenhagen-curis-oai-pmh-openapi.yml](openapi/university-of-copenhagen-curis-oai-pmh-openapi.yml) ([pristine copy](openapi/_original/university-of-copenhagen-curis-oai-pmh-openapi.yml)) — [OpenAPI 3.1](https://spec.openapis.org/oas/latest.html)
- Examples / probe record: [examples/university-of-copenhagen-curis-oai-pmh-examples.yml](examples/university-of-copenhagen-curis-oai-pmh-examples.yml)
- Authentication: [authentication/university-of-copenhagen-authentication.yml](authentication/university-of-copenhagen-authentication.yml)
- Errors: [errors/university-of-copenhagen-oai-pmh-errors.yml](errors/university-of-copenhagen-oai-pmh-errors.yml)
- Conformance: [conformance/university-of-copenhagen-conformance.yml](conformance/university-of-copenhagen-conformance.yml)
- Vocabulary: [vocabulary/university-of-copenhagen-vocabulary.yml](vocabulary/university-of-copenhagen-vocabulary.yml)
- Plans: [plans/university-of-copenhagen-plans-pricing.yml](plans/university-of-copenhagen-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-copenhagen-rate-limits.yml](rate-limits/university-of-copenhagen-rate-limits.yml)
- FinOps: [finops/university-of-copenhagen-finops.yml](finops/university-of-copenhagen-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-30

## Common Properties

- Website: https://www.ku.dk/en
- GitHub: https://github.com/ku-kom
- LinkedIn: https://www.linkedin.com/school/university-of-copenhagen/
- News: https://news.ku.dk/
- Research Repository: https://researchprofiles.ku.dk/
- Identity Federation: https://id.ku.dk/nidp/saml2/metadata
- Research Computing: https://hpc.ku.dk/
- Course Catalog: https://kurser.ku.dk/
- Review: [review.yml](review.yml)

## Notes

Re-profiled 2026-08-30 under the API Evangelist university pipeline, which settles operator attribution before saving any contract.

The June 2026 profile stated that Copenhagen's "programmatic OAI-PMH and web service endpoints returned access-restricted responses from the public internet, so no live public API base URL is asserted." **That was wrong, and it was wrong because the wrong host was probed.** `researchprofiles.ku.dk/ws/oai` does return 500 and redirects to `/error/` — but the harvesting endpoint is not on the portal host. `curis.ku.dk/ws/oai` answers every OAI-PMH verb at 200, unauthenticated, and always has.

The correction runs in both directions. Two further institution-operated surfaces were found that had never been catalogued (the SAML identity-provider metadata and the NHMD Darwin Core feeds), and one previously-credited surface was demoted: `researchprofiles.ku.dk` was carried as institution-operated on the strength of its `ku.dk` hostname, and DNS resolution shows it is an Elsevier Pure tenancy.

Negative results are recorded as findings, not gaps. `www.ku.dk` answers 200 with an identical 121,943-byte homepage for **every** unknown path, so `llms.txt`, `/.well-known/security.txt`, `/.well-known/ai.txt` and `/en/ai` are soft-404s and none is credited as a published artifact. `skema.ku.dk` returns 503; `federation.ku.dk` is registered in WAYF but firewalled from the public internet. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
