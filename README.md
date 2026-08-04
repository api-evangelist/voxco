# Voxco (voxco)

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

Voxco is an omnichannel survey platform serving market research firms and corporate research teams across 40+ countries. It provides a REST API for managing surveys, distributing questionnaires via multiple channels (online, CATI, mobile, IVR), collecting responses, and accessing survey analytics. The Ascribe text analytics API further enables AI-powered coding and analysis of open-ended survey responses.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/voxco/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/voxco/refs/heads/main/apis.yml)

## Tags

- Survey Software
- Market Research
- CATI
- Omnichannel
- Text Analytics
- Data Collection
- Panel Management

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Voxco Survey API

REST API for integrating with the Voxco survey platform, enabling programmatic management of surveys, distribution across channels, response collection, and access to analytics. Authenticated via a 140-character Access Token.

- **Human URL:** [https://www.voxco.com/professional-services](https://www.voxco.com/professional-services)
- **Base URL:** `https://na1.voxco.com`

#### Tags

- Surveys
- Data Collection
- Analytics

#### Properties

- [Documentation](https://www.voxco.com/resources)
- [OpenAPI](https://webservices.goascribe.com/coder) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Voxco Ascribe Coder API

REST API for automated coding and analysis of open-ended survey responses. Supports creating studies, loading questions and responses, polling for coding completion, and retrieving codebooks and coded results via Bearer token authentication.

- **Human URL:** [https://www.voxco.com/resources/automating-coding-workflow-with-the-ascribe-coder-api](https://www.voxco.com/resources/automating-coding-workflow-with-the-ascribe-coder-api)
- **Base URL:** `https://webservices.goascribe.com/coder`

#### Tags

- Text Analytics
- AI Coding
- Open-Ended Responses
- Market Research

#### Properties

- [Documentation](https://www.voxco.com/resources/using-swagger-documentation-postman-ascribe-apis)
- [Authentication](https://www.voxco.com/resources/ascribe-api-authentication)
- [OpenAPI](https://webservices.goascribe.com/coder) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Voxco Ascribe CX Inspector API

REST API for customer experience text analytics and verbatim coding, enabling analysis of CX survey open-ended responses with AI-powered theme extraction and sentiment analysis. Uses the same Bearer token authentication as the Ascribe Coder API.

- **Human URL:** [https://www.voxco.com/resources/using-swagger-documentation-postman-ascribe-apis](https://www.voxco.com/resources/using-swagger-documentation-postman-ascribe-apis)
- **Base URL:** `https://webservices.goascribe.com/cxi`

#### Tags

- Customer Experience
- Text Analytics
- Sentiment Analysis
- Verbatim Coding

#### Properties

- [Documentation](https://www.voxco.com/resources/using-swagger-documentation-postman-ascribe-apis)
- [Authentication](https://www.voxco.com/resources/ascribe-api-authentication)
- [OpenAPI](https://webservices.goascribe.com/cxi) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [Website](https://www.voxco.com)
- [Documentation](https://www.voxco.com/resources)
- [Blog](https://www.voxco.com/blog/)
- [Pricing](https://www.voxco.com/pricing)
- [LinkedIn](https://www.linkedin.com/company/voxco)
- [X (Twitter)](https://x.com/voxco)
- [Plans](plans/voxco-plans-pricing.yml)
- [Rate Limits](rate-limits/voxco-rate-limits.yml)
- [Fin Ops](finops/voxco-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
