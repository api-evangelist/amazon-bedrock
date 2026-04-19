# Amazon Bedrock

Amazon Bedrock is a fully managed service that makes high-performing foundation models (FMs) from leading AI companies available through a unified API. It enables developers to build and scale generative AI applications using foundation models for text generation, summarization, image generation, and conversational AI without managing infrastructure.

**Human URL:** [https://aws.amazon.com/bedrock/](https://aws.amazon.com/bedrock/)

**API Reference:** [https://docs.aws.amazon.com/bedrock/latest/APIReference/](https://docs.aws.amazon.com/bedrock/latest/APIReference/)

## APIs

### Amazon Bedrock API
Management API for foundation models, custom models, model customization jobs, provisioned throughput, guardrails, knowledge bases, agents, and model evaluation.

**Base URL:** `https://bedrock.us-east-1.amazonaws.com`

### Amazon Bedrock Runtime API
Inference API for invoking foundation models synchronously, with streaming, and via the unified Converse interface.

**Base URL:** `https://bedrock-runtime.us-east-1.amazonaws.com`

### Amazon Bedrock Agent API
Management API for autonomous agents, knowledge bases, data sources, and ingestion jobs.

**Base URL:** `https://bedrock-agent.us-east-1.amazonaws.com`

### Amazon Bedrock Agent Runtime API
Runtime API for invoking agents and retrieving from knowledge bases for RAG.

**Base URL:** `https://bedrock-agent-runtime.us-east-1.amazonaws.com`

#### Key Operations

| Operation | Description |
|---|---|
| InvokeModel | Invoke a foundation model for inference |
| Converse | Unified chat interface across model providers |
| ConverseStream | Streaming chat with token-by-token output |
| CreateKnowledgeBase | Create a RAG knowledge base |
| RetrieveAndGenerate | RAG query with grounded generation |
| InvokeAgent | Invoke an autonomous AI agent |
| CreateGuardrail | Create content safety guardrails |
| CreateModelCustomizationJob | Fine-tune a foundation model |
| CreateProvisionedModelThroughput | Reserve capacity for production |

## Features

- **30+ Foundation Models** — Anthropic Claude, Amazon Nova/Titan, Meta Llama, Mistral, Cohere, and more
- **Unified Converse API** — Consistent chat interface across all model providers
- **Retrieval-Augmented Generation (RAG)** — Knowledge bases with vector search for grounded responses
- **Autonomous Agents** — Multi-step orchestration with tool calls and knowledge base access
- **Guardrails** — Topic filtering, harmful content detection, PII redaction, prompt injection protection
- **Model Customization** — Fine-tuning and continued pre-training on proprietary data
- **Provisioned Throughput** — Reserved capacity for consistent production performance
- **Cross-Region Inference** — Automatic routing across regions for availability

## Use Cases

- Conversational AI and chatbots
- Document summarization and analysis
- Code generation and review
- Customer support automation
- RAG-powered knowledge management
- AI agent workflow automation

## Model Providers

Anthropic, Amazon, Meta, Mistral AI, Cohere, AI21 Labs, Stability AI, Writer, DeepSeek

## Artifacts

| Type | URL |
|---|---|
| OpenAPI (Bedrock) | [openapi/amazon-bedrock-openapi.yml](openapi/amazon-bedrock-openapi.yml) |
| OpenAPI (Runtime) | [openapi/amazon-bedrock-runtime-openapi.yml](openapi/amazon-bedrock-runtime-openapi.yml) |
| JSON Schema | [json-schema/amazon-bedrock-model-schema.json](json-schema/amazon-bedrock-model-schema.json) |
| JSON Structure | [json-structure/bedrock-resource-structure.json](json-structure/bedrock-resource-structure.json) |
| JSON-LD Context | [json-ld/amazon-bedrock-context.jsonld](json-ld/amazon-bedrock-context.jsonld) |
| Spectral Ruleset | [spectral/ruleset.yml](spectral/ruleset.yml) |
| Capabilities | [capabilities/capabilities.yml](capabilities/capabilities.yml) |
| Vocabulary | [vocabulary/vocabulary.yml](vocabulary/vocabulary.yml) |
| Examples | [examples/](examples/) |

## Common Properties

| Type | URL |
|---|---|
| Documentation | [https://docs.aws.amazon.com/bedrock/](https://docs.aws.amazon.com/bedrock/) |
| Pricing | [https://aws.amazon.com/bedrock/pricing/](https://aws.amazon.com/bedrock/pricing/) |
| FAQ | [https://aws.amazon.com/bedrock/faqs/](https://aws.amazon.com/bedrock/faqs/) |
| Blog | [https://aws.amazon.com/blogs/machine-learning/](https://aws.amazon.com/blogs/machine-learning/) |
| Console | [https://console.aws.amazon.com/bedrock/](https://console.aws.amazon.com/bedrock/) |

## Maintainers

**Kin Lane** — [kin@apievangelist.com](mailto:kin@apievangelist.com)
