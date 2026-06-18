# Release v3.29

Release v3.29: [2026-06-17] - Version 3.29 - Fable/Mythos suspension, Kimi K2.7 Code, MiniMax M3 GA, Arena Elo refresh, stale markers

## Latest Changelog Entry

### [2026-06-17] - Version 3.29 - Fable/Mythos suspension, Kimi K2.7 Code, MiniMax M3 GA, Arena Elo refresh, stale markers

### Added
- **Kimi K2.7 Code** (Frontier Models, Free-Source Models, Coding Models, Open-Source Coding Models, Autonomous Coding Agents): Open-weight coding-focused agentic model by Moonshot AI; 1T total params, 32B active (MoE); 262K context; 30% fewer thinking tokens vs K2.6; SWE-bench Verified 78.2%, AIME 2025 91.5%; $0.95/$4.00 per 1M tokens; Modified MIT license; released 2026-06-12.
  - Source: https://huggingface.co/moonshotai/Kimi-K2.7-Code
- **MiniMax M3** (Free-Source Models, Open-Source Coding Models): Open weights now released; frontier coding (SWE-Bench Pro 59.0%, SWE-Bench Verified 80.5%), 1M context, native multimodality; MIT license. Previously listed as API-only.
  - Source: https://www.minimax.io/news/minimax-m3

### Updated
- **Claude Fable 5 / Mythos 5** (Frontier Models, Coding Models): Marked with ⚠️ suspension notice. US government export control directive on June 12, 2026 forced Anthropic to disable global access to both models. Access may be restored for US-based users around July 1, 2026. All other Claude models unaffected.
  - Source: https://www.anthropic.com/news/fable-mythos-access
- **Arena Elo scores** (Frontier Models table): Updated Claude Opus 4.8 to 1483, Claude Opus 4.7 to 1502, GPT-5.5 to 1481, Gemini 3.1 Pro to 1486 based on arena.ai June 2026 data.
  - Source: https://arena.ai/leaderboard/text
- **SWE-bench Verified Leaderboard**: Added Kimi K2.7 Code (#21, 78.2%), MiniMax M3 (#13, 80.5%). Re-ranked entries #13-#26 accordingly.
  - Source: https://benchlm.ai/benchmarks/sweVerified
- **AIME 2025 Leaderboard**: Updated with BenchLM.ai June 2026 data. MAI-Thinking-1 now #1 (97%), Kimi K2.5 variants at #2 (96.1%).
  - Source: https://benchlm.ai/benchmarks/aime2025
- **Top Models by Category**: Coding #1 changed to Claude Opus 4.8 (Fable 5 suspended); Agentic Performance #1 changed to Claude Opus 4.8; Open Source #1 changed to MiniMax M3.
- **Codex CLI** (Autonomous Coding Agents): Updated description to reflect Rust-native rewrite, v0.140+, /goal persistent workflows, Chrome extension support.
  - Source: https://github.com/openai/codex
- **Gemini CLI deprecation note** (Assisted CLI Tools): Google confirmed shutdown date of June 18, 2026; migrate to Antigravity CLI (`agy`).
  - Source: https://blog.google/innovation-and-ai/technology/developers-tools/google-io-2026-developer-highlights/

### Removed / Deprecated
- **Stale ⭐ markers removed**: Removed ⭐ from entries older than 30 days from 2026-06-17: Gemini 3.5 Flash, Gemini Omni Flash, Qwen3.7-Max, Qwen3.7-Plus-Preview, Grok 4 Fast, Grok 4.20, MiniMax M3 (re-added as still within 30 days of GA), NVIDIA Nemotron 3 Ultra, MAI-Thinking-1, MAI-Code-1-Flash, Kimi Code CLI. Retained ⭐ on: MiniMax M3 (2026-06-01, still within 30 days), Kimi K2.7 Code (2026-06-12), Claude Fable 5 (2026-06-09), Claude Mythos 5 (2026-06-09).
- **Document Version**: 3.28 -> 3.29; Last Updated badge updated to 2026-06-17.

---

## Files in Release

- docs/readme.md
- docs/readme.pdf

---
*Generated on 2026-06-18T06:44:50.318Z*
