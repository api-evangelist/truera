# TruEra (Snowflake) (truera)

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

### TruEra AI Quality Platform (Legacy / Snowflake)
TruEra's hosted AI quality platform offered REST APIs for ingesting models, predictions, and feedback for traditional ML observability. Following the Snowflake acquisition, capabilities are migrating into Snowflake Cortex; standalone TruEra access is being phased out for new customers.
- **Docs:** https://truera.com/

## Common Properties
- [Website](https://truera.com/)
- [OpenSource](https://github.com/truera/trulens)
- [Plans](plans/truera-plans-pricing.yml) — reconciled (TruLens OSS; commercial via Snowflake)
- [RateLimits](rate-limits/truera-rate-limits.yml) — partial (Snowflake successor inherits account limits)
- [FinOps](finops/truera-finops.yml) — reconciled (FOCUS-aligned)

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
