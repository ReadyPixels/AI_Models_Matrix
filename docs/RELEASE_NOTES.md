# Release v3.32

Release v3.32: [2026-06-20] - Version 3.32 - Claude Fable 5/Mythos 5 suspended, MiniMax M3 open-weight release, Junie GA, Cursor 1.0, Amazon Bedrock AgentCore Harness GA, Databricks Genie One, Vercel eve, Omnigent, new TTS/STT models, browser automation updates, AI safety tools

## Latest Changelog Entry

### [2026-06-20] - Version 3.32 - Claude Fable 5/Mythos 5 suspended, MiniMax M3 open-weight release, Junie GA, Cursor 1.0, Amazon Bedrock AgentCore Harness GA, Databricks Genie One, Vercel eve, Omnigent, new TTS/STT models, browser automation updates, AI safety tools

### Added
- **MiniMax M3** (Free-Source Models, Frontier Models): ~428B total / ~23B active MoE; 1M context; native multimodal (text/image/video); MiniMax Sparse Attention; $0.30/$1.20 per 1M (≤512K); open weights released ~2026-06-11; SWE-bench Verified 80.5%.
  - Source: https://huggingface.co/MiniMaxAI/MiniMax-M3, https://www.minimax.io/blog/minimax-m3
- **Qwen3.7-Plus** (Frontier Models): Alibaba latest Plus-tier model; 1M context; $0.40/$2.40 per 1M; released 2026-06-03.
  - Source: https://openrouter.ai/blog/announcements/may-release-spotlight/
- **Step 3.7 Flash** (Frontier Models): StepFun open-weight model; 1M context; free tier available; released 2026-05-28.
  - Source: https://openrouter.ai/blog/announcements/may-release-spotlight/
- **Mercury 2** (Model Router Services): Inception Labs diffusion LLM; 1,009 tok/s on Blackwell; $0.25/$0.75 per 1M; 128K context; released 2026-05-12.
  - Source: https://www.inceptionlabs.ai/blog/introducing-mercury-2
- **Grok Imagine Video 1.5** (Video Generation): xAI image-to-video; #1 Image-to-Video Arena (Elo 1330); native audio+video; $0.06/s; GA 2026-06-16.
  - Source: https://www.techtimes.com/articles/318635/20260618/grok-imagine-video-15-goes-live-xai-tops-ai-video-leaderboard-86-percent-below-sora.htm
- **HappyHorse-1.0** (Video Generation): Alibaba ATH open-source video model; #1 Artificial Analysis leaderboard; unified Transformer; simultaneous audio/video; 15B params.
  - Source: https://www.atlascloud.ai/blog/ai-updates/happyHorse-hits-1-api-coming-soon
- **Microsoft Mirage** (Video Generation): Video world model with persistent spatial memory; 10.57x faster; built on Wan2.2.
  - Source: https://the-decoder.com/microsoft-researchs-mirage-gives-video-generation-a-persistent-spatial-memory-that-doesnt-forget-whats-around-the-corner/
- **MAI-Voice-2** (TTS Proprietary): Microsoft expressive TTS; 15 languages; granular emotion control; custom voice from 5-60s clip; released 2026-06-02.
  - Source: https://microsoft.ai/news/mai-voice-2expressive-speech-in-10-languages/
- **MAI-Transcribe-1.5** (STT): Microsoft multilingual STT; 43 languages; SOTA FLEURS; 5x faster than Gemini 3.1; keyword biasing; released 2026-06-02.
  - Source: https://microsoft.ai/news/mai-transcribe-1-5more-accurate-context-aware-and-built-for-production/
- **Cohere Transcribe** (STT): Open-source 2B Conformer ASR; #1 HuggingFace Open ASR Leaderboard (5.42% WER); 14 languages; Apache 2.0.
  - Source: https://cohere.com/blog/transcribe
- **Higgs Audio v3 TTS** (TTS Proprietary): Boson AI voice chat TTS; 100+ languages; inline emotion/style tags; zero-shot cloning.
  - Source: https://www.boson.ai/blog/higgs-audio-v3-tts
- **Chatterbox Multilingual v3** (TTS Open Source): Resemble AI; 25 languages; 0.5B Llama backbone; PerTh watermarking; MIT license.
  - Source: https://www.resemble.ai/resources/chatterbox-multilingual-v3-tts-with-embedded-watermarking-for-25-languages
- **MisoTTS** (TTS Open Source): Miso Labs 8B emotive TTS; RVQ; conditions on text + audio; modified MIT.
  - Source: https://www.marktechpost.com/2026/06/04/miso-labs-releases-misotts-an-8b-emotive-text-to-speech-model-with-open-weights/
- **MiniMax Speech 2.6** (TTS Proprietary): <250ms latency; Fluent LoRA; non-standard text handling; released 2026-06-20.
  - Source: https://www.minimax.io/news/minimax-speech-26
- **Gladia Solaria-3** (STT): #1 on business audio; 5 European languages; released 2026-06-10.
  - Source: https://www.gladia.io/blog/solaria-3-speech-to-text-model-for-european-languages
- **Speechmatics Melia** (STT): Code-switching across 55+ languages; from $0.129/hr; released 2026-06-17.
  - Source: https://www.speechmatics.com/company/articles-and-news/introducing-melia-multilingual-speech-to-text-model
- **Voxtral Realtime** (STT): Mistral open-source streaming ASR; 13 languages; 480ms delay; Apache 2.0.
  - Source: https://arxiv.org/pdf/2602.11298
- **Granite Embedding Multilingual R2** (Embedding Models): IBM; 97M and 311M variants; best sub-100M multilingual embedder; 32K context; Apache 2.0.
  - Source: https://huggingface.co/blog/ibm-granite/granite-embedding-multilingual-r2
- **LFM2.5-Embedding-350M** (Embedding Models): Liquid AI bidirectional embedder; 11 languages; runs on CPU/edge.
  - Source: https://www.liquid.ai/blog/lfm2-5-retrievers
- **pplx-embed-v1** (Embedding Models): Perplexity state-of-the-art embeddings; 0.6B and 4B; MTEB Multilingual leader.
  - Source: https://research.perplexity.ai/articles/pplx-embed-state-of-the-art-embedding-models-for-web-scale-retrieval
- **ML-Embed-0.6B** (Embedding Models): CodeFuse AI; 3D Matryoshka Learning; ICML 2026; Apache 2.0.
  - Source: https://huggingface.co/codefuse-ai/ML-Embed-0.6B
- **Sponsio** (AI Safety): Runtime contract enforcement; deterministic agent safety; <0.01ms per tool call; Apache 2.0.
  - Source: https://sponsio.dev/
- **ToolShield** (AI Safety): ICML 2026; multi-turn safety defense; 30% attack reduction; MIT.
  - Source: https://github.com/CHATS-lab/ToolShield
- **MobileMoE** (SLMs): First sub-billion MoE family; 0.3B-0.9B active; 1.8-3.8x faster than dense.
  - Source: https://arxiv.org/html/2605.27358v1
- **SLM-10M** (SLMs): Liodon AI; leads sub-10M Open SLM Leaderboard; Apache 2.0.
  - Source: https://huggingface.co/blog/PY-AI-Dev/slm10-blog
- **Vercel eve** (Multi-Agent Platforms): Open-source agent framework; durable execution + sandbox + approvals; public preview 2026-06-17.
  - Source: https://vercel.com/blog/introducing-eve
- **Omnigent** (Multi-Agent Platforms): Databricks open-source meta-harness; compose/control/share agents; Apache 2.0.
  - Source: https://www.databricks.com/blog/introducing-omnigent-meta-harness-combine-control-and-share-your-agents
- **GitKraken Kepler** (Multi-Agent Platforms): Agentic Development Environment; multi-agent oversight; cross-repo coordination.
  - Source: https://www.gitkraken.com/blog/introducing-kepler-the-delivery-engine-for-agent-driven-development
- **LangChain Deep Agents** (Multi-Agent Platforms): Long-horizon agent harness; planning + subagents + memory; MIT.
  - Source: https://awesomeagents.ai/news/langchain-deep-agents-release/
- **Cloudflare Flue** (Multi-Agent Platforms): Agent framework on Cloudflare Workers; multi-agent; Durable Objects.
  - Source: https://blog.cloudflare.com/agents-platform-flue-sdk/
- **Amazon Bedrock AgentCore Harness** (Cloud Automation): GA 2026-06-18; 2 API calls to production agent; sandboxed runtime.
  - Source: https://aws.amazon.com/blogs/machine-learning/amazon-bedrock-agentcore-harness-is-now-generally-available-go-from-idea-to-production-grade-agent-in-minutes/
- **Databricks Genie One** (Cloud Automation): GA 2026-06-16; data-smart agentic coworker; iOS/Android/web; 50+ app integrations.
  - Source: https://www.databricks.com/blog/introducing-genie-one-genie-ontology-and-genie-agents
- **Thoughtworks Agent/works** (Cloud Automation): GA 2026-06-16; governed runtime for enterprise agents; any cloud.
  - Source: https://www.thoughtworks.com/en-us/about-us/news/2026/thoughtworks-launches-agent-works
- **Kore.ai Artemis** (Cloud Automation): GA 2026-05-21; AI-native agent platform; Azure launch partner.
  - Source: https://www.kore.ai/news/kore-ai-launches-artemis-the-new-generation-of-the-kore-ai-agent-platform-for-building-governing-and-optimizing-enterprise-ai
- **Browserless Agent** (Browser Automation): Fastest MCP browser agent; stateful sessions; command batching; released 2026-06-12.
  - Source: https://www.browserless.io/blog/introducing-browserless-agent
- **Lightpanda Agent** (Browser Automation): Native headless browser agent; PandaScript reproducible scripts; released 2026-06-17.
  - Source: https://lightpanda.io/blog/posts/introducing-lightpanda-agent-and-pandascript
- **Webwright** (Browser Automation): Microsoft SOTA on long-horizon web tasks; Codex/Claude Code plugins; released 2026-04-08.
  - Source: https://github.com/microsoft/Webwright
- **SimuLang** (Browser Automation): Playwright for entire desktop; browser + native apps + OS workflows; released 2026-05-19.
  - Source: https://www.simular.ai/articles/introducing-simulang-playwright-for-the-entire-desktop
- **Pioneer** (Fine-tuning Platforms): Fastino Labs agentic fine-tuning; synthetic dataset generation; 10-min fine-tuning.
  - Source: https://pioneer.ai/blog/introducing-pioneer
- **Laminar** (Evaluation & Observability): Rust-based open-source observability; ultra-fast; OpenTelemetry-native; YC S24.
  - Source: https://github.com/lmnr-ai/lmnr
- **Agentic CLEAR** (Evaluation & Observability): IBM Research ACL 2026; automated multi-level agent evaluation.
  - Source: https://ibm.github.io/CLEAR/
- **Microsoft Foundry Toolkit for VS Code** (IDE Add-ons): GA 2026-04-16; end-to-end Hosted Agent lifecycle; consolidated extension.
  - Source: https://techcommunity.microsoft.com/blog/azuredevcommunityblog/foundry-toolkit-for-vs-code-at-build-hosted-agents-end-to-end-a-smarter-toolbox-/4524941
- **VS Code ACP Client** (IDE Add-ons): Connects 11+ AI agents to VS Code via Agent Client Protocol; MIT.
  - Source: https://blog.brightcoding.dev/2026/06/16/stop-juggling-ai-tools-vs-code-acp-client-unifies-every-agent
- **Google Agents CLI** (CLI Tools): Unified ADLC for Google Cloud Agent Platform; released 2026-04-22.
  - Source: https://developers.googleblog.com/agents-cli-in-agent-platform-create-to-production-in-one-cli/
- **Peri** (CLI Tools): Rust terminal coding agent; Claude Code compatible; MCP & ACP; Apache 2.0.
  - Source: https://github.com/KonghaYao/peri

### Updated
- **Claude Fable 5 / Mythos 5** (Frontier Models): Access suspended globally on 2026-06-12 per US government export control directive. May be restored for US users around July 1, 2026.
  - Source: https://www.anthropic.com/news/fable-mythos-access
- **GPT-5.5 Instant** (Frontier Models, Cached Pricing): API pricing corrected to $0.20/$1.00 per 1M (input/output), not $5.00/$30.00. Replaced GPT-5.3 Instant as free-tier ChatGPT default on 2026-05-05.
  - Source: https://openai.com/index/gpt-5-5-instant/
- **Gemini Embedding 2** (Embedding Models): GA 2026-04-22 (was preview).
  - Source: https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-embedding-2-generally-available/
- **Junie CLI** (CLI Tools, JetBrains Add-ons): Left beta, GA 2026-06-17. ACP-based IDE integration; agentic debugging; BYOK; local model support.
  - Source: https://blog.jetbrains.com/junie/2026/06/junie-coding-agent-out-of-beta/
- **Cursor** (IDEs): Cursor 1.0 released 2026-05-29 with Background Agents, Multi-Repo Context, Shadow Workspace. Pro $20/mo, Business $40/user/mo.
  - Source: https://shipped.news/articles/cursor-1-0-official.html
- **Arena Elo** (Frontier Models): Updated Arena Elo ratings from LMArena June 2026 data. Claude Opus 4.8 now #1 (1506), GPT-5.5 Pro #3 (1551), Gemini 3.1 Pro #4 (1505).
  - Source: https://www.swfte.com/lmsys-leaderboard
- **MCP Spec 2026-07-28** (MCP Ecosystem): Release candidate locked 2026-05-21. Stateless core, Tasks extension, MCP Apps, OAuth 2.1 alignment. Final spec ships 2026-07-28.
  - Source: https://blog.modelcontextprotocol.io/posts/2026-07-28-release-candidate/
- **OpenRouter** (Unified APIs): Added 5 major models in 10 days (May 27 - Jun 4): Claude Opus 4.8, Step 3.7 Flash, MiniMax M3, Qwen3.7-Plus, NVIDIA Nemotron 3 Ultra. Fusion API GA. Microsoft MAI models added.
  - Source: https://www.digitalapplied.com/blog/openrouter-new-models-june-2026-roundup-pricing-rankings
- **Gemini 3.5 Flash** (Frontier Models): Released 2026-05-19 at Google I/O; $1.50/$9.00 per 1M; 4x faster than 3.1 Pro; strongest agentic and coding model from Google.
  - Source: https://deepmind.google/blog/gemini-3-5-frontier-intelligence-with-action/
- **Antigravity 2.0** (CLI Tools): GA at Google I/O 2026; successor to Gemini CLI (sunset June 18).
  - Source: https://blog.google/innovation-and-ai/technology/developers-tools/google-io-2026-developer-highlights/
- **Sora 2** (Video Generation): Consumer app shut down 2026-04-26; API shutdown 2026-09-24.
  - Source: https://www.techtimes.com/articles/318635/20260618/grok-imagine-video-15-goes-live-xai-tops-ai-video-leaderboard-86-percent-below-sora.htm
- **Xcode 27** (IDEs): Agentic coding with Anthropic/Google/OpenAI models; interactive planning; Device Hub; MCP plug-ins; GitHub/Figma integration.
  - Source: https://www.apple.com/ca/newsroom/2026/06/apple-aids-app-development-with-new-intelligence-frameworks-and-advanced-tools/
- **IntelliJ IDEA 2026.1** (IDEs): ACP Registry for one-click agent install; Codex/Cursor/Claude Agent support; database access for AI agents.
  - Source: https://blog.jetbrains.com/idea/2026/03/intellij-idea-2026-1/
- **Mistral Medium 3.5** (Frontier Models): Pricing corrected to $1.50/$7.50 per 1M.
  - Source: https://mistral.ai/news/vibe-agent/
- **Mistral Large 3** (Frontier Models, Cached Pricing): Pricing corrected to $0.50/$1.50 per 1M (was $2/$6 from Large 2).
  - Source: https://awesomeagents.ai/pricing/llm-api-pricing-comparison/
- **Mistral Small 4** (Frontier Models, Cached Pricing): Pricing corrected to $0.10/$0.30 per 1M (was $0.15/$0.60).
  - Source: https://awesomeagents.ai/pricing/llm-api-pricing-comparison/

### Removed / Deprecated
- **Gemini CLI** (CLI Tools): Stopped serving requests 2026-06-18. Migrate to Antigravity CLI (`agy`).
  - Source: https://blog.google/innovation-and-ai/technology/developers-tools/google-io-2026-developer-highlights/

## Files in Release

- docs/readme.md
- docs/readme.pdf

---
*Generated on 2026-06-20T08:58:13.856Z*
