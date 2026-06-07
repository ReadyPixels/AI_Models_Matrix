# Release vv3.15

Release v3.15: [2026-05-28] - Version 3.15 - Claude Opus 4.8, Grok pricing cuts, GPU Cloud pricing, model data updates

## Latest Changelog Entry

### [2026-05-28] - Version 3.15 - Claude Opus 4.8, Grok pricing cuts, GPU Cloud pricing, model data updates

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

## Files in Release

- docs/readme.md
- docs/readme.pdf

---
*Generated on 2026-05-29T10:54:34.249Z*
