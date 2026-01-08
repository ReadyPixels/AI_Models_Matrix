# AI API Providers

_Last updated: 2026-01-08 08:40 UTC_

Quick link: [Awesome AI Models](./awesome-ai-models.md) | [Awesome AI IDEs](./awesome-ai-ides.md)

## Contents

- [Model Labs (Direct)](#model-labs-direct-)
- [Unified APIs & Aggregators](#unified-apis--aggregators-)
- [Inference Clouds & Serverless](#inference-clouds--serverless-)
- [GPU Clouds & Decentralized](#gpu-clouds--decentralized-)
- [Comparison](#comparison)

---

## Model Labs (Direct) 🧪

> **Direct API access from the unparalleled creators of the models.**

| Provider | Description | Website | Key Features | Pricing | Latest Version | Status | Verified |
|----------|-------------|---------|--------------|---------|---------------|--------|----------|
| **OpenAI** | Creator of GPT models | [platform.openai.com](https://platform.openai.com) | GPT-5, o1/o3, Assistants API | Pay-per-token | N/A | ✅ Active | 2026-01-08 |
| **Anthropic** | Creator of Claude models | [console.anthropic.com](https://console.anthropic.com) | Claude 3.5/4.5 (200k context), Caching | Pay-per-token | N/A | ✅ Active | 2026-01-08 |
| **Google AI Studio** | Gemini direct access | [ai.google.dev](https://ai.google.dev) | Gemini 2.5/3 Pro/Flash, 50% New Year discount | Free / Pay | N/A | ✅ Active | 2026-01-08 |
| **DeepSeek** | DeepSeek Labs | [deepseek.com](https://deepseek.com) | DeepSeek-V3/R1, Extremely cheap | Pay-per-token | N/A | ✅ Active | 2026-01-08 |
| **Mistral AI** | European Open-Weight Leader | [console.mistral.ai](https://console.mistral.ai) | Codestral, Pixtral, Mistral Large | Pay-per-token | N/A | ✅ Active | 2026-01-08 |
| **xAI** | Elon Musk's AI Lab | [x.ai](https://x.ai) | Grok models, real-time web search | Pay-per-token | N/A | ✅ Active | 2026-01-08 |
| **Cohere** | Enterprise RAG specialists | [cohere.com](https://cohere.com) | Command-R+, Rerank v3 | Pay-per-token | N/A | ✅ Active | 2026-01-08 |

---

## Unified APIs & Aggregators 🔗

> **One API key to access models from all providers.**

| Provider | Description | Website | Key Features | Pricing | Latest Version | Status | Verified |
|----------|-------------|---------|--------------|---------|---------------|--------|----------|
| **OpenRouter** | The widest model selection | [openrouter.ai](https://openrouter.ai) | 200+ models, crypto/fiat, rankings | Aggregated | N/A | ✅ Active | 2026-01-08 |
| **Hugging Face** | Community Hub Inference | [huggingface.co](https://huggingface.co/inference-api) | Access any OSS model, serverless | Free / Pro | N/A | ✅ Active | 2026-01-08 |

---

## Inference Clouds & Serverless ⚡

> **High-performance, low-latency infrastructure hosting open-source models.**

| Provider | Description | Website | Key Features | Pricing | Latest Version | Status | Verified |
|----------|-------------|---------|--------------|---------|---------------|--------|----------|
| **Together AI** | Fast inference cloud | [together.ai](https://together.ai) | Llama/Qwen/Mistral tuned stacks | Pay-per-token | N/A | ✅ Active | 2026-01-08 |
| **Fireworks AI** | Low-latency specialist | [fireworks.ai](https://fireworks.ai) | FireAttention engine, fine-tuning | Pay-per-token | N/A | ✅ Active | 2026-01-08 |
| **Groq** | LPU Hardware (Wait for it...) | [groq.com](https://groq.com) | Instant output (>500 T/s) | Pay-per-token | N/A | ✅ Active | 2026-01-08 |
| **Cerebras** | Wafer-Scale Engine | [cerebras.ai](https://cerebras.ai) | Massive throughput (2000 T/s) | Custom | N/A | ✅ Active | 2026-01-08 |
| **Anyscale** | Ray creators | [anyscale.com](https://anyscale.com) | Scalable production endpoints | Pay-per-token | N/A | ✅ Active | 2026-01-08 |
| **Modal** | Serverless Python | [modal.com](https://modal.com) | Define infra in code, auto-scale | Pay-per-compute | N/A | ✅ Active | 2026-01-08 |

---

## GPU Clouds & Decentralized ☁️

> **Rent raw GPU power or use decentralized networks.**

| Provider | Description | Website | Key Features | Pricing | Latest Version | Status | Verified |
|----------|-------------|---------|--------------|---------|---------------|--------|----------|
| **Vultr** | Global Cloud | [vultr.com](https://vultr.com) | 32 locations, H100s | Hourly | N/A | ✅ Active | 2026-01-08 |
| **Nebius** | AI-Centric Cloud | [nebius.com](https://nebius.com) | NVIDIA H200/Blackwell | Competitive | N/A | ✅ Active | 2026-01-08 |
| **Snova** | AI Cloud | [novita.ai](https://novita.ai) | 100+ models, cheap inference | Pay-as-you-go | N/A | ✅ Active | 2026-01-08 |
| **Hyperbolic** | Decentralized Network | [hyperbolic.xyz](https://hyperbolic.xyz) | Verifiable AI, shared GPUs | Crypto/Fiat | N/A | ✅ Active | 2026-01-08 |
| **RunPod** | GPU Rental | [runpod.io](https://runpod.io) | Community cloud, wide GPU selection| Hourly | N/A | ✅ Active | 2026-01-08 |
| **Replicate** | Model-as-a-Service | [replicate.com](https://replicate.com) | Run anything via API | Pay-per-sec | N/A | ✅ Active | 2026-01-08 |

---

## Comparison

### Pricing Models 💰
- **Labs**: Often premium prices for proprietary frontier models.
- **Inference Clouds**: Race to the bottom on price for open-source models (Llama 3, Mixtral).
- **Aggregators**: Convenient but may add a small markup (though OpenRouter typically matches direct prices).

### Speed & Latency 🚀
- **Groq & Cerebras**: Unbeatable speed for small/medium models.
- **Together & Fireworks**: Excellent balanced performance for production.
- **Labs**: Variable latency (can be slow during peak loads).

### Reliability 🛡️
- **Hyperscalers (AWS/Azure/Google)**: (Not listed above but implied) Best SLAs.
- **Unified APIs**: Best tailored for developers who want fallback options if one provider goes down.

---

### Official Status Pages
- [OpenAI Status](https://status.openai.com)
- [Anthropic Status](https://status.anthropic.com)
- [Google Cloud Status](https://status.cloud.google.com)
- [Mistral Status](https://status.mistral.ai)

Made with ❤️ by ReadyPixels LLC
