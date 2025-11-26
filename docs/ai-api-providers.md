# AI API Providers

Last updated: 2025-11-24 22:53 UTC

## Contents

- [Introduction](#introduction)
- [List of Providers](#list-of-providers)
- [Comparison](#comparison)
  - [Pricing Models](#pricing-models-)
  - [Model Coverage](#model-coverage-)
  - [Performance Focus](#performance-focus-)
  - [Ease of Integration](#ease-of-integration-)
- [Official Pricing and Rate Limit Docs](#official-pricing-and-rate-limit-docs)
- [Endpoint Changes and Notes](#endpoint-changes-and-notes)
- [Supplementary APIs (Search & Discovery)](#supplementary-apis-search--discovery)
- [Deprecations and Migrations](#deprecations-and-migrations)
- [Notes](#notes-)
- [Reliability and Uptime](#reliability-and-uptime)
- [Sources and Verification](#sources-and-verification)
- [Deprecation Sources](#deprecation-sources)
- [Revision History](#revision-history)

## Introduction

This document provides an overview of API providers that offer unified access to multiple AI language models, similar to OpenRouter.ai. These platforms aggregate models from various companies, providing developers with a single API interface for accessing diverse AI capabilities. They often include features like load balancing, automatic fallbacks, and competitive pricing 💰 to simplify AI integration.

## List of Providers

| Provider                  | Description                                                               | Website 🌐                          | Key Features 🚀                                      | Pricing 💰 |
|---------------------------|---------------------------------------------------------------------------|------------------------------------|----------------------------------------------------|------------|
| OpenAI                    | APIs for GPT models, embeddings, images, and responses                    | https://platform.openai.com/docs/overview | Broad model set, structured output, fine-tuning, batch, safety | Pay-per-token |
| Anthropic                | Claude models with long context and tool use                              | https://docs.anthropic.com/claude | Long context, tools, caching, policies            | Pay-per-token |
| Google Vertex AI         | Gemini models on Vertex AI                                                 | https://cloud.google.com/vertex-ai/docs/generative-ai | Enterprise controls, governance, extensions       | Per 1k tokens |
| Google AI Studio         | Gemini API in AI Studio                                                    | https://ai.google.dev              | Fast prototyping, API keys, client SDKs           | $2/$12 per 1M (preview) |
| Azure OpenAI Service     | OpenAI models on Azure with enterprise controls                           | https://learn.microsoft.com/azure/ai-services/openai/ | Azure compliance, quotas, regional deployment     | Pay-per-token |
| Amazon Bedrock           | Foundation models from multiple providers on AWS                           | https://aws.amazon.com/bedrock/   | Multi-model access, guardrails, agents, KBs       | Per model pricing |
| Cohere                   | Command, Embed, and Rerank APIs                                            | https://docs.cohere.com/docs      | Embeddings, rerank, safety                        | Pay-per-token |
| Mistral AI               | Mistral models via hosted platform                                         | https://docs.mistral.ai/          | Fast endpoints, open weights options               | Pay-per-token |
| xAI                      | Grok models API                                                            | https://docs.x.ai/                | Fast chat, web integration                         | Pay-per-token |
| Hugging Face Inference API | API access to open-source models hosted by the community                  | https://huggingface.co/inference-api | Wide OSS coverage, flexible deployment            | Free tier, pay-per-request |
| RunPod                   | GPU cloud platform for inference and training                              | https://runpod.io                 | Low cost GPUs, serverless jobs, APIs               | Pay-per-GPU-hour |
| Replicate                | Cloud platform to run models with simple APIs                              | https://replicate.com             | Model marketplace, quick deploy, streaming         | Pay-per-second |
| Together AI              | Training, fine-tuning, and deployment with a unified API                   | https://together.ai               | Unified API, tuned models, high throughput         | Pay-per-token |
| Fireworks AI             | Fast inference for open models                                             | https://fireworks.ai              | Low latency, enterprise features                    | Pay-per-token |
| OpenRouter               | Unified API to many models across providers                                | https://openrouter.ai             | Load balance, fallbacks, routing                   | Pay-per-token |
| Modal                    | Serverless platform for GPU workloads                                      | https://modal.com                 | Python native, autoscale, GPU acceleration         | Pay-per-compute |
| Anyscale                 | Ray-based platform for scalable model serving                              | https://anyscale.com              | Scalable inference, deployments, cloud native      | Pay-per-usage |
| Groq                     | Inference on custom LPU hardware                                           | https://groq.com                  | High speed, low latency, API                       | Pay-per-token |
| Cerebras                 | Inference on custom wafer-scale hardware                                   | https://cerebras.net              | Large models, energy efficient                      | Custom pricing |
| Modal                    | Serverless platform for GPU workloads (beta tool enhancements)            | https://modal.com                 | Python native, autoscale, GPU acceleration         | Pay-per-compute |
| Anyscale                 | Ray-based platform for scalable model serving (beta statuses)             | https://anyscale.com              | Scalable inference, deployments, cloud native      | Pay-per-usage |

## Comparison

### Pricing Models 💰
- Most providers bill per token or per request
- Many offer a free tier for testing
- Enterprise plans include SLAs and support

### Model Coverage 📊
- Coverage ranges from open-source focus to broad commercial support
- Some allow custom model deployment

### Performance Focus 🚀
- Speed focus: Groq, Cerebras
- Flexibility: Replicate, Hugging Face
- Scalability: Anyscale, Modal

### Ease of Integration 🔧
- Unified APIs reduce complexity versus many separate integrations
- Many support OpenAI-compatible endpoints for easier migration

## Official Pricing and Rate Limit Docs

- OpenAI — Pricing: https://openai.com/api/pricing — Rate limits: https://platform.openai.com/docs/guides/rate-limits
- Anthropic — Pricing: https://www.anthropic.com/pricing — Rate limits: https://docs.anthropic.com/claude/docs/rate-limits
- Google Vertex AI — Pricing: https://cloud.google.com/vertex-ai/pricing — Quotas: https://cloud.google.com/vertex-ai/docs/generative-ai/quotas
- Google AI Studio — Gemini 3 pricing: https://blog.google/technology/developers/gemini-3-developers/ — Verified: 2025-11-24 22:53 UTC
- Azure OpenAI — Pricing: https://azure.microsoft.com/pricing/details/cognitive-services/openai-service/ — Quotas: https://learn.microsoft.com/azure/ai-services/openai/quotas-limits
- Amazon Bedrock — Pricing: https://aws.amazon.com/bedrock/pricing/ — Quotas: https://docs.aws.amazon.com/bedrock/latest/userguide/quotas.html
- Cohere — Pricing: https://cohere.com/pricing — Rate limits: https://docs.cohere.com/docs/rate-limits
- Mistral AI — Pricing: https://mistral.ai/pricing/ — Rate limits: https://docs.mistral.ai/getting-started/ratelimits/
- xAI (Grok) — Pricing: https://x.ai/api/pricing — Rate limits: https://docs.x.ai/guides/rate-limits
- xAI Models and pricing — https://docs.x.ai/docs/models — Verified: 2025-11-14 22:07 UTC
- Hugging Face — Pricing: https://huggingface.co/inference-api/pricing — Rate limits: https://huggingface.co/docs/hub/en/security-and-limits#rate-limits
- Groq — Pricing: https://groq.com/pricing/ — Rate limits: https://wow.groq.com/docs/limits-and-rate-limits
- Together AI — Pricing: https://www.together.ai/pricing — Rate limits: https://docs.together.ai/docs/rate-limits
- OpenRouter — Pricing: https://openrouter.ai/pricing — Rate limits: https://openrouter.ai/docs#rate-limits
- Fireworks AI — Pricing: https://fireworks.ai/pricing — Rate limits: https://docs.fireworks.ai/quickstart/rate-limits


## Endpoint Changes and Notes

- OpenAI: Responses API supports multimodal, tool use, and structured output.
- Google Vertex AI: Gemini models are available on Vertex AI with enterprise controls.
- AWS Bedrock: New models added often. Guardrails and agents available.
- Azure OpenAI: API versions change. Check `api-version` in requests.
- OpenRouter and Together: Provide OpenAI-compatible routes for easier adoption.
- xAI: Live Search API deprecated by December 15, 2025; use agentic tool calling API. Pricing $25 per 1,000 sources. — Verified: 2025-11-14 22:07 UTC

### Supplementary APIs (Search & Discovery)

- Brave Search API — Programmatic web search suitable for discovery and cross-validation; supports pagination and freshness filters. Pricing and docs: https://brave.com/search/api/ — Verified: 2025-11-24 22:53 UTC

### Deprecations and Migrations
- Anthropic: Text Completions API deprecated, migrate to Messages API.
- OpenAI: Assistants API deprecated, migrate to Responses and Conversations APIs.
- OpenAI: Legacy GPT model snapshots have shutdown schedules; use current models.
- OpenAI: Text Moderation models deprecated, migrate to `omni-moderation`.
- OpenAI: Some Realtime preview endpoints deprecated; check current realtime docs.
- Azure OpenAI: Assistants API deprecation does not affect Azure service routes.
- Groq: Batch API has separate, higher limits; 429 returned when exceeding limits.
- Together AI: Rate limits increase automatically with usage and paid tiers.

Sources for endpoint details are listed below with verification.

## Notes 📝

- Offerings change over time. Verify details on official sites.
- Consider latency, cost, data residency, and model availability.
- Most providers publish docs, SDKs, and support channels.
- For production, review reliability, uptime, and support options.

## Reliability and Uptime

- OpenAI status: https://status.openai.com/
- Anthropic status: https://status.anthropic.com/
- Google Cloud status: https://status.cloud.google.com/
- AWS status: https://health.aws.amazon.com/
- Azure status: https://status.azure.com/
- Cohere status: https://status.cohere.com/
- Mistral status: https://status.mistral.ai/
- Groq status: https://status.groq.com/
- Together status: https://status.together.ai/

Review status pages for incidents, uptime, and maintenance windows.

## Sources and Verification

- OpenAI docs: https://platform.openai.com/docs/overview — Verified: 2025-11-14 22:07 UTC
- OpenAI pricing: https://openai.com/api/pricing — Verified: 2025-11-14 22:07 UTC
- OpenAI rate limits: https://platform.openai.com/docs/guides/rate-limits — Verified: 2025-11-14 22:07 UTC
- Anthropic docs: https://docs.anthropic.com/claude — Verified: 2025-11-14 22:07 UTC
- Anthropic pricing: https://www.anthropic.com/pricing — Verified: 2025-11-14 22:07 UTC
- Anthropic rate limits: https://docs.anthropic.com/claude/docs/rate-limits — Verified: 2025-11-14 22:07 UTC
- Google Vertex AI docs: https://cloud.google.com/vertex-ai/docs/generative-ai — Verified: 2025-11-14 22:07 UTC
- Vertex pricing: https://cloud.google.com/vertex-ai/pricing — Verified: 2025-11-14 22:07 UTC
- Vertex quotas: https://cloud.google.com/vertex-ai/docs/generative-ai/quotas — Verified: 2025-11-14 22:07 UTC
- Azure OpenAI docs: https://learn.microsoft.com/azure/ai-services/openai/ — Verified: 2025-11-14 22:07 UTC
- Azure OpenAI pricing: https://azure.microsoft.com/pricing/details/cognitive-services/openai-service/ — Verified: 2025-11-14 22:07 UTC
- Azure OpenAI quotas: https://learn.microsoft.com/azure/ai-services/openai/quotas-limits — Verified: 2025-11-14 22:07 UTC
- Amazon Bedrock: https://aws.amazon.com/bedrock/ — Verified: 2025-11-14 22:07 UTC
- Bedrock pricing: https://aws.amazon.com/bedrock/pricing/ — Verified: 2025-11-14 22:07 UTC
- Bedrock quotas: https://docs.aws.amazon.com/bedrock/latest/userguide/quotas.html — Verified: 2025-11-14 22:07 UTC
- Cohere docs: https://docs.cohere.com/docs — Verified: 2025-11-14 22:07 UTC
- Cohere pricing: https://cohere.com/pricing — Verified: 2025-11-14 22:07 UTC
- Cohere rate limits: https://docs.cohere.com/docs/rate-limits — Verified: 2025-11-14 22:07 UTC
- Mistral docs: https://docs.mistral.ai/ — Verified: 2025-11-14 22:07 UTC
- Mistral pricing: https://mistral.ai/pricing/ — Verified: 2025-11-14 22:07 UTC
- Mistral rate limits: https://docs.mistral.ai/getting-started/ratelimits/ — Verified: 2025-11-14 22:07 UTC
- xAI docs: https://docs.x.ai/ — Verified: 2025-11-14 22:07 UTC
- xAI pricing: https://x.ai/api/pricing — Verified: 2025-11-14 22:07 UTC
- xAI rate limits: https://docs.x.ai/guides/rate-limits — Verified: 2025-11-14 22:07 UTC
- Hugging Face Inference API: https://huggingface.co/inference-api — Verified: 2025-11-14 22:07 UTC
- HF pricing: https://huggingface.co/inference-api/pricing — Verified: 2025-11-14 22:07 UTC
- HF rate limits: https://huggingface.co/docs/hub/en/security-and-limits#rate-limits — Verified: 2025-11-14 22:07 UTC
- RunPod: https://runpod.io — Verified: 2025-11-14 22:07 UTC
- Replicate: https://replicate.com — Verified: 2025-11-14 22:07 UTC
- Together AI: https://together.ai — Verified: 2025-11-14 22:07 UTC
- Together pricing: https://www.together.ai/pricing — Verified: 2025-11-14 22:07 UTC
- Together rate limits: https://docs.together.ai/docs/rate-limits — Verified: 2025-11-14 22:07 UTC
- Fireworks AI: https://fireworks.ai — Verified: 2025-11-14 22:07 UTC
- Fireworks pricing: https://fireworks.ai/pricing — Verified: 2025-11-14 22:07 UTC
- Fireworks rate limits: https://docs.fireworks.ai/quickstart/rate-limits — Verified: 2025-11-14 22:07 UTC
- OpenRouter: https://openrouter.ai — Verified: 2025-11-14 22:07 UTC
- OpenRouter pricing: https://openrouter.ai/pricing — Verified: 2025-11-14 22:07 UTC
- OpenRouter rate limits: https://openrouter.ai/docs#rate-limits — Verified: 2025-11-14 22:07 UTC
- Modal: https://modal.com — Verified: 2025-11-14 22:07 UTC
- Anyscale: https://anyscale.com — Verified: 2025-11-14 22:07 UTC
- Groq: https://groq.com — Verified: 2025-11-14 22:07 UTC
- Groq rate limits: https://wow.groq.com/docs/limits-and-rate-limits — Verified: 2025-11-14 22:07 UTC
- Cerebras: https://cerebras.net — Verified: 2025-11-14 22:07 UTC

### Deprecation Sources
- Anthropic Completions → Messages: https://docs.anthropic.com/claude/docs/migrate-from-text-completions — Verified: 2025-11-09 00:58 UTC
- OpenAI deprecations overview: https://platform.openai.com/docs/deprecations — Verified: 2025-11-09 00:58 UTC
- OpenAI Assistants API deprecation: https://platform.openai.com/docs/deprecations/assistants — Verified: 2025-11-09 00:58 UTC

## Revision History

- 2025-11-24 22:53 UTC — Added Google AI Studio provider, Brave Search API section, updated pricing sources.
- 2025-11-09 00:58 UTC — Expanded provider table, added sources, status links, and endpoint notes.

Made with ❤️ by ReadyPixels LLC
