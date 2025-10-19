# Awesome AI Models Matrix [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> 🚀 A curated awesome list of top AI models and Large Language Models (LLMs) with comprehensive specifications, benchmarks, pricing, and official resources.

> **A comprehensive, community-driven resource meticulously curated to help developers, researchers, and organizations navigate the rapidly evolving landscape of artificial intelligence. This matrix provides transparent, up-to-date comparisons of 48+ leading AI models across performance benchmarks, pricing structures, deployment options, and licensing terms.**
>
> Whether you're building the next breakthrough application, conducting cutting-edge research, or making strategic technology decisions for your enterprise, this guide empowers you with the critical information needed to choose the perfect AI model for your specific needs.
>
**Last Updated:** 🗓️ October 7, 2025
**Total Models:** 48+ models from 15+ companies
**Data Sources:** OpenRouter Rankings, LLM-Stats.com, Official Documentation

---

## 📋 Table of Contents

- [🎯 About This Matrix](#-about-this-matrix)
- [🧠 Understanding LLMs](#-understanding-llms)
- [🆕 Latest Updates](#-latest-updates)
- [📊 Model Comparison Tables](#-model-comparison-tables)
  - [🔄 Sort by Latest Update](#-sort-by-latest-update)
  - [🏢 Sort by Company](#-sort-by-company)
  - [🖥️ Sort by Self-Hosting](#️-sort-by-self-hosting)
  - [💰 Sort by Price](#-sort-by-price)
- [🎯 Models by Category](#-models-by-category)
- [💻 Coding Models Deep Dive](#-coding-models-deep-dive)
- [🔗 Official Resources](#-official-resources)
- [📈 Performance Benchmarks](#-performance-benchmarks)
- [💰 Cost Analysis](#-cost-analysis)
- [🖥️ Self-Hosting Guide](#️-self-hosting-guide)
- [🔍 Model Selection Guide](#-model-selection-guide)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)

---

## 🎯 About This Matrix

This matrix provides a **comprehensive overview** of the leading AI models and LLMs available in 2025. Whether you're a 👨‍💻 developer, 🔬 researcher, or 🏢 enterprise decision-maker, this guide helps you understand the capabilities, costs, and trade-offs of each model.

### ✨ What's Included

- 🆕 **Latest Versions** - Up-to-date information on model releases
- 📊 **Benchmarks** - HumanEval, MMLU, SWE-bench, and other metrics
- 💰 **Pricing** - Transparent cost information per 1M tokens
- 🖥️ **Self-Hosting** - Open-source availability and licensing
- 🔗 **Official Links** - Direct access to documentation and APIs
- 🎯 **Sortable Tables** - Filter by update date, company, pricing, and more

---

## 🧠 Understanding LLMs

### What are Large Language Models?

**Large Language Models (LLMs)** are AI systems trained on vast amounts of text data to understand and generate human-like language. They power applications ranging from 💬 chatbots and 💻 coding assistants to ✍️ content creation and 📊 data analysis.

### 🔑 Key Concepts

- **Parameters** 📏 - The size of the model's neural network (billions or trillions of values)
- **Context Window** 📖 - How much text the model can process at once (measured in tokens)
- **Reasoning Models** 🧠 - Models that "think step-by-step" before answering
- **Multimodal** 🎨 - Models that can process text, images, audio, and video
- **MoE (Mixture of Experts)** 🎭 - Architecture that activates only relevant parts for efficiency
- **RAG (Retrieval Augmented Generation)** 🔍 - Enhancing models with external knowledge

### 🌟 Model Generations (2023-2025)

1. **GPT-3.5 Era** (2022-2023) 📱 - Foundation of conversational AI
2. **GPT-4 Era** (2023-2024) 🎨 - Multimodal capabilities and improved reasoning
3. **Reasoning Era** (2024-2025) 🧠 - Step-by-step thinking models (o1, R1)
4. **Unified Era** (2025) ⚡ - Hybrid models combining speed and reasoning
5. **Open-Source Surge** (2025) 🆓 - GPT-OSS, DeepSeek, Qwen competing with proprietary

---

## 🆕 Latest Updates

### 🔥 Recent Additions (Last 30 Days)

| Date | Model | Company | Highlights | Market Share* |
|------|-------|---------|------------|---------------|
| 2025-10-03 | 🏢 IBM Granite 4.0 | IBM | ISO 42001 certified, Mamba/Transformer hybrid, open weights | - |
| 2025-09-30 | 🇨🇳 GLM-4.6 | Zhipu AI | 355B MoE, real-world coding, open weights, $0.13/$0.39 | 6.0% tool calls |
| 2025-09-30 | 🔬 DeepSeek-V3.2-Exp | DeepSeek | Sparse Attention (DSA), efficient long-context, MIT license | 11.4% overall |
| 2025-09-29 | 👑 Claude 4.5 Sonnet | Anthropic | #2 Most Used - 35.5B tokens on OpenRouter | 13.6% overall |
| 2025-09-23 | 🤖 GPT-5 Codex | OpenAI | 7+ hour autonomous coding, API and open weights | 13.8% overall |
| 2025-09-11 | 🪶 Phi-4 | Microsoft | 14B compact reasoning, MIT license, self-hostable | - |
| 2025-09-10 | 🇨🇳 Qwen3-Next | Alibaba | Apache 2.0, strong coding, open weights | - |
| 2025-09-09 | 🌙 Kimi K2-0905 | Moonshot AI | 256K context, agentic coding, Modified MIT | - |
| 2025-09-05 | 🇨🇳 Qwen3-Max | Alibaba | 1T+ params, ranks 3rd globally, open weights | - |
| 2025-09-03 | 🇪🇺 TildeOpen LLM | Tilde AI | 30B params, 34 European languages, open weights | - |
| 2025-08-21 | 🔬 DeepSeek-V3.1 | DeepSeek | Hybrid architecture, 40% improvement, MIT license | 11.4% overall |
| 2025-08-07 | 🤖 GPT-5 | OpenAI | Unified reasoning, multimodal, open weights | - |
| 2025-08-05 | 🆓 GPT-OSS-120B | OpenAI | First open-weight since GPT-2, Apache 2.0 | - |
| 2025-08-05 | 🆓 GPT-OSS-20B | OpenAI | #6 Most Used - 20.7B tokens on OpenRouter, Apache 2.0 | - |
| 2025-08-01 | 🤗 StarCoder2 | BigCode/Hugging Face | New open-source coding models, community-driven | - |
| 2025-07-15 | 💻 Magistral | Mistral AI | European reasoning, open weights, self-hostable | - |

**Market Share Data from OpenRouter.ai (Live Usage Stats)*
| 2025-09-10 | 🇨🇳 Qwen3-Next | Alibaba | Apache 2.0, strong coding |
| 2025-09-09 | 🌙 Kimi K2-0905 | Moonshot AI | 256K context, agentic coding |
| 2025-09-05 | 🇨🇳 Qwen3-Max | Alibaba | 1T+ params, ranks 3rd globally |
| 2025-09-03 | 🇪🇺 TildeOpen LLM | Tilde AI | 30B params, 34 European languages |
| 2025-08-21 | 🔬 DeepSeek-V3.1 | DeepSeek | Hybrid architecture, 40% improvement |
| 2025-08-07 | 🤖 GPT-5 | OpenAI | Unified reasoning, multimodal |
| 2025-08-05 | 🆓 GPT-OSS-120B | OpenAI | First open-weight since GPT-2, Apache 2.0 | - |
| 2025-08-05 | 🆓 GPT-OSS-20B | OpenAI | #6 Most Used - 20.7B tokens on OpenRouter | - |

### 🔥 Top Performers (Real-World Usage - OpenRouter Rankings)

| Rank | Model | Company | Usage | Market Position |
|------|-------|---------|-------|-----------------|
| 🥇 #1 | **Grok Code Fast** | xAI | 174B tokens | 50% of coding category |
| 🥈 #2 | **Claude 4.5 Sonnet** | Anthropic | 35.5B tokens | 10.2% overall usage |
| 🥉 #3 | **Qwen3-Coder 30B** | Alibaba | 21.6B tokens | 6.2% coding market |
| #4 | **Claude 4 Sonnet** | Anthropic | 20.8B tokens | 6.0% overall |
| #5 | **GPT-OSS-20B** | OpenAI | 20.7B tokens | 6.0% overall |

**Market Share by Company (OpenRouter Live Stats):**
- 🥇 xAI: **26.8%** (426B tokens)
- 🥈 Google: **18.9%** (301B tokens)
- 🥉 OpenAI: **13.8%** (220B tokens)
- 🏅 Anthropic: **13.6%** (217B tokens)
- 🏅 DeepSeek: **11.4%** (181B tokens)

---

## 📊 Model Comparison Tables

### 🔄 Sort by Latest Update

> 💡 **Models sorted by most recently updated first** - ⭐ indicates updates within last 30 days

| 🏢 Company | 🤖 Model | 📦 Version | 📅 Release | 🔄 Last Updated | 💻 Coding | 📊 Benchmarks | 💰 Price ($/1M) | 🖥️ Self-Host | 🌟 Usage Rank | 🔗 Link |
|-----------|---------|----------|-----------|----------------|----------|--------------|----------------|-------------|---------------|---------|
| 🏢 **IBM** | Granite 4.0 | 4.0 Small | 2025-10-03 | **2025-10-03** ⭐ | ✅ Good | ~70% / ~75% | 🆓 Free | ✅ Apache 2.0 | - | [🔗](https://www.ibm.com/granite) |
| 🇨🇳 **Zhipu AI** | GLM-4.6 | GLM-4.6 | 2025-09-30 | **2025-09-30** ⭐ | ✅ Excellent | ~85% / ~84% | $0.13 / $0.39 | ✅ Open-weight | #4 Tool Calls | [🔗](https://chatglm.cn) |
| 🔬 **DeepSeek** | DeepSeek-V3.2-Exp | V3.2-Exp | 2025-09-29 | **2025-09-30** ⭐ | ✅ Excellent | Experimental DSA | $0.27 / $0.41 | ✅ MIT | #3 Coding | [🔗](https://www.deepseek.com) |
| 🤖 **Anthropic** | Claude 4.5 Sonnet | Sonnet 4.5 | 2025-09-29 | **2025-09-29** ⭐ | ✅ Best-in-class | SWE-bench leader | $3.00 / $15.00 | ❌ | 🥈 #2 Overall | [🔗](https://www.anthropic.com) |
| 🤖 **OpenAI** | GPT-5 Codex | Codex | 2025-09-23 | **2025-09-23** ⭐ | ✅ Best-in-class | Coding-optimized | API pricing | ❌ | [🔗](https://openai.com) |
| 🪶 **Microsoft** | Phi-4 | Phi-4 | 2024-12 | **2025-09-11** ⭐ | ✅ Good | ~70% / ~75% | 🆓 Free | ✅ MIT | [🔗](https://www.microsoft.com/research/) |
| 🇨🇳 **Alibaba** | Qwen3-Next | Qwen3-Next | 2025-09-10 | **2025-09-10** ⭐ | ✅ Good | ~80% / ~84% | Varies | ✅ Apache 2.0 | [🔗](https://qwenlm.github.io) |
| 🌙 **Moonshot AI** | Kimi K2-0905 | K2-0905 | 2025-09-09 | **2025-09-09** ⭐ | ✅ Excellent | 256K context | Varies | ✅ Modified MIT | [🔗](https://kimi.moonshot.cn) |
| 🇨🇳 **Alibaba** | Qwen3-Max | Qwen3-Max | 2025-09-05 | **2025-09-05** ⭐ | ✅ Excellent | ~82% / ~85% | $0.30 / $3.00 | ❌ API-only | [🔗](https://qwenlm.github.io) |
| 🇪🇺 **Tilde AI** | TildeOpen LLM | 30B | 2025-09-03 | **2025-09-03** ⭐ | ✅ Good | EU Languages | 🆓 Free | ✅ Open-source | [🔗](https://tilde.ai) |
| 🔬 **DeepSeek** | DeepSeek-V3.1 | V3.1 | 2025-08-21 | **2025-08-21** | ✅ Excellent | 82%+ / 85%+ | $0.27 / $0.41 | ✅ MIT | [🔗](https://www.deepseek.com) |
| 💻 **Mistral AI** | Codestral | 2508 | 2025-08 | **2025-08** | ✅ Excellent | Coding-specialized | $0.30 / $0.90 | ❌ | [🔗](https://mistral.ai) |
| 🤖 **OpenAI** | GPT-5 | GPT-5 | 2025-08-07 | **2025-08-07** | ✅ Excellent | ~90%+ / ~92% | $1.25 / $10.00 | ❌ | [🔗](https://openai.com) |
| 🤖 **Anthropic** | Claude Opus 4.1 | Opus 4.1 | 2025-08-05 | **2025-08-05** | ✅ Excellent | ~85%+ / ~85% | $15.00 / $75.00 | ❌ | [🔗](https://www.anthropic.com) |
| 🆓 **OpenAI** | GPT-OSS-120B | OSS-120B | 2025-08-05 | **2025-08-05** | ✅ Excellent | 91.4% / ~89% | 🆓 Free | ✅ Apache 2.0 | [🔗](https://openai.com) |
| 🆓 **OpenAI** | GPT-OSS-20B | OSS-20B | 2025-08-05 | **2025-08-05** | ✅ Good | ~85% / 85.3% | 🆓 Free | ✅ Apache 2.0 | [🔗](https://openai.com) |
| 🇨🇳 **Alibaba** | Qwen3-Coder | 480B | 2025-07-23 | **2025-07-23** | ✅ Excellent | Coding-optimized | 🆓 Free | ✅ Apache 2.0 | [🔗](https://qwenlm.github.io) |
| 🚀 **xAI** | Grok 4 | Grok 4 | 2025-07-09 | **2025-07-09** | ✅ Excellent | ~85% / ~87% | $3.00 / $15.00 | ❌ | [🔗](https://x.ai) |
| 🇨🇳 **Zhipu AI** | GLM-4.5 | GLM-4.5 | 2025-07 | **2025-07** | ✅ Good | ~82% / ~82% | $0.15 / $0.45 | ✅ Open-weight | [🔗](https://chatglm.cn) |
| 🌙 **Moonshot AI** | Kimi K2 | K2 | 2025-07 | **2025-07** | ✅ Excellent | ~85% / ~83% | Varies | ✅ Modified MIT | [🔗](https://kimi.moonshot.cn) |
| 💻 **Mistral AI** | Magistral | Magistral | 2025-06 | **2025-06** | ✅ Good | Reasoning | Varies | ❌ | [🔗](https://mistral.ai) |
| 🔬 **DeepSeek** | DeepSeek-R1 | R1-0528 | 2025-05-28 | **2025-05-28** | ✅ Excellent | 81% / 85% | $0.50 / $2.15 | ✅ MIT | [🔗](https://www.deepseek.com) |

---

### 🏢 Sort by Company

> 💡 **Models grouped by company/organization**

<details>
<summary><b>🤖 OpenAI Models (7 models)</b></summary>

| Model | Version | Release | Last Updated | Coding | Benchmarks | Price | Self-Host |
|-------|---------|---------|--------------|--------|------------|-------|-----------|
| GPT-5 Codex | Codex | 2025-09-23 | 2025-09-23 | ✅ Best | Coding-optimized | API | ❌ |
| GPT-5 | GPT-5 | 2025-08-07 | 2025-08-07 | ✅ Excellent | ~90%+ / ~92% | $1.25 / $10 | ❌ |
| 🆓 GPT-OSS-120B | OSS-120B | 2025-08-05 | 2025-08-05 | ✅ Excellent | 91.4% / ~89% | Free | ✅ Apache 2.0 |
| 🆓 GPT-OSS-20B | OSS-20B | 2025-08-05 | 2025-08-05 | ✅ Good | ~85% / 85.3% | Free | ✅ Apache 2.0 |
| o3 | o3 | 2025-04 | 2025-04 | ✅ Excellent | 85%+ / ~88% | $2.00 / $8 | ❌ |
| o1-Pro | o1-Pro API | 2025-03 | 2025-03 | ✅ Advanced | Pro reasoning | $150 / $600 | ❌ |
| o3-Mini | o3-Mini | 2024-12 | 2024-12 | ✅ Good | ~77% / ~87% | $1.10 / $4.40 | ❌ |

</details>

<details>
<summary><b>🤖 Anthropic Models (3 models)</b></summary>

| Model | Version | Release | Last Updated | Coding | Benchmarks | Price | Self-Host |
|-------|---------|---------|--------------|--------|------------|-------|-----------|
| Claude Sonnet 4.5 | Sonnet 4.5 | 2025-09-29 | 2025-09-29 | ✅ Best | SWE-bench leader | $3 / $15 | ❌ |
| Claude Opus 4.1 | Opus 4.1 | 2025-08-05 | 2025-08-05 | ✅ Excellent | ~85%+ / ~85% | $15 / $75 | ❌ |
| Claude 3.7 Sonnet | 3.7 Sonnet | 2025-02-24 | 2025-02-24 | ✅ Excellent | ~86% / ~84.8% | $3 / $15 | ❌ |

</details>

<details>
<summary><b>🔬 DeepSeek Models (4 models)</b></summary>

| Model | Version | Release | Last Updated | Coding | Benchmarks | Price | Self-Host |
|-------|---------|---------|--------------|--------|------------|-------|-----------|
| DeepSeek-V3.2-Exp | V3.2-Exp | 2025-09-29 | 2025-09-30 | ✅ Excellent | Experimental DSA | $0.27 / $0.41 | ✅ MIT |
| DeepSeek-V3.1 | V3.1 | 2025-08-21 | 2025-08-21 | ✅ Excellent | 82%+ / 85%+ | $0.27 / $0.41 | ✅ MIT |
| DeepSeek-R1 | R1-0528 | 2025-05-28 | 2025-05-28 | ✅ Excellent | 81% / 85% | $0.50 / $2.15 | ✅ MIT |
| 🆓 DeepSeek-Coder-V2 | Coder-V2 | 2024-06 | 2024-06 | ✅ Excellent | Coding specialist | Free | ✅ MIT |

</details>

<details>
<summary><b>🇨🇳 Alibaba/Qwen Models (5 models)</b></summary>

| Model | Version | Release | Last Updated | Coding | Benchmarks | Price | Self-Host |
|-------|---------|---------|--------------|--------|------------|-------|-----------|
| Qwen3-Next | Qwen3-Next | 2025-09-10 | 2025-09-10 | ✅ Good | ~80% / ~84% | Varies | ✅ Apache 2.0 |
| Qwen3-Max | Qwen3-Max | 2025-09-05 | 2025-09-05 | ✅ Excellent | ~82% / ~85% | $0.30 / $3 | ❌ API |
| 🆓 Qwen3-Coder | 480B | 2025-07-23 | 2025-07-23 | ✅ Excellent | Coding-optimized | Free | ✅ Apache 2.0 |
| 🆓 Qwen2.5-Coder | 32B | 2024-11 | 2024-11 | ✅ Excellent | Coding-focused | Free | ✅ Apache 2.0 |
| Qwen2.5-Max | 2.5-Max | 2025-01-29 | 2025-01-29 | ✅ Good | ~80% / ~84% | Varies | ❌ API |

</details>

<details>
<summary><b>🇨🇳 Zhipu AI (Z.ai) Models (2 models)</b></summary>

| Model | Version | Release | Last Updated | Coding | Benchmarks | Price | Self-Host |
|-------|---------|---------|--------------|--------|------------|-------|-----------|
| GLM-4.6 | GLM-4.6 | 2025-09-30 | 2025-09-30 | ✅ Excellent | ~85% / ~84% | $0.13 / $0.39 | ✅ Open-weight |
| GLM-4.5 | GLM-4.5 | 2025-07 | 2025-07 | ✅ Good | ~82% / ~82% | $0.15 / $0.45 | ✅ Open-weight |

</details>

<details>
<summary><b>🌙 Moonshot AI Models (2 models)</b></summary>

| Model | Version | Release | Last Updated | Coding | Benchmarks | Price | Self-Host |
|-------|---------|---------|--------------|--------|------------|-------|-----------|
| Kimi K2-0905 | K2-0905 | 2025-09-09 | 2025-09-09 | ✅ Excellent | 256K context | Varies | ✅ Modified MIT |
| Kimi K2 | K2 | 2025-07 | 2025-07 | ✅ Excellent | ~85% / ~83% | Varies | ✅ Modified MIT |

</details>

<details>
<summary><b>Other Companies (10+ models)</b></summary>

**🌐 Google DeepMind** - Gemini 2.5 Pro, Gemini 2.5 Flash
**🚀 xAI** - Grok 4, Grok 4 Fast, Grok 3
**🦙 Meta** - Llama 4 Maverick, Llama 4 Scout
**💻 Mistral AI** - Codestral, Magistral, Medium 3, Pixtral Large, Large 2
**🏢 IBM** - Granite 4.0
**🪶 Microsoft** - Phi-4
**🇪🇺 Tilde AI** - TildeOpen LLM
**And more...**

</details>

---

### 🖥️ Sort by Self-Hosting

> 💡 **Models filtered by self-hosting capability**

#### ✅ Self-Hostable Models (20+ models)

| Model | Company | Parameters | License | API Price | Last Updated |
|-------|---------|------------|---------|-----------|--------------|
| 🆓 GPT-OSS-120B | OpenAI | 117B (5.1B active) | Apache 2.0 | Free | 2025-08-05 |
| 🆓 GPT-OSS-20B | OpenAI | 21B (3.6B active) | Apache 2.0 | Free | 2025-08-05 |
| 🆓 DeepSeek-V3.2-Exp | DeepSeek | 671B (37B active) | MIT | $0.27/$0.41 | 2025-09-30 |
| 🆓 DeepSeek-V3.1 | DeepSeek | 671B (37B active) | MIT | $0.27/$0.41 | 2025-08-21 |
| 🆓 DeepSeek-R1 | DeepSeek | 671B | MIT | $0.50/$2.15 | 2025-05-28 |
| 🆓 DeepSeek-Coder-V2 | DeepSeek | 236B | MIT | Free | 2024-06 |
| 🆓 Qwen3-Next | Alibaba | Various | Apache 2.0 | Varies | 2025-09-10 |
| 🆓 Qwen3-Coder | Alibaba | 480B | Apache 2.0 | Free | 2025-07-23 |
| 🆓 Qwen2.5-Coder | Alibaba | 32B | Apache 2.0 | Free | 2024-11 |
| 🆓 Kimi K2-0905 | Moonshot AI | 1T (32B active) | Modified MIT | Varies | 2025-09-09 |
| 🆓 Kimi K2 | Moonshot AI | 1T (32B active) | Modified MIT | Varies | 2025-07 |
| 🆓 GLM-4.6 | Zhipu AI | 355B MoE | Open-weight | $0.13/$0.39 | 2025-09-30 |
| 🆓 GLM-4.5 | Zhipu AI | Various | Open-weight | $0.15/$0.45 | 2025-07 |
| 🆓 Llama 4 Maverick | Meta | 400B | Meta License | Free | 2025-04-05 |
| 🆓 Llama 4 Scout | Meta | 109B | Meta License | Free | 2025-04-05 |
| 🆓 Granite 4.0 | IBM | 8B-3B active | Apache 2.0 | Free | 2025-10-03 |
| 🆓 Phi-4 | Microsoft | 14B | MIT | Free | 2025-09-11 |
| 🆓 TildeOpen LLM | Tilde AI | 30B | Open-source | Free | 2025-09-03 |
| 🆓 Yi-Coder | 01.AI | 9B / 1.5B | Apache 2.0 | Free | 2024-09 |
| 🆓 StarCoder2 | BigCode/HF | 3B-15B | BigCode | Free | 2024 |

#### ❌ API-Only Models (Proprietary)

| Model | Company | Pricing | Performance | Last Updated |
|-------|---------|---------|-------------|--------------|
| GPT-5 | OpenAI | $1.25 / $10 | Excellent | 2025-08-07 |
| GPT-5 Codex | OpenAI | API pricing | Best coding | 2025-09-23 |
| Claude Sonnet 4.5 | Anthropic | $3 / $15 | Best coding | 2025-09-29 |
| Claude Opus 4.1 | Anthropic | $15 / $75 | Excellent | 2025-08-05 |
| Gemini 2.5 Pro | Google | $1.25 / $10 | 99% HumanEval | 2025-01-31 |
| Grok 4 | xAI | $3 / $15 | Excellent | 2025-07-09 |
| Grok 4 Fast | xAI | $0.20 / $1.50 | Cost-efficient | 2025-09 |

---

### 💰 Sort by Price

> 💡 **Models sorted by cost (cheapest first)**

#### 🆓 Free Models (Self-Hostable)

All models in the "Self-Hostable" section above are free to self-host!

#### 💵 Budget-Friendly (< $0.50 per 1M tokens)

| Model | Company | Input | Output | Total (avg) |
|-------|---------|-------|--------|-------------|
| 🥇 GLM-4.6 | Zhipu AI | $0.13 | $0.39 | $0.26 |
| 🥈 Yi-Lightning | 01.AI | $0.14 | $0.42 | $0.28 |
| 🥉 Grok 4 Fast | xAI | $0.20 | $1.50 | $0.85 |
| DeepSeek-V3.1/V3.2 | DeepSeek | $0.27 | $0.41 | $0.34 |
| Gemini 2.5 Flash | Google | $0.30 | $2.50 | $1.40 |
| Qwen3-Max | Alibaba | $0.30 | $3.00 | $1.65 |
| Codestral | Mistral AI | $0.30 | $0.90 | $0.60 |

#### 💰 Mid-Tier ($1 - $5 per 1M tokens)

| Model | Company | Input | Output | Total (avg) |
|-------|---------|-------|--------|-------------|
| GPT-5 | OpenAI | $1.25 | $10.00 | $5.63 |
| Gemini 2.5 Pro | Google | $1.25 | $10.00 | $5.63 |
| Mistral Medium 3 | Mistral AI | $1.00 | $3.00 | $2.00 |
| Mistral Large 2 | Mistral AI | $2.00 | $6.00 | $4.00 |
| o3 | OpenAI | $2.00 | $8.00 | $5.00 |
| Claude Sonnet 4.5 | Anthropic | $3.00 | $15.00 | $9.00 |
| Grok 4 | xAI | $3.00 | $15.00 | $9.00 |

#### 💎 Premium (> $5 per 1M tokens)

| Model | Company | Input | Output | Total (avg) |
|-------|---------|-------|--------|-------------|
| Claude Opus 4.1 | Anthropic | $15.00 | $75.00 | $45.00 |
| o1-Pro | OpenAI | $150.00 | $600.00 | $375.00 |

---

## 🎯 Models by Category

### 🏆 Frontier Models

The most advanced, cutting-edge models with state-of-the-art capabilities:

- **🥇 Grok Code Fast** (xAI) - **#1 Most Used** - 50% of coding market, 174B tokens
- **🥈 Claude 4.5 Sonnet** (Anthropic) - **#2 Overall** - Best coding, 35.5B tokens
- **GPT-5** (OpenAI) - Unified reasoning and multimodal, $1.25/$10
- **Gemini 2.5 Pro** (Google) - Leading multimodal reasoning, 99% HumanEval
- **Grok 4** (xAI) - First-principles reasoning, 26.8% company market share
- **Qwen3-Max** (Alibaba) - 1T+ parameters, ranks 3rd globally
- **GPT-OSS-120B** (OpenAI) - First open-weight since GPT-2, Apache 2.0

#### Commercial Coding Models
- **Claude Sonnet 4.5** (Anthropic) - SWE-bench Verified leader
- **GPT-5 Codex** (OpenAI) - 7+ hour autonomous coding
- **Codestral** (Mistral AI) - Low-latency, fill-in-middle
- **Grok 4 Fast** (xAI) - Cost-efficient at $0.20/$1.50

#### Open-Source Coding Models
- **GPT-OSS-120B** (OpenAI) - 91.4% AIME, Apache 2.0
- **Qwen3-Coder** (Alibaba) - 480B params, autonomous coding
- **DeepSeek-Coder-V2** (DeepSeek) - 236B params, MIT
- **Kimi K2-0905** (Moonshot AI) - 256K context, agentic tasks
- **GLM-4.6** (Zhipu AI) - Real-world coding, $0.13/$0.39
- **IBM Granite 4.0** - Enterprise-ready, ISO 42001

### 🧠 Reasoning Models

Models that employ chain-of-thought and step-by-step problem solving:

- **o3 / o1-Pro** (OpenAI) - Advanced reasoning with extended thinking
- **DeepSeek-R1** (DeepSeek) - Open-source reasoning champion, MIT
- **Claude 3.7 Sonnet** (Anthropic) - Hybrid reasoning model
- **Magistral** (Mistral AI) - European reasoning model
- **Qwen3-Max-Thinking** (Alibaba) - 100% AIME25 accuracy

### 🆓 Open-Source Models (2025)

Freely available models with permissive licenses (Apache 2.0, MIT, etc.) and public source code:

- **GPT-OSS-120B / GPT-OSS-20B** (OpenAI) — Apache 2.0; first open-weight since GPT-2; strong coding and reasoning.
- **DeepSeek-R1 / V3.1 / V3.2 / Coder-V2** (DeepSeek) — MIT License; top-tier open-source reasoning and coding.  
  [GitHub](https://github.com/deepseek-ai/deepseek-coder)
- **Llama 4 (Scout/Maverick)** (Meta) — Multimodal, open weights; supports text, image, and code tasks.
- **Qwen3-Next / Qwen3-Coder / Qwen3-Max / Qwen2.5-Coder** (Alibaba) — Apache 2.0; competitive coding and reasoning, multilingual.  
  [GitHub](https://github.com/QwenLM/Qwen)
- **Yi-Coder** (01.AI) — MIT License; 128K context, 52 programming languages, efficient for local deployment.  
  [GitHub](https://github.com/01-ai/Yi)
- **TildeOpen LLM** (Tilde AI) — European language specialist, open weights.
  [Hugging Face](https://huggingface.co/tilde-research)
- **Phi-4** (Microsoft) — MIT License; compact, efficient, strong reasoning.
- **GLM-4.6 / GLM-4.5** (Zhipu AI) — Open-weight, real-world coding, multilingual.
- **Kimi K2-0905 / Kimi K2** (Moonshot AI) — Modified MIT; agentic coding, 256K context.
- **Codestral** (Mistral AI) — Coding-specialized, low-latency, open weights.  
  [GitHub](https://github.com/mistralai/codestral)
- **StarCoder2** (BigCode/Hugging Face) — Community-driven, open-source coding.  
  [GitHub](https://github.com/bigcode-project/starcoder2)
- **Magistral** (Mistral AI) — European reasoning, open weights.
- **IBM Granite 4.0** — Apache 2.0; enterprise-ready, ISO 42001 certified.

**Recent 2025 additions:**
- **Qwen3-Max** (Alibaba) — 1T+ parameters, top-tier performance.
- **GLM-4.6** (Zhipu AI) — 355B MoE, real-world coding, multilingual.
- **StarCoder2** — New open-source coding models from BigCode/Hugging Face.
- **Magistral** — Reasoning-focused, open weights, European origin.

*Most open-source models now support context windows of 128K–256K tokens, multimodal capabilities, and community benchmarks (HumanEval, SWE-bench, MMLU).*

### 💻 Coding-Specialized Models

Optimized for software development tasks:

#### Commercial Coding Models
- **Claude Sonnet 4.5** (Anthropic) - SWE-bench Verified leader
- **GPT-5 Codex** (OpenAI) - 7+ hour autonomous coding
- **Codestral** (Mistral AI) - Low-latency, fill-in-middle
- **Grok 4 Fast** (xAI) - Cost-efficient at $0.20/$1.50

#### Open-Source Coding Models
- **GPT-OSS-120B** (OpenAI) - 91.4% AIME, Apache 2.0
- **Qwen3-Coder** (Alibaba) - 480B params, autonomous coding
- **DeepSeek-Coder-V2** (DeepSeek) - 236B params, MIT
- **Kimi K2-0905** (Moonshot AI) - 256K context, agentic tasks
- **GLM-4.6** (Zhipu AI) - Real-world coding, $0.13/$0.39
- **IBM Granite 4.0** - Enterprise-ready, ISO 42001

### 🎨 Multimodal Models

Process text, images, audio, and video:

- **GPT-5** (OpenAI) - Unified multimodal interface
- **Gemini 2.5 Pro/Flash** (Google) - Native multimodal architecture
- **Claude Sonnet 4.5** (Anthropic) - Vision and document understanding
- **Pixtral Large** (Mistral AI) - 124B params, image understanding
- **Llama 4 Maverick** (Meta) - Native multimodality

### 🏢 Enterprise Models

Designed for business and production deployments:

- **Claude Opus 4.1** (Anthropic) - ASL-3 safety, highest capability
- **Gemini 2.5 Pro** (Google) - Google Cloud integration
- **Command A** (Cohere) - Enterprise RAG, 10+ languages
- **Jamba 1.6** (AI21 Labs) - Private deployment, hybrid architecture
- **IBM Granite 4.0** - ISO 42001 certified, auditable

---

## 💻 Coding Models Deep Dive

### 🏆 Best Coding Models by Task

**Code Generation & Autocomplete:**
1. 🥇 **Grok Code Fast** (xAI) - **#1 Most Used** - 174B tokens
2. 🥈 Claude 4.5 Sonnet - Most accurate, #2 overall
3. 🥉 GPT-5 Codex - Complex algorithms

**Code Review & Refactoring:**
1. 🥇 Claude 4.5 Sonnet - Industry-leading, 35.5B tokens
2. 🥈 Grok Code Fast - Real-world proven, 50% market
3. 🥉 GPT-5 Codex - Large-scale refactoring

**Debugging & Error Fixing:**
1. 🥇 Claude 4.5 Sonnet - Clear explanations
2. 🥈 GPT-5 Codex - Deep analysis
3. 🥉 DeepSeek-V3.1 - Reasoning-based

**Test Generation:**
1. 🥇 Grok Code Fast - Real-world adoption leader
2. 🥈 Claude 4.5 Sonnet - Comprehensive coverage
3. 🥉 Codestral - Purpose-built for testing

**Real-World Usage (OpenRouter Live Data):**
- **Grok Code Fast dominates** with 50% of coding category
- **Claude 4.5 Sonnet** is #2 most deployed model
- **Qwen3-Coder 30B** is #3 in coding workflows

### 🏆 Coding Benchmarks (SWE-bench Verified)

1. 🥇 **Claude Sonnet 4.5** - State-of-the-art
2. 🥈 **GPT-5 Codex** - 7+ hour autonomous coding
3. 🥉 **GPT-OSS-120B** - 91.4% AIME, open-source leader
4. **Kimi K2-0905** - Agentic coding excellence
5. **Qwen3-Coder** - 480B autonomous generation
6. **DeepSeek-V3.2-Exp** - Sparse attention efficiency
7. **GLM-4.6** - Real-world tasks
8. **Grok 4 Fast** - Best cost/performance
9. **IBM Granite 4.0** - Enterprise-grade
10. **Phi-4** - Compact reasoning

### 📏 Context Window Comparison

For working with large codebases:

1. 🌙 **Kimi K2-0905** - 256K tokens (≈192K lines)
2. 🇨🇳 **GLM-4.6** - 200K tokens (≈150K lines)
3. 🤖 **Claude Sonnet 4.5** - 200K tokens (≈150K lines)
4. 🇨🇳 **Qwen3-Coder** - 128K tokens (≈96K lines)
5. 🔬 **DeepSeek-Coder-V2** - 128K tokens (≈96K lines)

---

## 🔗 Official Resources

### 🤖 OpenAI
- **Website:** [openai.com](https://openai.com)
- **API Docs:** [platform.openai.com](https://platform.openai.com/docs)
- **Models:** GPT-5, GPT-5 Codex, GPT-OSS-120B/20B, o3, o1-Pro

### 🤖 Anthropic
- **Website:** [anthropic.com](https://www.anthropic.com)
- **API Docs:** [docs.anthropic.com](https://docs.anthropic.com)
- **Models:** Claude Sonnet 4.5, Claude Opus 4.1, Claude 3.7 Sonnet

### 🌐 Google DeepMind
- **Website:** [deepmind.google/gemini](https://deepmind.google/technologies/gemini/)
- **API Docs:** [ai.google.dev](https://ai.google.dev)
- **Models:** Gemini 2.5 Pro, Gemini 2.5 Flash

### 🚀 xAI
- **Website:** [x.ai](https://x.ai)
- **Chat:** [grok.x.ai](https://grok.x.ai)
- **Models:** Grok 4, Grok 4 Fast, Grok 3

### 🔬 DeepSeek
- **Website:** [deepseek.com](https://www.deepseek.com)
- **GitHub:** [github.com/deepseek-ai](https://github.com/deepseek-ai)
- **Models:** DeepSeek-R1, V3.1, V3.2-Exp, Coder-V2

### 🇨🇳 Alibaba/Qwen
- **Website:** [qwenlm.github.io](https://qwenlm.github.io)
- **GitHub:** [github.com/QwenLM](https://github.com/QwenLM)
- **Models:** Qwen3-Max, Qwen3-Next, Qwen3-Coder

### 🇨🇳 Zhipu AI (Z.ai)
- **Website:** [chatglm.cn](https://chatglm.cn)
- **GitHub:** [github.com/THUDM](https://github.com/THUDM)
- **Models:** GLM-4.6, GLM-4.5

### 🌙 Moonshot AI
- **Website:** [moonshot.cn](https://www.moonshot.cn)
- **Chat:** [kimi.moonshot.cn](https://kimi.moonshot.cn)
- **Models:** Kimi K2-0905, Kimi K2

### 🦙 Meta AI
- **Website:** [llama.meta.com](https://llama.meta.com)
- **GitHub:** [github.com/meta-llama](https://github.com/meta-llama)
- **Models:** Llama 4 Maverick, Llama 4 Scout

### 💻 Mistral AI
- **Website:** [mistral.ai](https://mistral.ai)
- **Chat:** [chat.mistral.ai](https://chat.mistral.ai)
- **Models:** Codestral, Magistral, Mistral Large 2, Pixtral Large

### 🏢 IBM Research
- **Website:** [ibm.com/granite](https://www.ibm.com/granite)
- **GitHub:** [github.com/ibm-granite](https://github.com/ibm-granite)
- **Models:** Granite 4.0

### 🪶 Microsoft Research
- **Website:** [microsoft.com/research](https://www.microsoft.com/en-us/research/)
- **GitHub:** [github.com/microsoft](https://github.com/microsoft)
- **Models:** Phi-4

### 🇪🇺 Tilde AI
- **Website:** [tilde.ai](https://tilde.ai)
- **Hugging Face:** [huggingface.co/tilde-research](https://huggingface.co/tilde-research)
- **Models:** TildeOpen LLM

---

## 📈 Performance Benchmarks

### 🏆 Coding Benchmarks (SWE-bench Verified)

1. 🥇 **Claude Sonnet 4.5** - State-of-the-art
2. 🥈 **GPT-5 Codex** - 7+ hour autonomous coding
3. 🥉 **GPT-OSS-120B** - 91.4% AIME, open-source leader
4. **Kimi K2-0905** - Agentic coding excellence
5. **Qwen3-Coder** - 480B autonomous generation
6. **DeepSeek-V3.2-Exp** - Sparse attention efficiency
7. **GLM-4.6** - Real-world tasks
8. **Grok 4 Fast** - Best cost/performance
9. **IBM Granite 4.0** - Enterprise-grade
10. **Phi-4** - Compact reasoning

### 🧮 Reasoning Benchmarks (AIME 2025)

1. 🥇 **Qwen3-Max-Thinking** - 100% accuracy
2. 🥈 **o1-Pro** - Advanced reasoning
3. 🥉 **GPT-OSS-120B** - 91.4%
4. **GPT-5** - ~90%
5. **DeepSeek-R1** - 81%
6. **Grok 4** - ~85%

### 📚 General Knowledge (MMLU)

1. 🥇 **GPT-5** - ~92%
2. 🥈 **o3** - ~88%
3. 🥉 **Gemini 2.5 Pro** - 86.4%
4. **DeepSeek-V3.1** - 85%+
5. **Claude Opus 4.1** - ~85%

---

## 💰 Cost Analysis

### 🆓 Most Affordable Options

**Free Self-Hostable (20+ models):**
- All models in "Self-Hostable" section can be run for FREE!
- No API costs when self-hosting
- Just need appropriate hardware

**Cheapest Commercial APIs:**
1. 🥇 **GLM-4.6** - $0.13/$0.39 per 1M tokens
2. 🥈 **Yi-Lightning** - $0.14/$0.42 per 1M tokens
3. 🥉 **Grok 4 Fast** - $0.20/$1.50 per 1M tokens

### 💎 Best Value (Performance/Cost)

1. **DeepSeek-V3.1** - Excellent performance, ultra-low cost
2. **Grok 4 Fast** - Frontier performance, $0.20/$1.50
3. **Qwen3-Max** - Top-3 global, $0.30/$3.00
4. **Gemini 2.5 Flash** - Fast & capable, $0.30/$2.50
5. **Claude Sonnet 4.5** - Best coding, $3/$15 (reasonable)

---

## 🖥️ Self-Hosting Guide

### 🔧 Hardware Requirements

**Small Models (7-20B parameters):**
- **GPU:** 1x RTX 3090/4090 (24GB VRAM)
- **RAM:** 32GB+
- **Storage:** 50GB+ SSD
- **Examples:** Phi-4, GPT-OSS-20B, Yi-Coder

**Medium Models (30-70B parameters):**
- **GPU:** 2x RTX 4090 or 1x A100 (40-80GB)
- **RAM:** 64GB+
- **Storage:** 100GB+ SSD
- **Examples:** Qwen3-Coder, TildeOpen LLM, Llama 4 Scout

**Large Models (120B+ parameters):**
- **GPU:** 4x A100 (80GB) or 8x RTX 4090
- **RAM:** 128GB+
- **Storage:** 200GB+ SSD
- **Examples:** GPT-OSS-120B, Pixtral Large

### 📦 Deployment Options

**Local Inference:**
- **Ollama** - Easy local deployment ([ollama.ai](https://ollama.ai))
- **LM Studio** - User-friendly GUI ([lmstudio.ai](https://lmstudio.ai))
- **llama.cpp** - Efficient C++ implementation
- **vLLM** - High-throughput serving ([vllm.ai](https://vllm.ai))

**Cloud Self-Hosting:**
- **Hugging Face Inference** - Managed deployment
- **AWS/GCP/Azure** - Full control, scalable
- **RunPod/Vast.ai** - GPU rental platforms
- **Modal/Replicate** - Serverless options

### 🖥️ Self-Hosted Models (2025)

Models that can be run locally or on your own infrastructure (open weights, permissive license) with public source code:

**Coding:**
- DeepSeek-Coder-V2 (MIT) — [GitHub](https://github.com/deepseek-ai/deepseek-coder)
- Qwen3-Coder (Apache 2.0) — [GitHub](https://github.com/QwenLM/Qwen)
+- GPT-OSS-120B (Apache 2.0)
- Codestral (Mistral AI, open weights) — [GitHub](https://github.com/mistralai/codestral)
- StarCoder2 (BigCode/Hugging Face) — [GitHub](https://github.com/bigcode-project/starcoder2)

**General Use:**
- GPT-OSS-20B (Apache 2.0)
- Phi-4 (MIT) — [GitHub](https://github.com/microsoft/phi-1)
- DeepSeek-V3.1 (MIT) — [GitHub](https://github.com/deepseek-ai/deepseek-coder)
- Llama 4 Scout (Meta license) — [GitHub](https://github.com/meta-llama/llama3)
- GLM-4.6 (Zhipu AI, open weights) — [GitHub](https://github.com/THUDM/ChatGLM3)

**Enterprise:**
- IBM Granite 4.0 (Apache 2.0, ISO 42001)
- Llama 4 Maverick (Meta license) — [GitHub](https://github.com/meta-llama/llama3)
- Qwen3-Max (Apache 2.0) — [GitHub](https://github.com/QwenLM/Qwen)
- Magistral (Mistral AI, open weights)

**Recent 2025 additions:**
- Qwen3-Max (Alibaba) — 1T+ parameters, self-hostable.
- GLM-4.6 (Zhipu AI) — 355B MoE, open weights, self-hostable.
- StarCoder2 — New open-source coding models, easy to self-host.
- Magistral — Reasoning, open weights, European origin.

*Most self-hosted models now support large context windows, multimodal tasks, and efficient deployment on consumer or enterprise hardware.*

---

## 🔍 Model Selection Guide

### 💼 By Use Case

**🏢 Enterprise Production:**
- **Best:** Claude Opus 4.1, IBM Granite 4.0
- **Budget:** DeepSeek-V3.1, Qwen3-Max
- **Self-Host:** IBM Granite 4.0, Llama 4

**💻 Software Development:**
- **Best:** Claude Sonnet 4.5, GPT-5 Codex
- **Popular:** Grok Code Fast (50% market share)
- **Self-Host:** DeepSeek-Coder-V2, Qwen3-Coder

**🔬 Research & Analysis:**
- **Reasoning:** o1-Pro, Qwen3-Max-Thinking
- **General:** GPT-5, Gemini 2.5 Pro
- **Open:** GPT-OSS-120B, DeepSeek-R1

**🎨 Creative & Multimodal:**
- **Best:** GPT-5, Gemini 2.5 Pro
- **Vision:** Pixtral Large, Claude Sonnet 4.5
- **Affordable:** Gemini 2.5 Flash

**🌍 Multilingual & Regional:**
- **Chinese:** Qwen3-Max, GLM-4.6, Kimi K2
- **European:** TildeOpen LLM (34 languages)
- **Global:** GPT-5, Gemini 2.5 Pro

### 💰 By Budget

**🆓 Free (Self-Host Only):**
- GPT-OSS-120B/20B, DeepSeek models, Llama 4, Phi-4

**💵 Budget-Friendly ($0.10-$0.50 per 1M):**
- GLM-4.6, Yi-Lightning, Grok 4 Fast, DeepSeek-V3.1

**💎 Mid-Range ($1-$5 per 1M):**
- GPT-5, Gemini 2.5 Flash, Claude Sonnet 4.5, Grok 4

**👑 Premium ($10+ per 1M):**
- Claude Opus 4.1, o1-Pro, Gemini 2.5 Pro

### ⚡ By Performance Needs

**Speed Priority:**
- Gemini 2.5 Flash, Grok 4 Fast, Claude 3.7 Sonnet

**Quality Priority:**
- Claude Opus 4.1, GPT-5, o1-Pro

**Balanced:**
- Claude Sonnet 4.5, GPT-5, DeepSeek-V3.1

---

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

### 📝 How to Contribute

1. **Fork the Repository**
2. **Add/Update Model Information**
   - Verify from official sources
   - Include benchmark data
   - Add pricing information
   - Provide official links
3. **Follow the Style Guide**
   - Use emojis consistently
   - Match existing formatting
   - Keep tables aligned
4. **Submit a Pull Request**
   - Describe your changes
   - Include sources/verification
   - Follow [UPDATE_RULES.md](UPDATE_RULES.md)

### 🎯 What We Need

- ✅ New model releases and updates
- ✅ Benchmark results and performance data
- ✅ Pricing updates and corrections
- ✅ Bug fixes and typo corrections
- ✅ Additional resources and links
- ✅ Real-world usage insights
- ✅ Community feedback and reviews

### 📋 Guidelines

Please read our detailed contribution guidelines:
- [CONTRIBUTING.md](CONTRIBUTING.md) - Full contribution guide
- [UPDATE_RULES.md](UPDATE_RULES.md) - Update standards

### 🙏 Contributors

Special thanks to all contributors who help keep this matrix up-to-date!

---

## 📜 License

### Project License

This project is licensed under the **GNU General Public License v3.0 (GPL-3.0)**.

**Copyright (c) 2025 ReadyPixels**

For full license terms, see: [GNU GPL v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html)

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

### 📊 Data Sources Attribution

This project aggregates information from:
- **OpenRouter Rankings** - [openrouter.ai](https://openrouter.ai) - Real-world usage statistics
- **LLM-Stats.com** - [llm-stats.com](https://llm-stats.com) - Benchmark aggregation
- **Official Documentation** - Direct from model providers
- **Community Contributions** - GitHub contributors

### ⚖️ Model Licenses

Each AI model listed has its own license. Please refer to official documentation:
- **Open Source:** Apache 2.0, MIT, Modified MIT, etc.
- **Proprietary:** API usage terms from providers
- **Enterprise:** Contact providers for licensing

---

## 🔗 Quick Links

- 📊 [OpenRouter Rankings](https://openrouter.ai/rankings) - Live usage data
- 📈 [LLM-Stats.com](https://llm-stats.com) - Benchmark comparisons
- 🤗 [Hugging Face](https://huggingface.co/models) - Model repository
- 📖 [Awesome Lists](https://github.com/sindresorhus/awesome) - Curated lists

---



<div align="center">

**⭐ Star this repository if you find it helpful! ⭐**

*Last Updated: October 7, 2025*

</div>

---

## 📚 Additional Resources

- **OpenRouter Rankings** - [openrouter.ai/rankings](https://openrouter.ai/rankings)
- **LLM-Stats** - [llm-stats.com](https://llm-stats.com)
- **HuggingFace Leaderboard** - [huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard)
- **Awesome LLM** - [github.com/Hannibal046/Awesome-LLM](https://github.com/Hannibal046/Awesome-LLM)


---

**🚀 The most comprehensive AI models matrix on the internet!**
*Made with ❤️ by [ReadyPixels](https://readypixels.com) for the global AI community*
*Last Updated: October 7, 2025*
