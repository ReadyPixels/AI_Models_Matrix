# Release vv3.26

Release v3.26: [2026-06-08] - Version 3.26 - Nemotron 3 Ultra, Colab CLI, OpenRouter Speech API, benchmark & staleness fixes

## Latest Changelog Entry

### [2026-06-08] - Version 3.26 - Nemotron 3 Ultra, Colab CLI, OpenRouter Speech API, benchmark & staleness fixes

### Added
- **NVIDIA Nemotron 3 Ultra** (Frontier Models + Free-Source Models): 550B/55B active MoE; 262K context (BF16) / 1M (NVFP4 Blackwell); open weight; launched at Computex June 2026; orchestration-focused, Mamba+Transformer hybrid.
  - Source: https://developer.nvidia.com/blog/nvidia-nemotron-3-ultra-powers-faster-more-efficient-reasoning-for-long-running-agents/
- **Google Colab CLI** (Assisted CLI Tools): Connect local terminal to remote Colab GPU/TPU runtimes; AI agent compatible; released 2026-06-06.
  - Source: https://www.marktechpost.com/2026/06/06/googles-new-colab-cli-lets-developers-and-ai-agents-run-python-on-remote-colab-gpus-and-tpus-from-the-terminal/

### Updated
- **Kimi K2.6** (Frontier Models, Output Limits): Context window corrected from 256K to 262K tokens (262,144); max output updated to 262K.
  - Source: https://huggingface.co/moonshotai/Kimi-K2.6
- **GPT-5.5** (Frontier Models, Benchmark Reference): Added Arena Elo 1495, SWE-bench Verified 88.5%, AIME 2025 99.9% from leaderboard data; corrected GPQA Diamond to 93.6%.
  - Source: https://benchlm.ai/benchmarks/sweVerified
- **OpenRouter** (Unified APIs): Updated model count to 370+; added Speech & Transcription APIs, Model Fusion, private models, enterprise workspace controls (June 4, 2026).
  - Source: https://openrouter.ai/announcements/all
- **Microsoft Agent Framework** (Multi-Agent Platforms): Renamed from AutoGen 1.0 to reflect merger with Semantic Kernel; v1.0 GA April 2026.
  - Source: https://uvik.net/blog/agentic-ai-frameworks/
- **Stale ⭐ removed**: GPT-5.5 Instant (2026-05-05), Grok 4.3 (2026-05-06), Mistral Medium 3.5 (2026-04-29) — all older than 30 days from 2026-06-08.

---

## Files in Release

- docs/readme.md
- docs/readme.pdf

---
*Generated on 2026-06-07T23:01:20.917Z*
