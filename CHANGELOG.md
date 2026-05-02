# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

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

## [Unreleased]

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