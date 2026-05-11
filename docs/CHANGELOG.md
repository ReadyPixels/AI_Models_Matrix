# Changelog

All notable changes to this project are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

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
