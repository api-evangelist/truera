# TruEra (Snowflake) (truera)

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

TruEra was an AI quality, observability, and governance platform that was acquired by Snowflake in May 2024. The standalone TruEra product is being absorbed into Snowflake's Cortex/AI platform. The open-source TruLens evaluation library (originally from TruEra) remains active as a standalone Python project for LLM and RAG evaluation.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/truera/refs/heads/main/apis.yml)

## Type
- **x-type:** company

## Tags
- AI Evaluation, Observability, AI Governance, LLM, RAG, Snowflake

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### TruLens (Open Source)
Open-source Python library for evaluating and tracking LLM applications. Provides feedback functions (groundedness, relevance, etc.), tracing, and a local dashboard. Distributed via PyPI under Apache 2.0; runs in-process and integrates with LangChain and LlamaIndex.
- **Docs:** https://www.trulens.org/


## Common Properties
- [Website](https://truera.com/)
- [OpenSource](https://github.com/truera/trulens)
- [Plans](plans/truera-plans-pricing.yml) — reconciled (TruLens OSS; commercial via Snowflake)
- [RateLimits](rate-limits/truera-rate-limits.yml) — partial (Snowflake successor inherits account limits)
- [FinOps](finops/truera-finops.yml) — reconciled (FOCUS-aligned)

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
