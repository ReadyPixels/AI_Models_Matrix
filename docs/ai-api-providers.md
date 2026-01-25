# AI API Providers

 _Last updated: 2026-01-25 00:49 UTC_

Quick link: [Awesome AI Models](./awesome-ai-models.md) | [Awesome AI IDEs](./awesome-ai-ides.md)

## Contents

- [Model Labs (Direct)](#model-labs-direct-)
- [Unified APIs & Aggregators](#unified-apis--aggregators-)
- [Inference Clouds & Serverless](#inference-clouds--serverless-)
- [GPU Clouds & Decentralized](#gpu-clouds--decentralized-)
- [Supplementary APIs](#supplementary-apis-)
- [Comparison](#comparison)

---

## Model Labs (Direct) 🧪

> **Direct API access from the unparalleled creators of the models.**

| Provider | Description | Website | Key Features | Pricing | Latest Version | Status | Verified |
|----------|-------------|---------|--------------|---------|---------------|--------|----------|
| **OpenAI** | Creator of GPT models | [platform.openai.com](https://platform.openai.com) | GPT-5, o3/o4-mini, Assistants API | Pay-per-token | N/A | ✅ Active | 2026-01-25 |
| **Anthropic** | Creator of Claude models | [console.anthropic.com](https://console.anthropic.com) | Claude 4.5 Sonnet, SDK Agents | Pay-per-token | N/A | ✅ Active | 2026-01-25 |
| **Google AI Studio** | Gemini direct access | [ai.google.dev](https://ai.google.dev) | Gemini 3 Pro Preview/Flash, 1M+ context | Free / Pay | N/A | ✅ Active | 2026-01-25 |
| **DeepSeek** | DeepSeek Labs | [deepseek.com](https://deepseek.com) | DeepSeek-V4/R1, Interleaved Thinking | Pay-per-token | N/A | ✅ Active | 2026-01-25 |
| **Mistral AI** | European Open-Weight Leader | [console.mistral.ai](https://console.mistral.ai) | Mistral Large 3, Codestral | Pay-per-token | N/A | ✅ Active | 2026-01-25 |
| **xAI** | Elon Musk's AI Lab | [x.ai](https://x.ai) | Grok-4 models, real-time web search | Pay-per-token | N/A | ✅ Active | 2026-01-25 |
| **Cohere** | Enterprise RAG specialists | [cohere.com](https://cohere.com) | Command-R+, Rerank v3 | Pay-per-token | N/A | ✅ Active | 2026-01-25 |

### Google AI Studio (Gemini API)

**Overview**: Google's comprehensive AI development platform with Gemini models. Google AI Studio provides a free browser-based environment for prompt design, testing, and structured output validation. The Gemini API offers tiered pricing: Free (limited access), Paid (production-ready with higher limits and advanced features), and Enterprise (custom solutions via Vertex AI). Gemini 3 Pro Preview, launched in January 2026, is Google's most advanced multimodal model for understanding, agentic tasks, and coding.

**Pricing (January 2026)**:
- **Gemini 1.5 Pro**: $1.25/million input tokens, $5.00/million output tokens
- **Gemini 3 Pro Preview** (Model Code: `gemini-3-pro-preview`):
  - **Free Tier**: Free input/output tokens (limited model access, content used for product improvement).
  - **Paid Tier**: Input: $2.00 per 1 million tokens (text); $12.00 per 1 million tokens (audio/video). Output (including thinking tokens): $12.00 per 1 million tokens (text); $72.00 per 1 million tokens (audio).
  - **Context Window**: 1 million tokens input, up to 64K tokens output.
  - **Long Context (>200K tokens)**: 2x pricing for Pro models.
  - **Tools Integration**: Google Search grounding at $35 per 1,000 grounded prompts (after free limits).
  - **Notes**: Preview models may change before stabilization; higher rate limits in Paid tier; content not used for improvement in Paid tier.
- **Gemini 3 Flash**: $0.30/million input tokens, $2.50/million output tokens
- **Free Tier**: 5-15 RPM, 250k TPM, 1,000 requests/day. Access through Google AI Studio.

**Models Available**:
- Gemini 1.5 Flash (cost-effective)
- Gemini 1.5 Pro (balanced performance)
- Gemini 3 Pro Preview (advanced multimodal understanding, agentic reasoning, vibe-coding capabilities, 1M token context, thinking budgets, advanced search grounding)
- Gemini 3 Flash (Pro reasoning, Flash efficiency)

**Features**:
- Free and pay-as-you-go tiers
- Integration with Firebase Studio
- Antigravity platform support
- Vertex AI compatibility
- Superior multimodal understanding, agentic reasoning, vibe-coding capabilities, 1M token context, thinking budgets, advanced search grounding.

**Updates as of January 2026**: Launch of Gemini 3 Pro Preview with transparent context-tiered pricing; integration with Google AI Studio for free experimentation; support for tools like Google Search, Maps, and code execution.

**Documentation**: [Google AI for Developers](https://ai.google.dev/gemini-api/docs)

**Official Sources**:
- **Primary Source**: [Google AI for Developers - Gemini API Pricing](https://ai.google.dev/gemini-api/docs/pricing) (confirms free AI Studio usage, tier structure, and tool pricing; Gemini 3 Pro pricing referenced in context).
- **Cross-Validation Source 1**: [AI Free API - Gemini API Pricing 2026](https://www.aifreeapi.com/en/posts/gemini-api-pricing-2026) (aligns on $2.00/$12.00 per million tokens for Gemini 3 Pro Preview).
- **Cross-Validation Source 2**: [CostGoat - Gemini API Pricing Calculator](https://costgoat.com/pricing/gemini-api) (confirms $2.00 input / $12.00 output per million tokens).
- **Additional Reference**: [MetaCTO - Google Gemini API Pricing 2026](https://www.metacto.com/blogs/the-true-cost-of-google-gemini-a-guide-to-api-pricing-and-integration) (notes preview pricing around $1.50/$10, stabilizing at $2.00/$12.00).

**MCP Support**: ✅ Full integration available

---

## Unified APIs & Aggregators 🔗

> **One API key to access models from all providers.**

| Provider | Description | Website | Key Features | Pricing | Latest Version | Status | Verified |
|----------|-------------|---------|--------------|---------|---------------|--------|----------|
| **OpenRouter** | The widest model selection | [openrouter.ai](https://openrouter.ai) | 200+ models, crypto/fiat, rankings | Aggregated | N/A | ✅ Active | 2026-01-25 |
| **Hugging Face** | Community Hub Inference | [huggingface.co](https://huggingface.co/inference-api) | Access any OSS model, serverless | Free / Pro | N/A | ✅ Active | 2026-01-25 |

---

## Inference Clouds & Serverless ⚡

> **High-performance, low-latency infrastructure hosting open-source models.**

| Provider | Description | Website | Key Features | Pricing | Latest Version | Status | Verified |
|----------|-------------|---------|--------------|---------|---------------|--------|----------|
| **Together AI** | Fast inference cloud | [together.ai](https://together.ai) | Llama/Qwen/Mistral tuned stacks | Pay-per-token | N/A | ✅ Active | 2026-01-25 |
| **Fireworks AI** | Low-latency specialist | [fireworks.ai](https://fireworks.ai) | FireAttention engine, fine-tuning | Pay-per-token | N/A | ✅ Active | 2026-01-25 |
| **Groq** | LPU Hardware (Wait for it...) | [groq.com](https://groq.com) | Instant output (>500 T/s) | Pay-per-token | N/A | ✅ Active | 2026-01-25 |
| **Cerebras** | Wafer-Scale Engine | [cerebras.ai](https://cerebras.ai) | Massive throughput (2000 T/s) | Custom | N/A | ✅ Active | 2026-01-25 |
| **Anyscale** | Ray creators | [anyscale.com](https://anyscale.com) | Scalable production endpoints | Pay-per-token | N/A | ✅ Active | 2026-01-25 |
| **Modal** | Serverless Python | [modal.com](https://modal.com) | Define infra in code, auto-scale | Pay-per-compute | N/A | ✅ Active | 2026-01-25 |

---

## GPU Clouds & Decentralized ☁️

> **Rent raw GPU power or use decentralized networks.**

| Provider | Description | Website | Key Features | Pricing | Latest Version | Status | Verified |
|----------|-------------|---------|--------------|---------|---------------|--------|----------|
| **Vultr** | Global Cloud | [vultr.com](https://vultr.com) | 32 locations, H100s | Hourly | N/A | ✅ Active | 2026-01-25 |
| **Nebius** | AI-Centric Cloud | [nebius.com](https://nebius.com) | NVIDIA H200/Blackwell | Competitive | N/A | ✅ Active | 2026-01-25 |
| **Snova** | AI Cloud | [novita.ai](https://novita.ai) | 100+ models, cheap inference | Pay-as-you-go | N/A | ✅ Active | 2026-01-25 |
| **Hyperbolic** | Decentralized Network | [hyperbolic.xyz](https://hyperbolic.xyz) | Verifiable AI, shared GPUs | Crypto/Fiat | N/A | ✅ Active | 2026-01-25 |
| **RunPod** | GPU Rental | [runpod.io](https://runpod.io) | Community cloud, wide GPU selection| Hourly | N/A | ✅ Active | 2026-01-25 |
| **Replicate** | Model-as-a-Service | [replicate.com](https://replicate.com) | Run anything via API | Pay-per-sec | N/A | ✅ Active | 2026-01-25 |

---

## Supplementary APIs 🔗

> **Additional APIs for specialized use cases and enhanced functionality.**

### Brave Search API

**Overview**: Enterprise-grade Web search API with 35+ billion pages index. Brave Search API provides access to Brave's independent search index (35+ billion pages), offering real-time results for web, news, videos, images, and more. It emphasizes privacy-first infrastructure with low latencies and flexible pricing. Launched in 2023, updated in 2026 with AI Grounding features for enhanced AI applications.

**Pricing (January 2026)**:
- **Free Tier**: $0.00 (no credit card required); 1 request per second (RPS); 2,000 requests per month.
- **Base Tier**: $3.00 per 1,000 requests; 20 RPS; 20,000,000 requests per month.
- **Pro Tier**: $5.00 per 1,000 requests; 50 RPS; Unlimited requests.
- **AI Grounding Plan**: $4.00 per 1,000 web searches + $5.00 per 1 million tokens (input/output); optimized for AI reasoning, planning, and answer generation.
- **Custom Plans**: Available via direct contact for enterprise needs.

**Features**:
- Real-time indexing
- Low latencies
- Flexible pricing
- AI Grounding for enhanced search performance
- MCP server integration available
- Web search, Goggles (custom search filters), News/Video clusters, Images, Schema-enriched results, Infobox, FAQ, Discussions, Locations, Extra snippets for AI, Rights for AI inference and data storage.

**Updates as of January 2026**: Introduction of AI Grounding for better AI performance; expanded endpoints; better data structure for search/AI projects; comparison to Bing API with superior pricing and features.

**Use Cases**:
- AI model training data
- Real-time web search integration
- Content discovery and analysis
- Research and development

**Documentation**: [Brave Search API Documentation](https://api-dashboard.search.brave.com/app/documentation)

**Pricing Details**: [docs/pricing](docs/pricing.md)

**Official Sources**:
- **Primary Source**: [Brave Search API Pricing](https://api-dashboard.search.brave.com/app/plans) (official plans: Free at $0, Base at $3/1000, Pro at $5/1000; features listed).
- **Cross-Validation Source 1**: [Thurrott.com - Brave Releases its Search API](https://www.thurrott.com/cloud/web-browsers/283850/brave-releases-its-search-api) (confirms $3 CPM for Base tier, 20 RPS, up to 20M/month).
- **Cross-Validation Source 2**: [Brave Blog - AI Grounding](https://brave.com/blog/ai-grounding/) (details AI Grounding at $4/1000 searches + $5/1M tokens).

**MCP Support**: ✅ Available

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
