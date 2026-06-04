# University of Copenhagen (university-of-copenhagen)

The University of Copenhagen (Københavns Universitet, UCPH), founded in 1479, is Denmark's oldest and largest university and one of the leading research institutions in the Nordic region, ranked #53 in the QS World University Rankings 2025. This repository catalogs the institution's public developer and API footprint as an APIs.json provider profile. UCPH does not operate a centralized public developer portal or documented open-data API program; its public technical assets are the `ku-kom` GitHub organization (TYPO3 CMS components powering ku.dk) and the Pure/CURIS research portal.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-copenhagen/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-copenhagen-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Denmark, Nordic, Open Source

## APIs

- **University of Copenhagen Research Portal (CURIS / Pure)** — Elsevier Pure research information system; OAI-PMH and Pure web service are conventional but were not publicly confirmable at review time. Docs: https://researchprofiles.ku.dk/en/
- **University of Copenhagen Web Platform (ku-kom GitHub)** — Open-source TYPO3 CMS extensions and Bootstrap styleguide for ku.dk. Docs: https://github.com/ku-kom

## Plans / Rate Limits / FinOps

- Plans: [plans/university-of-copenhagen-plans-pricing.yml](plans/university-of-copenhagen-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-copenhagen-rate-limits.yml](rate-limits/university-of-copenhagen-rate-limits.yml)
- FinOps: [finops/university-of-copenhagen-finops.yml](finops/university-of-copenhagen-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.ku.dk/en
- GitHub: https://github.com/ku-kom
- LinkedIn: https://www.linkedin.com/school/university-of-copenhagen/
- Review: [review.yml](review.yml)

## Notes

No centralized public developer portal or documented open-data API was found. The `ku-kom` GitHub org is verified as "University of Copenhagen" (52 public repos, primarily TYPO3 web components) and is source code rather than a hosted, consumable web API. The Pure/CURIS research portal (researchprofiles.ku.dk) exists but its programmatic OAI-PMH and web service endpoints returned access-restricted responses from the public internet, so no live public API base URL is asserted. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
