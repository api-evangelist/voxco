# Voxco (voxco)

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
