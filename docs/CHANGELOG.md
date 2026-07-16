## [2026-07-16] - Version 3.48 - Codex CLI 0.144.5 and IDE release-note refresh

### Added
- None.

### Updated
- **Codex CLI** (CLI Tools - Autonomous Coding Agents, Highlights, Supplemental notes): updated tracked release from 0.144.3 to 0.144.5 and noted the 2026-07-16 dangerous-command detection patch plus the 0.144.4 no-op patch on 2026-07-14. Source: <a href="https://developers.openai.com/codex/changelog" rel="nofollow">🔗</a>
- **Cursor** (IDEs - VS Code Forks, Highlights, Supplemental notes): updated the tracked release from 2026-06-30 to Cursor 3.11 on 2026-07-10 with side chats, conversation search, and simplified project/repo pickers. Source: <a href="https://cursor.com/changelog" rel="nofollow">🔗</a>
- **Kiro** (IDEs - VS Code Forks, Highlights, Supplemental notes): updated the tracked IDE release from 1.0.52 to 1.0.138 on 2026-07-13 with faster sessions, PowerShell trust on Windows, compaction fixes, and improved MCP tool recovery. Source: <a href="https://kiro.dev/changelog/ide/" rel="nofollow">🔗</a>
- **Windsurf and GitHub Copilot pricing guidance** (VS Code Forks, Cursor Alternatives, Subscription Pricing): corrected Windsurf's post-March 2026 plan structure and clarified GitHub Copilot's June 2026 usage-based billing as base subscription plus bundled AI Credits rather than flat all-in monthly pricing. Sources: <a href="https://windsurf.com/pricing" rel="nofollow">🔗</a>, <a href="https://github.com/features/copilot/plans" rel="nofollow">🔗</a>
- **Browser-use, Vercel AI Gateway, and MCP Ecosystem** (Developer Libraries, Browser-Only Agents, Model Router Services, MCP Ecosystem): refreshed Browser Use cloud pricing/free-tier details, clarified AI Gateway availability across Vercel plans with zero-markup paid credits, and updated MCP registry wording to match the official preview registry and spec docs. Sources: <a href="https://browser-use.com/pricing" rel="nofollow">🔗</a>, <a href="https://docs.browser-use.com/cloud/quickstart" rel="nofollow">🔗</a>, <a href="https://vercel.com/docs/ai-gateway" rel="nofollow">🔗</a>, <a href="https://vercel.com/docs/ai-gateway/pricing" rel="nofollow">🔗</a>, <a href="https://modelcontextprotocol.io/registry/about" rel="nofollow">🔗</a>, <a href="https://modelcontextprotocol.io/specification/draft/deprecated" rel="nofollow">🔗</a>
- **Header metadata**: bumped document version to 3.48 and refreshed the Last Updated timestamp to 2026-07-16 07:03 UTC.

### Removed / Deprecated
- None.

---

## [2026-07-15] - Version 3.47 - xAI Grok-4.5, Codex CLI 0.144.3, MCP registry growth

### Added
- **Grok-4.5** (Frontier Models, Model Specifications, Model Labs (Direct), Full Benchmark Table): new xAI frontier multimodal LLM (2026-07-08) with 500K context, text+image input, function calling, structured outputs, and reasoning; API pricing $2.00 input / $0.50 cached input / $6.00 output per 1M tokens; available in Palantir AIP from 2026-07-14. Source: <a href="https://docs.x.ai/developers/models/grok-4.5" rel="nofollow">🔗</a>
- **Grok-4.5** (Sort by Latest Update, Model Pricing Comparison): mirrored the new flagship into the reference and pricing derived tables. Source: <a href="https://docs.x.ai/developers/models/grok-4.5" rel="nofollow">🔗</a>

### Updated
- **Codex CLI** (Autonomous Coding Agents): bumped tracked version from 0.142.5 (2026-07-01) to 0.144.3 (2026-07-13, version-only) and 0.144.2 (2026-07-13, restored Guardian auto-review policy after a prompting regression). Source: <a href="https://developers.openai.com/codex/changelog" rel="nofollow">🔗</a>
- **MCP Ecosystem**: refreshed the Glama community registry server count to 55,658 on 2026-07-15 (up from ~19,831 in March 2026). Sources: <a href="https://registry.modelcontextprotocol.io/" rel="nofollow">🔗</a>, <a href="https://glama.ai/mcp/servers" rel="nofollow">🔗</a>
- **Header metadata**: bumped document version to 3.47 and refreshed the Last Updated timestamp to 2026-07-15 13:24 UTC; refreshed the "latest data" reference date and added Grok-4.5 and Codex CLI highlights.

### Removed / Deprecated
- None.

---

## [2026-07-11] - Version 3.46 - API pricing and free-tier refocus

### Updated
- **API Providers - Model Labs (Direct)**: replaced generic provider coverage with cheapest verified direct text APIs and documented free or trial access for Groq, Google Gemini, DeepSeek, Mistral, Cohere, OpenAI, Anthropic, and xAI. Sources: <a href="https://groq.com/pricing" rel="nofollow">🔗</a>, <a href="https://groq.com/groqcloud" rel="nofollow">🔗</a>, <a href="https://ai.google.dev/gemini-api/docs/pricing" rel="nofollow">🔗</a>, <a href="https://api-docs.deepseek.com/quick_start/pricing" rel="nofollow">🔗</a>, <a href="https://docs.mistral.ai/models/model-cards/mistral-small-4-0-26-03" rel="nofollow">🔗</a>, <a href="https://docs.mistral.ai/getting-started/quickstarts/studio/activate-and-generate-api-key" rel="nofollow">🔗</a>, <a href="https://docs.cohere.com/docs/command-r" rel="nofollow">🔗</a>, <a href="https://docs.cohere.com/docs/how-does-cohere-pricing-work" rel="nofollow">🔗</a>, <a href="https://developers.openai.com/api/docs/pricing" rel="nofollow">🔗</a>, <a href="https://developers.openai.com/api/docs/quickstart" rel="nofollow">🔗</a>, <a href="https://platform.claude.com/docs/en/about-claude/pricing" rel="nofollow">🔗</a>, <a href="https://claude.com/pricing" rel="nofollow">🔗</a>, <a href="https://docs.x.ai/developers/pricing" rel="nofollow">🔗</a>
- **Free Tier APIs, Free AI APIs for Coding, Model Pricing Comparison, and Sort by Price**: rewrote these sections to focus on the cheapest official APIs and explicitly documented free access, including Groq Llama 3.1 8B Instant, Gemini 2.5 Flash-Lite, DeepSeek-V4-Flash, Mistral Small 4, Command R, GPT-5.4 nano, and Claude Haiku 4.5. Sources: <a href="https://groq.com/pricing" rel="nofollow">🔗</a>, <a href="https://ai.google.dev/gemini-api/docs/pricing" rel="nofollow">🔗</a>, <a href="https://api-docs.deepseek.com/quick_start/pricing" rel="nofollow">🔗</a>, <a href="https://docs.mistral.ai/models/model-cards/mistral-small-4-0-26-03" rel="nofollow">🔗</a>, <a href="https://docs.cohere.com/docs/command-r" rel="nofollow">🔗</a>, <a href="https://developers.openai.com/api/docs/pricing" rel="nofollow">🔗</a>, <a href="https://platform.claude.com/docs/en/about-claude/pricing" rel="nofollow">🔗</a>
- **Primary Sources**: added current official pricing and free-access references for OpenAI, Anthropic, Google Gemini, DeepSeek, Mistral, Cohere, Groq, xAI, and Vercel AI Gateway. Source: <a href="https://vercel.com/docs/ai-gateway/pricing" rel="nofollow">🔗</a>
- **Header metadata**: bumped document version to 3.46 and refreshed the Last Updated timestamp to 2026-07-11 19:14 UTC.

### Removed / Deprecated
- **Unsupported recurring free-tier claims**: removed standing free-tier wording for OpenAI and DeepSeek where the official pages did not support it.

---

## [2026-07-11] - Version 3.45 - GPT-Live voice models and Realtime API 2.1

### Added
- **GPT-Live (1 / 1 mini / Medium / High)** (Speech & TTS): OpenAI's full-duplex voice model family powering ChatGPT Voice, announced 2026-07-08; GPT-Live-1 default for paid tiers, GPT-Live-1 mini for Free; GPT-5.5 backend delegates complex work; API pending. Source: <a href="https://openai.com/index/introducing-gpt-live/" rel="nofollow">🔗</a>
- **GPT-Realtime 2.1 / 2.1-mini** (Speech & TTS): newer Realtime API speech-to-speech models with function calling, MCP servers, and SIP; shipped 2026-07-06. Source: <a href="https://platform.openai.com/docs/guides/realtime" rel="nofollow">🔗</a>

### Updated
- **Speech & TTS section**: refreshed "Prices as of" date to July 2026 and added GPT-Live and GPT-Realtime 2.1 rows to the TTS Proprietary table.
- **Sort by Latest Update**: added a GPT-Live row dated 2026-07-08.
- **Primary Sources**: added OpenAI GPT-Live announcement and Realtime API 2.1 documentation sources.
- **Supplemental agent & CLI notes**: added a GPT-Live voice models note.
- **Evaluation & Observability**: refreshed the "As of" date to July 2026 and added Braintrust Topics active-observability GA (June 2026) to the Braintrust row. Source: <a href="https://www.braintrust.dev/blog/topics-ga" rel="nofollow">🔗</a>
- **Header metadata**: bumped document version to 3.45 and refreshed the Last Updated timestamp to 2026-07-11 21:56 UTC.

### Removed / Deprecated
- None.

---

## [2026-07-11] - Version 3.44 - GPT-5.6 GA and Gemma 4 refresh

### Added
- **Gemma 4**: recorded the 2026-07-06 public release of Gemma 4 31B and Gemma 4 26B-A4B through the Gemini API and AI Studio. Source: <a href="https://ai.google.dev/gemini-api/docs/changelog" rel="nofollow">🔗</a>

### Updated
- **GPT-5.6**: changed Sol, Terra, and Luna from limited preview to general availability and refreshed release dates to 2026-07-09. Source: <a href="https://openai.com/index/gpt-5-6/" rel="nofollow">🔗</a>
- **Header metadata**: bumped document version to 3.44 and refreshed the Last Updated timestamp to 2026-07-11 00:00 UTC.

## [2026-07-03] - Version 3.43 - Deep infrastructure and source consistency refresh

### Added
- **Vercel AI Gateway** (API Providers): added the managed model router with $5/month free credits, zero-markup paid credits, BYOK on paid tier, model fallbacks, observability, and Routing Rules beta. Sources: <a href="https://vercel.com/changelog/ai-gateway-routing-rules" rel="nofollow">🔗</a>, <a href="https://vercel.com/docs/ai-gateway/pricing" rel="nofollow">🔗</a>
- **Vercel Sandbox** (Cloud Automation): added official FUSE support for mounting S3, network, and custom filesystems inside agent/runtime sandboxes. Source: <a href="https://vercel.com/changelog/vercel-sandbox-now-supports-fuse-based-filesystems" rel="nofollow">🔗</a>
- **jina-embeddings-v5-omni-small** (Embedding Models): added Jina's multimodal embedding model for text, image, video, audio, and PDF search. Source: <a href="https://jina.ai/models/jina-embeddings-v5-omni-small/" rel="nofollow">🔗</a>

### Updated
- **Header metadata**: bumped document version to 3.43 and refreshed the Last Updated timestamp to 2026-07-03 21:56 UTC.
- **Cloudflare Browser Run** (Browser Automation): updated the developer-library row and free coding guide with the `/json` Quick Action for schema-shaped extraction using Workers AI or BYOK. Source: <a href="https://developers.cloudflare.com/browser-run/quick-actions/json-endpoint/" rel="nofollow">🔗</a>
- **Vercel eve** (Multi-Agent Platforms): updated the row for Agent Runs inspection through Vercel MCP tools and `vercel agent-runs` CLI commands. Source: <a href="https://vercel.com/changelog" rel="nofollow">🔗</a>
- **Mastra** (Multi-Agent Platforms): updated the row with file-based agents, skills, workspaces, and subagents from the official Mastra release. Source: <a href="https://mastra.ai/blog/introducing-file-based-agents" rel="nofollow">🔗</a>
- **MCP Ecosystem**: replaced the third-party registry reference with the official MCP Registry domain and added the Python, TypeScript, Go, and C# SDK beta support note for the 2026-07-28 spec release candidate. Sources: <a href="https://registry.modelcontextprotocol.io/" rel="nofollow">🔗</a>, <a href="https://blog.modelcontextprotocol.io/posts/sdk-betas-2026-07-28/" rel="nofollow">🔗</a>
- **Agent Skills & Registries**: added Vercel's official Agent Resources skills documentation. Source: <a href="https://vercel.com/docs/agent-resources/skills" rel="nofollow">🔗</a>
- **Multi-Agent & Parallel Execution Summary**: expanded the Multi-Agent Platforms category list to include OpenAI Agents SDK, Google ADK, ADK Go 2.0, Genkit Agents, AI SDK 7, Mastra, and Vercel eve.
- **Primary Sources**: added official sources for Vercel AI Gateway, Vercel Sandbox, Vercel eve Agent Runs, Vercel Agent Resources, Cloudflare Browser Run, DeepReinforce Ornith, Jina AI, Mastra, Google ADK/Genkit, and MCP Registry/SDK betas.
- **Open-Source Coding Models**: corrected the duplicate MiniMax M2 row to MiniMax M2.7.
- **Cursor Alternatives guide**: removed unofficial Reddit/social quote sourcing and replaced it with an official-source basis note.

### Removed / Deprecated
- Replaced the nonofficial Ornith source in the active changelog trail with DeepReinforce's official Hugging Face collection and model card.

---

## [2026-07-03] - Version 3.42 - Open-source models and agent frameworks refresh

### Added
- **Ornith-1.0** open-source coding model family (9B/31B/35B-MoE/397B-MoE, MIT license, built on Gemma 4 and Qwen 3.5, 82.4% SWE-bench Verified) to Free-Source Models, Open-Source Coding Models, SWE-bench Verified Leaderboard, and Comprehensive Benchmark Reference. Sources: <a href="https://huggingface.co/collections/deepreinforce-ai/ornith-10" rel="nofollow">🔗</a>, <a href="https://huggingface.co/deepreinforce-ai/Ornith-1.0-9B" rel="nofollow">🔗</a>
- **AI SDK 7** (Vercel, June 25, 2026): major TypeScript agent platform release with terminal UI, WorkflowAgent, sandbox support, Node 22 minimum, ESM imports required. Source: <a href="https://vercel.com/changelog/ai-sdk-7" rel="nofollow">🔗</a>
- **ADK Go 2.0** (Google, June 30, 2026): graph-based agent workflow engine with human-in-the-loop, dynamic orchestration, and unified node runtime. Source: <a href="https://developers.googleblog.com/announcing-adk-go-20/" rel="nofollow">🔗</a>
- **Genkit Agents** (Google, July 1, 2026): full-stack agent framework with Developer UI, chat() API, and TypeScript/Go support. Source: <a href="https://developers.googleblog.com/build-agentic-full-stack-apps-with-genkit/" rel="nofollow">🔗</a>
- **Mastra** 1.48.0 (Vercel, July 1, 2026): agent framework with file-based agents, subagents, interval handlers, schedule beats, and sandbox exports. Source: <a href="https://github.com/mastra-ai/mastra" rel="nofollow">🔗</a>
- **Copilot Vision GA** (GitHub, July 1, 2026): GitHub Copilot Vision is now generally available. Source: <a href="https://github.blog/changelog/label/copilot/" rel="nofollow">🔗</a>

### Updated
- **Header metadata**: bumped document version to 3.42 and refreshed the Last Updated timestamp to 2026-07-03 19:19 UTC.
- **SWE-bench Verified Leaderboard**: added Ornith-1.0-397B at rank #10 with 82.4% SWE-bench Verified.
- **Comprehensive Benchmark Reference**: added Ornith-1.0-397B to the Full Benchmark Table with 82.4% SWE-bench Verified.
- **Free-Source Models table**: added Ornith-1.0 (9B/31B/35B-MoE/397B-MoE, MIT license).
- **Coding Models > Open-Source Coding Models**: added Ornith-1.0 (DeepReinforce, MIT, 160-320 GB VRAM).
- **Multi-Agent Platforms**: added AI SDK 7, ADK Go 2.0, Genkit Agents, and Mastra.
- **IDE Add-ons > Universal (Cross-Platform)**: added Copilot Vision GA (July 1, 2026) to GitHub Copilot entry.
- **Primary Sources**: added DeepReinforce, Vercel AI SDK, Google ADK Go, Genkit, Mastra, and GitHub Copilot changelog sources.

### Removed / Deprecated
- None

---

## [2026-07-03] - Version 3.41 - Browser automation refresh

### Added
- **Browser Harness** (Browser Automation - Developer Libraries): added Browser Use's self-healing CDP harness for direct LLM control of Chrome. Source: <a href="https://github.com/browser-use/browser-harness" rel="nofollow">🔗</a>
- **Vercel agent-browser** (Browser Automation - Developer Libraries): added the Rust/Node browser automation CLI for AI agents, with compact snapshots, ref-based actions, Chrome and Lightpanda engines, and packaged agent skill. Source: <a href="https://agent-browser.dev/" rel="nofollow">🔗</a>

### Updated
- **Header metadata**: bumped document version to 3.41 and refreshed the Last Updated timestamp to 2026-07-03 16:32 UTC.
- **Browser-use** (Browser Automation): updated developer-library and browser-only rows for Browser Use CLI 3.0, Browser Harness integration, `browser-use skill`, Cloud v3 premium agent, current free prompt / pay-as-you-go pricing, scheduling, persistent memory, skills, and integrations. Sources: <a href="https://github.com/browser-use/browser-use/releases" rel="nofollow">🔗</a>, <a href="https://browser-use.com/pricing" rel="nofollow">🔗</a>, <a href="https://docs.browser-use.com/cloud/faq" rel="nofollow">🔗</a>
- **Multi-Agent & Parallel Execution Summary** (Automation): updated the Developer Libraries category list to include Browser Harness and Vercel agent-browser.
- **Primary Sources**: added Browser Use, Browser Harness, and Vercel agent-browser sources used in this pass.

### Removed / Deprecated
- None

---

## [2026-07-03] - Version 3.40 - Official July coding-agent refresh

### Added
- **GitHub Copilot enterprise agent session streaming** (IDE Add-ons): added public preview enterprise session streaming/API coverage for Copilot clients. Source: <a href="https://github.blog/changelog/2026-07-02-copilot-agent-session-streaming-is-now-in-public-preview/" rel="nofollow">🔗</a>

### Updated
- **Header metadata**: bumped document version to 3.40 and refreshed the Last Updated timestamp to 2026-07-03 16:06 UTC.
- **Codex CLI** (Autonomous Coding Agents): updated to v0.142.5 and noted the Responses WebSocket trace logging fix. Source: <a href="https://developers.openai.com/codex/changelog" rel="nofollow">🔗</a>
- **GitHub Copilot** (IDE Add-ons): updated Copilot rows with July 2 enterprise agent session streaming, AI credit pools, and `GITHUB_TOKEN` support for Copilot CLI in GitHub Actions. Sources: <a href="https://github.blog/changelog/2026-07-02-copilot-agent-session-streaming-is-now-in-public-preview/" rel="nofollow">🔗</a>, <a href="https://github.blog/changelog/2026-07-02-copilot-cli-no-longer-needs-a-personal-access-token-in-github-actions/" rel="nofollow">🔗</a>
- **GitHub Copilot model availability** (IDE Add-ons): noted Copilot-only deprecation of Gemini 2.5 Pro and Gemini 3 Flash on 2026-07-31. Source: <a href="https://github.blog/changelog/2026-07-02-upcoming-deprecation-of-gemini-2-5-pro-and-gemini-3-flash/" rel="nofollow">🔗</a>
- **Claude Opus 4.7 fast mode** (Speed & Latency): noted Anthropic's 2026-07-24 fast-mode removal guidance and Opus 4.8 migration path. Source: <a href="https://docs.anthropic.com/en/docs/about-claude/models/choosing-a-model" rel="nofollow">🔗</a>
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
