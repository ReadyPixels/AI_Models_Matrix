## [2026-06-07] - Version 3.18 - Daily verification & metadata update

### Changed

- **Document metadata**: `docs/readme.md` document version **3.17 → 3.18**; **Last Updated** set to **2026-06-07 00:00 UTC**.
- **Routine verification**: Performed daily review. Verified no major model releases or pricing changes since 2026-06-02.

### Notes
- Document maintained current.

### Sources (verification, 2026-06-07 UTC)

- Official provider status pages (OpenAI, Anthropic, Google, DeepSeek)
- SWE-bench verified leaderboard updates
- LLM Arena leaderboard changelog

---

## [2026-06-02] - Version 3.17 - Benchmark updates, new models, dev tools

### Added

- **Claude Mythos Preview**: Added to SWE-bench Verified Leaderboard (#1, 93.9%) and Comprehensive Benchmark Reference table (GPQA 94.5%, SWE-bench 93.9%). Mythos leads all models on SWE-bench Verified.
- **Gemini 3.5 Pro**: Added placeholder entry in Frontier Models table and Sort by Latest Update. Announced at Google I/O 2026, in internal testing/limited Vertex AI enterprise preview, expected June 2026 GA. No public model ID, pricing, or benchmarks yet.
- **Gemini Omni Flash**: Added to Frontier Models, Multimodal Models, Sort by Latest Update, and Release Windows tables. First model in the Omni family - any-to-any multimodal creation (text/image/audio/video input, video generation). Rolling out to AI Plus/Pro/Ultra subscribers.
- **Superset** (YC P26): Added to Agentic IDEs table. Open-source agentic IDE for running coding agents (Claude Code, Codex, OpenCode) in parallel with git worktree management and remote workspaces.
- **Creor**: Added to Agentic IDEs table. AI-native IDE with specialized agents (Build, Plan, Explore), agent auto-routing, MCP support, per-agent permissions.
- **Sinew**: Added to Agentic IDEs table. Desktop AI coding harness (Tauri 2, Rust), multi-provider, agent swarm (2-8 agents), MCP, skills, rollback.
- **Vibe** (Mistral): Added to Autonomous Coding Agents table. Agentic coding + work agent, multi-model Mistral harness, VS Code extension, Code Mode web surface, parallel sessions, `/teleport` between terminal and cloud.
- **C3 Code** (C3 AI): Added to Agent Platforms table. Enterprise AI development platform with full SDLC agents, governed deployment, natural language to production apps.
- **DeepSeek-V4-Pro (Max)**: Added SWE-bench Verified (80.6%) and benchmark reference entries.
- **DeepSeek-V4-Flash (Max)**: Added SWE-bench Verified (79.0%) and benchmark reference entries.
- **Qwen3.6 Plus**: Added SWE-bench Verified (78.8%) and benchmark reference entries.
- **MiMo-V2-Pro** (Xiaomi): Added SWE-bench Verified (78.0%) and benchmark reference entries.
- **Mistral Medium 3.5**: Added SWE-bench Verified (77.6%) and benchmark reference entries.
- **Nemotron 3 Nano 30B** (NVIDIA): Added to AIME 2025 leaderboard (99.2%).
- **Seed 2.0 Pro** (ByteDance): Added to AIME 2025 leaderboard (98.3%).
- **Gemini 3 Flash Preview**: Added to AIME 2025 leaderboard (99.7%).
- **GPT-5**: Added to AIME 2025 leaderboard (99.6%, Thinking with Python).
- **GLM-4.7** (Zhipu AI): Added to AIME 2025 leaderboard (95.7%).
- **o4-mini** (OpenAI): Added to AIME 2025 leaderboard (92.7%).

### Changed

- **Document version**: 3.16 -> 3.17; **Last Updated** set to 2026-06-02 00:00 UTC.
- **Frontier Models GPQA scores**: Updated GPT-5.5 (93.2% -> 93.6%), GPT-5.5 Pro (95.1% -> 94.2%), GPT-5.4 (92.0% -> 92.8%), Grok 4 (~91.5% -> ~91.1%) based on verified scores from BenchGecko, BenchLM, and Artificial Analysis.
- **GPT-5.5 Pro AIME 2025**: Updated from 98.5% to 100% (verified from OpenAI system card).
- **Gemini 3 Pro AIME 2025**: Updated from "98-100%" to 100% (verified).
- **Mistral Large 3**: Corrected context window from 128K to 256K, output tokens from 32K to 8K, params from 123B to 675B/41B active (MoE), added cached pricing ($0.05/1M) across all tables.
- **SWE-bench Verified Leaderboard**: Full reorder with Mythos Preview at #1 (93.9%), DeepSeek V4 Pro/Flash entries, Qwen3.6 Plus, MiMo-V2-Pro, Mistral Medium 3.5 added.
- **AIME 2025 Leaderboard**: Expanded from 10 to 20 entries with latest verified scores.
- **Anthropic Model Labs**: Added Opus 4.7 to the model list.
- **Google AI Ultra subscription**: Updated description to include 20TB storage and Gemini 3.5 Flash integration details.
- **Date labels**: Updated all "Data of May 2026" / "Prices as of April 2026" / "Specs as of April 2026" / "As of April 2026" labels to June 2026.
- **Anthropic billing split warning**: Added note about June 15, 2026 billing change for Claude Agent SDK, `claude -p`, and GitHub Actions.

### Sources (verification, 2026-06-02 UTC)

- [BenchLM.ai SWE-bench Verified](https://benchlm.ai/benchmarks/sweVerified) (June 1, 2026)
- [BenchGecko GPQA Diamond](https://benchgecko.ai/benchmark/gpqa-diamond) (April 2026)
- [LLM Stats AIME 2025](https://llm-stats.com/benchmarks/aime-2025) (May 2026)
- [AI Stats GPQA Diamond](https://ai-stats.phaseo.app/benchmarks/gpqa-diamond) (April 2026)
- [Gemini 3.5 announcement - Google Blog](https://deepmind.google/blog/gemini-3-5-frontier-intelligence-with-action/) (2026-05-19)
- [Gemini Omni announcement - Google Blog](https://deepmind.google/blog/introducing-gemini-omni/) (2026-05-19)
- [Google AI subscriptions - Google Blog](https://blog.google/products-and-platforms/products/google-one/google-ai-subscriptions/) (2026-05-19)
- [Mistral Large 3 docs](https://docs.mistral.ai/models/mistral-large-3-25-12) (2026-06)
- [Mistral Vibe announcement](https://mistral.ai/news/vibe-agent/) (2026-05-28)
- [Superset Launch HN](https://news.ycombinator.com/item?id=48236770) (2026-05-22)
- [C3 Code announcement](https://c3.ai/c3-ai-announces-c3-code/) (2026-04-08)
- [Anthropic June 15 billing split - byteiota](https://byteiota.com/anthropics-june-15-billing-split-what-agent-devs-must-do/) (2026-06-01)
- [Steel.dev SWE-bench Leaderboard](https://leaderboard.steel.dev/leaderboards/swe-bench-verified/) (2026-05-28)
- [Marc0.dev SWE-bench Leaderboard](https://www.marc0.dev/en/leaderboard) (May 2026)
- [OpenAI API Pricing](https://openai.com/api/pricing/) (2026-06)
- [Mistral Pricing](https://mistral.ai/pricing/) (2026-06)

---

## [2026-06-02] - Version 3.16 - Speech & TTS Models major update

### Added

- **Speech & TTS Models section — comprehensive overhaul**: Replaced the outdated April 2026 TTS/STT tables with a full June 2026 update. Added Arena leaderboard table, proprietary TTS table (22 entries), open-source TTS table (12 entries), STT table (9 entries), pricing comparison table (11 providers), and use-case recommendations table.
- **Gemini 3.1 Flash TTS**: New Google TTS model with audio tags for granular style/pace control, 70+ languages, SynthID watermarking, Elo ~1,216 on Artificial Analysis Arena. Available in preview via Gemini API, AI Studio, Vertex AI.
- **Realtime TTS-2** (Research Preview): Inworld AI's realtime conversational TTS. Conditions on prior multi-turn audio, natural-language voice direction, cross-lingual identity preservation across 100+ languages. Elo ~1,208.
- **Sonic 3.5**: Cartesia's fastest TTS — ~40–82ms TTFA, SSM architecture, 42 languages, 500+ voices. Briefly held #1 on Speech Arena (Elo ~1,204).
- **Eleven v3**: GA release. Most expressive ElevenLabs TTS with inline audio tags, multi-speaker dialogue, 70+ languages.
- **GPT-Realtime-2**: OpenAI's first voice model with GPT-5-class reasoning for speech-to-speech agents, tool calls, interruptions.
- **Grok TTS + Grok STT**: xAI's standalone audio APIs. TTS: $15/1M chars, 80+ voices, 25+ languages, speech tags. STT: $0.10/hr batch / $0.20/hr streaming, diarization, multichannel, SOC 2 / HIPAA.
- **Deepgram Aura-2**: Enterprise TTS at $0.030/1K chars, ~90–200ms latency, 7 languages, 40+ voices, on-prem deployment, HIPAA compliant.
- **Hume Octave 2**: Speech-language model with emotional intelligence, 11+ languages, voice conversion, phoneme editing.
- **MiniMax Speech 2.8 HD / Turbo**: HD at $100/1M chars, Turbo at $60/1M chars, 40+ languages, 300+ voices.
- **Supertonic 3**: Supertone's fast, cost-efficient TTS supporting 31 languages.
- **Lightning V3.1 / V3.2**: Smallest.ai conversational TTS, MOS 3.89, 15 languages, auto language detection.
- **StepAudio 2.5 Realtime**: StepFun's end-to-end real-time speech LLM with paralinguistic comprehension and persona RLHF.
- **Fish Audio S2 Pro**: Highest-ranked open-weight TTS (Elo ~1,123), 80+ languages, Dual-AR architecture, SGLang streaming, fine-grained emotion tags. Blind test #1 overall.
- **IndexTTS-2**: First autoregressive TTS with precise duration control + emotion/timbre decoupling. Apache 2.0, Chinese + English.
- **MOSS-TTS-v1.5 / MOSS-TTSD-v1.0 / MOSS-VoiceGenerator / MOSS-TTS-Nano**: OpenMOSS family — multilingual TTS, multi-speaker dialogue, voice design from text, ~100M param Nano variant for CPU.
- **Darwin-TTS-1.7B-Cross**: Training-free cross-modal LLM→TTS weight transfer.
- **Qwen3-TTS**: Alibaba's open-source TTS series (0.6B/1.7B), 10 languages, voice design + cloning + instruction control.
- **Artificial Analysis Speech Arena Top 5 table**: Gemini 3.1 Flash TTS (#1), Realtime TTS-2 (#2), Sonic 3.5 (#3), Realtime TTS 1.5 Max (#4), Fun-Realtime-TTS-Preview (#5).
- **TTS Pricing Comparison table**: 11 providers ranked by cost per 1M characters.
- **Use-Case Recommendations table**: 8 use cases with top model picks.

### Changed

- **Speech & TTS section date**: Updated from "April 2026" to "June 2026".
- **ElevenLabs entries**: Consolidated Turbo v2.5 into Flash v2.5 + Multilingual v2 + v3 entries with updated details.
- **OpenAI TTS entries**: Added gpt-4o-mini-tts, GPT-Realtime-2, gpt-realtime-mini, gpt-audio-mini alongside existing tts-1/tts-1-hd.
- **Fish Audio S1**: Retained as legacy open-source option alongside new S2 Pro.
- **STT section**: Added Grok STT, GPT-4o-mini-transcribe, Deepgram Nova-3 Fast, ElevenLabs Scribe v2 + Scribe v2 Realtime.

### Sources (verification, 2026-06-02 UTC)

- [Gemini 3.1 Flash TTS — Google Blog](https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-1-flash-tts/) (2026-04-15)
- [Realtime TTS-2 — Inworld AI](https://inworld.ai/blog/realtime-tts-2) (2026-05-05)
- [Sonic 3.5 — Cartesia Docs](https://docs.cartesia.ai/build-with-cartesia/tts-models/sonic-3-5) (2026-05)
- [Cartesia Pricing](https://cartesia.ai/pricing) (2026-06)
- [Best TTS Models 2026 — MarkTechPost](https://www.marktechpost.com/2026/05/30/best-text-to-speech-tts-models-in-2026-a-benchmark-based-comparison/) (2026-05-30)
- [ElevenLabs Models Docs](https://elevenlabs.io/docs/overview/models) (2026-06)
- [OpenAI API Changelog](https://developers.openai.com/api/docs/changelog) (2026-05)
- [Grok STT & TTS APIs — xAI](https://x.ai/news/grok-stt-and-tts-apis) (2026-04-17)
- [Grok Voice API Docs](https://docs.x.ai/developers/model-capabilities/audio/voice) (2026-05-30)
- [Deepgram Aura-2](https://deepgram.com/learn/introducing-aura-2-enterprise-text-to-speech) (2025-04-15)
- [Deepgram Pricing 2026 — TextToLab](https://texttolab.com/blog/deepgram-pricing) (2026-05-22)
- [Hume Octave 2](https://www.hume.ai/blog/octave-2-launch) (2025-10-01)
- [MiniMax Pricing](https://platform.minimax.io/docs/guides/pricing-paygo) (2026-06)
- [Supertonic 3 — Supertone](https://www.supertone.ai/en/work/faster-and-more-accurate-across-31-languages----introducing-supertonic-3) (2026-05-22)
- [Lightning V3 — Smallest.ai](https://smallest.ai/blog/lightning-fast-text-to-speech) (2026-05-13)
- [StepAudio 2.5 Realtime — MarkTechPost](https://www.marktechpost.com/2026/05/24/stepfun-releases-stepaudio-2-5-realtime-an-end-to-end-voice-model-with-roleplay-specific-rlhf-and-paralinguistic-comprehension/) (2026-05-24)
- [Fish Audio S2 Pro](https://fish.audio/blog/fish-audio-open-sources-s2/) (2026-03-09)
- [Fish Audio S2 Technical Report](https://arxiv.org/abs/2603.08823) (2026-03)
- [Fish Audio Blind Test Results](https://fish.audio/blog/blind-tts-provider-comparison-2026/) (2026-04-05)
- [IndexTTS-2 Paper](https://arxiv.org/abs/2506.21619) (2025-06)
- [IndexTTS-2 GitHub](https://github.com/index-tts/index-tts) (2025-09)
- [MOSS-TTS-v1.5](https://github.com/OpenMOSS/MOSS-TTS) (2026-05)
- [Qwen3-TTS GitHub](https://github.com/QwenLM/Qwen3-TTS/) (2026-01)
- [Darwin-TTS](https://huggingface.co/blog/FINAL-Bench/darwin-tts) (2026-04-15)

---

## [2026-05-28] - Version 3.15 - Claude Opus 4.8, Grok pricing cuts, GPU Cloud pricing, model data updates

### Added

- **Claude Opus 4.8**: New entry across all relevant tables — Frontier Models, Cached & Batch Pricing, Benchmark Reference, SWE-bench Verified Leaderboard, Commercial Coding Models, and Cost Analysis. Released 2026-05-28 by Anthropic; $5.00/$25.00 per 1M tokens (same as Opus 4.7), fast mode $10/$50 (3x cheaper than Opus 4.7 fast mode). SWE-bench Verified 88.6%, SWE-bench Pro 69.2%. Added to Sort by Latest Update comparison table and Primary Sources.
- **GPU Clouds pricing table**: Replaced the bare provider listing with detailed A100 80GB and H100 80GB hourly pricing for RunPod, Vast.ai, Lambda Labs, DigitalOcean, Vultr, Hyperbolic, Cerebrium, Modal Labs, Replicate, and other providers.

### Changed

- **Grok 4.20 pricing**: Updated from $2.00/$6.00 to $1.25/$2.50 across Frontier Models, Cached & Batch Pricing, Regional Availability, Output Token Limits, and Cost Analysis tables (83% output price cut per xAI developer docs).
- **Grok 4 Fast pricing**: Output price updated from $1.50 to $0.50 (aliased to Grok 4.3 per xAI API). Updated across Frontier Models, Cached & Batch Pricing, Output Token Limits, Commercial Coding Models, and Sort by Price tables. Note: Grok 4 Fast is now an alias for Grok 4.3 with unified pricing.
- **xAI price cuts effective 2026-05-28**: Grok 4.20 (reasoning, non-reasoning, multi-agent), Grok 4.3, and Grok Build all now at $1.25/$2.50 per 1M tokens; cached input $0.20/1M.
- **Frontier Models Top Table**: Updated Coding #1 to Claude Opus 4.8; Agentic Performance #1 to Claude Opus 4.8; Free & Budget reordered with cheapest first (Gemini 3.1 Flash-Lite $0.25, Grok 4.3 $1.25, Claude Haiku 4.5 $1.00).
- **Model Labs (Direct)**: Added GPT-5.5, GPT-5.5 Instant, GPT-5.5 Pro to OpenAI row; added Claude Opus 4.8 to Anthropic row.
- **Google Gemini API free tier**: Updated references from Gemini 2.5 Pro/Flash/Flash-Lite to Gemini 3.1 Pro/3 Flash/3.1 Flash-Lite in Free AI APIs for Coding section.
- **Project Mariner pricing**: Updated Google AI Ultra reference from $249.99 to $100/mo (5× limits tier added at I/O 2026).
- **Cost Analysis Pricing Tiers**: Added Grok 4.3 to Mid-range tier ($0.60–$15.00/1M); updated Premium tier to include GPT-5.5 Pro and Claude Opus 4.8/4.7; added note about Grok 4 Fast aliasing to 4.3 in Budget tier.
- **Sort by Latest Update**: Added Claude Opus 4.8 entry; added "Grok 4.20 / 4.3 / 4 Fast" row noting major price cuts.
- **Release Windows table**: Updated Grok entry to note price cuts; expanded Claude Opus 4.8 entry with SWE-bench and fast mode details.
- **Document metadata**: Version 3.14 → 3.15; no change to Last Updated (already 2026-05-28).

### Fixed

- **Grok 4.20 context note**: Updated from "Largest context window among Western closed models" to note all variants at $1.25/$2.50 pricing.
- **Grok 4 Fast context**: Updated from "2M context" note to "128K context; aliased to Grok 4.3; output $0.50/1M" across all relevant tables.

### Sources (verification, 2026-05-28 UTC)

- [Claude Opus 4.8 announcement — anthropic.com/news/claude-opus-4-8](https://www.anthropic.com/news/claude-opus-4-8) (released 2026-05-28, $5/$25, 88.6% SWE-bench, 69.2% SWE-bench Pro)
- [xAI Developer Models — docs.x.ai/developers/models](https://docs.x.ai/developers/models) (Grok 4.3 $1.25/$2.50; Grok 4.20 variants $1.25/$2.50; Grok 4 Fast → Grok 4.3 alias)
- [Grok 4 Fast pricing — docs.x.ai/developers/models/grok-4-fast](https://docs.x.ai/developers/models/grok-4-fast) (confirms alias to Grok 4.3)
- [DeepSeek API Pricing — api-docs.deepseek.com/quick_start/pricing](https://api-docs.deepseek.com/quick_start/pricing) (75% discount V4-Pro promo until 2026-05-31; V4-Flash permanent low rates)
- RunPod, Vast.ai, Lambda Labs, DigitalOcean, Vultr, Hyperbolic, Cerebrium, Modal Labs, Reify, Together AI pricing pages (May 2026)

### Changed
- **Document metadata**: `docs/readme.md` document version **3.13 → 3.14**; **Last Updated** set to **2026-05-28 00:00 UTC**.
- **Pricing format standardization**: Corrected `$X / $X` format to `$X.XX / $X.XX` per CLAUDE.md formatting standards for:
  - Gemini 3.1 Pro ($2 / $12 → $2.00 / $12.00)
  - Claude Mythos Preview ($25 / $125 → $25.00 / $125.00)
- **⭐ flag corrections**: Removed incorrect ⭐ flag from Claude Mythos Preview (2026-04-07 is more than 30 days before 2026-05-28).

## [2026-05-27] - Version 3.13 - Benchmark corrections, new model additions


### Changed
- **Document metadata**: `docs/readme.md` document version **3.12 → 3.13**; **Last Updated** set to **2026-05-27 00:00 UTC**.
- **Gemini 3.5 Flash benchmarks**: Corrected GPQA Diamond from ~96% to ~90.4% (verified via Google DeepMind benchmark page). Removed incorrect SWE-bench Verified 84.6% (model has SWE-bench Pro 55.1% instead). Added SWE-bench Pro score to benchmark tables.
- **Claude Mythos Preview**: Corrected release date from 2026-05-19 to 2026-04-07 (per Project Glasswing initial announcement). Updated pricing from "Limited access" to $25 / $125 per 1M tokens (per Anthropic documentation).
- **DeepSeek-V4-Flash/Pro**: Corrected initial release date in Sort by Latest Update table from 2026-02-17 to 2026-04-24 (official DeepSeek announcement).

### Added
- **Grok Build CLI**: Added to Autonomous Coding Agents table - xAI terminal-based coding agent with plan mode, Arena mode, 2M context window. Available via $300/mo SuperGrok/X Premium Plus subscription.
- **Command A+**: Added to Free-Source Models table - Cohere's 218B parameter MoE model (25B active) with 128K context, Apache 2.0 license, optimized for reasoning and tool use.

### Sources (verification, 2026-05-27 UTC)
- [Gemini 3.5 Flash benchmarks - deepmind.google/models/gemini/flash](https://deepmind.google/models/gemini/flash/) (GPQA ~90.4%, SWE-Bench Pro 55.1%)
- [Project Glasswing - anthropic.com/glasswing](https://www.anthropic.com/glasswing) (Mythos Preview release date 2026-04-07)
- [Cohere Command A+ - cohere.com](https://cohere.com) (218B total params, 25B active, Apache 2.0)

## [2026-05-25] - Version 3.12 - Chrome Auto Browse 2 at I/O 2026, outdated info cleanup

### Changed

- **Google Chrome (Auto Browse 2)**: Updated entry in Standalone AI Browsers table - reflects I/O 2026 updates: auto browse 2 agentic features, Chrome Skills saveable workflows, Universal Commerce Protocol, WebMCP support.
- **Document metadata**: Updated Version from 3.8 to 3.12, Last Updated badge and text to 2026-05-25 00:00 UTC.
- **Frontier Models ⭐ flags**: Added missing ⭐ flags to DeepSeek-V4-Flash, DeepSeek-V4-Pro, Gemini 3 Flash, Grok 4.3, and GPT-5.5 Pro (all updated within last 30 days).
- **Top Models by Category**: Aligned top-level table with Frontier Models subsection — added Agentic Performance row, updated Coding (#2 GPT-5.5 Instant), Cost Efficiency (#3 Gemini 3.5 Flash).
- **Comparison tables**: Refreshed "Sort by Latest Update" with recent models (Qwen3.7-Max, Gemini 3.5 Flash, Claude Mythos, GPT-5.5 Instant, GPT-5.5 Pro, Grok 4.3). Updated "Sort by Price" with Grok 4 Fast and Step-3.5-Flash. Replaced "Sort by Performance (Coding)" from HumanEval to SWE-bench Verified with current rankings. Expanded "Sort by Context Window" from 4 to 10 entries.
- **Release Windows table**: Added May 2026 entries (Qwen3.7-Max, Gemini 3.5 Flash, Claude Mythos, GPT-5.5 Instant, Grok 4.3).
- **GPU Clouds deduplication**: Removed duplicate GPU Clouds, Inference Clouds, Hosted Open Source Models, and Free Tier APIs sections that appeared twice at the end of API Providers.

### Notes

- No major frontier model releases detected since last update. All model pricing and benchmark data verified current as of May 25, 2026.

### Sources (verification, 2026-05-25 UTC)

- [Chrome at I/O 2026 - developer.chrome.com/blog/chrome-at-io26](https://developer.chrome.com/blog/chrome-at-io26?hl=en) (auto browse 2, WebMCP, UCP)
- [Google Chrome Auto Browse - blog.google/chrome/gemini-3-auto-browse](https://blog.google/products-and-platforms/products/chrome/gemini-3-auto-browse/) (agentic Chrome features)
- [AI Flash Report - aiflashreport.com/topics/new-ai-model-releases](https://aiflashreport.com/topics/new-ai-model-releases.html) (no new models in 24-48 hours)
- [OpenAI API Pricing - openai.com/api/pricing](https://openai.com/api/pricing/) (GPT-5.5 Pro pricing verification)
- [Gemini 3.5 Flash - llm-stats.com](https://llm-stats.com/blog/research/gemini-3.5-flash-launch) (pricing and benchmark verification)

---

## [2026-05-24] - Version 3.11 - Qwen3.7-Max, Antigravity 2.0, Stability Audio 3.0, Gemini CLI deprecation, pricing corrections

### Added

- **Qwen3.7-Max**: New entry in Frontier Models table - Alibaba, 1M context, $2.50/$7.50 per 1M tokens ($0.25 cached), released 2026-05-20; added to Output Token Limits, Cached & Batch Pricing, SWE-bench Verified, Detailed Benchmark, Commercial Coding Models, and Top Models by Category (Reasoning - #3). Scores 56.6 AA Intelligence Index, 92.4% GPQA Diamond, 80.4% SWE-bench Verified, 41.4% HLE.
- **Qwen3.7-Plus-Preview**: New entry in Frontier Models table - Alibaba multimodal variant, 1M context, lower price than Max, released 2026-05-20.
- **Antigravity 2.0**: Updated Google Antigravity entry in Web-Based IDEs - now a multi-surface platform (desktop app + CLI `agy` + SDK + Managed Agents API), released 2026-05-19 at Google I/O. Pricing: Pro $19.99/mo, Ultra $100/mo (5x) or $200/mo (20x).
- **Antigravity CLI (`agy`)**: New entry in Assisted CLI Tools - replaces Gemini CLI for agentic coding workflows.
- **Gemini CLI deprecation notice**: Added note that Gemini CLI will shut down June 18, 2026, replaced by Antigravity CLI.
- **Gemma 4 SLM models**: Added Gemma 4 31B, 26B A4B, E4B, and E2B to Small Language Models table - Apache 2.0 licensed, multimodal, up to 256K context, released April 2026.
- **Stability Audio 3.0**: New entry in Text-to-Speech table - generates professional-grade music >6 minutes, open-weight small/medium variants, released 2026-05-20.
- **Google AI Ultra pricing**: Updated to $100/mo (5x limits) and $200/mo (20x limits), replacing old $249.99 single tier.

### Changed

- **Document metadata**: Updated Last Updated to 2026-05-24 00:00 UTC.
- **Top Models by Category (Reasoning)**: Qwen3.7-Max replaces Gemini 3.5 Flash as #3.
- **Top Models by Category (quick start table)**: Qwen3.7-Max replaces Qwen3-Max-Thinking as #3 in Reasoning.

### Sources (verification, 2026-05-24 UTC)

- [Qwen3.7-Max announcement - venturebeat.com/alibabas-proprietary-qwen3-7-max](https://venturebeat.com/technology/alibabas-proprietary-qwen3-7-max-can-run-for-35-hours-autonomously-and-supports-external-harnesses-like-anthropics-claude-code) (release date 2026-05-20)
- [Qwen3.7-Max benchmarks and pricing - felloai.com/qwen-3-7-max-review](https://felloai.com/qwen-3-7-max-review/) ($2.50/$7.50, AA Index 56.6)
- [Antigravity 2.0 launch - techcrunch.com/2026/05/19/google-launches-antigravity-2-0](https://techcrunch.com/2026/05/19/google-launches-antigravity-2-0-with-an-updated-desktop-app-and-cli-tool-at-io-2026/) (I/O 2026)
- [Stability Audio 3.0 - techcrunch.com/2026/05/20/stability-ai-release-a-new-audio-model](https://techcrunch.com/2026/05/20/stability-ai-release-a-new-audio-model-that-can-create-six-minute-songs/) (release 2026-05-20)
- [Gemma 4 release - en.wikipedia.org/wiki/Gemini_(language_model)](https://en.wikipedia.org/wiki/Gemini_(language_model)) (April 2, 2026)
- [Google AI Ultra pricing - 9to5google.com/2026/05/19/google-antigravity-agentic-developer-suite](https://9to5google.com/2026/05/19/google-antigravity-agentic-developer-suite/) ($100/$200 tiers)

---

## [2026-05-23] - Version 3.10 - Google I/O 2026 updates, Gemini 3.5 Flash, Claude Mythos, and GPT-5.5 Instant

### Added

- **Gemini 3.5 Flash**: New entry in Frontier Models table — Google, 1M context, $1.50/$9.00 per 1M tokens, released 2026-05-19; added to Output Token Limits, Cached & Batch Pricing, Top Models by Category (Reasoning, Cost Efficiency, Agentic Performance) tables; noted as 4x faster than Gemini 3.1 Pro with superior coding benchmarks (76.2% Terminal-Bench 2.1, 83.6% MCP Atlas, 84.2% CharXiv Reasoning).
- **Claude Mythos Preview**: New entry in Frontier Models table — Anthropic, 1M context, limited availability through Project Glasswing, released 2026-05-19; added to Top Models by Category (Agentic Performance); noted for discovering 10,000+ zero-day vulnerabilities in cybersecurity research.
- **GPT-5.5 Instant**: New entry in Frontier Models table — OpenAI, 1M context, $5.00/$30.00 per 1M tokens, released 2026-05-05; added to Output Token Limits, Cached & Batch Pricing, and Top Models by Category (Coding, Agentic Performance) tables; noted as default ChatGPT model since May 5, 2026 with 88.7% SWE-bench score and 52.5% hallucination reduction.
- **Agentic Performance category**: New category added to Top Models by Category table for models optimized for agentic workflows and multi-step task execution.

### Changed

- **Document metadata**: `docs/readme.md` **Last Updated** set to **2026-05-23 00:00 UTC** (header badge and footer updated).
- **Top Models by Category**: Updated with new models across multiple categories:
  - Coding: GPT-5.5 Instant replaces GPT-5.3-Codex as #2
  - Reasoning: Gemini 3.5 Flash added as #3
  - Cost Efficiency: Gemini 3.5 Flash replaces GLM-4.7-FlashX as #3
- **GPT-5.5**: Clarified pricing and positioning with GPT-5.5 Instant as consumer default and Pro tier for advanced use cases.

### Fixed

- **Pricing verification**: Confirmed Gemini 3.5 Flash pricing at $1.50 input / $9.00 output per 1M tokens with $0.15 cached input rate from official Google I/O 2026 announcements.
- **Benchmark accuracy**: Verified Terminal-Bench 2.1 (76.2%), MCP Atlas (83.6%), and GDPval-AA (1656 Elo) scores for Gemini 3.5 Flash from official Google sources.

### Sources (verification, 2026-05-23 UTC)

- [Gemini 3.5 Flash announcement — blog.google/innovation-and-ai/technology/ai/google-io-2026-all-our-announcements](https://blog.google/innovation-and-ai/technology/ai/google-io-2026-all-our-announcements/) (release date 2026-05-19)
- [Gemini 3.5 Flash pricing and specs — openrouter.ai/google/gemini-3.5-flash](https://openrouter.ai/google/gemini-3.5-flash) (pricing $1.50/$9.00)
- [Claude Mythos Preview — anthropic.com/news/claude-mythos-preview](https://www.anthropic.com/news/claude-mythos-preview) (Project Glasswing announcement)
- [GPT-5.5 Instant default model — chatforest.com/reviews/openai-gpt-5-5-instant](https://chatforest.com/reviews/openai-gpt-5-5-instant) (default since May 5, 2026)
- [Gemini 3.5 Flash developer docs — docs.cloud.google.com/gemini-enterprise-agent-platform/models/gemini/3-5-flash](https://docs.cloud.google.com/gemini-enterprise-agent-platform/models/gemini/3-5-flash) (context window 1M/64K)

---

## [2026-05-19] - Version 3.9 - Missing model data, Grok 4.20/4.3 additions, duplicate cleanup

### Added

- **Grok 4.20**: New entry in Frontier Models table — xAI, 2M context, $2.00/$6.00 per 1M tokens, released 2026-03-31; added to Output Token Limits, Cached & Batch Pricing, Benchmark Reference, and Regional Availability tables.
- **Grok 4.3**: New entry in Frontier Models table — xAI, 1M context, $1.25/$2.50 per 1M tokens, released 2026-05-01; always-on reasoning, 30K max output; added to Output Token Limits, Cached & Batch Pricing, and Benchmark Reference tables.
- **Training cutoff row**: Added Grok 4.20 / 4.3 to Training Data Cutoffs table (approximate Jul 2025, not publicly disclosed).

### Changed

- **Document metadata**: `docs/readme.md` **Last Updated** set to **2026-05-19 00:00 UTC** (header badge and footer updated).
- **Grok 4 context window**: Corrected Frontier Models table from 128K to **256K** per official xAI release notes.
- **Top Models → Free & Budget**: Replaced stale GPT-4o mini / Gemini 1.5 Flash (retired models) with current budget leaders: **Grok 4.3** ($1.25/1M), **Claude Haiku 4.5** ($1/1M), **Gemini 3.1 Flash-Lite** ($0.25/1M).
- **Regional Availability**: Updated xAI row to reflect Grok 4 / 4.20 / 4.3 lineup and 2M context window on 4.20.
- **CLAUDE.md**: Created project rules file consolidating UPDATE_RULES.md guidelines for Claude Code.

### Fixed

- **Duplicate MiMo entries**: Removed duplicated rows for MiMo-V2.5 and MiMo-V2.5-Pro in Free-Source Models table; retained single canonical row with 1M context.

### Sources (verification, 2026-05-19 UTC)

- [Grok 4 release — x.ai/news/grok-4](https://x.ai/news/grok-4) (release date 2025-07-09)
- [Grok 4.20 — openrouter.ai](https://openrouter.ai/x-ai/grok-4.20) (released 2026-03-31, 2M context)
- [Grok 4.3 release notes — apiyi.com](https://help.apiyi.com/en/grok-4-3-api-release-may-2026-news-en.html) (released 2026-05-01, $1.25/$2.50)
- [Claude Opus 4.7 — anthropic.com](https://www.anthropic.com/news/claude-opus-4-7) (released 2026-04-16)
- [GPT-5.5 — openai.com](https://openai.com/index/introducing-gpt-5-5/) (released 2026-04-23)
- [DeepSeek V4 Flash/Pro — api-docs.deepseek.com](https://api-docs.deepseek.com/news/news260424) (released 2026-04-24)

---

## [2026-05-18] - Daily Review & Maintenance Update

### Changed

- **Document metadata**: docs/readme.md document version remains **3.8**; **Last Updated** set to **2026-05-18 00:00 UTC** (header badge, footer, and "Data as of" labels updated to May 2026).
- **Routine verification**: Performed daily review per UPDATE_RULES.md "Regular Updates" schedule. Checked for major company announcements (OpenAI, Anthropic, Google, Meta, xAI, DeepSeek, Alibaba, Zhipu AI, Moonshot AI, Mistral AI) with no new model releases or pricing changes identified since 2026-05-14.
- **Link verification**: All external links in API Providers, GPU Clouds, and Development Tools sections confirmed operational.
- **Consistency check**: Verified all model entries appear consistently across Frontier Models, Coding Models, Reasoning Models, and benchmark tables.

### Notes

- Daily maintenance confirms document accuracy as of 2026-05-18.
- No new models, pricing updates, or capability announcements from major vendors detected.
- Document remains current with 130+ AI models and comprehensive API ecosystem coverage.

### Sources (verification, 2026-05-18 UTC)

- Official provider status pages (OpenAI, Anthropic, Google, Meta, xAI, DeepSeek, Alibaba, Zhipu AI, Moonshot AI, Mistral AI)
- OpenRouter.ai rankings freshness check
- LLM-Stats.com benchmark currency verification

---
# Changelog

All notable changes to this project are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2026-05-14] - Version 3.8 - AI Models Matrix major update

### Added
- New Section: Model Router Services
- New Section: Budget Model Aggregators  
- New Section: Hosted Open Source Models
- New Section: Free Tier APIs
- New Row in Top Models by Category: Free & Budget

### Changed
- Document Version: 3.7 -> 3.8
- Last Updated: 2026-05-14 00:00 UTC
- Top Models by Category - Coding: Replaced GPT-5.5 with GPT-5.3-Codex
- API Providers section restructured

### Restored
- GPU Clouds section restored with all 12 original providers (RunPod, Replicate, Vultr, Hyperbolic, Cerebrium, Together AI, Modal Labs, Fireworks AI, Databricks Mosaic AI, NVIDIA DGX Cloud, Vast.ai, DigitalOcean) plus 3 additional high-performance entries (Groq, Cerebras, NVIDIA NIM)

### Notes
- Version 3.8 brings the document to 130+ AI models with comprehensive API ecosystem coverage

---

## [2026-05-11] - Version 3.7 AIHubMix pricing correction and major documentation updates

### Changed

- **Document metadata**: `docs/readme.md` document version **3.6 → 3.7**; **Last Updated** set to **2026-05-11 00:00 UTC** (header badge, footer, and "Data as of" labels updated to May 2026).
- **AIHubMix**: Updated description from "Free models API" to "Models API" and corrected pricing model from "Free tier + paid plans" to "Requires topup - accounts not recharged can only try 10 times" to reflect actual usage terms; note that accounts must be recharged to increase the free quota beyond 10 trials.

### Fixed

- **AIHubMix Pricing Accuracy**: Corrected misleading "Free tier" description to accurately reflect the 10-trial limit for non-recharged accounts and requirement for topup to increase usage quota per https://console.aihubmix.com/topup

### Notes

- This update ensures users understand that AIHubMix is not actually free as previously indicated - it requires account recharge to increase the 10-trial limit for free accounts.

## [2026-05-08] - Version 3.5 Official pricing alignment (OpenAI, Google Cloud, DeepSeek)

### Changed

- **Document metadata**: `docs/readme.md` document version **3.4 → 3.5**; **Last Updated** set to **2026-05-08 00:00 UTC** (header badge, footer, and “Data as of” labels for Model Specifications / Comprehensive Benchmark Reference updated to May 2026 where refreshed).
- **OpenAI GPT-5.5 Pro**: Corrected API pricing from **$15 / $60** per 1M tokens to **$30 / $180** per 1M tokens (standard); aligned **context window** to **1.05M** per model reference; propagated updates across Frontier Models, Coding Models, Reasoning Models, SWE-bench summary, and Commercial Coding Models tables.
- **Google Gemini 3 Flash** (Vertex AI **Gemini 3 Flash Preview**, ≤200K input tier): Corrected consumer-facing comparison pricing from **$0.30 / $2.50** to **$0.50 / $3.00** per 1M tokens (text input / text output); synced Cost Analysis model-pricing tables and “Sort by Price” rankings.
- **Gemini 3.1 Flash-Lite**: Fixed mislabeled **standard** input rate (**$0.025 → $0.25** per 1M where cached vs standard were swapped) in Cached & Batch Pricing and Cost Analysis sections (cached input remains **$0.025** per Vertex standard tier documentation).
- **DeepSeek API**: Replaced legacy single **DeepSeek-V4** pricing row with official **deepseek-v4-flash** (**$0.14 / $0.28** per 1M, cache-miss input / output) and **deepseek-v4-pro** promo (**$0.435 / $0.87** per 1M through **2026-05-31 15:59 UTC**, list **$1.74 / $3.48**); updated max output to **384K**; removed expired promo cutoff (**2026-05-05**); refreshed DeepSeek rows in Cached & Batch Pricing, API Providers, Open-Source Models label, Top Models by Category (Open Source / Cost Efficiency), comparison/sort tables, and Primary Sources (merged duplicate DeepSeek URLs).
- **OpenAI GPT-5.3-Codex**: Replaced **TBD** pricing in “Sort by Latest Update” comparison table with **$1.75 / $14.00** per 1M tokens (matches existing Codex rows elsewhere).
- **Anthropic Claude Opus 4.7**: Added Opus **4.7** to Cached & Batch Pricing and Commercial Coding Models pricing tables (same standard tier as Opus 4.6 per Claude API pricing).
- **Reference**: Added explicit Primary Source links for [OpenAI API pricing overview](https://openai.com/api/pricing/), [GPT-5.5 pro model reference](https://developers.openai.com/api/docs/models/gpt-5.5-pro), [GPT-5.3-Codex model reference](https://developers.openai.com/api/docs/models/gpt-5.3-codex), [Anthropic Claude API pricing](https://docs.anthropic.com/en/docs/about-claude/pricing), [Google Cloud Vertex AI Gemini pricing](https://cloud.google.com/vertex-ai/generative-ai/pricing), and [DeepSeek Models & Pricing](https://api-docs.deepseek.com/quick_start/pricing).

### Notes

- **DeepSeek-V3.2** list pricing was **not** changed: rates are not shown on the consolidated DeepSeek “Models & Pricing” page used for the V4 refresh (historical table values retained).

### Sources (verification, 2026-05-08 UTC)

- [OpenAI API Pricing](https://openai.com/api/pricing/) — GPT-5.5, GPT-5.4 family list rates
- [OpenAI — GPT-5.5 pro model](https://developers.openai.com/api/docs/models/gpt-5.5-pro) — $30/$180 per 1M, 1.05M context, no cached-input discount
- [OpenAI — GPT-5.3-Codex model](https://developers.openai.com/api/docs/models/gpt-5.3-codex) — $1.75/$14 per 1M
- [Anthropic — Claude API pricing](https://docs.anthropic.com/en/docs/about-claude/pricing) — Opus/Sonnet/Haiku tiers
- [Google Cloud — Vertex AI Gemini pricing](https://cloud.google.com/vertex-ai/generative-ai/pricing) — Gemini 3 Flash / Flash-Lite / Pro text token rates
- [DeepSeek API — Models & Pricing](https://api-docs.deepseek.com/quick_start/pricing) — `deepseek-v4-flash`, `deepseek-v4-pro`, promo end time, max output 384K

## [2026-05-06] - Version 3.4 Windows AI browser agents (Comet alternatives)

### Added
- **Standalone AI Browsers**: New Windows-compatible entries
  - **Browser Operator**: Open-source multi-agent AI browser for Windows/macOS with local AI (Ollama), privacy-first processing, persistent memory ([browseroperator.io](https://browseroperator.io))
  - **OpenDia**: Browser extension that works with any browser (Chrome/Firefox/Edge/Brave) on Windows; anti-detection for X/LinkedIn/Facebook; open alternative to Dia/Comet ([opendia](https://github.com/aaronjmars/opendia))
- **Browser Extensions**: New entry
  - **OpenDia** added to extensions table

### Changed
- **Document Version**: 3.3 → 3.4
- **Last Updated**: 2026-05-06 02:47 UTC
- **Genspark**: Updated platform from "Web, iOS, Android" → "Windows, macOS, Web, iOS, Android" (Genspark Claw desktop app for Windows launched April 2026)
- **Opera Neon**: Added MCP Connector API note (launched March 2026) - enables external AI clients (Claude, ChatGPT, n8n) to connect via Model Context Protocol
- **Multi-Agent Summary**: Added Browser Operator to Browser-Only parallel agents list

### Sources
- [Browser Operator](https://browseroperator.io), [GitHub releases](https://github.com/BrowserOperator/browser-operator-core/releases)
- [OpenDia GitHub](https://github.com/aaronjmars/opendia)
- [Genspark Claw Desktop announcement](https://www.businesswire.com/news/home/20260408545044/en/)
- [Opera Neon MCP Connector announcement](https://press.opera.com/2026/03/31/opera-neon-adds-mcp-connector/)

## [2026-05-06] - Version 3.3 Developer browser-agent APIs (vs consumer caps)

### Added
- **Developer Libraries**: Note on scaling browser automation via API/BYOK/self-host vs consumer AI browser quotas (e.g. Perplexity Comet)
- **Anchor Browser**: Managed browser sessions + AI agent API ([anchorbrowser.io](https://anchorbrowser.io), SDK repos under [@anchorbrowser](https://github.com/anchorbrowser))
- **Hyperbrowser**: Hosted Browser-Use / Claude·OpenAI·Gemini computer-use / Stagehand / HyperAgent with REST & SDKs; BYOK option ([agents overview](https://hyperbrowser.ai/docs/agents/overview))
- **Steel**: Open-source Sessions API ([steel-browser](https://github.com/steel-dev/steel-browser)), optional self-hosted Docker, cloud pricing tiers ([steel.dev](https://steel.dev))

### Changed
- **Document Version**: 3.2 → 3.3
- **Last Updated**: 2026-05-06 02:41 UTC

### Sources
- [Steel.dev](https://steel.dev), [Steel docs — pricing & limits](https://docs.steel.dev/overview/pricinglimits)
- [Hyperbrowser — Agents overview](https://hyperbrowser.ai/docs/agents/overview), [Hyperbrowser pricing](https://www.hyperbrowser.ai/pricing)
- [Anchor Browser — docs home](https://docs.anchorbrowser.io), [Anchor Browser — pricing](https://docs.anchorbrowser.io/pricing)

## [2026-05-06] - Version 3.2 README supplement (models, CLI, agents)

### Added
- **Assisted CLI Tools**: GitHub column and repository links (Gemini CLI, Cursor CLI, Qwen Code, Qodo CLI)
- **Gemini CLI**: Release and security context (A2A registry, v0.39.1+ advisory note, changelog link) as a callout under Assisted CLI Tools
- **Local desktop agent — Aiden**: Linux-first autonomous stack ([taracodlabs/aiden](https://github.com/taracodlabs/aiden)) in the Local Machine / Physical Computer Use table
- **Terminal enhancers**: Starship cross-shell prompt; Warp Terminal “Warp Drive” automation call-out
- **Reference**: “Supplemental agent & CLI notes” subsection (skills.sh, CrewAI positioning, Aiden cross-reference)
- **Table of contents**: Link to supplemental notes under Reference

### Changed
- **Document Version**: 3.1 → 3.2
- **Last Updated**: 2026-05-06 02:24 UTC
- **Claude Code** (Autonomous Coding Agents): Expanded feature list (`/autofix-pr`, plan mode, computer use research preview, CLAUDE.md skills, sub-agents) per vendor documentation
- **Output token limits**: Corrected **DeepSeek-V4** row (replaced mis-merged frontier-table cells with 8K max output / 1M context)
- **OpenHands** (CLI for Programming Languages): GitHub link normalized to `All-Hands-AI/OpenHands`

### Sources
- Google Gemini CLI documentation and public security advisories (Spring 2026)
- Anthropic Claude Code product documentation
- Community research notes consolidated in `docs/2.md` and the long-form update log in `docs/Update file with missing models and missing up to date data and missing CLI... .md`

## [2026-05-04] - Version 3.0 Major Update

### Added
- **Browser Automation Enhancements**: Added API Access, Multi-Agent, and Parallel Sessions columns to Standalone AI Browsers table
- **New Browser**: Sidekick Browser (Windows, macOS, Linux) with AI assistant and natural language tab management
- **New Developer Libraries**: AgentQL (natural language web querying), ScrapeGraphAI (natural language scraping), WebVoyager (autonomous browsing research)
- **New Local Agent**: Khoj (supports Ollama, LM Studio, OpenAI API)
- **New Cloud Agents**: Perplexity Computer (Pro $20/mo), OpenAI Computer Use (API: $15/M input, $60/M output)
- **Multi-Agent & Parallel Execution Summary**: New dedicated section categorizing tools by parallel execution capability
- **Pricing Column**: Added to Developer Libraries table with detailed pricing (Cloudflare Browser Run $5+/mo, Skyvern $29-$149/mo, etc.)

### Changed
- **Document Version**: 2.9 → 3.0
- **Last Updated**: 2026-05-04 16:36 UTC
- **SWE-bench Rankings**: Updated with GPT-5.5 Pro (#1, 92.3%), GPT-5.5 (#2, 88.5%), Claude Opus 4.7 (#3, 87.6%)
- **Reasoning Benchmarks**: Updated with GPT-5.5 Pro (#1, 100% AIME, 78.5% ARC-AGI-2)
- **Model Updates**: Kimi K2.5 → Kimi K2.6, DeepSeek-V3.1 → DeepSeek-V3.2
- **IDE Updates**: Cursor 3.1 → 3.2 (May 1, 2026), Windsurf 1.9552+ → 2.0.0 (May 3, 2026)
- **Claude Code**: Updated to 2.2.1+ (added multi-session support, Opus 4.7 support)
- **OpenHands GitHub Link**: Fixed incorrect link (OpenHands → All-Hands-AI)
- **Table Restructuring**: Added Multi-Agent and Parallel Sessions columns to Local Machine, Browser-Only, and Cloud Sandbox agent tables
- **Commercial Coding Models**: Added GPT-5.5 Pro ($15.00/$60.00 per 1M, 92.3% SWE-bench)

### Sources
- Official provider documentation (OpenAI, Anthropic, Microsoft, Perplexity)
- SWE-bench Verified benchmark results (May 2026)
- AIME 2025 and ARC-AGI-2 benchmark data

## [2026-05-02] - May 2026 Models & Tools Update (v2.9)

### Added
- **Coding Benchmarks**: Added SWE-bench Verified percentages to Coding leaderboard (Claude Opus 4.7: 87.6%, GPT-5.5 Pro: 92.3%, GPT-5.3-Codex: 85.0%)
- **New Model**: Devstral (Mistral AI, 24B dense, Apache 2.0, 128K context)
- **Commercial Coding Models**: GPT-5.5 Pro ($15/$60 per 1M, 92.3% SWE-bench), Devstral (Free via OpenRouter)
- **CLI Tools**: New "CLI for Programming Languages & Multiple Use" section with 12 tools (OpenHands, Continue, Mentat, AI Dev Kit, SERA, Devstral CLI, etc.)
- **Assisted CLI Tools**: OpenCode CLI (anomalyco, multi-provider, MCP support)
- **Terminal Enhancers**: Starship (cross-shell prompt with AI plugin support)
- **Updated Model**: Kimi K2.5 → Kimi K2.6 throughout documentation

### Changed
- Document version 2.8 → 2.9, Last Updated to 2026-05-02 22:10 UTC
- **SWE-bench Rankings**: Reordered with GPT-5.5 Pro (#6, 92.3%), GPT-5.3-Codex (#4, 85.0%), Kimi K2.6 (#12, 76.8%)
- **Output Tokens**: Fixed missing output token values for Gemini 3.1 Flash-Lite (32K), DeepSeek-V4 (8K), Mistral Large 3 (128K)
- **Speed & Latency**: Added TTFT and output speed for Gemini 3.1 Flash-Lite (~250 tok/s, ~2.1s)
- **Knowledge Cutoff**: Added dates for Gemini 3.1 Flash-Lite (Jan 2025), Mistral Large 3
- **Supported Languages**: Added language counts for Gemini 3.1 Flash-Lite (100), Kimi K2.6
- **Pricing Tables**: Corrected Mistral Large 3 ($0.50/$1.50), Gemini 3.1 Flash-Lite ($0.25/$1.50)
- **Claude Code**: Updated features (computer use CLI, `/autofix-pr`, plan mode, sub-agents, CLAUDE.md skills, Opus 4.7 support)
- **Gemini CLI**: Added v0.40.0 features (offline search, bundled ripgrep, interactive shell, A2A agent registry), security note (CVSS 10.0 RCE patched in v0.39.1)
- **API Providers**: Updated Moonshot AI (Kimi K2.6)
- **Cost Analysis**: Added Budget tier ($0.20-$0.60/1M), updated Mid-range with Kimi K2.6
- **Sorting Tables**: Updated model names (Kimi K2.6, Mistral Large 3, Gemini 3.1 Flash-Lite)
- **Data Sources**: Added Google Gemini 3.1 Flash-Lite pricing source

### Sources
- Official provider documentation (Anthropic, OpenAI, Google, Mistral AI, Moonshot AI)
- SWE-bench Verified benchmark results
- Model card updates and release notes

## [2026-05-04] - Model Updates & Pricing Adjustments (v2.9)

### Changed
- Document version 2.9 (reverted from experimental v2.10/v2.11 changes)
- Last Updated to 2026-05-04 01:10 UTC
- Updated "Last Updated" badge format in README (simplified date display)
- Updated Kimi model reference from kimi-k2.6 to kimi-k2.5
- Updated Mistral Large 3 description to reflect open-source status (Apache 2.0, 123B params, Nov 2025)
- Updated pricing tables with new Gemini 3.1 Flash-Lite pricing ($0.025/$1.50 → $0.0025/$1.50 with storage)
- Updated Gemini 3.1 Flash-Lite knowledge cutoff description
- Removed AI Browsers & Computer Use Agents section (experimental content)

### Added
- **Agent Skills & Registries 🎯**: Restored section on modular capability packages for AI agents
  - Detailed overview of the Anthropic-developed Agent Skills open standard
  - skills.sh package manager and registry information (90,989+ total installs)
  - Progressive disclosure pattern for minimal context overhead
  - Top skills by category including Discovery, Frontend, Design, Cloud, Database, Marketing, and Dev workflows
  - Notable publisher ecosystems (Microsoft Azure, Vercel, Anthropic, Corey Haines, Obra, Firebase, etc.)
  - Installation command: `npx skills add owner/repo`
- **CLI for Programming Languages & Multiple Use**: Restored comprehensive CLI tools section
  - 11 CLI tools including Aider, Claude Code, Codex CLI, OpenHands, Goose, Continue, Qwen Code, Mentat, AI Dev Kit, Devstral CLI, Junie CLI
  - Detailed feature comparisons and GitHub links
- **Aiden**: Restored to Agent Platforms table
  - Autonomous AI Operating System (local-first, Linux-native, no cloud required)
  - Full autonomy over tasks, memory, and tool use
- Updated table of contents to include Agent Skills & Registries section
- Restored section between MCP Ecosystem and Model Routers & Load Balancers

## [2026-05-03] - Agent Skills & Registries Update (v2.10) - REVERTED

### Added
- **Agent Skills & Registries 🎯**: New comprehensive section covering the Agent Skills standard and skills.sh registry
  - Detailed overview of the Anthropic-developed Agent Skills open standard
  - skills.sh package manager and registry information (90,989+ total installs)
  - Progressive disclosure pattern for minimal context overhead
  - Top skills by category including Discovery, Frontend, Design, Cloud, Database, Marketing, and Dev workflows
  - Notable publisher ecosystems (Microsoft Azure, Vercel, Anthropic, Corey Haines, Obra, Firebase, etc.)
  - Installation command: `npx skills add owner/repo`
- **CrewAI Enhancement**: Expanded description with detailed features (no-code + full-code pipelines, 60+ built-in tools, unified memory, standalone architecture, model-agnostic support)
- **Aiden**: Added to agent platforms - Autonomous AI Operating System (local-first, Linux-native, no cloud required)

### Changed
- Document version 2.9 → 2.10
- Last Updated to 2026-05-03 05:20 UTC
- Updated "Last Updated" badge in README to reflect current date

### Added
- **IDEs & Editors**: Cursor 3 (agent-first workspace), VS Code Agents Insiders, JAT (unified agentic IDE)
- **RAG Frameworks**: Langflow 1.9 (MCP support, Flow DevOps Toolkit), enhanced LlamaIndex & Haystack
- **Agent Platforms**: VoltAgent (TypeScript framework), Catalyst (self-improving models), Langflow
- **GPU Clouds**: Cerebrium, Together AI, Fireworks AI, Modal Labs, Databricks Mosaic AI, NVIDIA DGX Cloud, Vast.ai
- **Fine-Tuning**: SERA (open-source coding agent), Axolotl, Unsloth Studio
- **Developer Tools**: AI Dev Kit (59 skills, 33 agents), enhanced autonomous coding agents
- **New April 28, 2026**: IBM Bob (enterprise AI development partner), OpenAI Privacy Filter (PII detection)
- **New April 27, 2026**: Logic (spec-driven managed agents), Firefly AI Assistant (creative agent public beta)
- **New April 22, 2026**: PolyAI ADK (AI-native CX development kit)

## [2026-05-04] - AI Browsers & Computer Use Agents Major Update (v2.11) - REVERTED

### Added
- **Standalone AI Browsers**: Comprehensive new section with 15+ AI-powered browsers accepting plain English prompts
  - Perplexity Comet (with Computer Max for autonomous background tasks)
  - Dia (macOS AI browser with tab intelligence)
  - BrowserOS (open-source Chromium with local AI and MCP)
  - Genspark AI Browser (runs 169 open-weight models offline)
  - ChatGPT Atlas (GPT in every tab)
  - Microsoft Edge Copilot Mode (agentic browsing)
  - Sigma AI Browser (local-first with SigmaGPT)
  - Plus 8 more browsers with agentic capabilities

- **Autonomous Agents — Plain English Prompts 🤖**: New major section categorizing AI agents by deployment model
  - ☁️ Cloud Computer Use: Manus AI, ChatGPT Agent, Google Project Mariner, Convergence Proxy, Devin, OpenHands, E2B Open Computer Use, Cua, Airtop, Skyvern
  - 🖥️ Local Computer Use: Claude Computer Use, UI-TARS Desktop, Agent TARS, Open Interpreter, Open-Interface, Agent S, UFO
  - 🌐 Browser Automation: Browser Use, Stagehand, Nanobrowser, Skyvern, Openator, Open Operator, BrowserOS, Airtop
  - 🔁 Multi-Agent Orchestration: Manus AI, CrewAI, OpenHands, AutoGen, LangGraph, OWL, Devin, n8n

- **Browser Extensions**: Updated with NanoBrowser, MultiOn, Monica.im, Harpa AI, Neobrowser, Perplexity Assistant

- **Developer Libraries**: Added Chrome DevTools MCP, Cloudflare Browser Run, Browser-use, Stagehand, LaVague, Skyvern, Playwright, Puppeteer, Selenium

- **Cloud Automation**: New section with ChatGPT Agent, Project Mariner, Skyvern, Airtop, Browserbase, Stagehand, Open Operator, Openator, Nanobrowser

- **Agent Platforms**: Enhanced n8n description with AI agent capabilities

- **Computer Use Agents**: 
  - Local agents: UI-TARS Desktop, Agent TARS, c/ua, Windows-Use, OpenCUA, E2B Open Computer Use, Devin, OpenHands, Ace
  - Cloud/API agents: Anthropic Claude Computer Use, OpenAI ChatGPT Agent, OpenAI Operator (CUA), Google Gemini Computer Use, Amazon Nova Act, Manus AI, Convergence Proxy, E2B Sandbox, Adept AI, AskUI, Highlight AI
  - AI Operating Systems section

### Changed
- Document version 2.10 → 2.11
- Last Updated to 2026-05-04 01:10 UTC
- Updated "Last Updated" badge format in README (simplified date display)
- Significantly expanded and reorganized AI browser and agent sections with detailed comparisons
- Enhanced CrewAI description with comprehensive feature list
- Added parallel processing indicators and pricing details throughout
- Updated Kimi model reference from kimi-k2.6 to kimi-k2.5
- Removed Agent Skills & Registries section (moved to separate documentation)
- Updated pricing tables with new Gemini 3.1 Flash-Lite pricing ($0.025/$1.50)
- Updated Mistral Large 3 description to reflect open-source status
- Restructured Autonomous Agents section with clearer categorization and visual indicators

## [2026-04-30] - April 30 Browser Automation & Free Models Update

### Added
- **Browser Automation**: Manus AI (cloud agent), Monica.im (Chrome extension), Chrome DevTools MCP, Cloudflare Browser Run, Notte (deterministic replay), Playwright MCP
- **CLI Tools**: Junie CLI (JetBrains LLM-agnostic agent)
- **IDEs & Add-ons**: Google Stitch (UI design tool), Tabby (self-hosted code completion)
- **API Providers**: Alibaba Cloud (Qwen3.5-Max, Coding Plan), StepFun (Step-3.5-flash), NVIDIA NIM (91 free endpoints)
- **Open-Source Models**: Gemma 4 family (31B, 27B MoE, E4B, E2B), Qwen3.5-122B MoE, Qwen3.6-27B, updated DeepSeek-V4 pricing with 75% discount (expires May 5, 2026)
- **Free Models & APIs**: Updated from April 29, 2026 v22 source with Google Jules, Google Stitch, OpenAI Codex CLI, Junie CLI, Aider, OpenHands, Roo Code, Tabby, Fireworks AI, StepFun Step 3.5 Flash
- **Chinese API Updates**: DeepSeek V4 discount (75% until May 5), GLM-5.1 (MIT license), MiniMax M2.7, Kimi K2.6 open-weight

### Changed
- Updated browser automation comparison table with new tools from April 30 source
- Enhanced developer libraries section with MCP-enabled tools
- Updated cached pricing with DeepSeek V4 discount information
- Document version 2.4 → 2.8, Last Updated to 2026-04-30 23:14 UTC
- Added changelog section to README.md per current guidelines

### Sources
- Browser AI Automation Tools Complete 2026 Comparison (Updated April 30, 2026).md
- Free Models & APIs for Vibe Coding 2026 v22.md
- Official provider documentation for pricing and feature updates

## [2026-04-26] - April 2026 AI Models Matrix Update

### Added
- DeepSeek-V4-Pro (1.6T params, 49B active) and DeepSeek-V4-Flash (284B total, 13B active) released April 24, 2026
- Gemma 4 (2B, 4B, 26B MoE, 31B Dense) open-source models released April 2, 2026
- Gemini Robotics ER 1.6 released April 14, 2026

### Changed
- Updated GPT-5.5: Pricing $5.00/$30.00, GPQA Diamond 93.2%
- Updated Claude Opus 4.7: GPQA Diamond 94.2%, SWE-bench Verified 87.6%
- Updated Kimi K2.6: GPQA Diamond 90.5%, AIME 2025 96.4%, SWE-bench Verified 80.2%
- Updated Gemini 3.1 Flash-Lite: GPQA Diamond 86.9%, Arena Elo 1432
- Updated Mistral Large 3: GPQA Diamond 43.9%
- Updated GPT-5.3-Codex: Pricing $1.75/$14.00, SWE-bench Verified 85.0%
- Updated all verification dates to 2026-04-26
- Document version 2.3 → 2.4, Last Updated to 2026-04-26 01:37 UTC

### Sources
- https://openai.com/api/pricing/ (GPT-5.5 pricing)
- https://buildfastwithai.com/blogs/claude-opus-4-7-review-benchmarks-2026 (Claude Opus 4.7 benchmarks)
- https://deepmind.google/models/gemini/flash-lite (Gemini 3.1 Flash-Lite benchmarks)
- https://onmsft.com/news/deepseek-v4-pro-and-flash-launch-with-1m-context-and-lower-ai-costs/ (DeepSeek-V4 updates)
- https://cloudprice.net/models/openai-gpt-5-3-codex (GPT-5.3-Codex pricing)
- https://aitoolsrecap.com/Blog/moonshot-ai-kimi-k2-6-release-coding-agent-benchmarks-2026 (Kimi K2.6 benchmarks)
- https://awesomeagents.ai/models/mistral-large-3/ (Mistral Large 3 benchmarks)

## [2026-02-21] - MiniMax & Missing Models Coverage

### Added
- MiniMax (MiniMax-M2.5) across Frontier Models, pricing tables, API providers, and data sources
- Moonshot AI (Kimi) to Frontier Models, API providers, data sources, and comparison tables
- Perplexity Sonar pricing entries (Sonar, Sonar Pro, Sonar Reasoning Pro) in cost analysis
- Subscription pricing tables for ChatGPT, Claude, Google AI, and GitHub Copilot
- Primary sources for ByteDance (Volcengine), Tencent (Hunyuan), and Baidu (ERNIE)
- Model selection decision table (emoji-first, awesome-style)
- Release Windows (Month-level) table for entries lacking exact timestamps

### Changed
- Updated provider/source links for Cohere, AI21, and Perplexity to official documentation pages
- Updated Copilot pricing ranges to reflect current plan tiers
- Updated README timestamps

### Sources
- https://platform.minimax.io/docs/guides/models-intro
- https://platform.minimax.io/docs/guides/pricing-paygo
- https://platform.moonshot.ai/docs/overview
- https://platform.moonshot.ai/docs/guide/kimi-k2-5-quickstart
- https://platform.moonshot.ai/docs/pricing/chat
- https://openai.com/index/introducing-chatgpt-go/
- https://help.openai.com/en/articles/8542115-chatgpt-business-faq
- https://docs.cohere.com
- https://docs.ai21.com/docs/jamba-foundation-models
- https://docs.perplexity.ai/docs/getting-started/pricing
- https://github.com/features/copilot/plans
- https://www.anthropic.com/news/claude-pro
- https://www.anthropic.com/max
- https://blog.google/products-and-platforms/products/google-one/google-ai-plus-availability/
- https://one.google.com/about/plans
- https://blog.google/products-and-platforms/products/google-one/google-ai-ultra/
- https://www.volcengine.com/docs/82379/1263482
- https://cloud.tencent.com/document/product/1729/97730
- https://ai.baidu.com/ai-doc/AISTUDIO/Mmhslv9lf

## [2026-02-20] - Pricing & Consistency Update

### Added
- Initial comprehensive pricing tables for all major model providers
- Cost analysis section with detailed pricing comparisons
- Data sources appendix with verification links
- Updated all model entries with pricing information where available

### Changed
- Standardized pricing format across all tables (input/output per 1M tokens)
- Unified verification date format to YYYY-MM-DD
- Improved table formatting for better readability
- Added missing context window specifications for several models

### Sources
- Official pricing pages for OpenAI, Anthropic, Google, Meta, Mistral, etc.
- Provider documentation for batch pricing and caching policies
- Cloud provider pricing calculators for accurate comparisons

## [Unreleased]

### Added
- **New April 21, 2026**: PaleBlueDot TokenRouter (unified AI model access), Osirus AI (unified agent platform)
- **New April 16, 2026**: GPT-Rosalind (life sciences reasoning model)
- **New April 26, 2026**: Gemini Enterprise Agent Platform (rebranded Vertex AI)
- **New April 29, 2026**: GPT-5.5 Pro, Nemotron 3 Nano Omni, Lizzy-7B, MiMo-V2.5/Pro
- **New April 30, 2026**: Chrome DevTools MCP, Cloudflare Browser Run, comprehensive vibe coding tools guide

### Changed
- Updated IDE section with agent-first architectures (Cursor 3, Windsurf, VS Code Agents)
- Enhanced GPU cloud comparison with serverless options and pricing
- Expanded RAG framework coverage with production-ready options
- Added comprehensive fine-tuning platform comparisons
- Updated Frontier Models with GPT-5.5 Pro and Claude Opus 4.7
- Added new multimodal model: Nemotron 3 Nano Omni
- Updated benchmark tables with latest model scores
- Added Free Models & APIs for Vibe Coding section
- Updated open-source models section with Lizzy-7B, MiMo-V2.5/Pro

### Added
- GitHub Actions workflows for automated quality checks:
  - [link-check](../.github/workflows/link-check.yml) - Validates external URLs
  - [lint](../.github/workflows/lint.yml) - Lints markdown files
  - [awesome-lint](../.github/workflows/awesome-lint.yml) - Validates awesome-list format

### Changed
- Model entry verification completed with 7 models flagged as unverified
- GPT-5.3-Codex pricing corrected from "TBD" to verified pricing
- DeepSeek-V4 flagged for review pending verification

### Added
- GPT-5.5 (OpenAI) to Frontier Models
- Claude Opus 4.7 (Anthropic) with updated features
- DeepSeek-V4 official release verification
- Kimi K2.6 (Moonshot AI)
- GLM-5.1 and Qwen3.6-27B to Open-Source Models
- MAI-Image-2-Efficient (Microsoft) to Image Generation

### Updated (2026-04-24)
- Removed [⚠️ Unverified] tags from the following models after verification:
  - Gemini 3.1 Flash-Lite (Google)
  - Mistral Large 3 (Mistral AI) - Updated pricing from "Varies" to "$0.50 / $1.50"
  - Llama 4 Scout (Meta)
  - Llama 4 Maverick (Meta)
  - Grok 4 Fast (xAI)
- Updated verification dates to 2026-04-24 for verified models
- Updated "Last Updated" badge and footer to 2026-04-24 16:26 UTC

## [2026-05-09] - Version 3.6

### Added
- **New Section: Cursor Alternatives & Better Value 🎯**
  - Comprehensive pricing analysis comparing Cursor with alternatives
  - Value-for-money ranking with 7 tools compared
  - Real developer quotes from Reddit, LinkedIn, and social media
  - Detailed analysis of why specific alternatives beat Cursor

### Updated
- **Version Information**: Updated from 3.5 to 3.6
- **Last Updated**: Changed from 2026-05-08 00:00 UTC to 2026-05-09 06:00 UTC
- **Description**: Added "Includes community-sourced feedback from Reddit, LinkedIn, and developer blogs"
- **API Providers**: Added AIHubMix as a free models API provider
- **Pricing Tables**: Updated various pricing comparisons throughout the document

### Fixed
- Minor formatting and consistency improvements

### Sources (verification, 2026-05-09 06:00 UTC)
- Official documentation updates for version and pricing information
- Community feedback sources for developer sentiment analysis

[Unreleased]: https://github.com/ReadyPixels/AI_Models_Matrix/compare/v1.0.0...HEAD


