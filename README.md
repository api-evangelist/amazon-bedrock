# Amazon Bedrock (amazon-bedrock)

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

Amazon Bedrock is a fully managed AWS service that makes high-performing foundation models from leading AI companies available through a unified API for building generative AI applications. It supports text and image generation, conversational AI, model customization and fine-tuning, retrieval-augmented generation (RAG) via knowledge bases, autonomous agents, guardrails for responsible AI, and provisioned throughput for production workloads. The Bedrock APIs are AWS regional service endpoints accessed over HTTPS using AWS Signature Version 4 (SigV4) authentication, typically via the AWS SDKs.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/amazon-bedrock/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/amazon-bedrock/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- AI
- AWS
- Foundation Models
- Generative AI
- LLM
- Machine Learning
- RAG
- Agents
- Responsible AI

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-19

## APIs

### Amazon Bedrock API

The Amazon Bedrock management API provides operations for managing foundation models, custom models, model customization jobs, provisioned throughput, guardrails, knowledge bases, agents, and model evaluation jobs. Authentication uses AWS Signature Version 4 (SigV4).

- **Human URL:** [https://docs.aws.amazon.com/bedrock/latest/APIReference/](https://docs.aws.amazon.com/bedrock/latest/APIReference/)
- **Base URL:** `https://bedrock.us-east-1.amazonaws.com`

#### Tags

- Foundation Models
- Generative AI
- Custom Models
- Guardrails
- Knowledge Bases
- Agents

#### Properties

- [Documentation](https://docs.aws.amazon.com/bedrock/latest/APIReference/)
- [OpenAPI](openapi/amazon-bedrock-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amazon-bedrock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amazon-bedrock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/amazon-bedrock-model-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/bedrock-resource-structure.json)
- [JSON-LD](json-ld/amazon-bedrock-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Ruleset](spectral/ruleset.yml)
- [Capabilities](capabilities/capabilities.yml)
- [Vocabulary](vocabulary/vocabulary.yml)

### Amazon Bedrock Runtime API

The Amazon Bedrock Runtime API provides operations for invoking foundation models for inference, including synchronous, streaming, and conversational invocation patterns (Converse API). Also supports guardrail evaluation and async batch inference. Authentication uses AWS Signature Version 4 (SigV4).

- **Human URL:** [https://docs.aws.amazon.com/bedrock/latest/APIReference/](https://docs.aws.amazon.com/bedrock/latest/APIReference/)
- **Base URL:** `https://bedrock-runtime.us-east-1.amazonaws.com`

#### Tags

- Foundation Models
- Generative AI
- Inference
- Streaming
- Converse

#### Properties

- [Documentation](https://docs.aws.amazon.com/bedrock/latest/APIReference/)
- [OpenAPI](openapi/amazon-bedrock-runtime-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amazon-bedrock-runtime.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amazon-bedrock-runtime.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amazon Bedrock Agent API

The Amazon Bedrock Agent API provides operations for managing and configuring autonomous AI agents, knowledge bases for RAG, data sources, and ingestion jobs. Authentication uses AWS Signature Version 4 (SigV4).

- **Human URL:** [https://docs.aws.amazon.com/bedrock/latest/APIReference/](https://docs.aws.amazon.com/bedrock/latest/APIReference/)
- **Base URL:** `https://bedrock-agent.us-east-1.amazonaws.com`

#### Tags

- Agents
- Knowledge Bases
- RAG

#### Properties

- [Documentation](https://docs.aws.amazon.com/bedrock/latest/APIReference/)
- [Postman Collection](collections/amazon-bedrock-runtime.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amazon-bedrock-runtime.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amazon-bedrock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amazon-bedrock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amazon Bedrock Agent Runtime API

The Amazon Bedrock Agent Runtime API provides operations for invoking Bedrock agents and retrieving content from knowledge bases for RAG applications. Authentication uses AWS Signature Version 4 (SigV4).

- **Human URL:** [https://docs.aws.amazon.com/bedrock/latest/APIReference/](https://docs.aws.amazon.com/bedrock/latest/APIReference/)
- **Base URL:** `https://bedrock-agent-runtime.us-east-1.amazonaws.com`

#### Tags

- Agents
- RAG
- Retrieval

#### Properties

- [Documentation](https://docs.aws.amazon.com/bedrock/latest/APIReference/)
- [Postman Collection](collections/amazon-bedrock-runtime.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amazon-bedrock-runtime.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/amazon-bedrock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amazon-bedrock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://aws.amazon.com/bedrock/)
- [Documentation](https://docs.aws.amazon.com/bedrock/)
- [Pricing](https://aws.amazon.com/bedrock/pricing/)
- [Sign Up](https://portal.aws.amazon.com/billing/signup)
- [Portal](https://aws.amazon.com/)
- [Console](https://console.aws.amazon.com/bedrock/)
- [Login](https://console.aws.amazon.com/)
- [Support](https://aws.amazon.com/support/)
- [Status Page](https://health.aws.amazon.com/health/status)
- [Blog](https://aws.amazon.com/blogs/machine-learning/)
- [F A Q](https://aws.amazon.com/bedrock/faqs/)
- [Getting Started](https://aws.amazon.com/bedrock/getting-started/)
- [Terms of Service](https://aws.amazon.com/service-terms/)
- [Privacy Policy](https://aws.amazon.com/privacy/)
- [GitHub Organization](https://github.com/aws)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
