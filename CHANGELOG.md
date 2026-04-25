# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

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