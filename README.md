# University of Sydney (university-of-sydney)

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
