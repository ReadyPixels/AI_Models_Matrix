# Awesome AI Models 🧠

_Last updated: 2026-01-28 00:20 UTC_

> A curated list of the most capable Large Language Models (LLMs), Small Language Models (SLMs), and specialized AI models available today.

## 🏆 Frontier Models (State-of-the-Art)

| Model | Company | Release | Context | Key Features | License | Model Size (GB) | Hardware Requirements | Status | Verified |
|-------|---------|---------|---------|--------------|---------|-----------------|----------------------|--------|----------|
| **DeepSeek-V4** | DeepSeek | 2026-01 | 128K | Reasoning Core, DSA, Interleaved Thinking | MIT | ~404 (Q4) / ~1,342 (FP16) | Min: 80GB VRAM<br>Rec: 4x A100 80GB | ✅ Active | 2026-01-28 00:20 UTC |
| **Qwen3-Max-Thinking** | Alibaba | 2026-01 | 128K | 100% AIME25/HMMT, parallel computation | Apache 2.0 | ~600+ (Q4) / ~2,000+ (FP16) | Min: 160GB VRAM<br>Rec: 8x A100 80GB | ✅ Active | 2026-01-28 00:20 UTC |
| **Gemini 3 Pro** | Google | 2025-11-18 | 1M+ | PhD-level reasoning, agentic tool-use | Proprietary | N/A | Cloud/API only | ✅ Active | 2026-01-28 00:20 UTC |
| **Gemini 3 Flash** | Google | 2025-12-17 | 10M | Pro-grade reasoning, Flash speed | Proprietary | N/A | Cloud/API only | ✅ Active | 2026-01-28 00:20 UTC |
| **GPT-5.2-Codex** | OpenAI | 2025-12-18 | 400K | Cybersecurity, long-horizon refactoring | Proprietary | N/A | Cloud/API only | ✅ Active | 2026-01-28 00:20 UTC |
| **GPT-5.2** | OpenAI | 2025-12-11 | 400K | Thinking & Instant variants, $1.75/1M | Proprietary | N/A | Cloud/API only | ✅ Active | 2026-01-28 00:20 UTC |
| **GPT-5 mini** | OpenAI | 2025-12 | 128K | Cheap reasoning, $0.25/1M | Proprietary | N/A | Cloud/API only | ✅ Active | 2026-01-28 00:20 UTC |
| **Mistral Large 3** | Mistral AI | 2025-12-02 | 128K | 675B params, MoE, Open-weight | Apache 2.0 | ~406 (Q4) / ~1,350 (FP16) | Min: 80GB VRAM<br>Rec: 4x A100 80GB | ✅ Active | 2026-01-28 00:20 UTC |
| **Claude Opus 4.5** | Anthropic | 2025-11-24 | 200K | Leading reasoning accuracy, effort param | Proprietary | N/A | Cloud/API only | ✅ Active | 2026-01-28 00:20 UTC |
| **Llama 4 Scout** | Meta | 2025-12 | 10M | Open-weight context king | Community | ~66 (Q4) / ~218 (FP16) | Min: 48GB VRAM<br>Rec: 2x RTX 4090 or A100 80GB | ✅ Active | 2026-01-28 00:20 UTC |
| **DeepSeek-V3.2-Speciale** | DeepSeek | 2025-12 | 128K | Maxed-out reasoning, IMO gold | MIT | ~404 (Q4) / ~1,342 (FP16) | Min: 80GB VRAM<br>Rec: 4x A100 80GB | ✅ Active | 2026-01-28 00:20 UTC |

### DeepSeek-V4 Hardware Requirements

**Model Size (GB):**
- Full precision (FP16/BF16): ~1,342 GB (671B parameters)
- Q4_K_M quantized: ~404 GB
- Q8_0 quantized: ~707 GB

**RAM Requirements:**
- Minimum RAM: 512 GB (with Q4_K_M, CPU inference)
- Recommended RAM: 1 TB+ (for FP16/BF16)

**GPU Requirements:**
- Minimum GPU VRAM: 80 GB (single A100/H100 with Q4_K_M, offload)
- Recommended GPU VRAM: 320 GB (4x A100 80GB or 2x H100 80GB)
- Multi-GPU support: Yes, tensor parallelism supported via vLLM, llama.cpp, SGLang

**CPU Inference:**
- Possible: Yes, but very slow
- Minimum CPU: 64+ cores (AMD EPYC or Intel Xeon), AVX-512 support recommended

**Disk Space:**
- Approximate download: 404 GB (Q4_K_M), 707 GB (Q8_0)

---

### Qwen3-Max-Thinking Hardware Requirements

**Model Size (GB):**
- Full precision (FP16/BF16): ~2,000+ GB (1T+ parameters)
- Q4_K_M quantized: ~600+ GB
- Q8_0 quantized: ~1,100+ GB

**RAM Requirements:**
- Minimum RAM: 768 GB (with Q4_K_M, CPU inference)
- Recommended RAM: 1.5 TB+

**GPU Requirements:**
- Minimum GPU VRAM: 160 GB (2x A100 80GB with Q4_K_M)
- Recommended GPU VRAM: 640 GB (8x A100 80GB or 4x H100 80GB)
- Multi-GPU support: Yes, required for practical inference

**CPU Inference:**
- Possible: Yes, but extremely slow (not recommended for production)
- Minimum CPU: 128+ cores, DDR5 memory recommended

**Disk Space:**
- Approximate download: 600+ GB (Q4_K_M)

---

### Mistral Large 3 Hardware Requirements

**Model Size (GB):**
- Full precision (FP16/BF16): ~1,350 GB (675B parameters, MoE)
- Q4_K_M quantized: ~406 GB
- Q8_0 quantized: ~712 GB

**RAM Requirements:**
- Minimum RAM: 512 GB (with Q4_K_M)
- Recommended RAM: 1 TB+

**GPU Requirements:**
- Minimum GPU VRAM: 80 GB (single A100 80GB with Q4_K_M, offload)
- Recommended GPU VRAM: 320 GB (4x A100 80GB)
- Multi-GPU support: Yes, via tensor parallelism

**CPU Inference:**
- Possible: Yes
- Minimum CPU: 64+ cores, AVX-512 support

**Disk Space:**
- Approximate download: 406 GB (Q4_K_M), 712 GB (Q8_0)

---

### Llama 4 Scout Hardware Requirements

**Model Size (GB):**
- Full precision (FP16/BF16): ~218 GB (109B parameters estimated)
- Q4_K_M quantized: ~66 GB
- Q8_0 quantized: ~115 GB

**RAM Requirements:**
- Minimum RAM: 96 GB (with Q4_K_M)
- Recommended RAM: 128 GB+ (for Q8_0 or FP16)

**GPU Requirements:**
- Minimum GPU VRAM: 48 GB (single A6000 or RTX 4090 with Q4_K_M)
- Recommended GPU VRAM: 80 GB (single A100 80GB for Q8_0)
- Multi-GPU support: Yes, 2x RTX 4090 (48GB) works well

**CPU Inference:**
- Possible: Yes, viable for Q4_K_M
- Minimum CPU: 32+ cores, AVX2 support minimum

**Disk Space:**
- Approximate download: 66 GB (Q4_K_M), 115 GB (Q8_0)

---

### DeepSeek-V3.2-Speciale Hardware Requirements

**Model Size (GB):**
- Full precision (FP16/BF16): ~1,342 GB (671B parameters, MoE)
- Q4_K_M quantized: ~404 GB
- Q8_0 quantized: ~707 GB

**RAM Requirements:**
- Minimum RAM: 512 GB (with Q4_K_M, CPU inference)
- Recommended RAM: 1 TB+

**GPU Requirements:**
- Minimum GPU VRAM: 80 GB (single A100 80GB with Q4_K_M, offload)
- Recommended GPU VRAM: 320 GB (4x A100 80GB or 2x H100 80GB)
- Multi-GPU support: Yes, tensor parallelism supported

**CPU Inference:**
- Possible: Yes, but very slow
- Minimum CPU: 64+ cores, AVX-512 support recommended

**Disk Space:**
- Approximate download: 404 GB (Q4_K_M), 707 GB (Q8_0)

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

#### Hardware Requirements

**Model Size (GB):**
- Full precision (FP16/BF16): ~2,000+ GB (1T+ parameters)
- Q4_K_M quantized: ~600+ GB
- Q8_0 quantized: ~1,100+ GB

**RAM Requirements:**
- Minimum RAM: 768 GB (with Q4_K_M, CPU inference)
- Recommended RAM: 1.5 TB+

**GPU Requirements:**
- Minimum GPU VRAM: 160 GB (2x A100 80GB with Q4_K_M)
- Recommended GPU VRAM: 640 GB (8x A100 80GB or 4x H100 80GB)
- Multi-GPU support: Yes, required for practical inference

**CPU Inference:**
- Possible: Yes, but extremely slow
- Minimum CPU: 128+ cores, DDR5 memory recommended

**Disk Space:**
- Approximate download: 600+ GB (Q4_K_M)

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

    #### Hardware Requirements

    **Llama 4 Scout:**
    - **Model Size (GB):**
      - Full precision (FP16/BF16): ~218 GB (109B parameters)
      - Q4_K_M quantized: ~66 GB
      - Q8_0 quantized: ~115 GB
    - **RAM Requirements:**
      - Minimum RAM: 96 GB (Q4_K_M)
      - Recommended RAM: 128 GB+
    - **GPU Requirements:**
      - Minimum GPU VRAM: 48 GB (A6000 or RTX 4090 with Q4_K_M)
      - Recommended GPU VRAM: 80 GB (A100 80GB)
      - Multi-GPU support: Yes, 2x RTX 4090 viable
    - **CPU Inference:** Possible, 32+ cores recommended
    - **Disk Space:** ~66 GB (Q4_K_M)

    **Llama 4 Maverick:**
    - **Model Size (GB):**
      - Full precision (FP16/BF16): ~800 GB (400B parameters)
      - Q4_K_M quantized: ~242 GB
      - Q8_0 quantized: ~424 GB
    - **RAM Requirements:**
      - Minimum RAM: 320 GB (Q4_K_M)
      - Recommended RAM: 512 GB+
    - **GPU Requirements:**
      - Minimum GPU VRAM: 160 GB (2x A100 80GB with Q4_K_M)
      - Recommended GPU VRAM: 320 GB (4x A100 80GB)
      - Multi-GPU support: Yes, required
    - **CPU Inference:** Possible but slow, 64+ cores
    - **Disk Space:** ~242 GB (Q4_K_M)

- **GLM-4.7** (Zhipu AI)
    - *Specs*: 400B+ MoE, Enterprise focus
    - *License*: Open-weight
    - *Note*: Launched Dec 2025. Enhanced multilingual and tool-use.
    - *Status*: ✅ Active
    - *Verified*: 2026-01-28 00:20 UTC

    #### Hardware Requirements

    **Model Size (GB):**
    - Full precision (FP16/BF16): ~820 GB (410B parameters, MoE)
    - Q4_K_M quantized: ~248 GB
    - Q8_0 quantized: ~435 GB

    **RAM Requirements:**
    - Minimum RAM: 320 GB (Q4_K_M)
    - Recommended RAM: 512 GB+

    **GPU Requirements:**
    - Minimum GPU VRAM: 160 GB (2x A100 80GB with Q4_K_M)
    - Recommended GPU VRAM: 320 GB (4x A100 80GB)
    - Multi-GPU support: Yes, tensor parallelism supported

    **CPU Inference:**
    - Possible: Yes
    - Minimum CPU: 64+ cores

    **Disk Space:**
    - Approximate download: 248 GB (Q4_K_M), 435 GB (Q8_0)

- **Mistral Large 3** (Mistral AI)
    - *Specs*: 675B (MoE)
    - *License*: Apache 2.0
    - *Note*: Released Dec 2, 2025. Top-tier open model.
    - *Status*: ✅ Active
    - *Verified*: 2026-01-28 00:20 UTC

    #### Hardware Requirements

    **Model Size (GB):**
    - Full precision (FP16/BF16): ~1,350 GB (675B parameters, MoE)
    - Q4_K_M quantized: ~406 GB
    - Q8_0 quantized: ~712 GB

    **RAM Requirements:**
    - Minimum RAM: 512 GB (Q4_K_M)
    - Recommended RAM: 1 TB+

    **GPU Requirements:**
    - Minimum GPU VRAM: 80 GB (single A100 80GB with Q4_K_M, offload)
    - Recommended GPU VRAM: 320 GB (4x A100 80GB)
    - Multi-GPU support: Yes, via tensor parallelism

    **CPU Inference:**
    - Possible: Yes
    - Minimum CPU: 64+ cores, AVX-512 support

    **Disk Space:**
    - Approximate download: 406 GB (Q4_K_M), 712 GB (Q8_0)

- **Qwen 3 (Max/Next/Thinking)** (Alibaba)
    - *Specs*: 1T+ (Max), Integrated Code Interpreter
    - *License*: Apache 2.0 (Next), API (Max)
    - *Note*: First Chinese model with 100% AIME25 score.
    - *Status*: ✅ Active
    - *Verified*: 2026-01-28 00:20 UTC

    #### Hardware Requirements

    **Qwen 3 Max/Thinking:**
    - **Model Size (GB):**
      - Full precision (FP16/BF16): ~2,000+ GB (1T+ parameters)
      - Q4_K_M quantized: ~600+ GB
      - Q8_0 quantized: ~1,100+ GB
    - **RAM Requirements:**
      - Minimum RAM: 768 GB (Q4_K_M)
      - Recommended RAM: 1.5 TB+
    - **GPU Requirements:**
      - Minimum GPU VRAM: 160 GB (2x A100 80GB)
      - Recommended GPU VRAM: 640 GB (8x A100 80GB)
      - Multi-GPU support: Yes, required
    - **CPU Inference:** Possible but extremely slow, 128+ cores
    - **Disk Space:** ~600+ GB (Q4_K_M)

    **Qwen 3 Next:**
    - **Model Size (GB):**
      - Full precision (FP16/BF16): ~472 GB (236B parameters estimated)
      - Q4_K_M quantized: ~143 GB
      - Q8_0 quantized: ~250 GB
    - **RAM Requirements:**
      - Minimum RAM: 192 GB (Q4_K_M)
      - Recommended RAM: 256 GB+
    - **GPU Requirements:**
      - Minimum GPU VRAM: 80 GB (A100 80GB)
      - Recommended GPU VRAM: 160 GB (2x A100 80GB)
      - Multi-GPU support: Yes
    - **CPU Inference:** Possible, 48+ cores
    - **Disk Space:** ~143 GB (Q4_K_M)

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

    #### Hardware Requirements

    **Model Size (GB):**
    - Full precision (FP16/BF16): ~472 GB (236B parameters, MoE)
    - Q4_K_M quantized: ~143 GB
    - Q8_0 quantized: ~250 GB

    **RAM Requirements:**
    - Minimum RAM: 192 GB (Q4_K_M)
    - Recommended RAM: 256 GB+

    **GPU Requirements:**
    - Minimum GPU VRAM: 48 GB (RTX A6000 with Q4_K_M)
    - Recommended GPU VRAM: 80 GB (A100 80GB) or 2x RTX 4090
    - Multi-GPU support: Yes

    **CPU Inference:**
    - Possible: Yes, viable for Q4_K_M
    - Minimum CPU: 32+ cores

    **Disk Space:**
    - Approximate download: 143 GB (Q4_K_M), 250 GB (Q8_0)

- **Qwen3-Coder** (Alibaba)
    - *License*: Apache 2.0
    - *Focus*: 480B params, autonomous dev capabilities.
    - *Status*: ✅ Active
    - *Verified*: 2026-01-28 00:20 UTC

    #### Hardware Requirements

    **Model Size (GB):**
    - Full precision (FP16/BF16): ~960 GB (480B parameters)
    - Q4_K_M quantized: ~290 GB
    - Q8_0 quantized: ~510 GB

    **RAM Requirements:**
    - Minimum RAM: 384 GB (Q4_K_M)
    - Recommended RAM: 512 GB+

    **GPU Requirements:**
    - Minimum GPU VRAM: 160 GB (2x A100 80GB with Q4_K_M)
    - Recommended GPU VRAM: 320 GB (4x A100 80GB)
    - Multi-GPU support: Yes, required

    **CPU Inference:**
    - Possible: Yes
    - Minimum CPU: 64+ cores

    **Disk Space:**
    - Approximate download: 290 GB (Q4_K_M), 510 GB (Q8_0)

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

    #### Hardware Requirements

    **Model Size (GB):**
    - Full precision (FP16/BF16): ~1,342 GB (671B parameters, MoE, based on V3 architecture)
    - Q4_K_M quantized: ~404 GB
    - Q8_0 quantized: ~707 GB

    **RAM Requirements:**
    - Minimum RAM: 512 GB (Q4_K_M)
    - Recommended RAM: 1 TB+

    **GPU Requirements:**
    - Minimum GPU VRAM: 80 GB (single A100 80GB with Q4_K_M, offload)
    - Recommended GPU VRAM: 320 GB (4x A100 80GB or 2x H100 80GB)
    - Multi-GPU support: Yes, tensor parallelism supported via vLLM, llama.cpp, SGLang

    **CPU Inference:**
    - Possible: Yes, but very slow
    - Minimum CPU: 64+ cores, AVX-512 support recommended

    **Disk Space:**
    - Approximate download: 404 GB (Q4_K_M), 707 GB (Q8_0)

- **DeepSeek-V4** (DeepSeek) 🆕
    - *Release*: Jan 2026
    - *Focus*: Reasoning Core architecture, Dynamic Sparse Attention, Interleaved Thinking.
    - *Status*: ✅ Active
    - *Verified*: 2026-01-28 00:20 UTC

    #### Hardware Requirements

    **Model Size (GB):**
    - Full precision (FP16/BF16): ~1,342 GB (671B parameters)
    - Q4_K_M quantized: ~404 GB
    - Q8_0 quantized: ~707 GB

    **RAM Requirements:**
    - Minimum RAM: 512 GB (Q4_K_M, CPU inference)
    - Recommended RAM: 1 TB+

    **GPU Requirements:**
    - Minimum GPU VRAM: 80 GB (single A100 80GB with Q4_K_M, offload)
    - Recommended GPU VRAM: 320 GB (4x A100 80GB or 2x H100 80GB)
    - Multi-GPU support: Yes, tensor parallelism supported

    **CPU Inference:**
    - Possible: Yes, but very slow
    - Minimum CPU: 64+ cores, AVX-512 support recommended

    **Disk Space:**
    - Approximate download: 404 GB (Q4_K_M), 707 GB (Q8_0)

- **Qwen3-Max-Thinking** (Alibaba) 🆕
    - *Release*: Jan 2026
    - *Focus*: Parallel test-time computation, math/coding benchmarks. 100% AIME25/HMMT.
    - *Benchmark Scores*: AIME25: 100% | HMMT: 100%
    - *Status*: ✅ Active
    - *Verified*: 2026-01-28 00:20 UTC

    #### Hardware Requirements

    **Model Size (GB):**
    - Full precision (FP16/BF16): ~2,000+ GB (1T+ parameters)
    - Q4_K_M quantized: ~600+ GB
    - Q8_0 quantized: ~1,100+ GB

    **RAM Requirements:**
    - Minimum RAM: 768 GB (Q4_K_M, CPU inference)
    - Recommended RAM: 1.5 TB+

    **GPU Requirements:**
    - Minimum GPU VRAM: 160 GB (2x A100 80GB with Q4_K_M)
    - Recommended GPU VRAM: 640 GB (8x A100 80GB or 4x H100 80GB)
    - Multi-GPU support: Yes, required for practical inference

    **CPU Inference:**
    - Possible: Yes, but extremely slow (not recommended for production)
    - Minimum CPU: 128+ cores, DDR5 memory recommended

    **Disk Space:**
    - Approximate download: 600+ GB (Q4_K_M)

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
