<p align="center">
  <img src="../assets/logo.png" alt="AI Models Matrix Logo" width="200">
</p>

# Awesome AI Models Matrix 🧠

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--04--02%2004%3A58%20UTC-green.svg)](https://github.com/ReadyPixels/AI_Models_Matrix)

> Research-based list of AI models, development tools, and automation resources. Use it to compare releases, pricing, benchmarks, and deployment options from official sources.

Document Version: 2.1
Last Updated: 2026-04-02 04:58 UTC
Repository: https://github.com/ReadyPixels/AI_Models_Matrix

## Contents

- [Models 🧠](#models-)
  - [Frontier Models 🚀](#frontier-models-)
  - [Model Specifications 📋](#model-specifications-)
  - [Open-Source Models 🆓](#open-source-models-)
  - [Coding Models 💻](#coding-models-)
  - [Reasoning Models 🧠](#reasoning-models-)
  - [Multimodal Models 🎨](#multimodal-models-)
  - [Hardware Requirements 🖥️](#hardware-requirements-️)
- [Development Tools 🛠️](#development-tools-️)
  - [IDEs 💻](#ides-)
  - [CLI Tools 🖥️](#cli-tools-️)
  - [IDE Add-ons 🧩](#ide-add-ons-)
  - [API Providers 🔌](#api-providers-)
- [Automation 🤖](#automation-)
  - [Browser Automation 🌐](#browser-automation-)
  - [Agent Platforms 🧩](#agent-platforms-)
  - [Desktop Automation 🖥️](#desktop-automation-️)
- [Guides 📚](#guides-)
  - [Getting Started 🚀](#getting-started-)
  - [Model Selection Guide 🎯](#model-selection-guide-)
  - [Self-Hosting Guide 🖥️](#self-hosting-guide-️)
  - [Cost Analysis 💰](#cost-analysis-)
  - [Comprehensive Benchmark Reference 📈](#comprehensive-benchmark-reference-)
- [AI Infrastructure 🏗️](#ai-infrastructure-️)
  - [Embedding & Reranking Models 🧲](#embedding--reranking-models-)
  - [Video Generation Models 🎬](#video-generation-models-)
  - [Speech & TTS Models 🔊](#speech--tts-models-)
  - [AI Safety & Guardrails 🛡️](#ai-safety--guardrails-️)
  - [RAG Frameworks 🗂️](#rag-frameworks-️)
  - [Fine-tuning Platforms ⚙️](#fine-tuning-platforms-️)
  - [Evaluation & Observability 📊](#evaluation--observability-)
  - [MCP Ecosystem 🔌](#mcp-ecosystem-)
  - [Model Routers & Load Balancers 🔀](#model-routers--load-balancers-)
  - [Small Language Models (SLMs) 📱](#small-language-models-slms-)
- [Reference 📖](#reference-)
  - [Glossary 📖](#glossary-)
  - [Comparison Tables 📊](#comparison-tables-)
  - [Data Sources 📚](#data-sources-)
- [License](#license)

## Models 🧠

Comprehensive documentation of Large Language Models (LLMs), Small Language Models (SLMs), and specialized AI models available today.

### Frontier Models 🚀

State-of-the-art proprietary AI models with cutting-edge capabilities from leading AI labs.

| Model | Company | Context | GPQA Diamond | Arena Elo | SWE-bench Verified | AIME 2025 | Pricing | Verified |
|-------|---------|---------|--------------|-----------|--------------------|-----------|---------|----------|
| **Claude Opus 4.6** | Anthropic | 1M | 91.3% | 1500 (Text) / 1549 (Code) | 80.8% | 99.8% | $5 / $25 | 2026-04-02 |
| **Claude Sonnet 4.6** | Anthropic | 1M | 89.9% | ~1438 (Text) / 1523 (Code) | 79.6% | ~95% | $3 / $15 | 2026-04-02 |
| **GPT-5.3-Codex** | OpenAI | 400K | 91.5% | — | — | — | $1.75 / $14.00 | 2026-04-02 |
| **Gemini 3.1 Pro** | Google | 1M | 94.3% | 1494 (Text) / 1455 (Code) | 80.6% | 100% | $2 / $12 | 2026-04-02 |
| **Gemini 3 Deep Think** | Google | 1M+ | ~97% | — | ~58% | — | Ultra subscription | 2026-04-02 |
| **GLM-5** | Zhipu AI | 200K | 82.0% | ~1451 (Text) / 1445 (Code) | 77.8% | 92.7% | $1.00 / $3.20 | 2026-04-02 |
| **GLM-5.1** | Zhipu AI | 200K | — | — | ~80.4% (est.) | — | $1.00 / $3.20 | 2026-04-02 |
| **MiniMax-M2.5** | MiniMax | 200K | 85.2% | — | 80.2% | 86.3% | $0.30 / $1.20 | 2026-04-02 |
| **Kimi K2.5** | Moonshot AI | 256K | 87.6% | — | 76.8% | 96.1% | $0.60 / $3.00 | 2026-04-02 |
| **DeepSeek-V4** [⚠️ Unverified] | DeepSeek | 1M+ | — | — | — | — | $0.30 / $0.50 | 2026-04-02 |
| **DeepSeek-V3.2** | DeepSeek | 164K | 87.1% | — | 67.8% | 89.3% | $0.28 / $0.42 | 2026-04-02 |
| **Qwen3.5-Max** | Alibaba | 128K | 89.3% | — | 76.4% | 91.3% | Pay-per-token | 2026-04-02 |
| **Gemini 3 Pro** | Google | 1M+ | 91.9% | 1486 (Text) / 1438 (Code) | 76.2% | 98–100% | Tiered pricing | 2026-04-02 |
| **Gemini 3 Flash** | Google | 10M | 90.4% | 1474 (Text) | 78.0% | — | $0.30 / $2.50 | 2026-04-02 |
| **Gemini 3.1 Flash-Lite** [⚠️ Unverified] | Google | 1M | — | — | — | — | $0.25 / $1.50 | 2026-04-02 |
| **GPT-5.4** | OpenAI | 1M | 92.0% | 1484 (Text) / 1457 (Code) | ~80% | 88% | $2.50 / $15.00 | 2026-04-02 |
| **GPT-5.4 mini** | OpenAI | 400K | 87.5% | — | — | — | $0.75 / $4.50 | 2026-04-02 |
| **GPT-5.4 nano** | OpenAI | 400K | — | — | — | — | $0.20 / $1.25 | 2026-04-02 |
| **Step-3.5-Flash** | StepFun | 256K | 83.1% | — | 74.4% | 97.3% | Pay-per-token | 2026-04-02 |
| **Mistral Large 3** [⚠️ Unverified] | Mistral AI | 128K | — | — | — | — | Varies | 2026-04-02 |
| **Claude Sonnet 4.5** | Anthropic | 200K | 83.4% | — | 77.2% | 87% | $3 / $15 | 2026-04-02 |
| **Llama 4 Scout** [⚠️ Unverified] | Meta | 10M | 57.2% | — | — | — | Free (self-host) | 2026-04-02 |
| **Llama 4 Maverick** [⚠️ Unverified] | Meta | 128K | 69.8% | — | — | — | Free (self-host) | 2026-04-02 |
| **Grok 4** | xAI | 128K | ~91.5% | ~1493 (Text) | — | 100% | $3 / $15 | 2026-04-02 |
| **Grok 4 Fast** [⚠️ Unverified] | xAI | 128K | — | — | — | — | $0.20 / $1.50 | 2026-04-02 |

#### Top Models by Category

| Category | #1 | #2 | #3 |
|----------|-----|-----|-----|
| **Coding** | Claude Opus 4.6 | GPT-5.3-Codex | Claude Sonnet 4.5 |
| **Reasoning** | Gemini 3 Deep Think | Qwen3-Max-Thinking | o3 |
| **Open Source** | DeepSeek-V4 | Qwen3.5-Max | Llama 4 |
| **Cost Efficiency** | DeepSeek-V3.1 | Grok 4 Fast | GLM-4.7-FlashX |
| **Context Window** | Gemini 3 Flash (10M) | Llama 4 Scout (10M) | Claude Opus 4.6 (1M) |

### Model Specifications 📋

Detailed technical specifications, pricing, and capabilities for all frontier models. Data as of April 2026.

#### Output Token Limits

Maximum output tokens per single API request.

| Model | Max Output | Context Window | Notes |
|-------|-----------|----------------|-------|
| **Claude Opus 4.6** | 128K (300K via beta) | 1M | Extended output via `output-128k-2025-02-19` beta header |
| **Claude Sonnet 4.6** | 64K | 1M | — |
| **Claude Sonnet 4.5** | 64K | 200K | — |
| **GPT-5.4** | 128K | 1.05M | — |
| **GPT-5.4 mini** | 128K | 400K | — |
| **GPT-5.4 nano** | 128K | 400K | — |
| **GPT-5.3-Codex** | 128K | 400K | — |
| **Gemini 3.1 Pro** | 64K | 1M | — |
| **Gemini 3 Pro** | 64K | 2M | — |
| **Gemini 3 Flash** | 64K | 1M | — |
| **Gemini 3.1 Flash-Lite** | 64K | 1M | — |
| **DeepSeek-V4** | 16K | 1M | — |
| **DeepSeek-V3.2** | 8K / 64K (reasoner) | 128K | Reasoner mode unlocks 64K output |
| **Qwen3.5-Max** | 65K | 1M | — |
| **GLM-5** | 128K | 200K | — |
| **GLM-5.1** | 131K | 200K | — |
| **MiniMax-M2.5** | 131K | 1M | — |
| **Kimi K2.5** | — | 256K | Not publicly specified |
| **Step-3.5-Flash** | 66K | 256K | — |
| **Grok 4** | — | 256K | Not publicly specified |
| **Grok 4 Fast** | 30K | 2M | — |
| **Mistral Large 3** | — | 262K | Not publicly specified |
| **Llama 4 Scout** | 16K | 10M | — |
| **Llama 4 Maverick** | 16K | 1M | — |

#### Cached & Batch Pricing

Discounted pricing tiers for high-volume usage. All prices in USD per million tokens.

| Model | Standard Input | Cached Input | Batch Discount | Notes |
|-------|---------------|-------------|----------------|-------|
| **Claude Opus 4.6** | $5.00 | $0.50 (hit) / $6.25 (5m write) | 50% off | Batch: $2.50 in / $12.50 out |
| **Claude Sonnet 4.6** | $3.00 | $0.30 (hit) / $3.75 (5m write) | 50% off | Batch: $1.50 in / $7.50 out |
| **Claude Sonnet 4.5** | $3.00 | $0.30 (hit) / $3.75 (5m write) | 50% off | Batch: $1.50 in / $7.50 out |
| **GPT-5.4** | $2.50 | $0.25 | 50% off | Data residency +10% |
| **GPT-5.4 mini** | $0.75 | $0.075 | 50% off | — |
| **GPT-5.4 nano** | $0.20 | $0.02 | 50% off | — |
| **GPT-5.3-Codex** | $1.75 | $0.175 | 50% off | — |
| **Gemini 3.1 Pro** | $2.00 | $0.20–$0.40 + $4.50/hr storage | 50% off | Tiered by input length |
| **Gemini 3 Flash** | $0.50 | $0.05 + $1.00/hr storage | 50% off | — |
| **Gemini 3.1 Flash-Lite** | $0.25 | Supported | Supported | Exact rate not published |
| **DeepSeek-V4** | $0.30 | $0.03 (90% off) | Off-peak 50% off | 11PM–7AM Beijing time |
| **DeepSeek-V3.2** | $0.28 | $0.028 | — | No formal batch API |
| **Qwen3.5-Max** | $0.40 | Available | 50% off | — |
| **GLM-5 / GLM-5.1** | $1.00 | $0.20 | — | — |
| **Grok 4** | $3.00 | $0.75 | — | — |
| **Grok 4 Fast** | $0.20 | $0.05 | — | — |
| **Mistral Large 3** | $0.50 | $0.05 | Available | — |
| **Step-3.5-Flash** | $0.10 | — | — | — |

#### Speed & Latency

Output throughput and time-to-first-token from [Artificial Analysis](https://artificialanalysis.ai) and provider benchmarks.

| Model | Output Speed (tok/s) | TTFT | Notes |
|-------|---------------------|------|-------|
| **Gemini 3.1 Flash-Lite** | ~363 | — | Fastest frontier model |
| **Step-3.5-Flash** | 85–350 | — | Variable by provider; peak ~350 tok/s |
| **Gemini 3 Flash** | ~193 | ~4.16s | — |
| **MiniMax-M2.5 Lightning** | ~100 | — | Faster tier |
| **GPT-5.3-Codex** | ~86 | ~77.86s | High TTFT due to extended reasoning |
| **Grok 4** | ~56 | ~8.96s | — |
| **MiniMax-M2.5 Standard** | ~50 | — | — |

> Most frontier models (Claude Opus/Sonnet 4.6, GPT-5.4, Gemini 3.1 Pro, etc.) have not yet been benchmarked on Artificial Analysis as of April 2026.

#### Training Data Cutoffs

Knowledge cutoff dates — the point after which a model has no training data.

| Model | Training Cutoff | Notes |
|-------|----------------|-------|
| **Claude Sonnet 4.6** | Jan 2026 | Most recent cutoff among frontier models |
| **Claude Opus 4.6** | Aug 2025 | Reliable knowledge: May 2025 |
| **GPT-5.4 / mini / nano** | Aug 31, 2025 | — |
| **GPT-5.3-Codex** | Aug 31, 2025 | — |
| **Grok 4 Fast** | Jul 2025 | — |
| **DeepSeek-V4** | May 2025 | — |
| **Gemini 3.1 Flash-Lite** | Jan 2026 | — |
| **Gemini 3.1 Pro / 3 Pro / 3 Flash** | Jan 2025 | — |
| **Grok 4** | ~Nov–Dec 2024 | Approximate |
| **DeepSeek-V3.2** | Jul 2024 | — |
| **Llama 4 Scout / Maverick** | Aug 2024 | — |
| **DeepSeek-R1** | ~Oct 2023 | Based on base model |

> Models not listed (Qwen, GLM, MiniMax, Kimi, Step, Mistral): training cutoff not publicly disclosed.

#### Multilingual Support

| Model | Languages | Details |
|-------|----------|---------|
| **Qwen3.5-Max** | 201 | Largest language coverage |
| **Llama 4 Scout** | 200 | Pre-training languages |
| **Qwen3-Max-Thinking** | 119 | Qwen3 series |
| **Gemini 3 Flash** | 100 | 91.8% MMMLU score across 100 languages |
| **Gemini 3.1 Pro / 3 Pro** | 100+ | — |
| **Gemini 3.1 Flash-Lite** | 100+ | 88.9% MMMLU |
| **Llama 4 Maverick** | 12 | Output languages |
| **Claude (all)** | Many | English-optimized; broad multilingual |
| **GPT-5.4 (all)** | Many | Broad multilingual coverage |
| **DeepSeek (all)** | Many | Chinese + English focused |
| **Grok (all)** | Many | — |
| **GLM-5 / GLM-5.1** | Many | 28.5T token training data |

#### Structured Output & Function Calling

All frontier models support structured JSON output and function/tool calling except where noted.

| Capability | Supported Models | Not Supported |
|-----------|-----------------|---------------|
| **Structured Output (JSON mode)** | All models listed in Frontier table | Gemini 3 Deep Think (no API) |
| **Function Calling / Tool Use** | All models listed in Frontier table | Gemini 3 Deep Think (no API) |

> **Gemini 3 Deep Think** is available only via Gemini's in-app Think mode — no API access for structured output or function calling.

#### Regional Availability

| Provider | API Availability | Cloud Partners | Notes |
|----------|-----------------|----------------|-------|
| **Anthropic** | Global | AWS Bedrock, GCP Vertex AI | US-only inference at 1.1x via `inference_geo` |
| **OpenAI** | Global | Azure OpenAI | Data residency endpoints +10% (post-3/5/26) |
| **Google** | Global | Google AI Studio, Vertex AI | Some regional restrictions per Google terms |
| **DeepSeek** | Global | Azure (R1 only, select regions) | China-based servers |
| **Alibaba (Qwen)** | Global | Alibaba Cloud Model Studio | China-based; globally accessible |
| **Zhipu AI (GLM)** | Global | Z.AI API | MIT license enables self-hosting anywhere |
| **MiniMax** | Global | MiniMax API | — |
| **Moonshot AI (Kimi)** | Global | platform.kimi.ai | MIT open-weight |
| **xAI (Grok)** | US-focused | Oracle OCI (East/Midwest/West) | Limited non-US availability |
| **Mistral** | Global | Azure AI Foundry, AWS, GCP | — |
| **Meta (Llama)** | Global (self-host) | All major cloud providers | Llama 4 Community License |
| **StepFun** | Global | HuggingFace | Apache 2.0 open-source |


### Open-Source Models 🆓

Self-hostable models with permissive licenses or open weights for privacy, cost control, and customization.

| Model | Company | Params | Context | License |
|-------|---------|--------|---------|---------|
| **DeepSeek-V4** | DeepSeek | 671B | 1M+ | MIT |
| **Qwen3.5-Max** | Alibaba | 1T+ | 128K | Apache 2.0 |
| **Qwen3-Max-Thinking** | Alibaba | 1T+ | 128K | Apache 2.0 |
| **Mistral Large 3** | Mistral AI | 675B (MoE) | 128K | Apache 2.0 |
| **Llama 4 Scout** | Meta | 109B | 10M | Community |
| **Llama 4 Maverick** | Meta | 400B | 128K | Community |
| **GPT-OSS-120B** | OpenAI | 117B | 128K | Apache 2.0 |
| **GPT-OSS-20B** | OpenAI | 21B | 128K | Apache 2.0 |
| **Qwen3-Coder** | Alibaba | 480B | 128K | Apache 2.0 |
| **GLM-4.7** | Zhipu AI | 400B+ MoE | 128K | Open Weight |
| **Phi-4** | Microsoft | 14B | 128K | MIT |
| **Granite 4.0** | IBM | 8B-3B | 128K | Apache 2.0 |
| **DeepSeek-Coder-V2** | DeepSeek | 236B | 128K | MIT |
| **GLM-5.1** | Zhipu AI | 744B (40B active MoE) | 200K | MIT |
| **Step-3.5-Flash** | StepFun | 196B (11B active MoE) | 256K | Open Weight |
| **Yi-Coder** | 01.AI | 9B/1.5B | 128K | Apache 2.0 |

#### Deployment Options

**Local Inference Tools:**
- **Ollama** - Easy local deployment
- **LM Studio** - User-friendly GUI
- **llama.cpp** - Efficient CPU inference
- **vLLM** - High-throughput serving
- **SGLang** - Structured generation

**Cloud Deployment:**
- **Hugging Face Inference** - Managed deployment
- **AWS SageMaker** - Full control
- **Google Cloud Vertex** - Integrated
- **RunPod** - GPU rental

### Coding Models 💻

Specialized AI models optimized for software development tasks.

#### SWE-bench Verified Leaderboard

| Rank | Model | Company | SWE-bench Verified |
|------|-------|---------|-------------------|
| 🥇 #1 | **Claude Opus 4.6** | Anthropic | 80.8% |
| 🥈 #2 | **Gemini 3.1 Pro** | Google | 80.6% |
| 🥉 #3 | **MiniMax-M2.5** | MiniMax | 80.2% |
| #4 | **GPT-5.4** | OpenAI | ~80% |
| #5 | **GPT-5.2** | OpenAI | 80.0% |
| #6 | **Claude Sonnet 4.6** | Anthropic | 79.6% |
| #7 | **Gemini 3 Flash** | Google | 78.0% |
| #8 | **GLM-5** | Zhipu AI | 77.8% |
| #9 | **Claude Sonnet 4.5** | Anthropic | 77.2% |
| #10 | **Kimi K2.5** | Moonshot AI | 76.8% |

#### Commercial Coding Models

| Model | Developer | Pricing | Best For |
|-------|-----------|---------|----------|
| **Claude Opus 4.6** | Anthropic | $5 / $25 per 1M | Agentic coding, complex tasks |
| **GPT-5.3-Codex** | OpenAI | TBD | Agentic coding, 7+ hour autonomy |
| **Claude Haiku 4.5** | Anthropic | $1 / $5 per 1M | Low-latency coding, sub-agents, computer use |
| **GLM-5-Code** | Zhipu AI | $1.20 / $5.00 per 1M | Code generation, refactoring |
| **MiniMax-M2.5** | MiniMax | $0.30 / $1.20 per 1M | Code generation, refactoring |
| **Claude Sonnet 4.5** | Anthropic | $3 / $15 per 1M | Code review, refactoring |
| **Codestral** | Mistral AI | $0.30 / $0.90 | Real-time completion |
| **Grok 4 Fast** | xAI | $0.20 / $1.50 | Most used (50% share) |

#### Open-Source Coding Models

| Model | Developer | License | Hardware |
|-------|-----------|---------|----------|
| **GPT-OSS-120B** | OpenAI | Apache 2.0 | 80-160 GB VRAM |
| **Qwen3-Coder** | Alibaba | Apache 2.0 | 160-320 GB VRAM |
| **DeepSeek-Coder-V2** | DeepSeek | MIT | 48-80 GB VRAM |
| **GLM-4.6** | Zhipu AI | Open Weight | 80-160 GB VRAM |
| **Phi-4** | Microsoft | MIT | 24-48 GB VRAM |

### Reasoning Models 🧠

Models optimized for step-by-step reasoning, mathematical problem-solving, and complex logical inference.

#### AIME 2025 Leaderboard

| Rank | Model | AIME 2025 | ARC-AGI-2 | Notes |
|------|-------|-----------|-----------|-------|
| 🥇 #1 | **Gemini 3.1 Pro** | 100% | 77.1% | Highest combined reasoning |
| 🥈 #2 | **GPT-5.2** | 100% | 52.9% | No tools needed |
| 🥉 #3 | **Grok 4** | 100% | — | First-principles reasoning |
| #4 | **Claude Opus 4.6** | 99.8% | 68.8% | Near-perfect AIME |
| #5 | **Gemini 3 Pro** | 98–100% | 31.1–45.1% | With code execution |
| #6 | **Step-3.5-Flash** | 97.3% | — | Best efficiency ratio |
| #7 | **Kimi K2.5** | 96.1% | — | Strong multimodal reasoning |
| #8 | **Claude Sonnet 4.6** | ~95% | 58.3% | Near-Opus performance |
| #9 | **GLM-5** | 92.7% | — | Thinking mode |
| #10 | **DeepSeek-V3.2** | 89.3% | — | Budget reasoning |

#### Reasoning Model Details

| Model | Type | Context | Pricing |
|-------|------|---------|---------|
| **Gemini 3 Deep Think** | Reasoning | 1M+ | Ultra subscription |
| **Qwen3-Max-Thinking** | Reasoning/Coding | 128K | $1.20 / $6.00 |
| **o3 / o1-Pro** | Reasoning | 128K | $2-150 / $8-600 |
| **Gemini 3 Pro** | General/Multimodal | 1M+ | $2 / $12 |
| **DeepSeek-R1** | Reasoning | 128K | $0.50 / $2.15 |
| **Claude Sonnet 4.5** | Hybrid | 200K | $3 / $15 |

#### Use Cases

- **Mathematical Problem Solving**: Qwen3-Max-Thinking, GPT-5 Pro, Gemini 3 Pro
- **Scientific Analysis**: Claude Opus 4.6, GPT-5, Gemini 3 Pro
- **Strategic Planning**: o3/o1-Pro, Claude Sonnet 4.5, DeepSeek-R1
- **Code Debugging**: Claude Sonnet 4.5, GPT-5.3-Codex, DeepSeek-V3.1

### Multimodal Models 🎨

Models capable of processing and generating multiple types of content: text, images, audio, and video.

#### Leading Multimodal Models

| Model | Developer | Context | Key Features |
|-------|-----------|---------|--------------|
| **GPT-5.4** | OpenAI | 1M | Unified multimodal, audio |
| **Gemini 3 Pro** | Google | 1M+ | Native multimodal, video |
| **Claude Sonnet 4.5** | Anthropic | 200K | Document understanding |
| **Llama 4 Maverick** | Meta | 128K | Open multimodal |

#### Vision Capabilities

| Model | MMMU / MMMU-Pro | MathVista | DocVQA |
|-------|----------------|-----------|--------|
| **Gemini 3.1 Pro** | 95% (MMMU-Pro) | — | — |
| **GPT-5.4** | 94% (MMMU-Pro) | — | — |
| **Gemini 3 Pro** | 81% (MMMU-Pro) | — | — |
| **Gemini 3 Flash** | 80% (MMMU-Pro) | — | — |
| **Claude Sonnet 4.5** | 77.8% (MMMU) | — | — |
| **Llama 4 Maverick** | 73.4% (MMMU) | — | — |

#### Audio & Video

| Model | Speech-to-Text | Text-to-Speech | Video Input |
|-------|----------------|----------------|-------------|
| **Gemini 3 Pro** | ✅ | ✅ | ✅ |
| **GPT-5** | ✅ | ✅ | ⚠️ |
| **Whisper v3** | ✅ | ❌ | ✅ |

#### Image Generation

| Model | Developer | License | Best For |
|-------|-----------|---------|----------|
| **Flux.1** | Black Forest Labs | Apache 2.0 | High-fidelity art |
| **Stable Diffusion 3.5** | Stability AI | Community License | Fine-tuning |
| **GLM-Image** | Zhipu AI (Z.ai) | API | Fast image generation |
| **CogView-4** | Zhipu AI (Z.ai) | API | Creative image generation |

### Hardware Requirements 🖥️

Comprehensive hardware specifications for self-hosting AI models.

#### Quick Reference by Model Size

| Model | Params | Q4 Size | Min VRAM | Rec VRAM | Min RAM |
|-------|--------|---------|----------|----------|---------|
| **Phi-4** | 14B | 8 GB | 24 GB | 48 GB | 32 GB |
| **GPT-OSS-20B** | 21B | 12 GB | 24 GB | 48 GB | 32 GB |
| **Llama 4 Scout** | 109B | 66 GB | 48 GB | 80 GB | 96 GB |
| **GPT-OSS-120B** | 117B | 70 GB | 80 GB | 160 GB | 128 GB |
| **DeepSeek-Coder-V2** | 236B | 143 GB | 48 GB | 80 GB | 192 GB |
| **Llama 4 Maverick** | 400B | 242 GB | 160 GB | 320 GB | 320 GB |
| **DeepSeek-V4** | 671B | 404 GB | 80 GB | 320 GB | 512 GB |
| **Qwen3-Max-Thinking** | 1T+ | 600+ GB | 160 GB | 640 GB | 768 GB |

#### By Hardware Tier

**Consumer/Entry Level (24-48 GB VRAM):**
- Phi-4, GPT-OSS-20B, Yi-Coder, Qwen2.5-Coder
- **Recommended GPUs**: RTX 3090 (24GB), RTX 4090 (24GB)

**Professional (80-160 GB VRAM):**
- Llama 4 Scout, GPT-OSS-120B, DeepSeek-Coder-V2
- **Recommended GPUs**: A100 80GB, 2x A100 40GB

**Enterprise (320+ GB VRAM):**
- Llama 4 Maverick, GLM-4.7, DeepSeek-V4, Qwen3-Max-Thinking
- **Recommended GPUs**: 4x A100 80GB, 8x A100 80GB

#### Quantization Explained

| Level | Bits | Size vs FP16 | Quality | Use Case |
|-------|------|--------------|---------|----------|
| **FP16/BF16** | 16 | 100% | Best | Training |
| **Q8_0** | 8 | ~50% | Excellent | High-quality inference |
| **Q4_K_M** | 4 | ~25% | Good | Recommended for deployment |
| **Q3_K_M** | 3 | ~19% | Fair | Limited resources |

---

### Comprehensive Benchmark Reference 📈

Detailed benchmark scores across all major evaluations. Scores are percentages (%) unless noted. Arena Elo scores are integers. `—` = not publicly reported. Data as of April 2026.

#### Full Benchmark Table

| Model | GPQA Diamond | MMLU-Pro | Arena Elo (Text) | HLE | SWE-bench Verified | SWE-bench Pro | LiveCodeBench | AIME 2025 | ARC-AGI-2 | MMMU-Pro | IFEval | FrontierMath |
|-------|-------------|----------|------------------|-----|--------------------|--------------|--------------|-----------|-----------|---------|---------|----|
| **Claude Opus 4.6** | 91.3% | — | 1500 | 40.0–53.0% | 80.8% | — | — | 99.8% | 68.8% | — | — | — |
| **Claude Sonnet 4.6** | 89.9% | — | ~1438 | 33.2–49.0% | 79.6% | — | — | ~95% | 58.3% | — | — | — |
| **Claude Sonnet 4.5** | 83.4% | 88.0% | — | — | 77.2% | — | — | 87–100% | — | — | — | — |
| **GPT-5.4** | 92.0% | 94% | 1484 | 36.6–41.6% | ~80% | 57.7% | 84–88% | 88% | 73.3% | 94% | — | 50% (Pro) |
| **GPT-5.4 mini** | 87.5% | — | — | — | — | 54.4% | — | — | — | — | — | — |
| **GPT-5.3-Codex** | 91.5% | — | — | — | — | 56.8% | 85% | — | — | — | — | — |
| **GPT-5.2** | 92.4% | — | 1479 | 35.2% | 80.0% | 55.6% | — | 100% | 52.9% | — | 95.6% | ~40.3% |
| **Gemini 3.1 Pro** | 94.3% | 92% | 1494 | 44.4–51.4% | 80.6% | 54.2–72% | 71% | 100% | 77.1% | 95% | 95% | — |
| **Gemini 3 Pro** | 91.9–93.8% | 83% | 1486 | 37.5% | 76.2% | 43.3% | 49% | 98–100% | 31.1–45.1% | 81% | 88% | 38% |
| **Gemini 3 Flash** | 90.4% | 72% | 1474 | 33.7% | 78.0% | 44% | — | — | — | 80% | 85% | — |
| **Gemini 3 Deep Think** | ~97% | 81% | — | 48.4% | ~58% | 63% | 58% | — | 84.6% | — | — | — |
| **DeepSeek-V3.2** | 87.1% | 85.0% | — | 25.1% | 67.8% | — | — | 89.3% | — | — | — | — |
| **DeepSeek-R1** | 71.5% | 84.0% | — | 8.5% | 49.2% | — | 63.5% | 70.0% | — | — | — | — |
| **Qwen3.5-Max** | 89.3% | — | — | — | 76.4% | — | — | 91.3% | — | 79% | — | — |
| **Qwen3-Max-Thinking** | 86.1% | — | — | 26.2% | — | — | — | — | — | — | — | — |
| **GLM-5** | 82.0% | — | ~1451 | 10.4% | 77.8% | — | — | 92.7% | — | — | — | — |
| **GLM-5.1** | — | — | — | — | ~80.4% (est.) | — | — | — | — | — | — | — |
| **Kimi K2.5** | 87.6% | 87.1% | — | 31.5–50.2% | 76.8% | — | 85.0% | 96.1% | — | 78.5% | — | — |
| **MiniMax-M2.5** | 85.2% | — | — | — | 80.2% | 55.4% | — | 86.3% | — | — | — | — |
| **Step-3.5-Flash** | 83.1% | — | — | — | 74.4% | — | 86.4% | 97.3% | — | — | — | — |
| **Grok 4** | ~91.5% | 91.5% | ~1493 | 50.7% | — | — | — | 100% | — | — | — | — |
| **Llama 4 Maverick** | 69.8% | 80.5% | — | — | — | — | 43.4% | — | — | — | — | — |
| **Llama 4 Scout** | 57.2% | 74.3% | — | — | — | — | 32.8% | — | — | — | — | — |

#### FrontierMath Scores

[FrontierMath](https://epoch.ai/frontiermath/tiers-1-4/about) is a benchmark of 350 original, exceptionally challenging mathematics problems created by expert mathematicians (Epoch AI). Problems span number theory, analysis, algebraic geometry, and category theory. Tier 4 problems can take research mathematicians multiple days.

| Model | Tiers 1–3 | Tier 4 | Source |
|-------|-----------|--------|--------|
| **GPT-5.4 Pro** | 50% | ~36–38% | [Epoch AI](https://epoch.ai/benchmarks/frontiermath-tier-4) |
| **GPT-5.2 Pro** | ~40.3% | 31% | [Epoch AI](https://epochai.substack.com/p/new-record-on-frontiermath-tier-4) |
| **Gemini 3 Pro** | 38% | 19% | [Epoch AI](https://epoch.ai/benchmarks/frontiermath-tier-4) |
| **GPT-5.1 Thinking** | ~25% | — | [llm-stats](https://llm-stats.com/benchmarks/frontiermath) |

#### Benchmark Glossary

| Benchmark | Description | Source |
|-----------|-------------|--------|
| **GPQA Diamond** | Graduate-level science questions (PhD difficulty) | Google Research |
| **MMLU-Pro** | Extended multi-task language understanding (harder than MMLU) | TIGER-Lab |
| **Arena Elo** | Crowdsourced human preference ranking | [lmarena.ai](https://lmarena.ai/leaderboard) |
| **HLE** | Humanity's Last Exam — expert-level questions | [Scale AI](https://lastexam.ai) |
| **SWE-bench Verified** | Real GitHub issue resolution (human-verified subset) | [SWE-bench](https://www.swebench.com) |
| **SWE-bench Pro** | More challenging subset of SWE-bench | [SWE-bench](https://www.swebench.com) |
| **LiveCodeBench** | Live competitive programming problems (not in training data) | [LiveCodeBench](https://livecodebench.github.io) |
| **AIME 2025** | American Invitational Mathematics Examination | MAA |
| **ARC-AGI-2** | Abstract reasoning challenge (fluid intelligence) | [ARC Prize](https://arcprize.org) |
| **MMMU / MMMU-Pro** | Multi-discipline multimodal understanding | [MMMU](https://mmmu-benchmark.github.io) |
| **IFEval** | Instruction-following evaluation | Google Research |
| **FrontierMath** | Expert-level research mathematics (Epoch AI) | [Epoch AI](https://epoch.ai/frontiermath/tiers-1-4/about) |



## Development Tools 🛠️

AI-powered tools for software development, from IDEs and CLI tools to API providers and IDE extensions.

### IDEs 💻

Integrated Development Environments with built-in AI capabilities.

#### Agentic IDEs

| IDE | Platform | Version | Release Date | Pricing | Key Features | GitHub |
|-----|----------|---------|---------------|---------|--------------|--------|
| **Firebase Studio** | Web | - | - | Free (3 workspaces, up to 30 with Google Developer Program) | Cloud-based, Gemini, MCP | [🔗](https://github.com/firebase-studio) |
| **[Lingma IDE (通义灵码)](https://lingma.aliyun.com/download)** | Windows, macOS | - | - | Free (download) | Built-in agent, MCP tool use, terminal command execution | ❌ |
| **Tonkotsu** | Windows, macOS | - | - | Free (during early access) | Team of agents, workflow | [🔗](https://github.com/tonkotsu-ai) |
| **OpenCode** | Windows, macOS, Linux | - | - | Free (OSS) | Terminal, desktop, IDE extension, multi-provider | [🔗](https://github.com/anomalyco/opencode) |
| **Codex app** | Windows | - | 2026-03-04 00:00 UTC | Included with Codex plans | Multiple agents, isolated worktrees, reviewable diffs, CLI and IDE interop | [🔗](https://github.com/openai/codex) |
| **Visual Studio** | Windows, macOS | 17.14.12+, 18.1.0+ | 2026-01-06 00:00 UTC | Free / $250/yr | Gemini 3 Flash integration, faster performance, zero-migration upgrades, real-time profiler agent | ❌ |
| **IntelliJ IDEA** | Windows, macOS, Linux | 2025.3.2 | 2026-01 | Free / $149/yr | Java 24 support, Kotlin K2 mode, performance and memory improvements | ❌ |

#### Native AI Editors

| Editor | Platform | Version | Release Date | Pricing | Key Features | GitHub |
|--------|----------|---------|---------------|---------|--------------|--------|
| **Zed** | macOS, Windows, Linux | 0.226.3 | 2026-03-03 00:00 UTC | Free (OSS) + Copilot $10/mo | Fast, collaboration, Gemini and Claude, Zeta AI, agent thread history, edit prediction providers, self-hosted OpenAI-compatible servers | [🔗](https://github.com/zed-industries/zed) |
| **Dyad** | Windows, macOS, Linux | - | - | Free (OSS) | Local generation, BYO keys | [🔗](https://github.com/dyad-sh/dyad) |
| **Memex** | macOS, Windows | - | - | Freemium (Free + $10/mo) | Agentic, browser↔desktop | [🔗](https://github.com/memextech) |

#### VS Code Forks

| IDE | Platform | Version | Release Date | Pricing | Autonomous | MCP | GitHub |
|----------|---------|---------|---------------|---------|------------|-----|--------|
| **Cursor** | Windows, macOS, Linux | 0.46+ | 2026-02-12 00:00 UTC | Freemium (Free + Pro $19/mo or $39/mo) | ✅ | ❌ | ❌ |
| **Windsurf** | Windows, macOS, Linux | 1.9552+ | 2026-02-12 00:00 UTC | Freemium (Free + Pro) | ✅ | ✅ | ❌ |
| **Trae** | macOS, Windows | - | - | Free | ❌ | ❌ | [🔗](https://github.com/Trae-AI/TRAE) |
| **PearAI** | Windows, macOS, Linux | - | - | Free (OSS) | ✅ | ❌ | [🔗](https://github.com/trypear/pearai-app) |
| **Void** | Windows, macOS, Linux | - | - | Free (OSS) | ✅ | ✅ | [🔗](https://github.com/voideditor/void) |
| **Kiro** | Windows, macOS, Linux | - | - | Free (Preview) | ✅ | ✅ | [🔗](https://github.com/kirodotdev/Kiro) |

#### Web-Based IDEs

| IDE | Platform | Version | Release Date | Pricing | Self-Hostable | Best For | GitHub |
|----------|----------|---------|---------------|---------|---------------|----------|--------|
| **Replit 3** | Web | - | - | Free Starter, Core **$20/mo**, Pro $100/mo | ❌ | Learning/Prototyping | ❌ |
| **Bolt.new** | Web | - | - | Free, Pro $20-25/mo, Teams **$30/user/mo** | ❌ | Quick apps | ❌ |
| **Bolt.diy** | Self-hosted | - | - | Free (MIT), bring your own API | ✅ | Self-hosted | [🔗](https://github.com/stackblitz-labs/bolt.diy) |
| **Lovable** | Web | - | - | Free (5 credits/day), Pro $25/mo, Business $50/mo | ❌ | UI/Full-stack | ❌ |
| **v0** | Web | - | - | Free ($5 credits/mo), Premium $20/mo, Teams $30/user | ❌ | React components | ❌ |
| **Gitpod** | Web | - | - | Free + Paid | ❌ | Cloud dev environments | ❌ |
| **Rork** | Web | - | - | Free & Paid (credits) | ❌ | Mobile apps (iOS/Android) | ❌ |
| **Google Antigravity** | Web | - | - | Google AI Pro / Ultra | Agent-first development with Gemini-powered coding | ❌ |
| **Jules** | Web | - | 2025-05-20 00:00 UTC | Free beta, higher limits on Google AI Pro / Ultra | Async repo agent, reviewable diffs, GitHub integration | ❌ |

### CLI Tools 🖥️

Command-line AI tools for autonomous coding and terminal enhancement.

#### Autonomous Coding Agents

| Tool | Platform | Pricing | Key Features | GitHub |
|------|----------|---------|--------------|--------|
| **Aider** | Windows, macOS, Linux | Free | Gold standard, Architect mode, thinking tokens | [🔗](https://github.com/Aider-AI/aider) |
| **Claude Code 2.1+** | macOS, Linux, Windows | Free + API | Fast mode for Opus 4.6, simple mode file editing, Unicode fix | [🔗](https://github.com/anthropics/claude-code) |
| **Codex CLI** | Windows, macOS, Linux | Included | Sandbox, approval modes | [🔗](https://github.com/openai/codex) |
| **Goose** | Windows, macOS, Linux | Free (Apache-2.0) | MCP, extensible, desktop app, 25+ providers | [🔗](https://github.com/block/goose) |
| **GPT-Pilot** | Windows, macOS, Linux | Free | Full dev team simulation | [🔗](https://github.com/Pythagora-io/gpt-pilot) |
| **OpenHands** | Windows, macOS, Linux | Free | Cloud agents, MCP | [🔗](https://github.com/OpenHands/OpenHands) |
| **Mentat** | Windows, macOS, Linux | Free | Multi-file coordination | [🔗](https://github.com/AbanteAI/mentat) |

#### Assisted CLI Tools

| Tool | Developer | Pricing | Best For |
|------|-----------|---------|----------|
| **Gemini CLI** | Google | Free | Google ecosystem |
| **Cursor CLI** | Cursor | Free tier | Terminal + IDE bridge |
| **Qwen Code** | Alibaba | Free | Qwen optimization |
| **Qodo CLI** | Qodo | Free tier | Testing and review |

#### Terminal Enhancers

| Tool | Platform | Pricing | Key Features |
|------|----------|---------|--------------|
| **Warp Terminal** | macOS, Linux, Windows | Free | AI Agents, workflow sharing |
| **Fig** | macOS, Linux | Free | Autocomplete, AI suggestions |

### IDE Add-ons 🧩

Extensions and plugins that add AI capabilities to existing IDEs.

#### Universal (Cross-Platform)

| Add-on | Platform | Pricing | Context | Best For | GitHub |
|--------|----------|---------|---------|----------|--------|
| **GitHub Copilot** | VS Code, JetBrains, Vim | Free / $10/mo / $39/mo | Large | General coding | ❌ |
| **Supermaven** | VS Code, JetBrains, Neovim | Free / $10/mo | 1M | Large codebases | ❌ |
| **Codeium** | VS Code, JetBrains, Vim | Free / $15/mo / $60/mo | Medium | Free alternative | ❌ |
| **Continue** | VS Code, JetBrains | Free (OSS) | Custom | Self-hosted | [🔗](https://github.com/continuedev/continue) |
| **Cody** | VS Code, JetBrains, Web | Free (discontinued) / Enterprise Starter $19/mo / Enterprise $59/mo | Enterprise | Code search | [🔗](https://github.com/sourcegraph/cody-vs) |
| **Tabnine** | VS Code, JetBrains, VS, Eclipse | Free / $39/mo | Local | Privacy | ❌ |

#### VS Code Specific

| Add-on | Pricing | Autonomous | MCP | Best For | GitHub |
|--------|---------|------------|-----|----------|--------|
| **Codex** | Free (with ChatGPT Plus $20/mo or Pro $200/mo) | ✅ | ✅ | OpenAI's official coding agent | [🔗](https://github.com/openai/codex) |
| **Cline** | Free | ✅ | ✅ | Full agent | [🔗](https://github.com/cline/cline) |
| **GitHub Copilot (Agent Mode)** | $0 / $10 / $39/mo | ⚠️ | ❌ | Guided agent workflows | ❌ |
| **RooCode** | Free/Pro | ⚠️ | ❌ | Complex tasks | [🔗](https://github.com/RooCodeInc/Roo-Code) |
| **Keploy** | OSS/Enterprise | ❌ | ❌ | Testing | ❌ |

#### JetBrains Specific

| Add-on | Pricing | Claude Agent | Best For |
|--------|---------|--------------|----------|
| **JetBrains AI Assistant** | $10/mo (Pro), $249/yr (Ultimate) | ✅ | Deep IDE integration |
| **JetBrains Claude Agent** | Included in subscription | ✅ | Native agent |

### API Providers 🔌

Services for accessing AI models via API.

#### Model Labs (Direct)

| Provider | Models | Pricing |
|----------|--------|---------|
| **OpenAI** | GPT-5.4, GPT-5.4 mini, GPT-5.4 nano, o3, Codex | Pay-per-token |
| **Anthropic** | Claude Opus 4.6, Sonnet 4.6, Haiku 4.5 | Pay-per-token |
| **Google AI Studio** | Gemini 3.1 Pro, Gemini 3.1 Flash-Lite, Gemini 3 Flash | Free / Pay |
| **Z.ai (Zhipu AI)** | GLM-5, GLM-5-Code, GLM-4.7 | Pay-per-token |
| **MiniMax** | MiniMax-M2.5/M2.1/M2 | Pay-per-token |
| **Cohere** | Command, Embed, Rerank | Pay-per-token |
| **AI21 Labs** | Jamba | Pay-per-token |
| **Perplexity** | Sonar / Sonar Pro / Sonar Reasoning Pro | Pay-per-token + request fees |
| **Moonshot AI** | Kimi (kimi-k2.5, kimi-k2-thinking) | Pay-per-token |
| **ByteDance (Volcengine)** | Doubao | Pay-per-token |
| **Tencent (Hunyuan)** | Hunyuan | Pay-per-token |
| **Baidu (ERNIE)** | ERNIE | Pay-per-token |
| **DeepSeek** | DeepSeek-V4/R1 | Pay-per-token |
| **Mistral AI** | Mistral Large 3 | Pay-per-token |
| **xAI** | Grok-4 | Pay-per-token |

#### Unified APIs & Aggregators

| Provider | Models | Key Features |
|----------|--------|--------------|
| **OpenRouter** | 200+ | Crypto/fiat, rankings |
| **Hugging Face** | Thousands | Serverless inference |

#### Inference Clouds

| Provider | Specialization | Speed |
|----------|----------------|-------|
| **Together AI** | Llama/Qwen/Mistral | Fast |
| **Fireworks AI** | FireAttention | Low-latency |
| **Groq** | LPU | >500 T/s |
| **Cerebras** | Wafer-Scale | >2000 T/s |

#### GPU Clouds

| Provider | Type | Best For |
|----------|------|----------|
| **RunPod** | GPU Rental | Flexibility |
| **Replicate** | Model-as-a-Service | Quick deployment |
| **Vultr** | Global Cloud | Hourly |
| **Hyperbolic** | Decentralized | Crypto/Fiat |

---

## Automation 🤖

AI-powered tools for automating browser and desktop tasks.

### Browser Automation 🌐

Tools and frameworks for AI-powered browser automation.

#### Standalone AI Browsers

| Browser | Pricing | Open Source | Local AI | Best For | GitHub |
|---------|---------|-------------|----------|----------|--------|
| **Sigma AI Browser** | Freemium (Free + Pro $9.99/mo) | ❌ | ✅ | Offline AI, agentic browsing | ❌ |
| **ChatGPT Atlas** | Free (with ChatGPT subscription) | ❌ | ❌ | OpenAI integration, macOS | [🔗](https://github.com/ComposioHQ/open-chatgpt-atlas) |
| **Genspark** | Freemium (Free + Plus $19.99/mo + Pro $249/mo) | ❌ | ❌ | AI Super Agent, research | ❌ |
| **BrowserOS** | Free | ✅ | ✅ | Privacy-focused | [🔗](https://github.com/browseros-ai/BrowserOS) |
| **Brave Leo** | Freemium (Free + Premium) | ❌ | ⚠️ (Experimental) | Privacy-focused AI | ❌ |
| **Fellou** | Freemium (Free for 4 tasks, $19/mo Pro) | ❌ | ❌ | True agentic browser | [🔗](https://github.com/FellouAI/eko) |
| **Perplexity Comet** | Free (with Pro $20/mo) or $5/mo Standalone | ❌ | ❌ | Research | ❌ |
| **Dia** | Freemium (Free limited, $20/mo Pro, Dia+ $50/mo) | ❌ | ❌ | Arc replacement | ❌ |
| **Opera Neon** | $19.90/mo | ❌ | ❌ | Agentic browsing | ❌ |
| **Opera One (Aria)** | Free | ❌ | ❌ | Built-in AI assistant | ❌ |
| **Edge Copilot** | Free (Copilot Pro $20/mo) | ❌ | ❌ | Enterprise AI browser | ❌ |
| **BrowserGPT** | Freemium (Free + Premium) | ❌ | ❌ | Mobile-first AI browser (iOS/Android) | ❌ |
| **Arc Max** | Free | ❌ | ❌ | AI-enhanced browsing, macOS | ❌ |
| **AnythingLLM** | Free (OSS) | ✅ | ✅ | All-in-one desktop AI, document chat, local models | [🔗](https://github.com/Mintplex-Labs/anything-llm) |

#### Browser Extensions

| Extension | Pricing | Free | Multi-Agent | Best For | GitHub |
|-----------|---------|------|-------------|----------|--------|
| **Harpa AI** | Free | ✅ | ❌ | Automation recipes | [🔗](https://github.com/wvkv/harpa) |
| **MultiOn** | Free/Paid | ⚠️ | ✅ | Complex tasks | [🔗](https://github.com/tmc/multion-api) |
| **NanoBrowser** | Free | ✅ | ✅ | Local control | [🔗](https://github.com/nanobrowser/nanobrowser) |
| **Neobrowser** | Free (OSS) | ✅ | ❌ | Local LLMs via Ollama, privacy-first, Chrome/Edge | ❌ |

#### Developer Libraries

| Library | Language | Best For | GitHub |
|---------|----------|----------|--------|
| **Browser-use** | Python | Agentic automation | [🔗](https://github.com/browser-use/browser-use) |
| **Stagehand** | TypeScript | Web apps | [🔗](https://github.com/browserbase/stagehand) |
| **LaVague** | Python | NL to code | [🔗](https://github.com/lavague-ai/LaVague) |
| **Skyvern** | Python | CV-based automation | [🔗](https://github.com/Skyvern-AI/skyvern) |
| **Firecrawl** | Python / CLI | LLM-powered crawling & scraping with prompt chaining | [🔗](https://github.com/mendableai/firecrawl) |

#### Cloud Automation

| Service | Platform | Pricing | Best For | GitHub |
|---------|----------|---------|----------|--------|
| **ChatGPT agent** | ChatGPT | Plus / Pro / Team | Guided browser tasks, research, forms, and spreadsheets | ❌ |
| **Project Mariner** | Google AI Ultra | Included with Google AI Ultra | Multi-step browser tasks, shopping, and reservations | ❌ |
| **Skyvern Cloud** | Cloud API | Paid | Resilient automation | [🔗](https://github.com/Skyvern-AI/skyvern) |
| **Browserbase** | Cloud API | Paid | Stealth mode, session recording | ❌ |

### Agent Platforms 🧩

Platforms and runtimes for running or connecting AI agents.

| Project | Type | Pricing | Self-Hostable | Best For | Official |
|---------|------|---------|:-------------:|----------|:-------:|
| **OpenClaw** | Personal AI assistant | Free (OSS) | ✅ | Always-on assistant across chat channels | [🔗](https://github.com/openclaw/openclaw) |
| **NanoClaw** | Lightweight agent framework | Free (OSS) | ✅ | Containerized agents for WhatsApp, Telegram, Slack, Discord | [🔗](https://github.com/qwibitai/NanoClaw) |
| **CrewAI** | Multi-agent orchestration | Free (OSS) / Enterprise | ✅ | Team-based AI agent workflows | [🔗](https://github.com/crewAIInc/crewAI) |
| **AutoGen** | Multi-agent framework | Free (OSS) | ✅ | Conversational agent collaboration | [🔗](https://github.com/microsoft/autogen) |
| **LangGraph** | Agent framework | Free (OSS) / LangSmith paid | ✅ | Stateful, cyclic agent workflows | [🔗](https://github.com/langchain-ai/langgraph) |
| **Dify** | LLM app platform | Free (OSS) / Cloud plans | ✅ | Visual workflow builder, RAG, agents | [🔗](https://github.com/langgenius/dify) |
| **n8n** | Workflow automation | Free (OSS) / Cloud from $20/mo | ✅ | No-code automation with AI agent nodes | [🔗](https://github.com/n8n-io/n8n) |
| **Flowise** | LLM orchestration | Free (OSS) | ✅ | Drag-and-drop LLM flow builder | [🔗](https://github.com/FlowiseAI/Flowise) |
| **Lindy** | AI agent builder | Freemium (Free + Pro $49/mo) | ❌ | No-code AI agents for business tasks | [🔗](https://www.lindy.ai/) |
| **Relevance AI** | Agent platform | Freemium (Free + Paid plans) | ❌ | Build and deploy AI agents, no-code | [🔗](https://relevanceai.com/) |
| **Moltbook** | Agent social network | Free | ❌ | Discovering and pairing with AI agents | [🔗](https://www.moltbook.com/) |
| **ZeroClaw** | Privacy-first agent runtime (Rust) | Free (OSS) | ✅ | Deploy anywhere, swap any LLM, zero external API calls | [🔗](https://github.com/zeroclaw-labs/zeroclaw) |
| **NullClaw** | Sandboxed agent runtime (Zig) | Free (OSS) | ✅ | Ultra-fast, minimal footprint, sandboxed agent tasks | [🔗](https://github.com/nullclaw/nullclaw) |
| **Moltis** | Rust-native single-binary agent | Free (OSS) | ✅ | Sandboxed, auditable, voice + memory + MCP tools built-in | [🔗](https://github.com/moltis-org/moltis) |
| **Hermes Agent** | Adaptive agent framework (Nous Research) | Free (OSS) | ✅ | Memory management, skills, UI dashboard, grows with you | [🔗](https://github.com/NousResearch/hermes-agent) |
| **PicoClaw** | Ultra-lightweight agent (Go) | Free (OSS) | ✅ | Tiny, fast, embedded/IoT deployments, single-binary | [🔗](https://github.com/sipeed/picoclaw) |
| **AutoGPT** | Autonomous agent | Free (OSS) | ✅ | Self-prompting GPT agent with memory, pioneer project | [🔗](https://github.com/Significant-Gravitas/AutoGPT) |
| **BabyAGI** | Task-driven agent | Free (OSS) | ✅ | Autonomous task creation and prioritization | [🔗](https://github.com/yoheinakajima/babyagi) |
| **Suna** | Generalist agent | Free (OSS) | ✅ | Versatile open-source agent for complex tasks (Kortix) | [🔗](https://github.com/kortix-ai/suna) |
| **OWL** | Multi-agent framework | Free (OSS) | ✅ | Distributed task automation (Camel-AI) | [🔗](https://github.com/camel-ai/owl) |
| **CogAgent** | Vision GUI model | Free (Research) | ✅ | High-performance vision-based GUI understanding (Tsinghua/Zhipu) | [🔗](https://github.com/THUDM/CogVLM2) |
| **HyperAgent** | Code agent | Free (OSS) | ✅ | GitHub issue resolution, repository-level code generation | [🔗](https://github.com/FSoft-AI4Code/HyperAgent) |

#### Cloud Agent Services

Managed cloud services for building and deploying AI agents at scale.

| Service | Provider | Pricing | Best For |
|---------|----------|---------|----------|
| **Google Vertex AI Agent Builder** | Google Cloud | Pay-per-use | Enterprise agents grounded in Google Search and data stores |
| **Amazon Bedrock Agents** | AWS | Pay-per-use | Serverless agents with knowledge bases and guardrails |
| **Azure AI Agent Service** | Microsoft Azure | Pay-per-use | Enterprise agents with Azure AI Search and OpenAI integration |

### Desktop Automation 🖥️

AI agents and tools for automating desktop tasks and OS-level interactions.

#### AI Agents (Computer Use)

##### Local Computer Use Agents

Agents that run directly on your machine and interact with the OS, screen, keyboard, and mouse.

| Agent | Windows | macOS | Linux | Vision | Best For | GitHub |
|-------|:-------:|:-----:|:-----:|:------:|----------|--------|
| **Agent S** | ✅ | ✅ | ✅ | ✅ | Research/SOTA, GUI grounding | [🔗](https://github.com/simular-ai/Agent-S) |
| **Simular Agent S2** | ✅ | ✅ | ✅ | ✅ | Latest SOTA, improved grounding | [🔗](https://github.com/simular-ai/Agent-S) |
| **Open Interpreter** | ✅ | ✅ | ✅ | ⚠️ | Natural language computer control, 63K+ stars | [🔗](https://github.com/OpenInterpreter/open-interpreter) |
| **Open-Interface** | ✅ | ✅ | ✅ | ✅ | General-purpose desktop automation | [🔗](https://github.com/AmberSahdev/Open-Interface) |
| **UFO** | ✅ | ❌ | ❌ | ✅ | Windows-specific app automation | [🔗](https://github.com/microsoft/UFO) |
| **Bytebot** | ❌ | ❌ | ✅ | ✅ | Self-hosted (Docker), headless | [🔗](https://github.com/bytebot-ai/bytebot) |
| **Microsoft Fara-7B** | ✅ | ✅ | ✅ | ✅ | Open-weight vision grounding model | [🔗](https://github.com/microsoft/Fara) |
| **UI-TARS** | ✅ | ✅ | ✅ | ✅ | Autonomous GUI execution, vision-language-action model (ByteDance) | [🔗](https://github.com/bytedance/UI-TARS-desktop) |
| **c/ua** | ✅ | ✅ | ✅ | ✅ | Isolated VM environments, open-source CU infrastructure | [🔗](https://github.com/trycua/cua) |
| **Windows-Use** | ✅ | ❌ | ❌ | ✅ | Windows OS-specific agent automation | [🔗](https://github.com/CursorTouch/Windows-Use) |
| **OpenCUA** | ✅ | ✅ | ✅ | ✅ | Open foundations for computer-use agents | [🔗](https://github.com/xlang-ai/OpenCUA) |
| **Devin** | ✅ | ✅ | ✅ | ✅ | Full-stack software engineering agent (Cognition Labs) | ❌ |
| **Ace** | ✅ | ✅ | ✅ | ✅ | 20x human speed on UI tasks (General Agents) | ❌ |

##### Cloud / API Computer Use Agents

Agents accessed via API or cloud service — OS-independent, but require internet connectivity.

| Agent | Interface | Vision | Best For | GitHub |
|-------|-----------|--------|----------|--------|
| **Anthropic Computer Use** | API | ✅ | Beta capability, Claude-powered desktop control | ❌ |
| **OpenAI Operator** | API | ✅ | Guided browser and desktop computer use | ❌ |
| **Amazon Nova Act** | API | ✅ | AWS browser automation SDK | ❌ |
| **Manus AI** | Cloud | ✅ | General-purpose cloud agent | ❌ |
| **Adept AI (ACT-1)** | API | ✅ | Pioneer in digital actions, self-correcting behavior | ❌ |
| **AskUI Vision Agent** | API | ✅ | Cross-platform vision automation without VMs | ❌ |
| **Highlight AI** | Desktop + Cloud | ✅ | Privacy-first desktop Q&A and automation | ❌ |

##### AI Operating Systems

AI-native operating systems and platforms that embed LLMs as core system components.

| OS / Platform | Type | Hardware | Local/Cloud | Best For | GitHub |
|---------------|------|----------|:-----------:|----------|--------|
| **AIOS** | Open Source (MIT) | Any | Both | Kernel-level LLM agent OS, agent scheduling & memory management | [🔗](https://github.com/agiresearch/AIOS) |
| **Ghost OS** | Open Source | Any | Local | Autonomous agent workflows | [🔗](https://github.com/ghostwright/ghost-os) |
| **computer_use_ootb** | Open Source | Any | Local/API | Out-of-the-box GUI automation (Claude 3.5 CU + local models) | [🔗](https://github.com/showlab/computer_use_ootb) |
| **Rabbit OS (R1)** | Commercial ($199 device) | R1 Device | Cloud | Consumer AI assistant, LAM-based app automation | ❌ |
| **Apple Intelligence** | Commercial (OS-level) | Apple Silicon (M1+) | On-device / Private Cloud | Privacy-first, system-wide writing, Siri, image generation | ❌ |
| **Windows Copilot+** | Commercial (OS-level) | NPU (40+ TOPS) | Hybrid | Recall, Cocreator, live captions, enterprise productivity | ❌ |

#### RPA & Visual Frameworks

| Tool | Platform | Best For |
|------|----------|----------|
| **Ui.Vision RPA** | Windows, macOS, Linux | Visual automation |
| **OmniParser V2** | Cross-platform | Screen parsing |

#### Scripting Libraries

| Tool | Platform | Key Features | GitHub |
|------|----------|--------------|--------|
| **PyAutoGUI** | Cross-platform | Simple API, fail-safe | [🔗](https://github.com/asweigart/pyautogui) |
| **Nut.js** | Cross-platform | Visual search, image matching | ❌ |
| **OpenAdapt** | Windows, macOS | Learning from demonstration | [🔗](https://github.com/OpenAdaptAI/OpenAdapt) |

#### Research Projects (Computer Use)

Notable academic and industry research advancing the field of computer-use agents.

| Project | Developer | Focus | Year | Paper |
|---------|-----------|-------|------|-------|
| **Gato** | Google DeepMind | Multi-modal, multi-task, multi-embodiment agent | 2022 | [DeepMind](https://deepmind.google/research/publications/60307/) |
| **PaLM-E** | Google DeepMind | Embodied multimodal language model | 2023 | [arXiv](https://arxiv.org/abs/2303.03378) |
| **RT-2** | Google DeepMind | Vision-language-action model for robotics | 2023 | [arXiv](https://arxiv.org/abs/2307.15818) |
| **HuggingGPT (Jarvis)** | Microsoft | Orchestrates specialists for multi-modal tasks | 2023 | [arXiv](https://arxiv.org/abs/2303.17580) |
| **SIMA** | Google DeepMind | Generalist AI agent for 3D virtual environments | 2024 | [DeepMind](https://deepmind.google/discover/blog/sima/) |
| **Magma** | Microsoft Research | Vision-language-action foundation model | 2025 | [arXiv](https://arxiv.org/abs/2502.12256) |
| **WebAgent** | Google DeepMind | Autonomous web browsing and form-filling | 2024 | [arXiv](https://arxiv.org/abs/2310.03685) |
| **WebVoyager** | Hongliang He et al. | Autonomous web browsing (59.1% on 15-website benchmark) | 2024 | [arXiv](https://arxiv.org/abs/2401.13919) |

---

## AI Infrastructure 🏗️

Tools, frameworks, and specialized models for building production AI systems — from embeddings and video generation to safety, evaluation, and model routing.

### Embedding & Reranking Models 🧲

Specialized models for converting text (or images) into dense vector representations and for reranking retrieval results. Essential infrastructure for RAG pipelines and semantic search. *Prices as of April 2026.*

#### Embedding Models

| Model | Developer | Dimensions | Max Tokens | Pricing | Best For | GitHub |
|-------|-----------|-----------|------------|---------|----------|--------|
| text-embedding-3-small | OpenAI | 1,536 | 8,191 | $0.02/1M tokens | Cost-effective English embeddings | — |
| text-embedding-3-large | OpenAI | 3,072 | 8,191 | $0.13/1M tokens | Highest-quality English retrieval | — |
| Embed v4 | Cohere | 1,536 | 128K | $0.12/1M (text), $0.47/1M (image) | Multimodal text + image RAG | — |
| voyage-3-large | Voyage AI | 256–2,048 (flex) | 32K | ~$0.18/1M tokens | Highest-quality retrieval, long context | — |
| jina-embeddings-v3 | Jina AI | 32–1,024 (flex) | 8,192 | API pay-per-use | Multilingual, task-adaptive (LoRA heads) | [🔗](https://github.com/jina-ai/jina-embeddings-v3) |
| BGE-M3 | BAAI | 1,024 | 8,192 | Free (open-source) | Multi-functional: dense + sparse + ColBERT | [🔗](https://github.com/FlagOpen/FlagEmbedding) |
| Nomic Embed v2 (MoE) | Nomic AI | 256–768 (flex) | 512 | Free (open-source) | Multilingual, MoE efficiency (305M active) | [🔗](https://github.com/nomic-ai/nomic) |
| text-embedding-005 | Google (Vertex AI) | 768 | 2,048 | $0.10/1M tokens | GCP-native semantic search | — |

#### Reranking Models

| Model | Developer | Max Tokens | Pricing | Best For | GitHub |
|-------|-----------|-----------|---------|----------|--------|
| Rerank 4.0 Pro | Cohere | 32K | $1.00/1K queries | High-accuracy domain-specific reranking | — |
| Rerank 4.0 Fast | Cohere | 32K | $0.50/1K queries | Low-latency production reranking | — |
| rerank-2.5 | Voyage AI | 32K | API pay-per-use | Instruction-following, multilingual | — |
| BGE Reranker v2-m3 | BAAI | 8,192 | Free (open-source) | Open-source cross-encoder reranking | [🔗](https://github.com/FlagOpen/FlagEmbedding) |
| Jina Reranker v2 | Jina AI | 8,192 | API pay-per-use | Multilingual, long-context reranking | — |

### Video Generation Models 🎬

Text-to-video and image-to-video generation models for creating short clips from prompts. The field is moving rapidly — resolutions, durations, and pricing change frequently. *Specs as of April 2026.*

| Model | Developer | Resolution | Duration | Pricing | Open Source | Best For | GitHub |
|-------|-----------|-----------|---------|---------|-------------|----------|--------|
| Sora 2 | OpenAI | Up to 1080p | Up to 20s (Pro) | $20–$200/mo via ChatGPT | No | Cinematic quality, long clips | — |
| Veo 3 | Google DeepMind | 720p–1080p | Up to 8s (extendable) | ~$0.20–$0.40/s | No | Native audio + video, realistic physics | — |
| Runway Gen-4 / Gen-4.5 | Runway | Up to 4K | Up to 16s | $12–$76/mo | No | Professional creative workflows | — |
| Kling 2.0 | Kuaishou | 1080p | Up to 10s | Free / $5.99–$66/mo | No | Budget production, fast turnaround | — |
| Pika 2.0 | Pika Labs | 1080p | Up to 5s | Free / $8–$58/mo | No | Social media, creative effects | — |
| MiniMax Video-01 | MiniMax | 720p | Up to 6s | ~$0.40/video | No | Strong text-motion responsiveness | — |
| HunyuanVideo | Tencent | 720p–2K | Up to 16s | Free (self-host; ~60GB VRAM) | Yes (Apache 2.0) | High per-frame fidelity, long clips | [🔗](https://github.com/Tencent/HunyuanVideo) |
| Wan 2.2 (14B) | Alibaba | 480p–1080p | Up to 10s | ~$0.10–$0.30/clip (API) | Yes (Apache 2.0) | Motion quality, VBench #1 benchmark | [🔗](https://github.com/Wan-Video/Wan2.1) |
| Mochi 1 | Genmo | 480p | Up to 5.4s @ 30fps | Free (open-source) | Yes (Apache 2.0) | High-quality open text-to-video | [🔗](https://github.com/genmoai/mochi) |
| LTX Video | Lightricks | 720p | Variable | Free (open-source) | Yes | Fast generation, ComfyUI-native | [🔗](https://github.com/Lightricks/LTX-Video) |
| CogVideoX | Zhipu AI / Tsinghua | 720p | ~6s | Free (open-source) | Yes (Apache 2.0) | Image-to-video quality, LoRA fine-tuning | [🔗](https://github.com/THUDM/CogVideo) |

### Speech & TTS Models 🔊

Text-to-speech (TTS) and speech-to-text (STT / ASR) models for voice generation, transcription, and real-time audio. *Prices as of April 2026.*

#### Text-to-Speech (TTS)

| Model | Developer | Languages | Real-time | Open Source | Pricing | Best For | GitHub |
|-------|-----------|-----------|----------|-------------|---------|----------|--------|
| ElevenLabs Turbo v2.5 | ElevenLabs | 29+ | Yes | No | Free – $1,320/mo | Best quality (4.8 MOS), instant voice cloning | — |
| OpenAI TTS / TTS HD | OpenAI | 57 | Yes | No | $15 / $30 per 1M chars | Enterprise, seamless GPT integration | — |
| Sesame CSM | Sesame AI Labs | English | Yes | Yes | Free | Conversational, emotionally expressive (4.7 MOS) | [🔗](https://github.com/SesameAILabs/csm) |
| Kokoro-82M | Hexgrad | Multilingual | Yes | Yes (Apache 2.0) | Free | Tiny (82M params), CPU-runnable, near-commercial quality | [🔗](https://github.com/hexgrad/kokoro) |
| Fish Audio S1 | Fish Audio | Multilingual | Yes | Yes | Free / $0.016/1K chars (API) | Voice cloning, multilingual fluency | [🔗](https://github.com/fishaudio/fish-speech) |
| Parler-TTS | HuggingFace | English | No | Yes (Apache 2.0) | Free | Style-controllable via text descriptions | [🔗](https://github.com/huggingface/parler-tts) |
| XTTS v2 | Coqui AI | 17 | Yes | Yes (MPL 2.0) | Free | Best open-source multilingual, 6s voice cloning | [🔗](https://github.com/coqui-ai/TTS) |
| Bark | Suno AI | 13+ | No | Yes (MIT) | Free | Expressive, non-verbal sounds, long-form audio | [🔗](https://github.com/suno-ai/bark) |

#### Speech-to-Text (STT / ASR)

| Model | Developer | Languages | Real-time | Open Source | Pricing | Best For | GitHub |
|-------|-----------|-----------|----------|-------------|---------|----------|--------|
| Whisper large-v3 | OpenAI | 100+ | No | Yes (MIT) | $0.006/min (API) | Open-source multilingual baseline | [🔗](https://github.com/openai/whisper) |
| GPT-4o Transcribe | OpenAI | 50+ | Yes | No | $0.006/min | High-accuracy managed STT | — |
| Deepgram Nova-3 | Deepgram | 36+ | Yes | No | $0.0043/min | Ultra-low latency, production STT | — |
| AssemblyAI Universal-2 | AssemblyAI | Multilingual | Yes | No | $0.0025/min | Accurate, feature-rich transcription | — |

### AI Safety & Guardrails 🛡️

Tools and frameworks for detecting unsafe content, preventing prompt injection, validating outputs, and enforcing policy compliance in LLM-powered applications. *As of April 2026.*

| Tool | Developer | Type | Open Source | Pricing | Best For | GitHub |
|------|-----------|------|-------------|---------|----------|--------|
| Llama Guard 3 | Meta | Safety classifier (8B LLM) | Yes (Meta license) | Free / ~$0.02/1M tokens (API) | Input/output safety classification, 8 languages | [🔗](https://github.com/meta-llama/PurpleLlama) |
| NeMo Guardrails | NVIDIA | Programmable guardrail toolkit (Colang DSL) | Yes (Apache 2.0) | Free | Dialog safety, policy enforcement, LangChain-native | [🔗](https://github.com/NVIDIA/NeMo-Guardrails) |
| Guardrails AI | Guardrails AI | Python validator framework | Yes | Free (OSS) | Output validation, PII detection, hallucination guards | [🔗](https://github.com/guardrails-ai/guardrails) |
| Amazon Bedrock Guardrails | AWS | Managed safety layer | No | Pay-per-use (AWS) | AWS-native, zero-ops compliance and content filtering | — |
| ShieldGemma 2 | Google | Safety classifier (open weights) | Yes (open weights) | Free | Text safety (2B/9B/27B), image safety (4B) | — |
| Rebuff | Protect AI | Prompt injection detector | Yes | Free | Self-hardening anti-injection using vector memory | [🔗](https://github.com/protectai/rebuff) |
| Lakera Guard | Lakera | Managed LLM security API | No | Free tier + Enterprise | Runtime LLM security, <50ms latency, PII + injection | — |

### RAG Frameworks 🗂️

Frameworks and libraries for building Retrieval-Augmented Generation (RAG) pipelines — connecting LLMs to external knowledge sources. *As of April 2026.*

| Framework | Developer | Language | Key Features | Open Source | GitHub |
|-----------|-----------|---------|--------------|-------------|--------|
| LlamaIndex | LlamaIndex | Python | 160+ data connectors, hybrid search, multi-agent support | Yes (MIT) | [🔗](https://github.com/run-llama/llama_index) |
| LangChain | LangChain AI | Python / JS | Chains, agents, memory, 50K+ integrations, LangGraph | Yes (MIT) | [🔗](https://github.com/langchain-ai/langchain) |
| RAGFlow | InfiniFlow | Python | Visual workflow builder, deep document parsing (PDF/tables) | Yes (Apache 2.0) | [🔗](https://github.com/infiniflow/ragflow) |
| Haystack | deepset | Python | Modular pipelines, enterprise-grade, built-in monitoring | Yes (Apache 2.0) | [🔗](https://github.com/deepset-ai/haystack) |
| Verba | Weaviate | Python | No-code UI, Weaviate-native vector search | Yes | [🔗](https://github.com/weaviate/Verba) |
| Mem0 | Mem0 AI | Python / JS | Persistent memory layer, graph memory, session recall | Yes (Apache 2.0) | [🔗](https://github.com/mem0ai/mem0) |
| txtai | NeuML | Python | All-in-one semantic search + workflow automation | Yes (Apache 2.0) | [🔗](https://github.com/neuml/txtai) |
| R2R | SciPhi | Python | Lightweight, low-latency, REST API, production-first | Yes (MIT) | [🔗](https://github.com/SciPhi-AI/R2R) |

### Fine-tuning Platforms ⚙️

Tools and platforms for adapting pre-trained LLMs to specific tasks or domains via supervised fine-tuning, RLHF, LoRA/QLoRA, and related methods. *Prices as of April 2026.*

| Platform | Type | Supported Models | Pricing | Best For | GitHub |
|----------|------|-----------------|---------|----------|--------|
| Unsloth | OSS library | Llama, Mistral, Gemma, Qwen, Phi, + more | Free | 2–5× faster training, 80% VRAM reduction via custom kernels | [🔗](https://github.com/unslothai/unsloth) |
| Axolotl | OSS framework | Most Hugging Face models | Free | Config-as-code (YAML), reproducibility, multi-GPU training | [🔗](https://github.com/axolotl-ai-cloud/axolotl) |
| OpenAI Fine-tuning | Managed API | GPT-4o, GPT-4o-mini, GPT-3.5 Turbo | GPT-4o-mini: $0.30/1M training tokens | Managed, no infra, direct production deployment | — |
| Google Vertex AI | Managed cloud | Gemini 2.5 Pro/Flash, Gemma 3 | Gemini 2.5 Pro: $25/1M training tokens | GCP-native, Gemini model access | — |
| Predibase / LoRAX | Cloud + OSS server | Llama, Mistral, 50+ HF models | Free tier + per-GPU pricing | Multi-adapter serving: many LoRA adapters on one GPU | [🔗](https://github.com/predibase/lorax) |
| PEFT | Hugging Face | All Hugging Face models | Free | LoRA, QLoRA, prefix tuning, prompt tuning — full HF ecosystem | [🔗](https://github.com/huggingface/peft) |
| LLaMA-Factory | Community | 100+ models | Free | Web UI, low-code interface, beginner-friendly fine-tuning | [🔗](https://github.com/hiyouga/LLaMA-Factory) |
| torchtune | PyTorch | Llama, Gemma, Mistral, Phi | Free | PyTorch-native, composable training recipes | [🔗](https://github.com/pytorch/torchtune) |

### Evaluation & Observability 📊

Tools for tracing LLM calls, evaluating output quality, debugging RAG pipelines, and monitoring production AI systems. *Prices as of April 2026.*

| Tool | Developer | Type | Open Source | Pricing | Best For | GitHub |
|------|-----------|------|-------------|---------|----------|--------|
| LangSmith | LangChain AI | Tracing + evaluation platform | No (enterprise self-host) | Free (5K traces/mo), paid plans | LangChain apps, chain + agent debugging | — |
| Braintrust | Braintrust Data | Eval-first platform | Partial (AI proxy OSS) | Free (1M spans), enterprise | CI/CD evals, dataset management, LLM-as-judge | — |
| Helicone | Helicone | Proxy-based observability | Yes | Free tier, usage-based | Cost tracking, request caching, drop-in API proxy | [🔗](https://github.com/Helicone/helicone) |
| Arize Phoenix | Arize AI | OSS tracing + evaluation | Yes | Free (OSS); Arize Cloud paid | RAG debugging, LLM-as-judge, local dev | [🔗](https://github.com/Arize-ai/phoenix) |
| Langfuse | Langfuse | Tracing + evaluation | Yes (MIT) | Free / self-host; cloud paid | Open-source, 19K+ GitHub stars, OpenTelemetry | [🔗](https://github.com/langfuse/langfuse) |
| Ragas | Ragas | RAG evaluation framework | Yes | Free | RAG-specific metrics: faithfulness, recall, precision | [🔗](https://github.com/explodinggradients/ragas) |
| DeepEval | Confident AI | LLM evaluation framework | Yes | Free (OSS); cloud paid | 14+ built-in metrics, pytest-style eval runner | [🔗](https://github.com/confident-ai/deepeval) |

### MCP Ecosystem 🔌

The [Model Context Protocol (MCP)](https://modelcontextprotocol.io) is an open standard by Anthropic for connecting LLMs to external tools and data sources via a unified JSON-RPC 2.0 interface. It supports STDIO and Streamable HTTP transports. The official MCP registry at [mcp.so](https://mcp.so) lists 2,000+ servers.

**MCP Clients:** Claude Desktop, Claude Code, Cursor, Windsurf, VS Code (Copilot), Continue.dev, Zed, LibreChat, and more.

#### Popular MCP Servers

| Tool / Server | Developer | Category | Open Source | Best For | GitHub |
|--------------|-----------|---------|-------------|----------|--------|
| MCP Filesystem | Anthropic / Community | File I/O | Yes (MIT) | Read/write local files from any MCP client | [🔗](https://github.com/modelcontextprotocol/servers) |
| MCP GitHub | GitHub / Anthropic | Code & DevOps | Yes | Repo management, issues, PRs, code search | [🔗](https://github.com/modelcontextprotocol/servers) |
| MCP Slack | Community | Messaging | Yes | Slack workspace read/write interaction | [🔗](https://github.com/modelcontextprotocol/servers) |
| MCP PostgreSQL | Community | Database | Yes | Read-only SQL queries against Postgres | [🔗](https://github.com/modelcontextprotocol/servers) |
| MCP Google Drive | Community | Storage | Yes | Drive file access and search | [🔗](https://github.com/modelcontextprotocol/servers) |
| MCP Docker | Community | DevOps | Yes | Container management and inspection | [🔗](https://github.com/modelcontextprotocol/servers) |
| MCP Brave Search | Brave | Search | Yes | Web + local search via Brave API | [🔗](https://github.com/modelcontextprotocol/servers) |
| MCP AWS | AWS Labs | Cloud | Yes (Apache 2.0) | AWS service integration | [🔗](https://github.com/aws/aws-mcp-servers) |
| MCP Notion | Community | Productivity | Yes | Notion page and database access | [🔗](https://github.com/modelcontextprotocol/servers) |
| FastMCP | Community | Framework | Yes | Python framework for building MCP servers fast | [🔗](https://github.com/jlowin/fastmcp) |
| Context7 | Upstash | Dev Tools | Yes | Up-to-date library docs for AI coding assistants | [🔗](https://github.com/upstash/context7) |

### Model Routers & Load Balancers 🔀

Tools for routing LLM requests across multiple providers, models, and deployments — optimizing for cost, latency, quality, or reliability. *Prices as of April 2026.*

| Tool | Developer | Key Features | Open Source | Pricing | GitHub |
|------|-----------|-------------|-------------|---------|--------|
| LiteLLM | BerriAI | 100+ provider support, proxy server, load balancing, fallbacks, spend tracking | Yes (MIT) | Free (OSS) / $99/mo cloud | [🔗](https://github.com/BerriAI/litellm) |
| Portkey | Portkey | 250+ LLMs, AI gateway, guardrails, observability, virtual keys | Yes (Apache 2.0) | Free tier / $49/mo+ | [🔗](https://github.com/Portkey-AI/gateway) |
| OpenRouter | OpenRouter | 200+ model catalog, unified API, pay-per-use credit system | No | ~5% markup on provider cost | — |
| RouteLLM | LMSys | Open-source router (strong vs. weak model) using classifier or matrix factorization | Yes | Free | [🔗](https://github.com/lm-sys/RouteLLM) |
| Not Diamond | Not Diamond | Pre-trained + custom task-specific routers, cost/quality tradeoff | No | Free tier + enterprise | — |
| Unify AI | Unify | Quality / cost / latency-aware routing across 100+ model deployments | No | Usage-based | — |
| Semantic Router | Aurelio AI | Embedding-based semantic intent routing for agents and pipelines | Yes | Free | [🔗](https://github.com/aurelio-labs/semantic-router) |

### Small Language Models (SLMs) 📱

Compact models designed for on-device inference, edge deployment, low-latency APIs, and resource-constrained environments. Generally defined as models under ~15B parameters. *Specs as of April 2026.*

| Model | Developer | Params | Context | License | Best For |
|-------|-----------|--------|---------|---------|----------|
| Phi-4 | Microsoft | 14B | 16K | MIT | Reasoning, math, code — STEM benchmark leader at class size |
| Phi-4-mini | Microsoft | 3.8B | 128K | MIT | On-device STEM reasoning with long context |
| Phi-4-multimodal | Microsoft | 5.6B | 128K | MIT | Vision + audio + text multimodal, edge deployment |
| Gemma 3 27B | Google | 27B | 128K | Apache 2.0 | Top open model, multilingual (140+ languages) |
| Gemma 3 4B | Google | 4B | 128K | Apache 2.0 | CPU inference, 140+ languages, mobile-friendly |
| Gemma 3 1B | Google | 1B | 32K | Apache 2.0 | On-device, embedded, ultra-lightweight |
| SmolLM3 | Hugging Face | 3B | 128K | Apache 2.0 | Efficient, tool use, multilingual, reasoning |
| Qwen2.5 3B | Alibaba | 3B | 128K | Apache 2.0 | Asian and multilingual tasks, coding |
| Qwen2.5 7B | Alibaba | 7B | 128K | Apache 2.0 | Strong multilingual baseline, function calling |
| Llama 3.2 3B | Meta | 3B | 128K | Llama 3.2 license | General-purpose, on-device, Meta ecosystem |
| Llama 3.2 1B | Meta | 1B | 128K | Llama 3.2 license | Lightweight edge inference, distillation target |
| Granite 3.3 8B | IBM | 8B | 128K | Apache 2.0 | Enterprise tasks, tool use, business-domain |
| MiniCPM 3.0 | ModelBest / Tsinghua | 4B | 32K | Apache 2.0 | Compact yet capable, mobile and edge |
| Danube 3 500M | H2O.ai | 500M | 8K | Apache 2.0 | Ultra-lightweight on-device, IoT |

**Notable GitHub repos:**
- SmolLM / SmolLM2: [🔗](https://github.com/huggingface/smollm)
- Granite 3.x: [🔗](https://github.com/ibm-granite/granite-3.0-language-models)
- MiniCPM: [🔗](https://github.com/OpenBMB/MiniCPM)
- Danube 3: [🔗](https://github.com/h2oai/h2o-danube3)


---

## Guides 📚

Tutorials, how-tos, and in-depth guides for getting the most out of AI models and tools.

### Getting Started 🚀

A beginner-friendly introduction to AI models and how to start using them effectively.

#### Understanding LLMs

| Concept | Description |
|---------|-------------|
| **Parameters** | Size of model (B = billions). More = more capable |
| **Context Window** | How much text model can process (128K standard) |
| **Tokens** | Basic units of text (~0.75 words per token) |

#### Accessing AI Models

| Method | Best For | Setup Difficulty |
|--------|----------|------------------|
| **Web Interfaces** | Quick experiments | Easiest |
| **API Access** | Building applications | Easy |
| **Self-Hosting** | Privacy, no API costs | Medium-Hard |
| **IDE Integration** | Daily coding | Easy |

#### Model Recommendations by Task

| Task | Free Option | Premium Option |
|------|-------------|----------------|
| **Chat** | Llama 4 (self-hosted) | GPT-5.4, Claude Opus 4.6 |
| **Coding** | DeepSeek-Coder-V2 | Claude Opus 4.6 |
| **Reasoning** | DeepSeek-R1 | Gemini 3 Deep Think, o3 |
| **Long docs** | Llama 4 Scout | Gemini 3 Flash |
| **Vision** | Llama 4 Maverick | GPT-5.4, Gemini 3 Pro |

### Model Selection Guide 🎯

A comprehensive guide to choosing the right AI model for your specific needs.

#### Quick Decision Tree

| Need | 🆓 Free / Self-Host | 💎 Best Quality | ⚡ Fast / Autonomous |
|------|---------------------|----------------|----------------------|
| 💻 Coding | DeepSeek-Coder-V2 | Claude Opus 4.6 | GPT-5.3-Codex |
| 🧠 Reasoning / Math | DeepSeek-R1 | Gemini 3 Deep Think | o3 |
| 💬 General Chat | Llama 4 (self-hosted) | GPT-5.4, Claude Opus 4.6 | Gemini 3 Flash |
| 🎨 Vision | Llama 4 Maverick | GPT-5.4, Gemini 3.1 Pro | Gemini 3 Flash |
| 🖥️ Self-Hosting | Phi-4 | DeepSeek-V4 | vLLM / SGLang (serving) |

#### By Budget

| Budget | Options |
|--------|---------|
| **Free** | Self-hosted (Llama 4, Qwen3, Mistral) |
| **$0-10/mo** | API entry tiers, Gemini Flash |
| **$10-50/mo** | Copilot, Claude API, GPT-5 API |
| **$50+/mo** | Heavy usage, multiple models |

### Self-Hosting Guide 🖥️

A comprehensive guide to running AI models on your own hardware.

#### Benefits

| Benefit | Description |
|---------|-------------|
| **Privacy** | Data never leaves your infrastructure |
| **Cost Control** | No per-token API costs for unlimited usage |
| **Customization** | Fine-tune models for specific needs |
| **No Rate Limits** | Process as much as hardware allows |
| **Offline Access** | Work without internet |

#### Quick Start with Ollama

For installation and usage instructions, refer to the [official Ollama documentation](https://ollama.com).

#### Local GPU Quick Guide

**Recommended apps (local-first):**
- [Ollama](https://ollama.com) - Simple local runtime with a local HTTP API
- [LM Studio](https://lmstudio.ai) - Desktop UI for downloading and running models locally
- [llama.cpp](https://github.com/ggerganov/llama.cpp) - Fast local inference (CPU/GPU), great for quantized models
- [Open WebUI](https://github.com/open-webui/open-webui) - Optional local web UI (pairs well with local runtimes)

**If you want “server-style” hosting (advanced):**
- [vLLM](https://github.com/vllm-project/vllm) - High-throughput serving for NVIDIA GPUs
- [SGLang](https://github.com/sgl-project/sglang) - Structured generation and serving workflows

**Practical setup tips:**
1. Install the latest NVIDIA drivers (enable GPU acceleration in your chosen app)
2. Start with smaller quantized models (Q4 is a common “best default”)
3. Keep context windows realistic for local hardware (lower context = faster, less memory)
4. Watch VRAM first, then system RAM; reduce model size or quantization if either saturates
5. Prefer running locally on `localhost` and only expose to LAN if you understand firewall rules

**Example hardware configurations:**
| Hardware | Good starting point | Notes |
|----------|---------------------|------|
| **Consumer GPU (24 GB VRAM)** | 7B–14B quantized | e.g., RTX 4090, RTX 3090 — great for chat/coding |
| **Pro GPU (48–80 GB VRAM)** | 14B–70B quantized | e.g., A6000, A100 — coding agents, longer contexts |
| **Multi-GPU (160+ GB VRAM)** | 70B+ quantized | e.g., 2×A100 — larger open-source models |
| **CPU-only (32–64 GB RAM)** | 7B–14B quantized | Slower but viable for offline chat; keep context moderate |

#### Deployment Options

| Option | Best For | Pros | Cons |
|--------|----------|------|------|
| **Local Machine** | Personal use | Simple, no latency | Limited hardware |
| **Dedicated Server** | Team use | Full control | Maintenance |
| **Cloud GPU Rental** | Experimentation | On-demand | Hourly costs |
| **Kubernetes** | Enterprise | Scalable | Complex |

### Cost Analysis 💰

Comprehensive pricing comparisons and cost calculations.

#### Pricing Tiers

| Tier | Price Range | Models |
|------|-------------|--------|
| 🆓 **Free** | $0 | Self-hosted, free tiers |
| 💵 **Budget** | $0.07 - $0.50/1M | GLM-4.7-FlashX, GLM-4-32B-0414-128K, Yi-Lightning, GPT-5.4 nano, Gemini 3.1 Flash-Lite, DeepSeek-V3.1, MiniMax-M2.5 |
| 💰 **Mid-range** | $0.60 - $15.00/1M | GPT-5.4 mini, Claude Haiku 4.5, Kimi K2.5, Sonar, GLM-5, GPT-5.4, Claude Sonnet |
| 💎 **Premium** | $15.00 - $600.00/1M | GPT-5.4 Pro, Claude Opus, o1-Pro |

#### Subscription Pricing (Monthly, USD)

**AI chat apps**

| Product | Plans (USD) | Notes | Official Source |
|--------|-------------|-------|:---:|
| **ChatGPT** | Go **$8**, Plus **$20**, Pro **$200**, Business **$25/seat** (annual) or **$30/seat** (monthly), Enterprise (contact sales) | Consumer prices are US-listed; Go is localized in some markets | [🔗](https://openai.com/index/introducing-chatgpt-go/) |
| **Claude** | Pro **$20**, Max **$100** (5×) or **$200** (20×), Team/Enterprise (see pricing) | Prices shown exclude applicable taxes; availability varies by region | [🔗](https://www.anthropic.com/max) |
| **Google AI (Gemini)** | Plus **$7.99**, Pro **$19.99**, Ultra **$249.99** | US pricing; some regions/local pricing differ | [🔗](https://blog.google/products-and-platforms/products/google-one/google-ai-ultra/) |

**Coding assistants**

| Tool | Plans (USD) | Notes | Official Source |
|------|-------------|-------|:---:|
| **GitHub Copilot** | Free **$0**, Pro **$10**, Pro+ **$39**, Business **$19/user**, Enterprise **$39/user** | Annual options available for Pro/Pro+ | [🔗](https://github.com/features/copilot/plans) |

#### Model Pricing Comparison

| Model | Input | Output | Cached Input | Best For |
|-------|-------|--------|-------------|----------|
| **GLM-4.7-FlashX** | $0.07 | $0.40 | — | Fast budget tasks |
| **Step-3.5-Flash** | $0.10 | $0.30 | — | Ultra-fast reasoning (85–350 tok/s) |
| **GLM-4-32B-0414-128K** | $0.10 | $0.10 | — | Budget chat/coding |
| **Llama 4 Maverick** | $0.15 | $0.60 | — | Open multimodal (self-host: $0) |
| **GPT-5.4 nano** | $0.20 | $1.25 | $0.02 | Classification and lightweight subagents |
| **Grok 4 Fast** | $0.20 | $0.50 | $0.05 | Fast Grok reasoning |
| **Gemini 3.1 Flash-Lite** | $0.25 | $1.50 | Supported | High-volume multimodal tasks |
| **DeepSeek-V3.1** | $0.27 | $0.41 | — | Everything |
| **DeepSeek-V3.2** | $0.28 | $0.42 | $0.028 | Budget workhorse, reasoning |
| **DeepSeek-V4** | $0.30 | $0.50 | $0.03 | Engram memory, coding (off-peak 50% off) |
| **Gemini 3 Flash** | $0.30 | $2.50 | $0.05 + $1/hr | Long context |
| **MiniMax-M2.5** | $0.30 | $1.20 | Auto (included) | Coding, long context |
| **Mistral Large 3** | $0.50 | $1.50 | $0.05 | Open-weight 675B MoE |
| **Kimi K2.5** | $0.60 | $3.00 | Auto (included) | Multimodal + agent tasks |
| **GPT-5.4 mini** | $0.75 | $4.50 | $0.075 | Fast coding and multimodal tasks |
| **Claude Haiku 4.5** | $1.00 | $5.00 | — | Low-latency coding and sub-agents |
| **GLM-5** | $1.00 | $3.20 | $0.20 | Agentic engineering |
| **Perplexity Sonar** | $1.00 | $1.00 | — | Web-grounded chat (request fees apply) |
| **GPT-5.3-Codex** | $1.75 | $14.00 | $0.175 | Agentic coding, 7+ hour autonomy |
| **Gemini 3.1 Pro** | $2.00 | $12.00 | $0.20–$0.40 + $4.50/hr | Frontier reasoning |
| **Perplexity Sonar Reasoning Pro** | $2.00 | $8.00 | — | Reasoning + search (request fees apply) |
| **GPT-5.4** | $2.50 | $15.00 | $0.25 | Frontier coding and professional work |
| **Grok 4** | $3.00 | $15.00 | $0.75 | First-principles reasoning |
| **Perplexity Sonar Pro** | $3.00 | $15.00 | — | Higher quality + search (request fees apply) |
| **Claude Sonnet 4.5** | $3.00 | $15.00 | $0.30 (hit) | Best coding |
| **Claude Sonnet 4.6** | $3.00 | $15.00 | $0.30 (hit) | Near-Opus performance |
| **Claude Opus 4.6** | $5.00 | $25.00 | $0.50 (hit) | Agentic coding |


#### Self-Hosting vs API (Monthly)

| Usage Level | Self-Host (A100) | API (GPT-5) | Winner |
|-------------|------------------|-------------|--------|
| **Light** (1M tokens) | $300 (rental) | $10 | API |
| **Medium** (100M tokens) | $300 | $1,000 | Self-host |
| **Heavy** (1B tokens) | $300 | $10,000 | Self-host |
| **Enterprise** (10B+ tokens) | $2,000 (owned) | $100,000+ | Self-host |

---

## Reference 📖

Reference materials including glossary, comparison tables, and data sources.

### Glossary 📖

Definitions of common terms used throughout the documentation.

#### A-E

| Term | Definition |
|------|------------|
| **Agent** | AI system that autonomously performs tasks and interacts with environments |
| **API** | Interface for programmatically accessing AI models |
| **Attention Mechanism** | Neural network component focusing on relevant input parts |
| **Benchmark** | Standardized test measuring model performance |
| **Chain-of-Thought (CoT)** | Prompting technique showing step-by-step reasoning |

#### F-L

| Term | Definition |
|------|------------|
| **Fine-Tuning** | Adapting pre-trained model to specific tasks |
| **Frontier Model** | State-of-the-art proprietary model |
| **GPU** | Hardware accelerator essential for ML |
| **LLM** | Large Language Model |
| **LoRA** | Efficient fine-tuning method |

#### M-R

| Term | Definition |
|------|------------|
| **MCP** | Model Context Protocol for tool interaction |
| **MMLU** | Massive Multitask Language Understanding benchmark |
| **MoE** | Mixture of Experts architecture |
| **Multimodal** | Processing multiple input types |
| **RAG** | Retrieval-Augmented Generation |

#### S-Z

| Term | Definition |
|------|------------|
| **Self-Hosting** | Running models on own infrastructure |
| **SLM** | Small Language Model |
| **SWE-bench** | Benchmark for real GitHub issue resolution |
| **Token** | Basic unit of text processing |
| **VRAM** | GPU memory for model storage |

### Comparison Tables 📊

Side-by-side comparisons of AI models sorted by various criteria.

#### Sort by Latest Update (Default)

| 🏢 Company | 🤖 Model | 📦 Version | 📅 Release Date | 🔄 Latest Updated | 💻 Coding | 📊 Benchmarks | 💰 Price | 🖥️ Self-Host | 🔗 Official Site |
|:---:|---|---|---|---|:---:|---|---|:---:|:---:|
| 🤖 OpenAI | GPT-5 | 5.4 mini | 2026-03-17 00:00 UTC | 2026-03-17 00:00 UTC ⭐ | ✅ | GPQA 87.5% | $0.75 / $4.50 | ❌ | [🔗](https://openai.com/news/?display=list) |
| 🤖 OpenAI | GPT-5 | 5.4 | 2026-03-05 00:00 UTC | 2026-03-05 00:00 UTC ⭐ | ✅ | GPQA 92.0%, SWE-bench ~80% | $2.50 / $15.00 | ❌ | [🔗](https://openai.com/research/index/release/) |
| 🌐 Google DeepMind | Gemini 3.1 | Flash-Lite | 2026-03-03 00:00 UTC | 2026-03-03 00:00 UTC ⭐ | ✅ | — | $0.25 / $1.50 | ❌ | [🔗](https://deepmind.google/models/model-cards/gemini-3-1-flash-lite/) |
| 🔬 DeepSeek | DeepSeek | V4 | 2026-02-17 00:00 UTC | 2026-02-17 00:00 UTC | ✅ | No public benchmarks | Pay-per-token | ✅ | [🔗](https://www.deepseek.com/) |
| 🌐 Google DeepMind | Gemini 3 | Deep Think | 2026-02-12 00:00 UTC | 2026-02-12 00:00 UTC ⭐ | ✅ | GPQA ~97%, ARC-AGI-2 84.6%, HLE 48.4% | Ultra subscription | ❌ | [🔗](https://deepmind.google/technologies/gemini/) |
| 🇨🇳 Zhipu AI | GLM | 5 | 2026-02-12 00:00 UTC | 2026-02-12 00:00 UTC ⭐ | ✅ | GPQA 82.0%, SWE-bench 77.8% | $1.00 / $3.20 | ✅ | [🔗](https://docs.z.ai/release-notes/new-released) |
| 🤖 Anthropic | Claude | Opus 4.6 | 2026-02-05 00:00 UTC | 2026-02-05 00:00 UTC ⭐ | ✅ | GPQA 91.3%, SWE-bench 80.8% | $5 / $25 | ❌ | [🔗](https://www.anthropic.com/) |
| 🤖 OpenAI | GPT-5 | 5.3-Codex | 2026-02-05 00:00 UTC | 2026-02-05 00:00 UTC ⭐ | ✅ | GPQA 91.5%, SWE-bench Pro 56.8% | TBD | ❌ | [🔗](https://openai.com/) |
| 🌙 Moonshot AI | Kimi | K2.5 | 2026-01-29 00:00 UTC | 2026-02-02 00:00 UTC ⭐ | ✅ | GPQA 87.6%, SWE-bench 76.8% | $0.60 / $3.00 | ❌ | [🔗](https://platform.moonshot.ai/docs/pricing/chat) |

#### Release Windows (Month-level)

| 🏢 Company | 🤖 Model | 📅 Release Window | Notes | 🔗 Official Site |
|:---:|---|---|---|:---:|
| 🧠 MiniMax | MiniMax M2.5 | 2026-02 | $0.30 / $1.20 | [🔗](https://platform.minimax.io/docs/guides/models-intro) |
| 🇨🇳 Alibaba/Qwen | Qwen 3.5-Max | 2026-02 | Open-source release window | [🔗](https://qwenlm.github.io/) |
| 🌐 Google DeepMind | Gemini 3.1 Flash-Lite | 2026-03 | $0.25 / $1.50 | [🔗](https://deepmind.google/models/model-cards/gemini-3-1-flash-lite/) |
| 🌐 Google DeepMind | Gemini 3 Pro | 2026-01 | Tiered pricing | [🔗](https://deepmind.google/models/gemini/) |
| 🤖 OpenAI | GPT-5.4 family | 2026-03 | GPT-5.4, GPT-5.4 mini, GPT-5.4 nano | [🔗](https://openai.com/news/?display=list) |
| 💻 Mistral AI | Mistral Large 3 | 2026-01 | Open-weight | [🔗](https://mistral.ai/) |

#### Sort by Price (Cheapest)

| Rank | Model | Input | Output | License |
|------|-------|-------|--------|---------|
| 1 | **Self-hosted** | $0 | $0 | Various |
| 2 | **GLM-4.7-Flash** | $0 | $0 | Free |
| 3 | **GLM-4.7-FlashX** | $0.07 | $0.40 | API |
| 4 | **GLM-4-32B-0414-128K** | $0.10 | $0.10 | API |
| 5 | **Yi-Lightning** | $0.14 | $0.42 | Apache 2.0 |
| 6 | **GPT-5.4 nano** | $0.20 | $1.25 | Proprietary |
| 7 | **Gemini 3.1 Flash-Lite** | $0.25 | $1.50 | Proprietary |
| 8 | **DeepSeek-V3.1** | $0.27 | $0.41 | MIT |
| 9 | **Gemini 3 Flash** | $0.30 | $2.50 | Proprietary |
| 10 | **MiniMax-M2.5** | $0.30 | $1.20 | Proprietary |

#### Sort by Performance (Coding)

| Rank | Model | HumanEval | Self-Host |
|------|-------|-----------|-----------|
| 1 | **Claude Sonnet 4.5** | ~92% | ❌ |
| 2 | **GPT-OSS-120B** | ~89% | ✅ |
| 3 | **DeepSeek-Coder-V2** | ~92% | ✅ |
| 4 | **Qwen3-Coder** | ~92% | ✅ |
| 5 | **DeepSeek-V3.1** | 82%+ | ✅ |

#### Sort by Context Window

| Rank | Model | Context | Best For |
|------|-------|---------|----------|
| 1 | **Gemini 3 Flash** | 10M | Entire libraries |
| 2 | **Llama 4 Scout** | 10M | Long-document RAG |
| 3 | **Gemini 3 Pro** | 1M+ | Research papers |
| 4 | **Kimi K2.5** | 256K | Large codebases |

### Data Sources 📚

Attribution, verification sources, and methodology.

#### Primary Sources

| Company | Source | URL |
|---------|--------|-----|
| **OpenAI** | Official Documentation | [openai.com](https://openai.com) |
| **OpenAI** | ChatGPT agent release notes | [help.openai.com](https://help.openai.com/en/articles/11794368-chatgpt-agent-release-notes) |
| **OpenAI** | Model release notes | [help.openai.com](https://help.openai.com/en/articles/9624314-model-release-notes/) |
| **OpenAI** | API pricing | [platform.openai.com](https://platform.openai.com/docs/pricing) |
| **OpenAI** | March 2026 model news | [openai.com](https://openai.com/news/?display=list) |
| **OpenAI** | ChatGPT subscriptions (Go/Plus/Pro) | [openai.com](https://openai.com/index/introducing-chatgpt-go/) |
| **OpenAI** | ChatGPT Business pricing | [help.openai.com](https://help.openai.com/en/articles/8542115-chatgpt-business-faq) |
| **Anthropic** | Claude Documentation | [anthropic.com](https://www.anthropic.com) |
| **Anthropic** | Claude Haiku 4.5 announcement | [anthropic.com](https://www.anthropic.com/news/claude-haiku-4-5?type=product) |
| **Anthropic** | Claude Pro pricing | [anthropic.com](https://www.anthropic.com/news/claude-pro) |
| **Anthropic** | Max plan pricing | [anthropic.com](https://www.anthropic.com/max) |
| **Google** | Gemini Documentation | [deepmind.google](https://deepmind.google/models/gemini/) |
| **Google** | Gemini 3.1 Flash-Lite model card | [deepmind.google](https://deepmind.google/models/model-cards/gemini-3-1-flash-lite/) |
| **Google** | Project Mariner | [deepmind.google](https://deepmind.google/en/models/project-mariner/) |
| **Google** | Google AI plans | [one.google.com](https://one.google.com/about/google-ai-plans/) |
| **Google** | Google AI Plus pricing | [blog.google](https://blog.google/products-and-platforms/products/google-one/google-ai-plus-availability/) |
| **Google** | Google AI Pro pricing | [one.google.com](https://one.google.com/about/plans) |
| **Google** | Google AI Ultra pricing | [blog.google](https://blog.google/products-and-platforms/products/google-one/google-ai-ultra/) |
| **GitHub** | Copilot plans & pricing | [github.com](https://github.com/features/copilot/plans) |
| **Zhipu AI (Z.ai)** | Developer Documentation | [docs.z.ai](https://docs.z.ai/) |
| **MiniMax** | Developer Documentation | [platform.minimax.io](https://platform.minimax.io/docs/guides/models-intro) |
| **MiniMax** | Pricing (Pay‑as‑you‑go) | [platform.minimax.io](https://platform.minimax.io/docs/guides/pricing-paygo) |
| **Moonshot AI** | Developer Documentation | [platform.moonshot.ai](https://platform.moonshot.ai/docs/overview) |
| **Moonshot AI** | Models & Pricing | [platform.moonshot.ai](https://platform.moonshot.ai/docs/pricing/chat) |
| **Cohere** | Developer Documentation | [docs.cohere.com](https://docs.cohere.com) |
| **AI21 Labs** | Developer Documentation | [docs.ai21.com](https://docs.ai21.com/docs/jamba-foundation-models) |
| **Perplexity** | Developer Documentation | [docs.perplexity.ai](https://docs.perplexity.ai) |
| **ByteDance (Volcengine)** | Developer Documentation | [volcengine.com](https://www.volcengine.com/docs/82379/1263482) |
| **Tencent (Hunyuan)** | Cloud Documentation | [cloud.tencent.com](https://cloud.tencent.com/document/product/1729/97730) |
| **Baidu (ERNIE)** | AI Studio Documentation | [ai.baidu.com](https://ai.baidu.com/ai-doc/AISTUDIO/Mmhslv9lf) |
| **DeepSeek** | Official Website | [deepseek.com](https://www.deepseek.com) |
| **Meta** | Llama Documentation | [llama.meta.com](https://llama.meta.com) |

#### Benchmark Sources

| Benchmark | Source | Description |
|-----------|--------|-------------|
| **GPQA Diamond** | Google Research | Graduate-level science questions (PhD difficulty) |
| **MMLU-Pro** | TIGER-Lab | Extended multi-task language understanding |
| **Arena Elo** | [lmarena.ai](https://lmarena.ai) | Crowdsourced human preference ranking |
| **HLE** | [Scale AI](https://lastexam.ai) | Humanity's Last Exam — expert-level questions |
| **SWE-bench Verified** | [Princeton](https://www.swebench.com) | Real GitHub issue resolution (human-verified) |
| **SWE-bench Pro** | [Princeton](https://www.swebench.com) | More challenging subset of SWE-bench |
| **LiveCodeBench** | [LiveCodeBench](https://livecodebench.github.io) | Live competitive programming problems |
| **AIME 2025** | MAA | American Invitational Mathematics Examination |
| **ARC-AGI-2** | [ARC Prize](https://arcprize.org) | Abstract reasoning challenge (fluid intelligence) |
| **MMMU / MMMU-Pro** | [MMMU](https://mmmu-benchmark.github.io) | Multi-discipline multimodal understanding |
| **IFEval** | Google Research | Instruction-following evaluation |
| **FrontierMath** | [Epoch AI](https://epoch.ai/frontiermath/tiers-1-4/about) | Expert-level research mathematics |
| **HumanEval** | OpenAI | 164 Python programming problems |

#### Verification Methodology

1. **Primary Source Review** - Check official documentation
2. **Cross-Validation** - Compare multiple sources
3. **Timestamp Verification** - All data includes verification date
4. **Update Tracking** - Monitor official channels


---

**Last Updated:** 2026-04-02 04:58 UTC
**Maintained by:** ReadyPixels LLC

---

Made with ❤️ by ReadyPixels LLC

[![Star on GitHub](https://img.shields.io/github/stars/ReadyPixels/AI_Models_Matrix?style=social)](https://github.com/ReadyPixels/AI_Models_Matrix)
