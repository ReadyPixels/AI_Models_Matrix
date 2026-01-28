# Awesome AI Models 🧠

_Last updated: 2026-01-28 00:20 UTC_

> A curated list of the most capable Large Language Models (LLMs), Small Language Models (SLMs), and specialized AI models available today.

## 🏆 Frontier Models (State-of-the-Art)

| Model | Company | Release | Context | Key Features | License | Status | Verified |
|-------|---------|---------|---------|--------------|---------|--------|----------|
| **DeepSeek-V4** | DeepSeek | 2026-01 | 128K | Reasoning Core, DSA, Interleaved Thinking | MIT | ✅ Active | 2026-01-28 00:20 UTC |
| **Qwen3-Max-Thinking** | Alibaba | 2026-01 | 128K | 100% AIME25/HMMT, parallel computation | Apache 2.0 | ✅ Active | 2026-01-28 00:20 UTC |
| **Gemini 3 Pro** | Google | 2025-11-18 | 1M+ | PhD-level reasoning, agentic tool-use | Proprietary | ✅ Active | 2026-01-28 00:20 UTC |
| **Gemini 3 Flash** | Google | 2025-12-17 | 10M | Pro-grade reasoning, Flash speed | Proprietary | ✅ Active | 2026-01-28 00:20 UTC |
| **GPT-5.2-Codex** | OpenAI | 2025-12-18 | 400K | Cybersecurity, long-horizon refactoring | Proprietary | ✅ Active | 2026-01-28 00:20 UTC |
| **GPT-5.2** | OpenAI | 2025-12-11 | 400K | Thinking & Instant variants, $1.75/1M | Proprietary | ✅ Active | 2026-01-28 00:20 UTC |
| **GPT-5 mini** | OpenAI | 2025-12 | 128K | Cheap reasoning, $0.25/1M | Proprietary | ✅ Active | 2026-01-28 00:20 UTC |
| **Mistral Large 3** | Mistral AI | 2025-12-02 | 128K | 675B params, MoE, Open-weight | Apache 2.0 | ✅ Active | 2026-01-28 00:20 UTC |
| **Claude Opus 4.5** | Anthropic | 2025-11-24 | 200K | Leading reasoning accuracy, effort param | Proprietary | ✅ Active | 2026-01-28 00:20 UTC |
| **Llama 4 Scout** | Meta | 2025-12 | 10M | Open-weight context king | Community | ✅ Active | 2026-01-28 00:20 UTC |
| **DeepSeek-V3.2-Speciale** | DeepSeek | 2025-12 | 128K | Maxed-out reasoning, IMO gold | MIT | ✅ Active | 2026-01-28 00:20 UTC |

## 🧠 Advanced Reasoning Models (2024-2025)

### Qwen3-Max-Thinking ⭐ (Latest: Jan 2026)
- **Developer**: Alibaba (Qwen Team)
- **Performance**: 100% accuracy on AIME25 and HMMT benchmarks (perfect scores)
- **Benchmark Scores**: AIME25: 100% | HMMT: 100% | HumanEval: ~92% | MMLU: ~91%
- **Architecture**: 1T+ parameters, parallel test-time computation
- **Key Features**: First Chinese model with perfect math benchmarks, peer reasoning mechanism, integrated code interpreter
- **Pricing**: API tier available
- **Self-Host**: Yes (Apache 2.0 license)
- **Official Site**: [🔗](https://qwen.ai/)
- **Status**: ✅ Active
- **Verified**: 2026-01-28 00:20 UTC

### Gemini 3 Pro ⭐ (Latest: Nov 2025)
- **Developer**: Google DeepMind
- **Capabilities**: State-of-the-art reasoning with unprecedented depth and nuance
- **Features**: Exceptional instruction following, meaningful improved tool use, agentic coding, multimodal (text, images, video, audio, code)
- **Access**: Google AI Studio, Vertex AI, Antigravity platform
- **Benchmark Scores**: HumanEval: ~89% | MMLU: ~90.6% | ARC-AGI-2: 31.1%
- **Context Window**: 1M+ tokens
- **Pricing**: Tiered pricing available
- **Self-Host**: Via Vertex AI (enterprise)
- **Official Site**: [🔗](https://deepmind.google/models/gemini/pro/)
- **Status**: ✅ Active
- **Verified**: 2026-01-28 00:20 UTC

### GPT-5 Series
- **Developer**: OpenAI
- **Variants**: GPT-5, GPT-5.1, GPT-5.2, GPT-5.2-Codex
- **Capabilities**: Smartest, fastest, most useful model with thinking built-in
- **Performance**: Significant leap in intelligence over previous models
- **Features**: State-of-the-art across coding, math, writing, health, visual perception
- **Benchmark Scores**: AIME 2025: 100% | ARC-AGI-2: 52.9% | GPQA Diamond: 92.4% | SWE-Bench Pro: 55.6%
- **Pricing**: GPT-5.2: $1.75/1M tokens | GPT-5 mini: $0.25/1M tokens
- **Self-Host**: API-only
- **Status**: Available to everyone
- **Verified**: 2026-01-28 00:20 UTC

### Granite 4.0
- **Developer**: IBM
- **Architecture**: Hybrid Mamba-2/transformer with MoE strategy
- **Efficiency**: 70% lower memory, 2x faster inference
- **Models**: Micro, Tiny, Small variants
- **Focus**: Enterprise efficiency and performance
- **Status**: Released October 2025
- **Verified**: 2026-01-28 00:20 UTC

## 🔓 Open-Source / Open-Weight Models

### 🏢 Enterprise / General Purpose
- **Llama 4 (Scout/Maverick)** (Meta)
    - *Specs*: 10M Token Context (Scout), 400B (Maverick)
    - *License*: Meta Community License
    - *Note*: Native multimodal, 10M context standard for RAG.
    - *Status*: ✅ Active
    - *Verified*: 2026-01-28 00:20 UTC
- **GLM-4.7** (Zhipu AI)
    - *Specs*: 400B+ MoE, Enterprise focus
    - *License*: Open-weight
    - *Note*: Launched Dec 2025. Enhanced multilingual and tool-use.
    - *Status*: ✅ Active
    - *Verified*: 2026-01-28 00:20 UTC
- **Mistral Large 3** (Mistral AI)
    - *Specs*: 675B (MoE)
    - *License*: Apache 2.0
    - *Note*: Released Dec 2, 2025. Top-tier open model.
    - *Status*: ✅ Active
    - *Verified*: 2026-01-28 00:20 UTC
- **Qwen 3 (Max/Next/Thinking)** (Alibaba)
    - *Specs*: 1T+ (Max), Integrated Code Interpreter
    - *License*: Apache 2.0 (Next), API (Max)
    - *Note*: First Chinese model with 100% AIME25 score.
    - *Status*: ✅ Active
    - *Verified*: 2026-01-28 00:20 UTC

### 💻 Coding Specialized
- **GPT-5.2-Codex** (OpenAI)
    - *Release*: 2025-12-18
    - *Focus*: Cybersecurity, long-horizon refactoring, Windows compatibility.
    - *Benchmark*: SWE-Bench Pro: 55.6%
    - *Status*: ✅ Active
    - *Verified*: 2026-01-28 00:20 UTC
- **DeepSeek-Coder-V2** (DeepSeek)
    - *License*: MIT
    - *Focus*: 236B params, MoE, beats GPT-4 Turbo in coding.
    - *Status*: ✅ Active
    - *Verified*: 2026-01-28 00:20 UTC
- **Qwen3-Coder** (Alibaba)
    - *License*: Apache 2.0
    - *Focus*: 480B params, autonomous dev capabilities.
    - *Status*: ✅ Active
    - *Verified*: 2026-01-28 00:20 UTC
- **Nemotron 3 Nano** (NVIDIA)
    - *Release*: 2025-12
    - *Specs*: 1M context, high accuracy in coding/math.
    - *Status*: ✅ Active
    - *Verified*: 2026-01-28 00:20 UTC

## 🧪 Experimental & Reasoning
- **Gemini 3 Deep Research** (Google)
    - *Focus*: Autonomous multi-step research and synthesis.
    - *Status*: ✅ Active
    - *Verified*: 2026-01-28 00:20 UTC
- **o1 / o3** (OpenAI)
    - *Focus*: Chain-of-thought reasoning ("System 2" thinking).
    - *Status*: ✅ Active
    - *Verified*: 2026-01-28 00:20 UTC
- **DeepSeek-R1** (DeepSeek)
    - *Focus*: Pure RL-based reasoning model.
    - *Status*: ✅ Active
    - *Verified*: 2026-01-28 00:20 UTC
- **DeepSeek-V4** (DeepSeek) 🆕
    - *Release*: Jan 2026
    - *Focus*: Reasoning Core architecture, Dynamic Sparse Attention, Interleaved Thinking.
    - *Status*: ✅ Active
    - *Verified*: 2026-01-28 00:20 UTC
- **Qwen3-Max-Thinking** (Alibaba) 🆕
    - *Release*: Jan 2026
    - *Focus*: Parallel test-time computation, math/coding benchmarks. 100% AIME25/HMMT.
    - *Benchmark Scores*: AIME25: 100% | HMMT: 100%
    - *Status*: ✅ Active
    - *Verified*: 2026-01-28 00:20 UTC
- **NVIDIA Nemotron 3 Family** (NVIDIA) 🆕
    - *Release*: Expected H1 2026
    - *Focus*: For agentic AI with Super and Ultra variants.
    - *Status*: Expected
    - *Verified*: 2026-01-28 00:20 UTC
- **DeepSeek AI** (DeepSeek) 🆕
    - *Release*: 2025
    - *Focus*: Strong in reasoning and agentic tasks.
    - *Status*: ✅ Active
    - *Verified*: 2026-01-28 00:20 UTC
- **Kimi K2** (Moonshot AI) 🆕
    - *Release*: 2025
    - *Focus*: Multilingual agentic model.
    - *Status*: ✅ Active
    - *Verified*: 2026-01-28 00:20 UTC

## 📊 Reasoning Benchmarks Comparison

| Model | AIME25 | HMMT | HumanEval | MMLU | ARC-AGI-2 |
|-------|--------|------|-----------|------|-----------|
| **Qwen3-Max-Thinking** | 100% | 100% | ~92% | ~91% | - |
| **GPT-5.2** | 100% | - | - | - | 52.9% |
| **GPT-5.2-Codex** | - | - | - | - | - |
| **Gemini 3 Pro** | - | - | ~89% | ~90.6% | 31.1% |
| **Claude Opus 4.5** | - | - | - | - | 37.6% |
| **DeepSeek-V4** | - | - | - | - | - |
| **DeepSeek-V3.2-Speciale** | - | - | - | - | - |

## 📉 Legacy / Superseded (Reference Only)
- *GPT-4o / GPT-4 Turbo* (Superseded by GPT-5 series)
- *Claude 3.5 Sonnet* (Superseded by 4.5)
- *Llama 3.1* (Superseded by Llama 4)
- *Mistral Large 2* (Superseded by Large 3)

---

## 📚 Sources & Verification

### Primary Sources
- [Google DeepMind - Gemini Models](https://deepmind.google/models/gemini/)
- [OpenAI GPT-5 Documentation](https://openai.com/gpt-5)
- [Anthropic Claude Documentation](https://www.anthropic.com/claude)
- [Alibaba Qwen Blog](https://qwen.ai/blog)
- [Meta Llama Documentation](https://llama.meta.com)
- [Mistral AI Documentation](https://mistral.ai)
- [DeepSeek Official](https://deepseek.ai)

### Benchmark Sources
- [DEV Community - Qwen3-Max Analysis](https://dev.to/czmilo/qwen3-max-2025-complete-release-analysis-in-depth-review-of-alibabas-most-powerful-ai-model-3j7l)
- [LM Council Benchmarks](https://lmcouncil.ai/benchmarks)
- [LLM Stats Leaderboard](https://llm-stats.com/leaderboards/llm-leaderboard)
- [Vellum - GPT-5.2 Benchmarks](https://www.vellum.ai/blog/gpt-5-2-benchmarks)

### Methodology
- All benchmarks verified from official sources or authoritative third parties
- Timestamps in UTC format (YYYY-MM-DDThh:mm:ss.sssZ)
- Last verification: 2026-01-28 00:20 UTC

---

*Last Updated: 2026-01-28 00:20 UTC*
*Maintained by: AI Models Matrix Contributors*
