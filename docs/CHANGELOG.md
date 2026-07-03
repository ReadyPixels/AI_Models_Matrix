## [2026-07-03] - Version 3.40 - Official July coding-agent refresh

### Added
- **GitHub Copilot enterprise agent session streaming** (IDE Add-ons): added public preview enterprise session streaming/API coverage for Copilot clients. Source: <a href="https://github.blog/changelog/2026-07-02-copilot-agent-session-streaming-is-now-in-public-preview/" rel="nofollow">🔗</a>

### Updated
- **Header metadata**: bumped document version to 3.40 and refreshed the Last Updated timestamp to 2026-07-03 16:06 UTC.
- **Codex CLI** (Autonomous Coding Agents): updated to v0.142.5 and noted the Responses WebSocket trace logging fix. Source: <a href="https://developers.openai.com/codex/changelog" rel="nofollow">🔗</a>
- **GitHub Copilot** (IDE Add-ons): updated Copilot rows with July 2 enterprise agent session streaming, AI credit pools, and `GITHUB_TOKEN` support for Copilot CLI in GitHub Actions. Sources: <a href="https://github.blog/changelog/2026-07-02-copilot-agent-session-streaming-is-now-in-public-preview/" rel="nofollow">🔗</a>, <a href="https://github.blog/changelog/2026-07-02-copilot-cli-no-longer-needs-a-personal-access-token-in-github-actions/" rel="nofollow">🔗</a>
- **Primary Sources**: added the GitHub Copilot changelog source used in this pass.

### Removed / Deprecated
- None

---

## [2026-07-02] - Version 3.39 - Official-source software and speech refresh

### Added
- **MiniMax Speech 2.8** (Speech & TTS): added official launch details for native sound tags, high-fidelity cloning, and studio-grade multilingual TTS. Source: <a href="https://www.minimax.io/news/minimax-speech-28" rel="nofollow">🔗</a>
- **Claude Science** (Cloud Automation): added Anthropic's scientist workbench with auditable artifacts and compute/credit program details. Source: <a href="https://www.anthropic.com/news/claude-science-ai-workbench" rel="nofollow">🔗</a>
- **OpenAI Workspace Agents** (Cloud Automation): added ChatGPT workspace agents for Business, Enterprise, Edu, and Teachers plans. Source: <a href="https://openai.com/index/introducing-workspace-agents-in-chatgpt/" rel="nofollow">🔗</a>
- **Amazon Bedrock AgentCore** (Cloud Automation): added AWS agent runtime, gateway, memory, browser, code interpreter, identity, and observability platform. Source: <a href="https://aws.amazon.com/bedrock/agentcore/" rel="nofollow">🔗</a>

### Updated
- **Header metadata**: bumped document version to 3.39 and refreshed the Last Updated timestamp to 2026-07-02 23:00 UTC.
- **Kiro** (Agentic IDEs): updated to IDE 1.0.52 with custom agents, permissions, agent focus mode, natural-language hooks, dockable chat tabs, and paused 1.0.x auto-updates. Source: <a href="https://kiro.dev/changelog/ide/" rel="nofollow">🔗</a>
- **Cursor** (VS Code Forks): updated 2026-06-30 changelog note for Team MCPs and organization groups in team marketplaces. Source: <a href="https://cursor.com/changelog" rel="nofollow">🔗</a>
- **Windsurf** (VS Code Forks / Cursor Alternatives): corrected current plan structure to Free, Pro $20/mo, Teams $40/user/mo, and Max $200/mo. Source: <a href="https://windsurf.com/pricing" rel="nofollow">🔗</a>
- **Codex CLI** (Autonomous Coding Agents): refreshed official CLI description and v0.142.0 changelog details. Source: <a href="https://developers.openai.com/codex/changelog" rel="nofollow">🔗</a>
- **Cartesia Sonic-3.5 and Ink-2** (Speech & TTS): refreshed from official Cartesia launch and TTS docs. Sources: <a href="https://www.cartesia.ai/launch" rel="nofollow">🔗</a>, <a href="https://docs.cartesia.ai/build-with-cartesia/tts-models/latest" rel="nofollow">🔗</a>
- **Gemini 3.1 Flash-Lite Image** (Image Generation): corrected the row to the current official model-card naming and link. Source: <a href="https://deepmind.google/models/model-cards/" rel="nofollow">🔗</a>
- **Primary Sources**: added official sources used in this pass for OpenAI, Anthropic, Google, Kiro, Cursor, Windsurf, MiniMax, Cartesia, and AWS.

### Removed / Deprecated
- Removed the unofficial Seed 2.1 Pro note because the README update rules require official sources for model entries.
- Removed duplicate Lightpanda Agent and duplicate enterprise agent platform rows from the automation tables.

---

## [2026-07-02] - Version 3.38 - Claude Sonnet 5 and Fable 5 redeployment

### Added
- **Claude Sonnet 5** launched 2026-06-30 00:00 UTC with 1M context, 128K output, $2.00 / $10.00 introductory pricing through 2026-08-31 00:00 UTC, and 92.4% SWE-bench Verified
- **Claude Fable 5 and Mythos 5** access restored 2026-07-01 00:00 UTC after export controls were lifted; Fable 5 globally available while Mythos 5 remains restricted to Project Glasswing partners
- **GPT-5.6 Sol/Terra/Luna** family: limited preview announced; Sol $5/$30, Terra $2.50/$15, Luna $1/$6 per 1M tokens
- **Gemini Omni Flash**: any-to-any video generation at $0.10/s with conversational editing
- **Nano Banana 2 Lite**: fastest Gemini image model at 4s generation with pricing at $0.034/1K images
- **MiniMax M2** (230B/10B active MoE, 1M context, Apache 2.0) and **M2.1** (229B/10B active MoE, 1M context, Apache 2.0); API at $0.30/$1.20 per 1M tokens
- **Kimi K2.7 Code** in GitHub Copilot: first open-weight model in Copilot model picker (July 1, 2026)

### Updated
- **Highlights section**: Added Claude Sonnet 5, Fable 5/Mythos 5, GPT-5.6 pricing, and MiniMax M2/M2.1 information
- **Frontier Models table**: Added Claude Sonnet 5, Claude Fable 5, Claude Mythos 5, GPT-5.6 Sol/Terra/Luna, MiniMax M2.1, Zhipu GLM-5.2
- **Model Specifications**: Updated with Claude Sonnet 5 output token limits and pricing; added GPT-5.6 Sol/Terra/Luna pricing; corrected MiniMax M2/M2.1 parameter counts to 230B/10B active and 229B/10B active
- **SWE-bench Verified Leaderboard**: Updated rankings with Claude Sonnet 5 at 92.4%
- **Commercial Coding Models**: Added Claude Sonnet 5, GPT-5.6 family, MiniMax M2/M2.1, Kimi K2.7 Code, Qoder 1.0, Junie CLI; updated Fable 5 access information
- **Free-Source Models table**: Added MiniMax M2 and M2.1 with corrected specs
- **IDE Add-ons table**: Added Kimi K2.7 Code GitHub Copilot integration
- **Comparison Tables**: Updated Sort by Latest Update with all new releases and corrected MiniMax M2/M2.1 specs

### Removed / Deprecated
- None

---
