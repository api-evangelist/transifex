# Transifex (transifex)

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

Transifex is a cloud-based localization management platform that enables development and content teams to translate software, websites, mobile apps, and digital content at scale. The Transifex REST API v3 provides programmatic access to manage translation projects, resources, language teams, and translation memory. Developers can automate localization workflows, push and pull source strings, trigger translation jobs, and integrate continuous localization into CI/CD pipelines. The platform supports OAuth 2.0 and bearer token authentication, with SDKs available for Python, JavaScript, Swift, Java, and a Go-based CLI tool.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/transifex/refs/heads/main/apis.yml
- Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=transifex-api-evangelist&utm_content=repo

## Tags

- Localization
- Translation
- i18n
- l10n
- Language
- Content Management
- Workflow Automation

## APIs

### Transifex API

The Transifex REST API v3 provides full programmatic control over localization operations including project management, resource handling, translation memory, language team administration, and automated workflow triggers. The API follows JSON:API specification and uses bearer token authentication.

- Documentation: https://developers.transifex.com/reference/
- OpenAPI: https://transifex.github.io/openapi/
- Base URL: https://rest.api.transifex.com

## Plans, Rate Limits, and FinOps

- Plans and Pricing: [plans/transifex-plans-pricing.yml](plans/transifex-plans-pricing.yml)
- Rate Limits: [rate-limits/transifex-rate-limits.yml](rate-limits/transifex-rate-limits.yml)
- FinOps: [finops/transifex-finops.yml](finops/transifex-finops.yml)

### Pricing Summary

| Plan | Monthly | Annual (per month) | Collaborators | AI Words/Year |
|---|---|---|---|---|
| Starter | $160+ | $135+ | 10 | — |
| Growth | $236+ | $200+ | 30 | 60,000 |
| Enterprise+ | Custom | Custom | 100 | 300,000 |

### Rate Limits Summary

| Endpoint Type | Limit |
|---|---|
| Standard endpoints | 500 requests/minute per IP |
| Async polling endpoints | 1,200 requests/minute per IP |

## Timestamps

- Created: 2026-06-13
- Modified: 2026-06-13

## Common

| Type | URL |
|---|---|
| Website | https://www.transifex.com |
| Documentation | https://developers.transifex.com |
| GitHub Org | https://github.com/transifex |
| LinkedIn | https://www.linkedin.com/company/transifex |
| Blog | https://www.transifex.com/blog |
| Pricing | https://www.transifex.com/pricing |
| Status Page | https://status.transifex.com |
| X (Twitter) | https://twitter.com/transifex |

## Maintainers

- Kin Lane (kin@apievangelist.com)
