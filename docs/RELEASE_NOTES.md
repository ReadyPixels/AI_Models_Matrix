# Release v3.31

Release v3.31: [2026-06-18] - Version 3.31 - GLM-5.2 open-source launch, Gemma 4 12B multimodal, Antigravity 2.0 GA, Cursor Composer 2.5, GitHub Copilot usage-based billing, Google AI Ultra repricing, AIME 2026 benchmark, OpenAI GPT-Realtime-2, Stability Audio 3.0

## Latest Changelog Entry

### [2026-06-18] - Version 3.31 - GLM-5.2 open-source launch, Gemma 4 12B multimodal, Antigravity 2.0 GA, Cursor Composer 2.5, GitHub Copilot usage-based billing, Google AI Ultra repricing, AIME 2026 benchmark, OpenAI GPT-Realtime-2, Stability Audio 3.0

### Added
- **GLM-5.2** (Free-Source Models, Open-Source Coding Models): Zhipu AI flagship open-weight model; 753B params (MoE, 40B active), 1M context, 128K max output, MIT license; AIME 2026 99.2% (#1), Terminal-Bench 2.1 81.0, SWE-bench Pro 62.1%, FrontierSWE 74.4%; API $1.40/$4.40 per 1M; released 2026-06-13, weights open-sourced 2026-06-17.
  - Source: https://z.ai/blog/glm-5.2, https://aitoolly.com/ai-news/article/2026-06-14-zhipu-ai-releases-glm-52-a-fully-open-source-frontier-model-featuring-a-1m-context-window
- **Gemma 4 12B** (Free-Source Models, SLMs): Google encoder-free unified multimodal model; 12B dense, 256K context, Apache 2.0; text+image+audio input; released June 2026.
  - Source: https://blog.google/innovation-and-ai/technology/developers-tools/introducing-gemma-4-12b/
- **Supertonic 3** (TTS Proprietary): Supertone on-device TTS; 99M params, 31 languages, 167x real-time on CPU; Voice Builder for custom voices; released May 2026.
  - Source: https://github.com/supertone-inc/supertonic
- **Stability Audio 3.0** (TTS Open Source): Professional-grade music generation >6 min; open-weight small/medium under Apache 2.0; released May 2026.
  - Source: https://techcrunch.com/2026/05/20/stability-ai-release-a-new-audio-model-that-can-create-six-minute-songs/
- **OpenAI GPT-Realtime-2** (TTS Proprietary): Speech-to-speech with GPT-5-class reasoning, tool calls, interruptions; voices Cedar and Marin; released 2026-05-07.
  - Source: https://openai.com/index/advancing-voice-intelligence-with-new-models-in-the-api
- **Aion 1.0 Instruct + Aion 1.0 Plan** (SLMs): Microsoft on-device SLMs for Windows; Instruct is a smaller/faster SLM; Plan is a reasoning/tool-calling model for local agentic capabilities; announced Build 2026.
  - Source: https://blogs.windows.com/windowsdeveloper/2026/06/02/build-2026-furthering-windows-as-the-trusted-platform-for-development
- **Microsoft Windows Agent Framework** (Autonomous Agents - Local Machine): Open-sourced MIT at Build 2026; Agent Registration Service, Declarative Agent Manifest (agent.json), gRPC pub/sub bus, Memory Service; `wagent` CLI.
  - Source: https://blogs.windows.com/windowsdeveloper/2026/06/02/build-2026-furthering-windows-as-the-trusted-platform-for-development

### Updated
- **Google AI Ultra pricing** (Subscription Pricing): Reduced to $200/mo (from $249.99); new $100/mo tier added (5x Pro limits, 20 TB Drive, Antigravity priority).
  - Source: https://blog.google/products-and-platforms/products/google-one/google-ai-ultra/
- **Antigravity 2.0** (Web-Based IDEs, Assisted CLI Tools): GA at Google I/O 2026 on 2026-05-19; desktop app + CLI (`agy`) + SDK + Managed Agents API; multi-agent orchestration; successor to Gemini CLI (sunset June 18).
  - Source: https://blog.google/innovation-and-ai/technology/developers-tools/google-io-2026-developer-highlights/
- **Gemini Spark** (Cloud Automation): New 24/7 always-on personal AI agent; included with Google AI Ultra ($200/mo); runs on Cloud VMs; MCP connections to Canva, OpenTable, Instacart; US beta 2026-05-26.
  - Source: https://www.digitalapplied.com/blog/google-io-2026-complete-ai-announcement-guide
- **Cursor Composer 2.5** (Cursor Alternatives): Launched 2026-05-18 at $0.50/$2.50 per M tokens (10x cheaper than Opus 4.7); Cursor training larger model on Colossus 2 (Q3-Q4 2026 expected).
  - Source: https://www.digitalapplied.com/blog/agentic-coding-h2-2026-what-ships-next-after-io
- **GitHub Copilot** (Cursor Alternatives, VS Code Specific): Usage-based billing effective June 1, 2026; $0.01/AI credit model; free tier remains 2K completions + 50 premium req/month.
  - Source: https://codex.danielvaughan.com/2026/06/05/coding-agent-landscape-june-2026-codex-cli-copilot-flex-devin-desktop-antigravity-kiro
- **Android CLI 1.0** (CLI Tools): Google Android CLI stable at v1.0; enables AI agents to build Android apps from command line; "android studio" command taps Android Studio capabilities.
  - Source: https://techcrunch.com/2026/05/19/agentic-app-coding-gets-an-upgrade-with-googles-release-of-android-cli
- **Arena Elo scores** (Frontier Models, Benchmark Reference): Updated from arena.ai live data as of June 16, 2026: Claude Fable 5 #1 (1508), Claude Opus 4.6 Thinking #2 (1504), Claude Opus 4.7 Thinking #3 (1502), Claude Opus 4.6 #4 (1499), Claude Opus 4.7 #5 (1493), Muse Spark #6 (1487), Gemini 3.1 Pro #7 (1486), Gemini 3 Pro #8 (1486), Claude Opus 4.8 Thinking #9 (1483), GPT-5.5 High #10 (1481).
  - Source: https://arena.ai/leaderboard/text
- **MCP ecosystem stats** (MCP Ecosystem): Official registry 10,000+ active public servers; SDK downloads 97M+ monthly (March 2026); MCP donated to Agentic AI Foundation (Linux Foundation) Dec 2025; 2026-07-28 spec RC introduces stateless transport, Tasks primitive, enterprise auth.
  - Source: https://www.digitalapplied.com/blog/mcp-adoption-statistics-2026-model-context-protocol, https://blog.modelcontextprotocol.io/posts/2026-mcp-roadmap/
- **VS Code 1.124** (IDE Add-ons): Released June 10, 2026; Agents window (preview); Autopilot enabled by default; background send for sessions; session navigation via keyboard.
  - Source: https://code.visualstudio.com/updates
- **Document Version**: 3.30 -> 3.31; Last Updated badge, At a Glance, Highlights bumped to 2026-06-18.

### Notes
- GLM-5.2 is the second major Chinese open-source frontier model release within weeks of MiniMax M3. 753B parameters with 1M context at MIT license represents a significant accessibility milestone.
- Supertonic 3's 167x real-time on-device TTS (99M params, 31 languages) sets a new edge TTS benchmark.
- Google's Antigravity 2.0 converges developer (CLI) and consumer (Spark) agent surfaces under one harness.
- MCP 2026-07-28 spec RC introduces breaking changes: stateless transport, new required HTTP headers, Tasks lifecycle.

---

## Files in Release

- docs/readme.md
- docs/readme.pdf

---
*Generated on 2026-06-19T07:13:13.866Z*
