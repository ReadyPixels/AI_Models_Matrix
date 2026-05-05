# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

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
  - [link-check](.github/workflows/link-check.yml) - Validates external URLs
  - [lint](.github/workflows/lint.yml) - Lints markdown files
  - [awesome-lint](.github/workflows/awesome-lint.yml) - Validates awesome-list format

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

[Unreleased]: https://github.com/shariqmehmood/AI_Models_Matrix/compare/v1.0.0...HEAD