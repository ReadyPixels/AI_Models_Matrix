# Awesome AI Models Matrix 🧠

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--02--23%2023%3A50%20UTC-green.svg)](https://github.com/ReadyPixels/AI_Models_Matrix)

> Comprehensive curated list of AI models, tools, and resources for developers and researchers. From frontier proprietary models to self-hostable open-source alternatives, from AI-powered IDEs to automation frameworks.

---

## Table of Contents

- [Awesome AI Models Matrix 🧠](#awesome-ai-models-matrix-)
  - [Table of Contents](#table-of-contents)
  - [Models 🧠](#models-)
    - [Frontier Models 🚀](#frontier-models-)
      - [Top Models by Category](#top-models-by-category)
      - [January 2026 Model Releases](#january-2026-model-releases)
      - [February 2026 Model Releases](#february-2026-model-releases)
      - [Latest Updates ⭐ (Last 30 Days)](#latest-updates--last-30-days)
    - [Open-Source Models 🆓](#open-source-models-)
      - [Deployment Options](#deployment-options)
    - [Coding Models 💻](#coding-models-)
      - [SWE-bench Verified Leaderboard](#swe-bench-verified-leaderboard)
      - [Commercial Coding Models](#commercial-coding-models)
      - [Open-Source Coding Models](#open-source-coding-models)
    - [Reasoning Models 🧠](#reasoning-models-)
      - [AIME 2025 Leaderboard](#aime-2025-leaderboard)
      - [Reasoning Model Details](#reasoning-model-details)
      - [Use Cases](#use-cases)
    - [Multimodal Models 🎨](#multimodal-models-)
      - [Leading Multimodal Models](#leading-multimodal-models)
      - [Vision Capabilities](#vision-capabilities)
      - [Audio \& Video](#audio--video)
      - [Image Generation](#image-generation)
    - [Hardware Requirements 🖥️](#hardware-requirements-️)
      - [Quick Reference by Model Size](#quick-reference-by-model-size)
      - [By Hardware Tier](#by-hardware-tier)
      - [Quantization Explained](#quantization-explained)
  - [Development Tools 🛠️](#development-tools-️)
    - [IDEs 💻](#ides-)
      - [Agentic IDEs](#agentic-ides)
      - [Native AI Editors](#native-ai-editors)
      - [IDE Updates (January 2026)](#ide-updates-january-2026)
      - [IDE Updates (February 2026)](#ide-updates-february-2026)
      - [VS Code Forks](#vs-code-forks)
      - [Web-Based IDEs](#web-based-ides)
    - [CLI Tools 🖥️](#cli-tools-️)
      - [Autonomous Coding Agents](#autonomous-coding-agents)
      - [Assisted CLI Tools](#assisted-cli-tools)
      - [Terminal Enhancers](#terminal-enhancers)
    - [IDE Add-ons 🧩](#ide-add-ons-)
      - [Universal (Cross-Platform)](#universal-cross-platform)
      - [IDE Extension Updates (January 2026)](#ide-extension-updates-january-2026)
      - [VS Code Specific](#vs-code-specific)
      - [JetBrains Specific](#jetbrains-specific)
    - [API Providers 🔌](#api-providers-)
      - [Model Labs (Direct)](#model-labs-direct)
      - [Unified APIs \& Aggregators](#unified-apis--aggregators)
      - [Inference Clouds](#inference-clouds)
      - [GPU Clouds](#gpu-clouds)
  - [Automation 🤖](#automation-)
    - [Browser Automation 🌐](#browser-automation-)
      - [Standalone AI Browsers](#standalone-ai-browsers)
      - [Browser Extensions](#browser-extensions)
      - [Developer Libraries](#developer-libraries)
      - [Cloud Automation](#cloud-automation)
    - [Agent Platforms 🧩](#agent-platforms-)
    - [Desktop Automation 🖥️](#desktop-automation-️)
      - [AI Agents (Computer Use)](#ai-agents-computer-use)
      - [RPA \& Visual Frameworks](#rpa--visual-frameworks)
      - [Scripting Libraries](#scripting-libraries)
  - [Guides 📚](#guides-)
    - [Getting Started 🚀](#getting-started-)
      - [Understanding LLMs](#understanding-llms)
      - [Accessing AI Models](#accessing-ai-models)
      - [Model Recommendations by Task](#model-recommendations-by-task)
    - [Model Selection Guide 🎯](#model-selection-guide-)
      - [Quick Decision Tree](#quick-decision-tree)
      - [By Budget](#by-budget)
    - [Self-Hosting Guide 🖥️](#self-hosting-guide-️)
      - [Benefits](#benefits)
      - [Quick Start with Ollama](#quick-start-with-ollama)
      - [Local GPU Quick Guide (NVIDIA RTX 5090 / Laptop 64 GB RAM)](#local-gpu-quick-guide-nvidia-rtx-5090--laptop-64-gb-ram)
      - [Deployment Options](#deployment-options-1)
    - [Cost Analysis 💰](#cost-analysis-)
      - [Pricing Tiers](#pricing-tiers)
      - [Subscription Pricing (Monthly, USD)](#subscription-pricing-monthly-usd)
      - [Model Pricing Comparison](#model-pricing-comparison)
      - [Self-Hosting vs API (Monthly)](#self-hosting-vs-api-monthly)
  - [Reference 📖](#reference-)
    - [Glossary 📖](#glossary-)
      - [A-E](#a-e)
      - [F-L](#f-l)
      - [M-R](#m-r)
      - [S-Z](#s-z)
    - [Comparison Tables 📊](#comparison-tables-)
      - [Sort by Latest Update (Default)](#sort-by-latest-update-default)
      - [Release Windows (Month-level)](#release-windows-month-level)
      - [Sort by Price (Cheapest)](#sort-by-price-cheapest)
      - [Sort by Performance (Coding)](#sort-by-performance-coding)
      - [Sort by Context Window](#sort-by-context-window)
    - [Data Sources 📚](#data-sources-)
      - [Primary Sources](#primary-sources)
      - [Benchmark Sources](#benchmark-sources)
      - [Verification Methodology](#verification-methodology)
  - [License](#license)

---

## Models 🧠

Comprehensive documentation of Large Language Models (LLMs), Small Language Models (SLMs), and specialized AI models available today.

### Frontier Models 🚀

State-of-the-art proprietary AI models with cutting-edge capabilities from leading AI labs.

| Model | Company | Context | Key Features | Pricing |
|-------|---------|---------|--------------|---------|
| **Claude Opus 4.6** | Anthropic | 1M | Agent teams, enhanced coding/reasoning | $5 / $25 |
| **Claude Sonnet 4.6** | Anthropic | 1M | Near-Opus performance, Sonnet price | $3 / $15 |
| **GPT-5.3-Codex** | OpenAI | 400K | Agentic coding, 128K output | TBD |
| **Gemini 3.1 Pro** | Google | 1M | 77.1% ARC-AGI-2, 2x reasoning boost | $2 / $12 |
| **Gemini 3 Deep Think** | Google | 1M+ | 84.6% ARC-AGI-2, science/research | Ultra subscription |
| **GLM-5** | Zhipu AI | 200K | Agentic engineering, long-horizon tasks | $1.00 / $3.20 |
| **MiniMax-M2.5** | MiniMax | 200K | Coding/refactoring, tool calling, long context | $0.30 / $1.20 |
| **Kimi K2.5** | Moonshot AI | 256K | Native multimodal, thinking & agent tasks | $0.60 / $3.00 |
| **DeepSeek-V4** | DeepSeek | 1M+ | Engram memory, coding focus | Pay-per-token |
| **Qwen3.5-Max** | Alibaba | 128K | Hybrid attention, native VLM | Pay-per-token |
| **Gemini 3 Pro** | Google | 1M+ | PhD-level reasoning, agentic tool-use | Tiered pricing |
| **Gemini 3 Flash** | Google | 10M | Pro-grade reasoning, Flash speed | $0.30 / $2.50 |
| **GPT-5** | OpenAI | 400K | Thinking & Instant variants | $1.25 / $10.00 |
| **GPT-5 mini** | OpenAI | 128K | Cheap reasoning | $0.25/1M |
| **Mistral Large 3** | Mistral AI | 128K | 675B params, MoE, Open-weight | Varies |
| **Claude Sonnet 4.5** | Anthropic | 200K | SWE-bench leader, best coding | $3 / $15 |
| **Llama 4 Scout** | Meta | 10M | Open-weight context king | Free (self-host) |
| **Llama 4 Maverick** | Meta | 128K | 400B params, multimodal | Free (self-host) |
| **Grok 4** | xAI | 128K | First-principles reasoning | $3 / $15 |
| **Grok 4 Fast** | xAI | 128K | Cost-efficient variant | $0.20 / $1.50 |

#### Top Models by Category

| Category | #1 | #2 | #3 |
|----------|-----|-----|-----|
| **Coding** | Claude Opus 4.6 | GPT-5.3-Codex | Claude Sonnet 4.5 |
| **Reasoning** | Gemini 3 Deep Think | Qwen3-Max-Thinking | o3 |
| **Open Source** | DeepSeek-V4 | Qwen3.5-Max | Llama 4 |
| **Cost Efficiency** | DeepSeek-V3.1 | Grok 4 Fast | GLM-4.7-FlashX |
| **Context Window** | Gemini 3 Flash (10M) | Llama 4 Scout (10M) | Claude Opus 4.6 (1M) |

#### January 2026 Model Releases

| Model | Company | Release Date | Key Features | Category |
|-------|---------|--------------|--------------|----------|
| **DeepSeek R1** | DeepSeek | January 2026 | State-of-the-art reasoning, math, coding; 671B params | Reasoning |
| **NVIDIA Alpamayo** | NVIDIA | January 5, 2026 | Open AI models for autonomous vehicles; human-like reasoning for self-driving cars | Specialized |
| **TranslateGemma** | Google | January 16, 2026 | Multilingual translation models for mobile, laptops, cloud; supports 55 languages | Specialized |
| **Kimi K2.5** | Moonshot AI | January 29, 2026 | Native multimodal; thinking/non-thinking; dialogue + agent tasks | Frontier |

#### February 2026 Model Releases

| Model | Company | Release Date | Key Features | Category |
|-------|---------|--------------|--------------|----------|
| **Gemini 3.1 Pro** | Google | February 19, 2026 | 77.1% ARC-AGI-2, 2x reasoning boost, 1M context | Frontier |
| **Claude Sonnet 4.6** | Anthropic | February 17, 2026 | Near-Opus performance at Sonnet price, 1M context | Frontier |
| **Claude Opus 4.6** | Anthropic | February 5, 2026 | Agent teams, enhanced coding/reasoning, 1M context | Frontier |
| **GPT-5.3-Codex** | OpenAI | February 5, 2026 | Most capable agentic coding model, 400K context, 128K output | Coding |
| **Gemini 3 Deep Think** | Google | February 12, 2026 | 84.6% ARC-AGI-2, science/research/engineering focus | Reasoning |
| **GLM-5** | Zhipu AI | February 12, 2026 | Agentic LLM, long-range agent tasks, 200K context | Frontier |
| **DeepSeek-V4** | DeepSeek | February 2026 | Engram memory, 1M+ context, coding focus | Open Source |
| **Qwen3.5-Max** | Alibaba | February 2026 | Hybrid attention, native VLM, multimodal | Open Source |

#### Latest Updates ⭐ (Last 30 Days)

| Model | Company | Latest Updated | Notes | Official Site |
|-------|---------|---------------|-------|:---:|
| **Gemini 3.1 Pro** | Google | 2026-02-19 00:00 UTC ⭐ | 77.1% ARC-AGI-2, 2x reasoning boost | [🔗](https://deepmind.google/models/model-cards/gemini-3-1-pro/) |
| **Claude Sonnet 4.6** | Anthropic | 2026-02-17 00:00 UTC ⭐ | Near-Opus performance at Sonnet price | [🔗](https://www.anthropic.com/claude/sonnet) |
| **Gemini 3 Deep Think** | Google | 2026-02-12 00:00 UTC ⭐ | ARC-AGI-2 result highlighted | [🔗](https://deepmind.google/technologies/gemini/) |
| **GLM-5** | Zhipu AI | 2026-02-12 00:00 UTC ⭐ | Agentic engineering, long-horizon tasks | [🔗](https://docs.z.ai/release-notes/new-released) |
| **Claude Opus 4.6** | Anthropic | 2026-02-05 00:00 UTC ⭐ | Agent teams, enhanced coding/reasoning | [🔗](https://www.anthropic.com/) |
| **GPT-5.3-Codex** | OpenAI | 2026-02-05 00:00 UTC ⭐ | Agentic coding focus | [🔗](https://openai.com/) |
| **Kimi K2.5** | Moonshot AI | 2026-02-02 00:00 UTC ⭐ | Models & pricing published | [🔗](https://platform.moonshot.ai/docs/pricing/chat) |
| **DeepSeek-V4** | DeepSeek | 2026-02-17 00:00 UTC | Release window announced | [🔗](https://www.deepseek.com/) |
| **Qwen3.5-Max** | Alibaba | 2026-02 | February 2026 release window | [🔗](https://qwenlm.github.io/) |

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

| Rank | Model | Company | Score |
|------|-------|---------|-------|
| 🥇 #1 | **Claude Opus 4.6** | Anthropic | SOTA |
| 🥈 #2 | **GPT-5.3-Codex** | OpenAI | Agentic leader |
| 🥉 #3 | **Claude Sonnet 4.5** | Anthropic | ~92% |
| #4 | **GPT-OSS-120B** | OpenAI | 91.4% AIME |
| #5 | **Kimi K2.5** | Moonshot AI | Excellent |

#### Commercial Coding Models

| Model | Developer | Pricing | Best For |
|-------|-----------|---------|----------|
| **Claude Opus 4.6** | Anthropic | $5 / $25 per 1M | Agentic coding, complex tasks |
| **GPT-5.3-Codex** | OpenAI | TBD | Agentic coding, 7+ hour autonomy |
| **GLM-5-Code** | Zhipu AI | $1.20 / $5.00 per 1M | Code generation, refactoring |
| **MiniMax-M2.5** | MiniMax | $0.30 / $1.20 per 1M | Code generation, refactoring |
| **Claude Sonnet 4.5** | Anthropic | $3 / $15 per 1M | Code review, refactoring |
| **Codestral** | Mistral AI | $0.30 / $0.90 | Real-time completion |
| **Grok Code Fast** | xAI | $0.20 / $1.50 | Most used (50% share) |

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

| Rank | Model | Score | Notes |
|------|-------|-------|-------|
| 🥇 #1 | **Gemini 3 Deep Think** | 84.6% ARC-AGI-2 | Science/research focus |
| 🥈 #2 | **Qwen3-Max-Thinking** | 100% | Perfect AIME score |
| 🥉 #3 | **GPT-5 Pro (with tools)** | 100% | With Python tools |
| #4 | **GPT-OSS-120B** | 91.4% | Open-source leader |
| #5 | **o3** | ~96.5% | OpenAI reasoning |
| #6 | **DeepSeek-R1** | 81% | Pure RL-based |

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
| **GPT-5** | OpenAI | 400K | Unified multimodal, audio |
| **Gemini 3 Pro** | Google | 1M+ | Native multimodal, video |
| **Claude Sonnet 4.5** | Anthropic | 200K | Document understanding |
| **Llama 4 Maverick** | Meta | 128K | Open multimodal |

#### Vision Capabilities

| Model | MMMU | MathVista | DocVQA |
|-------|------|-----------|--------|
| **Gemini 3 Pro** | SOTA | SOTA | SOTA |
| **GPT-5** | Excellent | Excellent | Excellent |
| **Claude Sonnet 4.5** | Strong | Strong | Excellent |
| **Llama 4 Maverick** | Good | Good | Good |

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

## Development Tools 🛠️

AI-powered tools for software development, from IDEs and CLI tools to API providers and IDE extensions.

### IDEs 💻

Integrated Development Environments with built-in AI capabilities.

#### Agentic IDEs

| IDE | Platform | Pricing | Key Features | GitHub |
|-----|----------|---------|--------------|--------|
| **Firebase Studio** | Web | Free (3 workspaces, up to 30 with Google Developer Program) | Cloud-based, Gemini, MCP | ❌ |
| **[Lingma IDE (通义灵码)](https://lingma.aliyun.com/download)** | Windows, macOS | Free (download) | Built-in agent, MCP tool use, terminal command execution | ❌ |
| **Tonkotsu** | Windows, macOS | Free (during early access) | Team of agents, workflow | ❌ |
| **OpenCode** | Windows, macOS, Linux | Free (OSS) | Terminal, desktop, IDE extension, multi-provider | [🔗](https://github.com/anomalyco/opencode) |

#### Native AI Editors

| Editor | Platform | Pricing | Key Features | GitHub |
|--------|----------|---------|--------------|--------|
| **Zed** | macOS, Windows, Linux | Free (OSS) + Copilot $10/mo | Fast, collaboration, Gemini/Claude, Zeta AI | [🔗](https://github.com/zed-industries/zed) |
| **Dyad** | Windows, macOS, Linux | Free (OSS) | Local generation, BYO keys | [🔗](https://github.com/dyad-sh/dyad) |
| **Memex** | macOS, Windows | Freemium (Free + $10/mo) | Agentic, browser↔desktop | ❌ |

#### IDE Updates (January 2026)

| IDE | Version | Release Date | Key Features |
|-----|---------|--------------|--------------|
| **Visual Studio** | 17.14.12+, 18.1.0+ | January 6, 2026 | Gemini 3 Flash integration, faster performance, zero-migration upgrades, real-time profiler agent |
| **IntelliJ IDEA** | 2025.3.2 | January 2026 | Java 24 support, Kotlin K2 mode by default, performance/memory improvements |
| **JetBrains IDEs** | Various | January 2026 | AI Assistant with deep IDE integration, Claude Agent capabilities |

#### IDE Updates (February 2026)

| IDE | Version | Release Date | Key Features |
|-----|---------|--------------|--------------|
| **Zed** | 0.225.0 | February 18, 2026 | Agent thread history, edit prediction providers (Zeta, Mercury, Copilot), mermaid diagrams |
| **Cursor** | 0.46+ | February 12, 2026 | Long-running autonomous agents, complex task completion |
| **Windsurf** | 1.9552+ | February 12, 2026 | Plan Mode auto-switch to Code Mode, .agents/skills directory support |
| **Windsurf** | 1.9544+ | February 3, 2026 | Claude Opus 4.6 fast mode, JetBrains plugin, Cascade improvements |
| **Zed** | 0.224.0 | February 11, 2026 | AI agent thread history, tool call permissions, edit prediction providers |

#### VS Code Forks

| IDE | Platform | Pricing | Autonomous | MCP | GitHub |
|----------|---------|---------|------------|-----|--------|
| **Cursor** | Windows, macOS, Linux | Freemium | ✅ | ❌ | ❌ |
| **Windsurf** | Windows, macOS, Linux | Freemium | ✅ | ✅ | ❌ |
| **Trae** | macOS, Windows | Free | ❌ | ❌ | ❌ |
| **PearAI** | Windows, macOS, Linux | Free (OSS) | ✅ | ❌ | ❌ |
| **Void** | Windows, macOS, Linux | Free (OSS) | ✅ | ✅ | ❌ |
| **Google Antigravity** | Windows, macOS, Linux | Free | ✅ | ❌ | ❌ |
| **Kiro** | Windows, macOS, Linux | Free (Preview) | ✅ | ✅ | ❌ |

#### Web-Based IDEs

| Platform | Platform | Pricing | Self-Hostable | Best For | GitHub |
|----------|----------|---------|---------------|----------|--------|
| **Replit 3** | Web | Free Starter, Core $20-25/mo, Pro $100/mo | ❌ | Learning/Prototyping | ❌ |
| **Bolt.new** | Web | Free (limited), $20-25/mo Pro, $200/mo Teams | ❌ | Quick apps | ❌ |
| **Bolt.diy** | Self-hosted | Free (MIT), bring your own API | ✅ | Self-hosted | [🔗](https://github.com/stackblitz-labs/bolt.diy) |
| **Lovable** | Web | Free (5 credits/day), Pro $25/mo, Business $50/mo | ❌ | UI/Full-stack | ❌ |
| **v0** | Web | Free ($5 credits/mo), Premium $20/mo, Teams $30/user | ❌ | React components |
| **Gitpod** | Web | Free + Paid | ❌ | Cloud dev environments |
| **Rork** | Web | Free & Paid (credits) | ❌ | Mobile apps (iOS/Android) |

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

#### IDE Extension Updates (January 2026)

| Add-on | Platform | Release Date | Key Features |
|--------|----------|--------------|--------------|
| **Gemini 3 Flash Integration** | VS Code, JetBrains, Xcode, Eclipse | January 6, 2026 | Access to Google's latest Gemini 3 Flash model directly from IDE; fast response times |
| **JetBrains AI Assistant** | All JetBrains IDEs | January 2026 | Enhanced AI capabilities, Claude Agent integration, better context understanding |

#### VS Code Specific

| Add-on | Pricing | Autonomous | MCP | Best For | GitHub |
|--------|---------|------------|-----|----------|--------|
| **Codex** | Free (with ChatGPT Plus $20/mo or Pro $200/mo) | ✅ | ✅ | OpenAI's official coding agent | [🔗](https://github.com/openai/codex) |
| **Cline** | Free | ✅ | ✅ | Full agent | [🔗](https://github.com/cline/cline) |
| **GitHub Copilot (Agent Mode)** | $0 / $10 / $39/mo | ⚠️ | ❌ | Guided agent workflows | ❌ |
| **RooCode** | Free/Pro | ⚠️ | ❌ | Complex tasks | ❌ |
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
| **OpenAI** | GPT-5, o3, Codex | Pay-per-token |
| **Anthropic** | Claude 4.6 | Pay-per-token |
| **Google AI Studio** | Gemini 3 | Free / Pay |
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
| **BrowserOS** | Free | ✅ | ✅ | Privacy-focused | ❌ |
| **Brave Leo** | Freemium (Free + Premium) | ❌ | ⚠️ (Experimental) | Privacy-focused AI | ❌ |
| **Fellou** | Freemium (Free for 4 tasks, $20/mo Plus) | ❌ | ❌ | True agentic browser | ❌ |
| **Perplexity Comet** | Free (with Pro $20/mo) or $5/mo | ❌ | ❌ | Research | ❌ |
| **Dia** | Freemium (Free limited, $20/mo Pro) | ❌ | ❌ | Arc replacement | ❌ |
| **Opera Neon** | $19.90/mo | ❌ | ❌ | Agentic browsing | ❌ |
| **Opera One (Aria)** | Free | ❌ | ❌ | Built-in AI assistant | ❌ |
| **Edge Copilot** | Free (Copilot Pro $20/mo) | ❌ | ❌ | Enterprise AI browser | ❌ |

#### Browser Extensions

| Extension | Pricing | Free | Multi-Agent | Best For | GitHub |
|-----------|---------|------|-------------|----------|--------|
| **Harpa AI** | Free | ✅ | ❌ | Automation recipes | ❌ |
| **MultiOn** | Free/Paid | ⚠️ | ✅ | Complex tasks | ❌ |
| **NanoBrowser** | Free | ✅ | ✅ | Local control | ❌ |

#### Developer Libraries

| Library | Language | Best For | GitHub |
|---------|----------|----------|--------|
| **Browser-use** | Python | Agentic automation | [🔗](https://github.com/browser-use/browser-use) |
| **Stagehand** | TypeScript | Web apps | [🔗](https://github.com/browserbase/stagehand) |
| **LaVague** | Python | NL to code | [🔗](https://github.com/lavague-ai/LaVague) |
| **Skyvern** | Python | CV-based automation | [🔗](https://github.com/Skyvern-AI/skyvern) |

#### Cloud Automation

| Service | Platform | Pricing | Best For | GitHub |
|---------|----------|---------|----------|--------|
| **Skyvern Cloud** | Cloud API | Paid | Resilient automation | [🔗](https://github.com/Skyvern-AI/skyvern) |
| **Browserbase** | Cloud API | Paid | Stealth mode, session recording | ❌ |

### Agent Platforms 🧩

Platforms and runtimes for running or connecting AI agents.

| Project | Type | Self-Hostable | Best For | Official |
|---------|------|:-------------:|----------|:-------:|
| **OpenClaw** | Personal AI assistant | ✅ | Always-on assistant across chat channels | [🔗](https://github.com/openclaw/openclaw) |
| **Moltbook** | Agent social network | ❌ | Discovering and pairing with AI agents | [🔗](https://www.moltbook.com/) |

### Desktop Automation 🖥️

AI agents and tools for automating desktop tasks and OS-level interactions.

#### AI Agents (Computer Use)

| Agent | Platform | Vision-Based | Cross-Platform | Best For | GitHub |
|-------|----------|--------------|----------------|----------|--------|
| **Agent S** | Cross-platform | ✅ | ✅ | Research/SOTA | [🔗](https://github.com/simular-ai/Agent-S) |
| **Bytebot** | Linux (Docker) | ✅ | ✅ | Self-hosted | ❌ |
| **UFO** | Windows | ✅ | ❌ | Windows automation | [🔗](https://github.com/microsoft/UFO) |
| **Open-Interface** | Cross-platform | ✅ | ✅ | General use | [🔗](https://github.com/AmberSahdev/Open-Interface) |
| **Anthropic Computer Use** | API | ✅ | ✅ | Beta capability | ❌ |

#### RPA & Visual Frameworks

| Tool | Platform | Best For |
|------|----------|----------|
| **Ui.Vision RPA** | Windows, macOS, Linux | Visual automation |
| **OmniParser V2** | Cross-platform | Screen parsing |

#### Scripting Libraries

| Tool | Platform | Key Features | GitHub |
|------|----------|--------------|--------|
| **PyAutoGUI** | Cross-platform | Simple API, fail-safe | ❌ |
| **Nut.js** | Cross-platform | Visual search, image matching | ❌ |
| **OpenAdapt** | Windows, macOS | Learning from demonstration | [🔗](https://github.com/OpenAdaptAI/OpenAdapt) |

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
| **Chat** | Llama 4 (self-hosted) | GPT-5, Claude |
| **Coding** | DeepSeek-Coder-V2 | Claude Opus 4.6 |
| **Reasoning** | DeepSeek-R1 | Gemini 3 Deep Think, o3 |
| **Long docs** | Llama 4 Scout | Gemini 3 Flash |
| **Vision** | Llama 4 Maverick | GPT-5, Gemini 3 |

### Model Selection Guide 🎯

A comprehensive guide to choosing the right AI model for your specific needs.

#### Quick Decision Tree

| Need | 🆓 Free / Self-Host | 💎 Best Quality | ⚡ Fast / Autonomous |
|------|---------------------|----------------|----------------------|
| 💻 Coding | DeepSeek-Coder-V2 | Claude Opus 4.6 | GPT-5.3-Codex |
| 🧠 Reasoning / Math | DeepSeek-R1 | Gemini 3 Deep Think | o3 |
| 💬 General Chat | Llama 4 (self-hosted) | GPT-5, Claude Opus 4.6 | Gemini 3 Flash |
| 🎨 Vision | Llama 4 Maverick | GPT-5, Gemini 3 Pro | Gemini 3 Flash |
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

#### Local GPU Quick Guide (NVIDIA RTX 5090 / Laptop 64 GB RAM)

**Recommended apps (local-first):**
- [Ollama](https://ollama.com) - Simple local runtime with a local HTTP API
- [LM Studio](https://lmstudio.ai) - Desktop UI for downloading and running models locally
- [llama.cpp](https://github.com/ggerganov/llama.cpp) - Fast local inference (CPU/GPU), great for quantized models
- [Open WebUI](https://github.com/open-webui/open-webui) - Optional local web UI (pairs well with local runtimes)

**If you want “server-style” hosting (advanced):**
- [vLLM](https://github.com/vllm-project/vllm) - High-throughput serving for NVIDIA GPUs
- [SGLang](https://github.com/sgl-project/sglang) - Structured generation and serving workflows

**Practical setup (works for both desktop and laptop):**
1. Install the latest NVIDIA drivers (enable GPU acceleration in your chosen app)
2. Start with smaller quantized models (Q4 is a common “best default”)
3. Keep context windows realistic for local hardware (lower context = faster, less memory)
4. Watch VRAM first, then system RAM; reduce model size or quantization if either saturates
5. Prefer running locally on `localhost` and only expose to LAN if you understand firewall rules

**What fits on your hardware (quick rules):**
| Hardware | Good starting point | Notes |
|----------|---------------------|------|
| **RTX 5090 desktop GPU** | 14B–70B quantized | Best experience for coding agents and longer contexts |
| **Laptop, 64 GB RAM** | 7B–14B quantized | Great for offline chat/coding; keep context moderate |

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
| 💵 **Budget** | $0.07 - $0.50/1M | GLM-4.7-FlashX, GLM-4-32B-0414-128K, Yi-Lightning, DeepSeek-V3.1, MiniMax-M2.5 |
| 💰 **Mid-range** | $0.60 - $15.00/1M | Kimi K2.5, Sonar, GLM-5, GPT-5, Claude Sonnet |
| 💎 **Premium** | $15.00 - $600.00/1M | Claude Opus, o1-Pro |

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

| Model | Input | Output | Best For |
|-------|-------|--------|----------|
| **GLM-4.7-FlashX** | $0.07 | $0.40 | Fast budget tasks |
| **GLM-4-32B-0414-128K** | $0.10 | $0.10 | Budget chat/coding |
| **DeepSeek-V3.1** | $0.27 | $0.41 | Everything |
| **Gemini 3 Flash** | $0.30 | $2.50 | Long context |
| **MiniMax-M2.5** | $0.30 | $1.20 | Coding, long context |
| **GLM-4.6** | $0.60 | $2.20 | General purpose |
| **Kimi K2.5** | $0.60 | $3.00 | Multimodal + agent tasks |
| **GLM-5** | $1.00 | $3.20 | Agentic engineering |
| **Perplexity Sonar** | $1.00 | $1.00 | Web-grounded chat (request fees apply) |
| **GPT-5** | $1.25 | $10.00 | General purpose |
| **Claude Sonnet 4.5** | $3.00 | $15.00 | Best coding |
| **Perplexity Sonar Reasoning Pro** | $2.00 | $8.00 | Reasoning + search (request fees apply) |
| **Perplexity Sonar Pro** | $3.00 | $15.00 | Higher quality + search (request fees apply) |
| **Claude Opus 4.6** | $5.00 | $25.00 | Agentic coding |

**Note:** Some search-grounded models charge both token rates and per-request search/context fees. See Perplexity’s official pricing for details: https://docs.perplexity.ai/docs/getting-started/pricing

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
| 🔬 DeepSeek | DeepSeek | V4 | 2026-02-17 00:00 UTC | 2026-02-17 00:00 UTC | ✅ | N/A | Pay-per-token | ✅ | [🔗](https://www.deepseek.com/) |
| 🌐 Google DeepMind | Gemini 3 | Deep Think | 2026-02-12 00:00 UTC | 2026-02-12 00:00 UTC ⭐ | ✅ | 84.6% ARC-AGI-2 | Ultra subscription | ❌ | [🔗](https://deepmind.google/technologies/gemini/) |
| 🇨🇳 Zhipu AI | GLM | 5 | 2026-02-12 00:00 UTC | 2026-02-12 00:00 UTC ⭐ | ✅ | SWE-bench 77.8 | $1.00 / $3.20 | ✅ | [🔗](https://docs.z.ai/release-notes/new-released) |
| 🤖 Anthropic | Claude | Opus 4.6 | 2026-02-05 00:00 UTC | 2026-02-05 00:00 UTC ⭐ | ✅ | SWE-bench SOTA | $5 / $25 | ❌ | [🔗](https://www.anthropic.com/) |
| 🤖 OpenAI | GPT-5 | 5.3-Codex | 2026-02-05 00:00 UTC | 2026-02-05 00:00 UTC ⭐ | ✅ | Agentic leader | TBD | ❌ | [🔗](https://openai.com/) |
| � Moonshot AI | Kimi | K2.5 | 2026-01-29 00:00 UTC | 2026-02-02 00:00 UTC ⭐ | ✅ | N/A | $0.60 / $3.00 | ❌ | [🔗](https://platform.moonshot.ai/docs/pricing/chat) |

#### Release Windows (Month-level)

| � Company | 🤖 Model | 📅 Release Window | Notes | 🔗 Official Site |
|:---:|---|---|---|:---:|
| 🧠 MiniMax | MiniMax M2.5 | 2026-02 | $0.30 / $1.20 | [🔗](https://platform.minimax.io/docs/guides/models-intro) |
| 🇨🇳 Alibaba/Qwen | Qwen 3.5-Max | 2026-02 | Open-source release window | [🔗](https://qwenlm.github.io/) |
| 🌐 Google DeepMind | Gemini 3 Pro | 2026-01 | Tiered pricing | [🔗](https://deepmind.google/models/gemini/) |
| 🤖 OpenAI | GPT-5 5.3 | 2026-01 | $1.25 / $10.00 | [🔗](https://openai.com/) |
| 💻 Mistral AI | Mistral Large 3 | 2026-01 | Open-weight | [🔗](https://mistral.ai/) |

#### Sort by Price (Cheapest)

| Rank | Model | Input | Output | License |
|------|-------|-------|--------|---------|
| 1 | **Self-hosted** | $0 | $0 | Various |
| 2 | **GLM-4.7-Flash** | $0 | $0 | Free |
| 3 | **GLM-4.7-FlashX** | $0.07 | $0.40 | API |
| 4 | **GLM-4-32B-0414-128K** | $0.10 | $0.10 | API |
| 5 | **Yi-Lightning** | $0.14 | $0.42 | Apache 2.0 |
| 6 | **DeepSeek-V3.1** | $0.27 | $0.41 | MIT |
| 7 | **Gemini 3 Flash** | $0.30 | $2.50 | Proprietary |
| 8 | **MiniMax-M2.5** | $0.30 | $1.20 | Proprietary |

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
| **OpenAI** | ChatGPT subscriptions (Go/Plus/Pro) | [openai.com](https://openai.com/index/introducing-chatgpt-go/) |
| **OpenAI** | ChatGPT Business pricing | [help.openai.com](https://help.openai.com/en/articles/8542115-chatgpt-business-faq) |
| **Anthropic** | Claude Documentation | [anthropic.com](https://www.anthropic.com) |
| **Anthropic** | Claude Pro pricing | [anthropic.com](https://www.anthropic.com/news/claude-pro) |
| **Anthropic** | Max plan pricing | [anthropic.com](https://www.anthropic.com/max) |
| **Google** | Gemini Documentation | [deepmind.google](https://deepmind.google/models/gemini/) |
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
| **Perplexity** | Developer Documentation | [docs.perplexity.ai](https://docs.perplexity.ai/docs/getting-started/pricing) |
| **ByteDance (Volcengine)** | Developer Documentation | [volcengine.com](https://www.volcengine.com/docs/82379/1263482) |
| **Tencent (Hunyuan)** | Cloud Documentation | [cloud.tencent.com](https://cloud.tencent.com/document/product/1729/97730) |
| **Baidu (ERNIE)** | AI Studio Documentation | [ai.baidu.com](https://ai.baidu.com/ai-doc/AISTUDIO/Mmhslv9lf) |
| **DeepSeek** | Official Website | [deepseek.com](https://www.deepseek.com) |
| **Meta** | Llama Documentation | [llama.meta.com](https://llama.meta.com) |

#### Benchmark Sources

| Benchmark | Source | Description |
|-----------|--------|-------------|
| **HumanEval** | OpenAI | 164 Python programming problems |
| **SWE-bench** | Princeton | Real GitHub issue resolution |
| **MMLU** | UC Berkeley | 57 subjects, multi-task |
| **AIME** | MAA | American Invitational Math Exam |
| **ARC-AGI** | ARC Prize | Abstract reasoning challenge |

#### Verification Methodology

1. **Primary Source Review** - Check official documentation
2. **Cross-Validation** - Compare multiple sources
3. **Timestamp Verification** - All data includes verification date
4. **Update Tracking** - Monitor official channels

---

## License

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) License - see the [LICENSE](LICENSE) file for details.

---

**Last Updated:** 2026-02-24 00:36 UTC  
**Maintained by:** ReadyPixels LLC & AI Models Matrix Contributors

---

Made with ❤️ by ReadyPixels LLC

[![Star on GitHub](https://img.shields.io/github/stars/ReadyPixels/AI_Models_Matrix?style=social)](https://github.com/ReadyPixels/AI_Models_Matrix)
