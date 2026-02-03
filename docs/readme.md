# Awesome AI Models Matrix 🧠

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--02--03%2002%3A36%20UTC-green.svg)](https://github.com/your-org/ai-models-matrix)

> Comprehensive curated list of AI models, tools, and resources for developers and researchers. From frontier proprietary models to self-hostable open-source alternatives, from AI-powered IDEs to automation frameworks.

---

## Table of Contents

- [Models](#models-)
  - [Frontier Models](#frontier-models-)
  - [Open-Source Models](#open-source-models-)
  - [Coding Models](#coding-models-)
  - [Reasoning Models](#reasoning-models-)
  - [Multimodal Models](#multimodal-models-)
  - [Hardware Requirements](#hardware-requirements-)
- [Development Tools](#development-tools-)
  - [IDEs](#ides-)
  - [CLI Tools](#cli-tools-)
  - [IDE Add-ons](#ide-add-ons-)
  - [API Providers](#api-providers-)
- [Automation](#automation-)
  - [Browser Automation](#browser-automation-)
  - [Desktop Automation](#desktop-automation-)
- [Guides](#guides-)
  - [Getting Started](#getting-started-)
  - [Model Selection Guide](#model-selection-guide-)
  - [Self-Hosting Guide](#self-hosting-guide-)
  - [Cost Analysis](#cost-analysis-)
- [Reference](#reference-)
  - [Glossary](#glossary-)
  - [Comparison Tables](#comparison-tables-)
  - [Data Sources](#data-sources-)
- [Contributing](#contributing)
- [License](#license)

---

## Models 🧠

Comprehensive documentation of Large Language Models (LLMs), Small Language Models (SLMs), and specialized AI models available today.

### Frontier Models 🚀

State-of-the-art proprietary AI models with cutting-edge capabilities from leading AI labs.

| Model | Company | Context | Key Features | Pricing |
|-------|---------|---------|--------------|---------|
| **DeepSeek-V4** | DeepSeek | 128K | Reasoning Core, DSA, Interleaved Thinking | Pay-per-token |
| **Qwen3-Max-Thinking** | Alibaba | 128K | 100% AIME25, 100% HMMT | $1.20 / $6.00 |
| **Gemini 3 Pro** | Google | 1M+ | PhD-level reasoning, agentic tool-use | Tiered pricing |
| **Gemini 3 Flash** | Google | 10M | Pro-grade reasoning, Flash speed | $0.30 / $2.50 |
| **GPT-5.2** | OpenAI | 400K | Thinking & Instant variants | $1.75/1M |
| **GPT-5 mini** | OpenAI | 128K | Cheap reasoning | $0.25/1M |
| **Mistral Large 3** | Mistral AI | 128K | 675B params, MoE, Open-weight | Varies |
| **Claude Opus 4.5** | Anthropic | 200K | Leading reasoning accuracy | $15 / $75 |
| **Claude Sonnet 4.5** | Anthropic | 200K | SWE-bench leader, best coding | $3 / $15 |
| **Llama 4 Scout** | Meta | 10M | Open-weight context king | Free (self-host) |
| **Llama 4 Maverick** | Meta | 128K | 400B params, multimodal | Free (self-host) |
| **Grok 4** | xAI | 128K | First-principles reasoning | $3 / $15 |
| **Grok 4 Fast** | xAI | 128K | Cost-efficient variant | $0.20 / $1.50 |

#### Top Models by Category

| Category | #1 | #2 | #3 |
|----------|-----|-----|-----|
| **Coding** | Claude Sonnet 4.5 | GPT-5 Codex | Grok Code Fast |
| **Reasoning** | Qwen3-Max-Thinking | o3 | Gemini 3 Pro |
| **Open Source** | DeepSeek-V4 | Qwen3-Max | Llama 4 |
| **Cost Efficiency** | DeepSeek-V3.1 | Grok 4 Fast | GLM-4.6 |
| **Context Window** | Gemini 3 Flash (10M) | Llama 4 Scout (10M) | Kimi K2-0905 (256K) |

#### January 2026 Model Releases

| Model | Company | Release Date | Key Features | Category |
|-------|---------|--------------|--------------|----------|
| **DeepSeek R1** | DeepSeek | January 2026 | State-of-the-art reasoning, math, coding; 671B params | Reasoning |
| **NVIDIA Alpamayo** | NVIDIA | January 5, 2026 | Open AI models for autonomous vehicles; human-like reasoning for self-driving cars | Specialized |
| **TranslateGemma** | Google | January 16, 2026 | Multilingual translation models for mobile, laptops, cloud; supports 55 languages | Specialized |

### Open-Source Models 🆓

Self-hostable models with permissive licenses for privacy, cost control, and customization.

| Model | Company | Params | Context | License |
|-------|---------|--------|---------|---------|
| **DeepSeek-V4** | DeepSeek | 671B | 128K | MIT |
| **Qwen3-Max-Thinking** | Alibaba | 1T+ | 128K | Apache 2.0 |
| **Mistral Large 3** | Mistral AI | 675B (MoE) | 128K | Apache 2.0 |
| **Llama 4 Scout** | Meta | 109B | 10M | Community |
| **Llama 4 Maverick** | Meta | 400B | 128K | Community |
| **GPT-OSS-120B** | OpenAI | 117B | 128K | Apache 2.0 |
| **GPT-OSS-20B** | OpenAI | 21B | 128K | Apache 2.0 |
| **Qwen3-Coder** | Alibaba | 480B | 128K | Apache 2.0 |
| **GLM-4.7** | Zhipu AI | 400B+ MoE | 128K | Open Weight |
| **Kimi K2-0905** | Moonshot | 1T (MoE) | 256K | Modified MIT |
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
| 🥇 #1 | **Claude Sonnet 4.5** | Anthropic | SOTA |
| 🥈 #2 | **GPT-5 Codex** | OpenAI | ~55.6% |
| 🥉 #3 | **GPT-OSS-120B** | OpenAI | 91.4% AIME |
| #4 | **Kimi K2-0905** | Moonshot | Excellent |
| #5 | **Qwen3-Coder** | Alibaba | 480B params |

#### Commercial Coding Models

| Model | Developer | Pricing | Best For |
|-------|-----------|---------|----------|
| **Claude Sonnet 4.5** | Anthropic | $3 / $15 per 1M | Code review, refactoring |
| **GPT-5 Codex** | OpenAI | API pricing | 7+ hour autonomy |
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
| 🥇 #1 | **Qwen3-Max-Thinking** | 100% | Perfect score |
| 🥈 #2 | **GPT-5 Pro (with tools)** | 100% | With Python tools |
| 🥉 #3 | **Gemini 3 Pro** | ~98% | Frontier agentic |
| #4 | **GPT-OSS-120B** | 91.4% | Open-source leader |
| #5 | **o3** | ~96.5% | OpenAI reasoning |
| #6 | **DeepSeek-R1** | 81% | Pure RL-based |

#### Reasoning Model Details

| Model | Type | Context | Pricing |
|-------|------|---------|---------|
| **Qwen3-Max-Thinking** | Reasoning/Coding | 128K | $1.20 / $6.00 |
| **o3 / o1-Pro** | Reasoning | 128K | $2-150 / $8-600 |
| **Gemini 3 Pro** | General/Multimodal | 1M+ | $2 / $12 |
| **DeepSeek-R1** | Reasoning | 128K | $0.50 / $2.15 |
| **Claude 3.7 Sonnet** | Hybrid | 200K | $3 / $15 |

#### Use Cases

- **Mathematical Problem Solving**: Qwen3-Max-Thinking, GPT-5 Pro, Gemini 3 Pro
- **Scientific Analysis**: Claude Opus 4.5, GPT-5.2, Gemini 3 Pro
- **Strategic Planning**: o3/o1-Pro, Claude Sonnet 4.5, DeepSeek-R1
- **Code Debugging**: Claude Sonnet 4.5, GPT-5 Codex, DeepSeek-V3.2

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
- Llama 4 Maverick, GLM-4.7, DeepSeek-V4, Qwen3-Max
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

| IDE | Platform | Pricing | Key Features |
|-----|----------|---------|--------------|
| **Firebase Studio** | Web | Free | Cloud-based, Gemini, MCP |
| **Tonkotsu** | Web | Freemium | Team of agents, workflow |

#### Native AI Editors

| Editor | Platform | Pricing | Key Features |
|--------|----------|---------|--------------|
| **Zed** | macOS, Windows, Linux | Free + Copilot | Fast, collaboration, Gemini/Claude |
| **Dyad** | Windows, macOS, Linux | Free (OSS) | Local generation, BYO keys |
| **Memex** | macOS, Windows | Freemium | Agentic, browser↔desktop |
| **Kiro** | Desktop | TBD | Subagents, Claude Opus |

#### IDE Updates (January 2026)

| IDE | Version | Release Date | Key Features |
|-----|---------|--------------|--------------|
| **Visual Studio** | 17.14.12+, 18.1.0+ | January 6, 2026 | Gemini 3 Flash integration, faster performance, zero-migration upgrades, real-time profiler agent |
| **IntelliJ IDEA** | 2025.3.2 | January 2026 | Java 24 support, Kotlin K2 mode by default, performance/memory improvements |
| **JetBrains IDEs** | Various | January 2026 | AI Assistant with deep IDE integration, Claude Agent capabilities |

#### VS Code Forks

| IDE | Platform | Pricing | Autonomous | MCP |
|-----|----------|---------|------------|-----|
| **Cursor** | Windows, macOS, Linux | Freemium | ✅ | ❌ |
| **Windsurf** | Windows, macOS, Linux | Freemium | ✅ | ✅ |
| **Trae** | macOS, Windows | Free | ❌ | ❌ |
| **PearAI** | Windows, macOS, Linux | Free (OSS) | ✅ | ❌ |
| **Void** | Windows, macOS, Linux | Free (OSS) | ✅ | ✅ |
| **Google Antigravity** | Windows, macOS, Linux | Free | ✅ | ❌ |

#### Web-Based IDEs

| Platform | Platform | Self-Hostable | Best For |
|----------|----------|---------------|----------|
| **Replit 3** | Web | ❌ | Learning/Prototyping |
| **Bolt.new** | Web | ❌ | Quick apps |
| **Bolt.diy** | Self-hosted | ✅ | Self-hosted |
| **Lovable** | Web | ❌ | UI/Full-stack |
| **v0** | Web | ❌ | React components |
| **Gitpod** | Web | ❌ | Cloud dev environments |

### CLI Tools 🖥️

Command-line AI tools for autonomous coding and terminal enhancement.

#### Autonomous Coding Agents

| Tool | Platform | Pricing | Key Features |
|------|----------|---------|--------------|
| **Aider** | Windows, macOS, Linux | Free | Gold standard, Architect mode |
| **Claude Code 2.1** | macOS, Linux, Windows | Free + API | Autonomous, async subagents; Shift+enter for newlines, hooks for agents/skills, wildcard tool permissions |
| **Codex CLI** | Windows, macOS, Linux | Included | Sandbox, approval modes |
| **Goose** | Windows, macOS, Linux | Free (Apache-2.0) | MCP, extensible |
| **GPT-Pilot** | Windows, macOS, Linux | Free | Full dev team simulation |
| **OpenHands** | Windows, macOS, Linux | Free | Cloud agents, MCP |
| **Mentat** | Windows, macOS, Linux | Free | Multi-file coordination |

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

| Add-on | Platform | Pricing | Context | Best For |
|--------|----------|---------|---------|----------|
| **GitHub Copilot** | VS Code, JetBrains, Vim | $10-19/mo | Large | General coding |
| **Supermaven** | VS Code, JetBrains, Neovim | $10/mo | 1M | Large codebases |
| **Codeium** | VS Code, JetBrains, Vim | Free | Medium | Free alternative |
| **Continue** | VS Code, JetBrains | Free (OSS) | Custom | Self-hosted |
| **Cody** | VS Code, JetBrains, Web | Free/Enterprise | Enterprise | Code search |
| **Tabnine** | VS Code, JetBrains, VS, Eclipse | Free/Pro | Local | Privacy |

#### IDE Extension Updates (January 2026)

| Add-on | Platform | Release Date | Key Features |
|--------|----------|--------------|--------------|
| **Gemini 3 Flash Integration** | VS Code, JetBrains, Xcode, Eclipse | January 6, 2026 | Access to Google's latest Gemini 3 Flash model directly from IDE; fast response times |
| **JetBrains AI Assistant** | All JetBrains IDEs | January 2026 | Enhanced AI capabilities, Claude Agent integration, better context understanding |

#### VS Code Specific

| Add-on | Pricing | Autonomous | MCP | Best For |
|--------|---------|------------|-----|----------|
| **Cline** | Free | ✅ | ✅ | Full agent |
| **RooCode** | Free/Pro | ⚠️ | ❌ | Complex tasks |
| **Keploy** | OSS/Enterprise | ❌ | ❌ | Testing |

#### JetBrains Specific

| Add-on | Pricing | Claude Agent | Best For |
|--------|---------|--------------|----------|
| **JetBrains AI Assistant** | $10-20/mo | ✅ | Deep IDE integration |
| **JetBrains Claude Agent** | Included in subscription | ✅ | Native agent |

### API Providers 🔌

Services for accessing AI models via API.

#### Model Labs (Direct)

| Provider | Models | Pricing |
|----------|--------|---------|
| **OpenAI** | GPT-5, o3, Codex | Pay-per-token |
| **Anthropic** | Claude 4.5 | Pay-per-token |
| **Google AI Studio** | Gemini 3 | Free / Pay |
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

| Browser | Open Source | Local AI | Best For |
|---------|-------------|----------|----------|
| **BrowserOS** | ✅ | ✅ | Privacy-focused |
| **Fellou** | ❌ | ❌ | True agentic browser |
| **Perplexity Comet** | ❌ | ❌ | Research |
| **Dia** | ❌ | ❌ | Arc replacement |

#### Browser Extensions

| Extension | Free | Multi-Agent | Best For |
|-----------|------|-------------|----------|
| **Harpa AI** | ✅ | ❌ | Automation recipes |
| **MultiOn** | ⚠️ | ✅ | Complex tasks |
| **NanoBrowser** | ✅ | ✅ | Local control |

#### Developer Libraries

| Library | Language | Best For |
|---------|----------|----------|
| **Browser-use** | Python | Agentic automation |
| **Stagehand** | TypeScript | Web apps |
| **LaVague** | Python | NL to code |
| **Skyvern** | Python | CV-based automation |

#### Cloud Automation

| Service | Platform | Best For |
|---------|----------|----------|
| **Skyvern Cloud** | Cloud API | Resilient automation |
| **Browserbase** | Cloud API | Stealth mode, session recording |

### Desktop Automation 🖥️

AI agents and tools for automating desktop tasks and OS-level interactions.

#### AI Agents (Computer Use)

| Agent | Platform | Vision-Based | Cross-Platform | Best For |
|-------|----------|--------------|----------------|----------|
| **Agent S** | Cross-platform | ✅ | ✅ | Research/SOTA |
| **Bytebot** | Linux (Docker) | ✅ | ✅ | Self-hosted |
| **UFO** | Windows | ✅ | ❌ | Windows automation |
| **Open-Interface** | Cross-platform | ✅ | ✅ | General use |
| **Anthropic Computer Use** | API | ✅ | ✅ | Beta capability |

#### RPA & Visual Frameworks

| Tool | Platform | Best For |
|------|----------|----------|
| **Ui.Vision RPA** | Windows, macOS, Linux | Visual automation |
| **OmniParser V2** | Cross-platform | Screen parsing |

#### Scripting Libraries

| Tool | Platform | Key Features |
|------|----------|--------------|
| **PyAutoGUI** | Cross-platform | Simple API, fail-safe |
| **Nut.js** | Cross-platform | Visual search, image matching |
| **OpenAdapt** | Windows, macOS | Learning from demonstration |

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
| **Coding** | DeepSeek-Coder-V2 | Claude Sonnet 4.5 |
| **Reasoning** | DeepSeek-R1 | o3, Qwen3-Max-Thinking |
| **Long docs** | Llama 4 Scout | Gemini 3 Flash |
| **Vision** | Llama 4 Maverick | GPT-5, Gemini 3 |

### Model Selection Guide 🎯

A comprehensive guide to choosing the right AI model for your specific needs.

#### Quick Decision Tree

```
What do you need?
│
├── Coding/Development
│   ├── Best quality → Claude Sonnet 4.5
│   ├── Autonomous → GPT-5 Codex
│   └── Open source → DeepSeek-Coder-V2
│
├── Reasoning/Math
│   ├── Best quality → Qwen3-Max-Thinking (100% AIME)
│   └── Open source → DeepSeek-R1
│
├── General Purpose
│   ├── Best overall → GPT-5, Claude Sonnet 4.5
│   └── Budget → DeepSeek-V3.1
│
├── Multimodal (Vision)
│   ├── Best overall → GPT-5, Gemini 3 Pro
│   └── Open source → Llama 4 Maverick
│
└── Self-Hosting
    ├── Small (consumer GPU) → Phi-4
    └── Large (enterprise) → DeepSeek-V4
```

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
| 💵 **Budget** | $0.10 - $0.50/1M | GLM-4.6, DeepSeek-V3 |
| 💰 **Mid-range** | $1.00 - $15.00/1M | GPT-5, Claude Sonnet |
| 💎 **Premium** | $15.00 - $600.00/1M | Claude Opus, o1-Pro |

#### Model Pricing Comparison

| Model | Input | Output | Best For |
|-------|-------|--------|----------|
| **GLM-4.6** | $0.13 | $0.39 | Budget coding |
| **DeepSeek-V3.1** | $0.27 | $0.41 | Everything |
| **Gemini 3 Flash** | $0.30 | $2.50 | Long context |
| **GPT-5** | $1.25 | $10.00 | General purpose |
| **Claude Sonnet 4.5** | $3.00 | $15.00 | Best coding |
| **Claude Opus 4.5** | $15.00 | $75.00 | Maximum quality |

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

#### Sort by Price (Cheapest)

| Rank | Model | Input | Output | License |
|------|-------|-------|--------|---------|
| 1 | **Self-hosted** | $0 | $0 | Various |
| 2 | **GLM-4.6** | $0.13 | $0.39 | Open-weight |
| 3 | **Yi-Lightning** | $0.14 | $0.42 | Apache 2.0 |
| 4 | **DeepSeek-V3.1** | $0.27 | $0.41 | MIT |
| 5 | **Gemini 3 Flash** | $0.30 | $2.50 | Proprietary |

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
| 4 | **Kimi K2-0905** | 256K | Large codebases |

### Data Sources 📚

Attribution, verification sources, and methodology.

#### Primary Sources

| Company | Source | URL |
|---------|--------|-----|
| **OpenAI** | Official Documentation | [openai.com](https://openai.com) |
| **Anthropic** | Claude Documentation | [anthropic.com](https://www.anthropic.com) |
| **Google** | Gemini Documentation | [deepmind.google](https://deepmind.google/models/gemini/) |
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

## Contributing

Thank you for your interest in contributing to the Awesome AI Models Matrix!

### How to Contribute

1. **Fork the Repository** - Create your own fork
2. **Create a Branch** - Make a new branch for your contribution
3. **Make Your Changes** - Follow the guidelines below
4. **Submit a Pull Request** - Describe your changes clearly
5. **Wait for Review** - Maintainers will review and provide feedback

### Contribution Standards

All model entries MUST include:
- ✅ **Official Source** - Link to official announcement or documentation
- ✅ **Verification** - At least one authoritative source
- ✅ **Accuracy** - Information must be current and factual
- ✅ **Completeness** - All table columns filled

### Style Guidelines

- **Headers**: Use proper hierarchy (H1 → H6)
- **Tables**: Align columns consistently
- **Links**: Use descriptive text
- **Date Format**: YYYY-MM-DD HH:MM UTC
- **Emoji**: ✅ for Yes, ❌ for No, 🚀 for highlights

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

---

## License

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0) License - see the [LICENSE](LICENSE) file for details.

---

**Last Updated:** 2026-02-03 02:35 UTC  
**Maintained by:** ReadyPixels LLC & AI Models Matrix Contributors

---

Made with ❤️ by ReadyPixels LLC

[![Star on GitHub](https://img.shields.io/github/stars/your-org/ai-models-matrix?style=social)](https://github.com/your-org/ai-models-matrix)
