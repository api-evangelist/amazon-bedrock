# Amazon Bedrock (amazon-bedrock)

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
