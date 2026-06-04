# University of Sydney (university-of-sydney)

The University of Sydney is Australia's first university (founded 1850) and is ranked #32 in the QS World University Rankings 2025. This repository catalogs its public developer/API footprint as an APIs.json provider profile for the API Evangelist network. The institution does not operate a central public developer portal; its API surface is concentrated in library, repository, and student systems that are largely gated behind authentication or vendor key issuance.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-sydney/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-sydney-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Library, Research, Open Data, Australia

## APIs

- **Sydney eScholarship Repository (OAI-PMH)** — institutional repository metadata harvesting over OAI-PMH 2.0. Docs: https://ses.library.usyd.edu.au/
- **Library Discovery (Ex Libris Primo / Alma)** — library platform with vendor Alma REST and Primo Search APIs; access requires an institution-issued key. Docs: https://developers.exlibrisgroup.com/
- **myUni Student Portal API (gated)** — internal authenticated JSON APIs backing the student portal; not public. Docs: https://myuni.sydney.edu.au/

## Plans / Rate Limits / FinOps

- Plans: [plans/university-of-sydney-plans-pricing.yml](plans/university-of-sydney-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-sydney-rate-limits.yml](rate-limits/university-of-sydney-rate-limits.yml)
- FinOps: [finops/university-of-sydney-finops.yml](finops/university-of-sydney-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.sydney.edu.au/
- GitHub: https://github.com/Sydney-Informatics-Hub
- LinkedIn: https://au.linkedin.com/school/university-of-sydney/
- Library: https://www.library.sydney.edu.au/
- Service Portal: https://sydneyuni.service-now.com/sm

## Notes

- No central public developer portal or openly documented API program was found at time of review (2026-06-03).
- Alma/Primo APIs are real but require an institution-issued Ex Libris key and are not openly published.
- The Sydney eScholarship OAI-PMH endpoint is documented but returned HTTP 403 to automated requests (bot-blocking, not confirmed dead).
- myUni student endpoints require an authenticated student session and are not available to third parties.
- The Sydney Informatics Hub GitHub org hosts research/training code, not productized APIs; the `usyd` GitHub org exists but is private.
- No endpoints were fabricated. See [review.yml](review.yml) for per-URL verification status.

## Maintainers

- Kin Lane — kin@apievangelist.com
