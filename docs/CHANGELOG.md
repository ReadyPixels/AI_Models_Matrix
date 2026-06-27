## [2026-06-26] - Version 3.37 - GPT-Image-2, Apple Foundation Models 3, GPU pricing update, Cursor $20/$60/$200, Windsurf $15 Pro, GPT-4.1 ChatGPT retirement, Gemini 3.1 Flash Image pricing fix, MiniMax Speech 2.8 in Comparison Tables

### Added
- **GPT Image 2** (Image Generation): ChatGPT Images 2.0; 2K resolution; agentic reasoning; multilingual text rendering; released 2026-04-21; $0.006-$0.211/image (quality/resolution); $8/1M image input tokens; $30/1M image output tokens. Source: https://openai.com/index/introducing-chatgpt-images-2-0/
- **Apple Foundation Models 3rd Generation** (SLMs): AFM 3 Core (3B dense), AFM 3 Core Advanced (20B sparse, 1-4B active), AFM 3 Cloud, ADM 3 Cloud (Image), AFM 3 Cloud Pro. Announced June 8, 2026 at WWDC 2026. Not available via public API; power Apple Intelligence on-device and Private Cloud Compute. Source: https://machinelearning.apple.com/research/introducing-third-generation-of-apple-foundation-models
- **Microsoft VibeVoice-Realtime (0.5B)** (TTS Open Source): Real-time streaming TTS; 0.5B params; <300ms TTFA; streaming text input; ~10-min robust generation; Qwen2.5 base; MIT license; released 2025-12-03. Source: https://github.com/microsoft/VibeVoice
- **Microsoft VibeVoice-ASR (7B)** (STT Open Source): 60-min single-pass ASR with speaker diarization and timestamps; 50+ languages; structured Who/When/What output; MIT license; released 2026-01-21. Source: https://github.com/microsoft/VibeVoice

### Updated
- **GPU Cloud pricing table**: Updated RunPod RTX 4090 to $0.34-$0.69/hr; updated Vast.ai to ~$0.09-$0.59/hr. Source: https://www.runpod.io/pricing, https://www.buildmvpfast.com/api-costs/gpu
- **OpenRouter** (Unified APIs): Added GPT-Image-1.5, GPT-Image-2, Poolside Laguna, Qwen3-Coder to new models list. Source: https://openrouter.ai/models
- **GPT-4.1 / mini / nano**: Added ChatGPT retirement date (Feb 13, 2026) across all relevant tables. API remains available. Source: https://openai.com/index/retiring-gpt-4o-and-older-models/
- **Gemini 3.1 Flash Image pricing**: Corrected to $0.50/1M text+image input tokens; output images by resolution ($0.045/512px, $0.067/1Kpx). Source: https://ai.google.dev/gemini-api/docs/pricing
- **Cursor pricing**: Updated to Pro $20/mo, Pro+ $60/mo, Ultra $200/mo. Source: https://felloai.com/cursor-pricing/
- **Windsurf pricing**: Updated Pro tier to $15/mo. Source: https://uibakery.io/blog/windsurf-vs-cursor-pricing
- **Cursor vs Windsurf comparison**: Updated to June 2026 pricing.
- **Value-For-Money Ranking**: Updated to reflect Windsurf Pro at $15/mo as best value paid tier.
- **Claude Fable 5** (Frontier Models note): Clarified status -- removed from subscription plans June 23, requires usage credits. Mythos 5 only via Project Glasswing.
- **MiniMax Speech** (Comparison Tables): Updated from v2.6 to v2.8.
- **Data Sources**: Added Apple Foundation Models, OpenAI GPT-4.1 retirement, GPT-Image-2 sources.
- **Header & Metadata**: Updated Last Updated badge to 2026-06-26 19:03 UTC; incremented document version to 3.37.

---

## [2026-06-26] - Version 3.36 - Corrected GPT-4.5 API retirement (July 2025), Gemini 3.1 Flash image pricing (resolution-based output), Cursor $20/$60/$200, Windsurf $15 Pro, GPT-4.1 ChatGPT retirement (Feb 2026)

### Corrected
- **GPT-4.5** (Training Data Cutoffs): Previous note said "API unaffected" -- actually retired from API July 2025. Source: https://developers.openai.com/api/docs/deprecations
- **GPT-4.5** (Comprehensive Benchmark): Added retirement tracking note.
- **Gemini 3.1 Flash Image pricing**: Previous "$0.25/$1.50 per 1M" was incorrect (that was Flash-Lite pricing). Corrected to $0.50/1M text+image input; output by resolution ($0.045/512px, $0.067/1Kpx). Source: https://ai.google.dev/gemini-api/docs/pricing
- **GPT-4.1 / mini / nano**: Added ChatGPT retirement date (Feb 13, 2026) across all tables. API remains available. Source: https://openai.com/index/retiring-gpt-4o-and-older-models/
- **Cursor pricing**: Updated from $19/$39 to actual 2026 pricing: Pro $20/mo, Pro+ $60/mo, Ultra $200/mo. Source: https://felloai.com/cursor-pricing/
- **Windsurf pricing**: Updated Pro tier from $20 to $15/mo. Source: https://uibakery.io/blog/windsurf-vs-cursor-pricing
- **Claude Fable 5** (Frontier Models note): Clarified status -- removed from subscription plans June 23, requires usage credits. Mythos 5 only accessible via Project Glasswing.

---

## [2026-06-26] - Version 3.35 - Cartesia Sonic-3.5/Ink-2 (TTS/STT), MiniMax M2.7 to LLM tables, MiniMax Speech 2.8, Cohere Command A+/Transcribe v2, Google AI Ultra $99.99 pricing, Seed 2.1 Pro tracking note, Cursor $20/$60/$200 pricing, Windsurf $15 Pro, GPT-4.1 ChatGPT retirement, GPT-4.5 API correction, Gemini 3.1 Flash Image pricing fix

### Added
- **Cartesia Sonic-3.5** (TTS Proprietary): #1 Artificial Analysis Speech Arena; ~$39/1M chars; 40+ languages; ~100ms TTFA; released 2026-06-21. Source: https://www.cartesia.ai/launch/
- **Cartesia Ink-2** (STT): #1 Artificial Analysis Speech-to-Text leaderboard; real-time streaming; native turn detection; released 2026-06-21. Source: https://www.cartesia.ai/launch/
- **MiniMax M2.7** (Cached & Batch Pricing, Model Pricing Comparison, Commercial Coding Models, Output Token Limits, Free-Source Models): Self-evolution LLM; $0.30/$1.20; 205K context; SWE-Pro 56.22%; Agent Teams native; released 2026-03-18. Source: https://www.minimax.io/news/minimax-m27-en
- **Cohere Command A+** (Cached & Batch Pricing, Model Pricing Comparison): 25B active (218B total MoE); open-weight; faster than GPT-5.4 nano, Claude Haiku, Grok 4.3; released 2026-05. Source: https://artificialanalysis.ai/articles/cohere-launches-open-weights-model-command-a-more-than-a-year-since-the-command-a-release
- **Cohere Transcribe v2** (STT): Real-time streaming STT; open-source Apache 2.0; released 2026-05. Source: https://betakit.com/qa-behind-the-scenes-of-coheres-new-ai-transcription-model/
- **MiniMax Speech 2.8 / 2.8 HD** (TTS Proprietary): 40+ languages; 300+ voices; $100/1M chars (HD); released 2026-06-20. Source: https://www.minimax.io/news/minimax-speech-28
- **North Mini Code** (Commercial Coding Models): 30B MoE (3B active); Apache 2.0; free on OpenRouter; released 2026-06-09. Source: https://andrew.ooo/answers/what-is-north-mini-code-cohere-developer-model-june-2026/
- **MiniMax Hailuo 2.3** (Video Generation): Successor to Hailuo 02; 1080p; released 2026-06-22. Source: https://www.minimax.io/news/minimax-hailuo-23
- **Cohere** (Free Tier APIs): North Mini Code, Command A+ available with limited free tier.
- **Seed 2.1 Pro** (Frontier Models note): Early-access preview; #8 Code Arena Frontend (1539); on par with Claude Opus 4.6; no public API yet. Source: https://felloai.com/seed-2-1-pro/

### Updated
- **Speech Arena table**: Sonic-3.5 now #1 (was Gemini 3.1 Flash TTS). Source: https://artificialanalysis.ai/text-to-speech, June 2026.
- **Google AI Ultra pricing**: Corrected from $100 to $99.99/mo. Source: https://blog.google/products-and-platforms/products/google-one/google-ai-subscriptions/
- **Google Antigravity pricing**: Updated to reflect $99.99 Ultra tier.
- **MiniMax Speech 2.5/2.6**: Superseded by 2.8/2.8 HD in TTS table.
- **Claude Fable 5** (Frontier Models note): Updated status -- removed from subscription plans June 23; requires usage credits. Mythos 5 remains offline, accessible only via Project Glasswing. Source: https://www.anthropic.com/news/fable-mythos-access
- **GPT-4.5** (Training Data Cutoffs): Corrected -- retired from API July 2025; retiring from ChatGPT June 27, 2026. Source: https://developers.openai.com/api/docs/deprecations, https://help.openai.com/en/articles/9624314-model-release-notes
- **GPT-4.1 / mini / nano**: Added ChatGPT retirement note (Feb 13, 2026); API still available. Updated across Output Token Limits, Cached & Batch Pricing, Model Pricing Comparison, Training Data Cutoffs, Free Tier APIs tables. Source: https://openai.com/index/retiring-gpt-4o-and-older-models/
- **Gemini 3.1 Flash Image pricing**: Corrected from $0.25/$1.50 to actual pricing -- $0.50/1M text+image input tokens; output images by resolution ($0.045/512px, $0.067/1Kpx). Source: https://ai.google.dev/gemini-api/docs/pricing, https://deepmind.google/models/model-cards/gemini-3-1-flash-image/
- **Cursor pricing**: Updated to 2026 values -- Pro $20/mo, Pro+ $60/mo, Ultra $200/mo. Source: https://felloai.com/cursor-pricing/
- **Windsurf pricing**: Updated Pro tier to $15/mo. Source: https://uibakery.io/blog/windsurf-vs-cursor-pricing
- **Cursor vs Windsurf comparison**: Updated to June 2026 pricing; Windsurf Pro now $15/mo vs Cursor Pro $20/mo.
- **Value-For-Money Ranking**: Updated to reflect Windsurf Pro at $15/mo as best value paid tier.
- **Data Sources** (Reference): Added ByteDance Seed blog URL. Source: https://seed.bytedance.com/en/blog/seed-2-1-preview-model-release-on-arena
- **Header & Metadata**: Updated Last Updated badge to 2026-06-26 17:30 UTC; incremented document version to 3.35.

### Removed / Deprecated
- **MiniMax Speech 2.6** (TTS table): Superseded by Speech 2.8.
- **GPT-4.5 from Training Cutoffs**: Previous note "API unaffected" was incorrect; GPT-4.5 API was retired July 2025.

---

## [2026-06-26] - Version 3.34 - GPT-4.1 family pricing, Grok 4.3 on Amazon Bedrock, Claude Tag (Slack AI teammate), Claude Fable 5 usage credits, Gemini 3.1 Flash Image GA pricing, GPT-4.5 ChatGPT retirement notice

### Added
- **GPT-4.1 / mini / nano** (Pricing & Specs): Added to Output Token Limits, Cached & Batch Pricing, Training Data Cutoffs, Model Pricing Comparison tables. Pricing: GPT-4.1 $2/$8, GPT-4.1 mini $0.40/$1.60, GPT-4.1 nano $0.10/$0.40. 1M context, June 2024 knowledge cutoff. Source: https://openai.com/index/gpt-4-1/
- **Grok 4.3 on Amazon Bedrock** (API Providers): Added to xAI model list and Regional Availability. Pricing $1.25/$2.50 on-demand; 1M token context. Source: https://aws.amazon.com/blogs/aws/aws-weekly-roundup-ny-summit-recap-local-zone-in-hanoi-grok-4-3-in-bedrock-price-reductions-and-more-june-22-2026/
- **Claude Tag** (IDE Add-ons note): Anthropic's always-on AI teammate for Slack; persistent memory per channel; Team/Enterprise plans. Source: https://www.anthropic.com/news/introducing-claude-tag
- **Gemini 3.1 Flash Image** (Image Generation): Added to Image Generation table; GA June 2026; $0.25/$1.50 per 1M (standard API), $60/1M image output tokens. Source: https://deepmind.google/models/model-cards/gemini-3-1-flash-image/

### Updated
- **Claude Fable 5** (Frontier Models note): Removed from Pro/Max/Team/Enterprise subscription plans on June 23; now requires usage credits at standard API rates. Mythos 5 remains offline. Source: https://www.anthropic.com/news/claude-fable-5-mythos-5
- **GPT-4.5** (Training Data Cutoffs): Added note: retiring from ChatGPT on June 27, 2026; API unaffected. Source: https://help.openai.com/en/articles/9624314-model-release-notes
- **xAI Regional Availability**: Added Amazon Bedrock as distribution channel (June 2026). Source: https://aws.amazon.com/blogs/aws/aws-weekly-roundup-ny-summit-recap-local-zone-in-hanoi-grok-4-3-in-bedrock-price-reductions-and-more-june-22-2026/
- **Model Pricing Comparison table**: Re-sorted by input price; added GPT-4.1 models, Gemini 3.1 Flash Image, Qwen3.7-Max (was missing). Data as of 2026-06-26.
- **Free AI APIs for Coding**: Added OpenAI GPT-4.1 nano (free credits for new accounts).
- **Pricing Tiers Budget row**: Added GPT-4.1 nano.
- **Release Windows**: Added GPT-4.1 family (2026-04).
- **Sort by Latest Update**: Added GPT-4.1/4.1 mini entries.

### Removed / Deprecated
- **Gemini 3.1 Flash-Lite Preview**: Deprecated 2026-05-11, shutting down July 9, 2026. Migrate to gemini-3-1-flash-lite. Source: https://ai.google.dev/gemini-api/docs/changelog
- **Gemini 3.1 Flash Image Preview / Gemini 3 Pro Image Preview**: Shut down June 25, 2026. Migrate to GA gemini-3-1-flash-image. Source: https://ai.google.dev/gemini-api/docs/changelog.md.txt

---

## [2026-06-21] - Version 3.33 - MiniMax Hailuo 02 video model, MiniMax Speech 2.6, Mistral Voxtral TTS 4B, Apple Core AI/Foundation Models at WWDC26, Aion 1.0 on-device SLMs, Gemini CLI shutdown/Antigravity CLI replacement, Amazon Bedrock AgentCore Harness GA, Databricks Genie One GA, Vercel eve agent framework, Omnigent meta-harness, GitKraken Kepler ADE, Zensar AgentMesh, Konecta Kolibri, Sedai AI Agent Optimization, GMI Cloud AgentBox, OpenRouter Fusion, GLM 5.2 on Fireworks, Gemma 4 on Cerebras, MCP 2026-07-28 stateless spec RC, new VS Code extensions, browser automation tools, AI safety updates

### Added
- **MiniMax Hailuo 02** (Video Generation): 3x params vs predecessor, 4x training data, native 1080p, #2 Artificial Analysis Video Arena; released 2026-06-20.
  - Source: https://www.minimax.io/news/minimax-hailuo-02
- **MiniMax Video-01** (Video Generation): First AI-native video model from MiniMax; 720p/25fps; text-to-video and image-to-video; up to 6s clips; released 2026-06-20.
  - Source: https://www.minimax.io/news/video-01
- **MiniMax Speech 2.6** (TTS Proprietary): <250ms latency; Fluent LoRA; non-standard text handling; released 2026-06-20.
  - Source: https://www.minimax.io/news/minimax-speech-26
- **Mistral Voxtral TTS** (TTS Proprietary): 4B parameter TTS; 9 languages; 70ms latency; voice cloning from 3s audio; $0.016/1K chars; released 2026-06-18.
  - Source: https://mistral.ai/news/voxtral-tts
- **Apple Core AI / Foundation Models** (SLMs / On-Device): WWDC26 announcement; successor to Core ML; on-device inference + Private Cloud Compute; hybrid platform spanning on-device, PCC, and third-party models (Claude/Gemini); open-source Swift framework; Aion 1.0 Instruct (open weights, Edge Insider preview) and Aion 1.0 Plan (14B reasoning, 32K context, agentic, shipping in-box "in the coming months"); released 2026-06-20.
  - Source: https://developer.apple.com/documentation/coreai, https://blog.google/innovation-and-ai/technology/developers-tools/google-io-2026-developer-highlights/
- **Aion 1.0** (SLMs): Microsoft on-device AI family; Aion 1.0 Instruct (small open-weights SLM for everyday tasks, Edge Insider preview, HuggingFace open-source July 2026) and Aion 1.0 Plan (14B reasoning model, 32K context, agentic workflows, shipping in-box Windows "in the coming months"); released 2026-06-02.
  - Source: https://blogs.windows.com/windowsdeveloper/2026/06/02/build-2026-furthering-windows-as-the-trusted-platform-for-development/
- **Antigravity CLI (`agy`)** (CLI Tools): Google's replacement for Gemini CLI; Go-based; async multi-agent workflows; free tier ~20 req/day; released 2026-06-18.
  - Source: https://blog.google/innovation-and-ai/technology/developers-tools/google-io-2026-developer-highlights/
- **Vercel eve** (Multi-Agent Platforms): Open-source agent framework; filesystem-first TypeScript; durable execution; sandboxed compute; human-in-the-loop; public preview 2026-06-17.
  - Source: https://vercel.com/blog/introducing-eve
- **Omnigent** (Multi-Agent Platforms): Databricks open-source meta-harness; composes multiple agents (Claude Code, Codex, Pi); stateful policies; session sharing; Apache 2.0; alpha 2026-06-13.
  - Source: https://www.databricks.com/blog/introducing-omnigent-meta-harness-combine-control-and-share-your-agents
- **GitKraken Kepler** (Agent Platforms): Agentic Development Environment; multi-agent orchestration; conflict resolver; branch intelligence; released 2026-06-15.
  - Source: https://www.gitkraken.com/blog/introducing-kepler-the-delivery-engine-for-agent-driven-development
- **Zensar ZenseAI.AgentMesh** (Agent Platforms): Enterprise agentic AI platform; 80+ pre-built agents; governed orchestration; EU AI Act alignment; GA 2026-06-19.
  - Source: https://www.prnewswire.com/news-releases/zensar-technologies-launches-zenseaiagentmesh-to-accelerate-enterprise-ai-adoption-at-scale-302792208.html
- **Konecta Kolibri** (Agent Platforms): Agentic AI orchestration platform; 80% pre-built use cases; FinOps dashboards; GA 2026-06-16.
  - Source: https://konecta.com/news-insights/konecta-launches-kolibri-an-agentic-platform-to-speed-up-enterprise-deployment-of-agentic-ai-and-end-pilot-purgatory
- **Sedai AI Agent Optimization** (Agent Platforms): Autonomous platform for AI agent optimization; governance, observability, smart routing; early access 2026-06-09.
  - Source: https://www.prnewswire.com/news-releases/sedai-launches-the-first-autonomous-platform-for-ai-agent-optimization-302792208.html
- **GMI Cloud AgentBox** (Agent Platforms): Marketplace for AI agents; 100+ models via single key; usage-based pricing; GA 2026-06-08.
  - Source: https://www.gmicloud.ai/en/blog/agentbox-is-live-the-whole-stack-for-production-ai-agents-in-one-place
- **OpenRouter Fusion** (API Providers): Model synthesis tool; combines multiple model outputs via judge; Fable 5 + GPT-5.5 fusion scored 69.0% surpassing individual models; launched 2026-06-12.
  - Source: https://openrouter.ai/blog/announcements/fusion-beats-frontier/
- **Kilo for GitHub** (CLI Tools): AI coding agent living in GitHub; @kilocode-bot mentions in issues/PRs; Cloud Agent backend; released 2026-06-18.
  - Source: https://blog.kilo.ai/p/introducing-kilo-for-github
- **Qoder 1.0** (IDEs): Alibaba Cloud Autonomous Development Desktop; Quest window for agent command; editor + agent parallel workspaces; GA 2026-06-16.
  - Source: https://www.alibabacloud.com/blog/introducing-qoder-1-0-from-ai-ide-to-autonomous-development-desktop_603260
- **OpenHands Agent Canvas** (Agent Platforms): Workspace for creating automations integrating Slack, GitHub; self-hostable; released 2026-06-16.
  - Source: https://www.openhands.dev/blog/introducing-agent-canvas
- **Hermes Agent v0.17.0** (CLI Tools): Major desktop app update; live subagent watch-windows; VS Code theme support; released 2026-06-19.
  - Source: https://github.com/NousResearch/hermes-agent/releases/tag/v2026.6.19
- **Mastra Harness** (Multi-Agent Platforms): Agent loop abstraction; persistent sessions; tool approval; model switching; available in @mastra/core@1.43.0; released 2026-06-18.
  - Source: https://mastra.ai/blog/announcing-agent-harness
- **Kling 3.0 Turbo** (Video Generation): Fast-preview mode; 1-15s clips at 480p/720p; rapid iteration before full Kling 3.0 production; released 2026-06-17.
  - Source: https://news.financenewsworld.com/story/564950/kling-30-turbo-released-kling-ai-brings-fast-video-previews-for-rapid-creative-iteration.html
- **ZONOS2** (TTS Open Source): Zyphra 8B MoE TTS; Apache 2.0; multilingual + code-switched; zero-shot voice cloning; ECAPA-TDNN speaker embeddings; released 2026-06-12.
  - Source: https://www.zyphra.com/our-work/zonos2
- **dots.tts** (TTS Open Source): RedNote 2B fully continuous AR TTS; 48kHz AudioVAE; no discrete tokens; Apache 2.0; released 2026-06.
  - Source: https://github.com/rednote-hilab/dots.tts
- **Soniox v5 Async** (STT): Structured speech-to-text; speaker separation; language IDs; normalized structured entities; released 2026-06-11.
  - Source: https://soniox.com/blog/soniox-v5-async
- **Gnani Prisma v2.5** (STT): #1 in 8 of 9 Indian languages; 15% lower WER rural Hindi; 14M hours training data; released 2026-06-19.
  - Source: https://cxotoday.com/media-coverage/gnani-ai-launches-prisma-v2-5-ranked-1-in-8-of-9-indian-languages-on-real-world-and-noisy-asr-benchmarks/
- **NVIDIA Nemotron 3.5 ASR Streaming 0.6B** (STT): 40 language-locales; language-ID prompt conditioning; punctuation/capitalization; released 2026-06-04.
  - Source: https://huggingface.co/nvidia/nemotron-speech-streaming-en-0.6b
- **Infron** (API Providers): Enterprise AI model inference provider; unified API; up to 35% off direct pricing; provisioned throughput plan; released 2026-06-10.
  - Source: https://infron.ai/
- **Aethir Mesh** (API Providers): Open-source LLM API platform; single API for open-source models (DeepSeek V4, Kimi K2.6, etc.); decentralized GPU infrastructure; released 2026-06-12.
  - Source: https://aethir.com/blog-posts/aethir-mesh-opens-the-llm-api-layer-to-everyone-leverage-top-tier-open-source-llms
- **Unsloth Studio** (Fine-tuning Platforms): No-code local training and inference; runs 100% offline; GGUF/Safetensors; tool-calling; web search; released 2026-06-18.
  - Source: https://unsloth.ai/
- **Arkor** (Fine-tuning Platforms): TypeScript framework for fine-tuning open-weight LLMs; type-safe configs; local Studio; managed GPUs; alpha 2026-06-11.
  - Source: https://github.com/WlyZhang/arkor
- **Langtrain** (Fine-tuning Platforms): Sovereign AI platform; fine-tune, align, deploy on own infrastructure; 20+ models; public beta 2026-06.
  - Source: https://www.langtrain.xyz/
- **Dynatrace dt-evals** (Evaluation & Observability): Open-source CLI for LLM/agent quality evaluation from real traces; LLM judge scoring; CI/CD integration; released 2026-06-11.
  - Source: https://www.dynatrace.com/news/blog/evaluate-llm-and-agent-quality-in-dynatrace-ai-observability/
- **Currai** (Evaluation & Observability): AI observability platform; prompt tracing; A/B testing; LLM evaluations; cost analytics; released 2026-06-18.
  - Source: https://www.currai.app
- **Agentic CLEAR** (Evaluation & Observability): IBM multi-level agent evaluation; LLM-as-judge with Key Point Analysis; ACL 2026; released 2026.
  - Source: https://ibm.github.io/CLEAR/
- **tracesage** (Evaluation & Observability): Local-first observability for LangChain/LangGraph agents; interactive graph + timeline UI; MCP tool-source attribution; pytest fixture; MIT; released 2026-06-16.
  - Source: https://dev.to/kjgpta/tracesage-see-inside-your-langgraph-agents-55ek
- **MOTHRAG** (RAG Frameworks): Deterministic multi-hop RAG; research-SOTA parity on commodity LLM APIs; no GPU; proof tree per answer; Apache 2.0; released 2026-06-17.
  - Source: https://github.com/juliangeymonat-jpg/mothrag
- **AkasicDB / Omni RAG** (RAG Frameworks): Unified vector-graph-relational DBMS; Omni RAG improves accuracy by 78% vs conventional RAG; 20x faster complex queries; SIGMOD 2026; released 2026-06-19.
  - Source: https://techxplore.com/news/2026-06-generation-database-ai-hallucinations-accuracy.html
- **Ennoia** (RAG Frameworks): Declarative Document Indexing framework; typed schemas; hybrid filter + vector search; MCP tool surface; Apache 2.0; alpha 2026-06.
  - Source: https://github.com/vunone/ennoia
- **VORTEXRAG** (RAG Frameworks): 7-layer pipeline solving semantic drift + context poisoning; EM=74.8 on multi-hop QA; MIT; released 2026-05-18.
  - Source: https://github.com/vignesh2027/VORTEXRAG
- **MemGraphRAG** (RAG Frameworks): Memory-based multi-agent graph RAG; three-layer memory architecture; KDD 2026; MIT; released 2026-05-17.
  - Source: https://github.com/XMUDeepLIT/MemGraphRAG
- **UnWeaver** (RAG Frameworks): Entity-based decomposition RAG; better than GraphRAG precision without explicit graph; ICLR 2026; released 2026-06-08.
  - Source: https://arxiv.org/html/2603.29875
- **Google Agentic RAG** (RAG Frameworks): Gemini Enterprise Agent Platform; multi-agent workflow with sufficient context agent; +34% accuracy vs standard RAG; public preview 2026-06-05.
  - Source: https://research.google/blog/unlocking-dependable-responses-with-gemini-enterprise-agent-platforms-agentic-rag/
- **LFM2.5 Retrievers** (Embedding Models): Liquid AI bidirectional embedder; LFM2.5-ColBERT-350M and LFM2.5-Embedding-350M; 11 languages; runs on CPU/edge; released 2026-06-18.
  - Source: https://www.liquid.ai/blog/lfm2-5-retrievers
- **edge-lm** (SLMs): Gemma 4 edge-optimized checkpoints; 7x smaller; E2B in 1.44GB; MLX-ready; MIT; released 2026-06-02.
  - Source: https://github.com/TheStageAI/edge-lm
- **Atome LM** (SLMs): Ternary zero-heap LM for microcontrollers; 60K params; runs on ESP32; Apache 2.0; released 2026-05-23.
  - Source: https://github.com/TilelliLab/atome-lm
- **mech-gov-framework** (AI Safety): Mechanical Governance for LLM decisions; model-agnostic; hard gates; entropy commit-reveal; Apache 2.0; released 2026-06-17.
  - Source: https://github.com/SantanderAI/mech-gov-framework
- **Vermillio** (AI Safety): AI-Guardrails-as-a-Service SDK; real-time prompt/response filtering; copyright and data leakage protection; released 2026-06-11.
  - Source: https://www.archynewsy.com/vermillio-launches-sdk-and-ai-guardrails-as-a-service/
- **Amazon Bedrock Guardrails InvokeGuardrailChecks API** (AI Safety): Granular per-request safeguard checks; numeric scores; custom thresholds; detect-only mode; released 2026-06-16.
  - Source: https://aws.amazon.com/blogs/machine-learning/safeguard-your-agentic-ai-applications-with-the-amazon-bedrock-guardrails-invokeguardrailchecks-api/
- **Google AI Control Roadmap** (AI Safety): Defense-in-depth framework for agent security; MITRE ATT&CK-based threat modeling; AI supervisor monitoring; detection/prevention/response levels; published 2026-06-18.
  - Source: https://deepmind.google/blog/securing-the-future-of-ai-agents/
- **Prompt Foundry** (IDE Add-ons): VS Code/Cursor extension; modular prompt blocks with Liquid syntax; MCP server for context updates; released 2026-06-18.
  - Source: https://github.com/simondevries/prompt-foundry
- **GrackerAI** (IDE Add-ons): Free VS Code extension; validates llms.txt, robots.txt, AI visibility signals; released 2026-06-16.
  - Source: https://gracker.ai/blog/grackerai-brings-ai-visibility-checks-into-vs-code
- **A11yResolver** (IDE Add-ons): VS Code extension for accessibility remediation; AI agent flags WCAG issues; 50-70% time reduction; free during beta; released 2026-06-18.
  - Source: https://dev.to/a11ysolutions/how-i-cut-accessibility-remediation-time-by-70-without-leaving-vs-code-igi
- **Dev Browser** (Browser Automation): Claude Code plugin for browser automation; stateful Playwright wrapper; released 2026-06-19.
  - Source: https://blog.brightcoding.dev/2026/06/19/dev-browser-the-revolutionary-claude-code-automation-plugin
- **Intuned** (Browser Automation): YC-backed browser automation as code; AI agent generates Playwright code; auto-healing; released 2026-06-08.
  - Source: https://runany.dev/blog/intuned-browser-automation-yc-s22/
- **Veilbrowser** (Browser Automation): Stealth browser for AI agents; real Chrome over raw CDP; passes sannysoft 57/57; MCP-native; MIT; released 2026-06-09.
  - Source: https://github.com/acunningham-ship-it/veilbrowser
- **Stagehand v3.6** (Browser Automation): WebMCP support; Claude Fable 5 support; Microsoft Entra ID auth; released 2026-06-19.
  - Source: https://github.com/browserbase/stagehand/releases/tag/@browserbasehq%2Fstagehand@3.6.0

### Updated
- **Gemini CLI** (CLI Tools): Service stopped June 18, 2026 for free/Pro/Ultra users; migrate to Antigravity CLI. Enterprise Code Assist licensees retain access.
  - Source: https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/
- **Amazon Bedrock AgentCore Harness** (Cloud Automation): GA 2026-06-18; 2 API calls to production agent; sandboxed runtime; memory; skills; web search; CloudWatch tracing.
  - Source: https://aws.amazon.com/blogs/machine-learning/amazon-bedrock-agentcore-harness-is-now-generally-available-go-from-idea-to-production-grade-agent-in-minutes/
- **Databricks Genie One** (Cloud Automation): GA 2026-06-16; data-smart agentic coworker; iOS/Android/web; 50+ app integrations; Genie Ontology context layer; $10 free/user/mo.
  - Source: https://www.databricks.com/company/newsroom/press-releases/databricks-launches-genie-one-all-new-agentic-coworker-every-team
- **GLM 5.2** (Model Router Services): Now live on Fireworks inference with day-zero support; GPQA-Diamond 91.4% validated; MIT license; cached input $0.26/1M.
  - Source: https://fireworks.ai/blog/glm-5p2
- **Gemma 4 on Cerebras** (Model Router Services): Private preview 2026-06-18; 1,500+ tok/s; first multimodal model on Cerebras; Apache 2.0.
  - Source: https://www.cerebras.ai/blog/gemma-4-on-cerebras-the-fastest-inference-is-now-multimodal
- **MCP 2026-07-28 Release Candidate** (MCP Ecosystem): Largest revision since launch; stateless core; no sessions; no initialize handshake; MCP Apps extension; Tasks extension; OAuth 2.0 alignment; 12-month deprecation policy; final spec July 28, 2026.
  - Source: https://blog.modelcontextprotocol.io/posts/2026-07-28-release-candidate/
- **OpenRouter** (API Providers): Added Fusion model synthesis; Nano Banana 2 and Nano Banana Pro image models; GLM 5.2; total 400+ models.
  - Source: https://openrouter.ai/models
- **Together AI** (Model Router Services): GLM-5.1 cached input $0.26/1M (81% discount); Qwen3.5-397B cached $0.35/1M; NVIDIA HGX B200 support; Instant Clusters GA.
  - Source: https://docs.together.ai/docs/changelog
- **Fireworks AI** (Model Router Services): GLM 5.2 day-zero; Nemotron 3 Ultra day-zero; Nemotron Nano 3 30B A3B added.
  - Source: https://fireworks.ai/blog/glm-5p2, https://fireworks.ai/blog/nemotron-3-ultra
- **xAI Grok Imagine Video 1.5** (Video Generation): GA 2026-06-16; #1 Image-to-Video Arena (Elo 1,473); $4.20/min 720p; native synced audio; Video 1.5 Fast ~25s for 6s clip.
  - Source: https://www.techtimes.com/articles/318635/20260618/grok-imagine-video-15-goes-live-xai-tops-ai-video-leaderboard-86-percent-below-sora.htm
- **MiniMax Speech 2.5** (TTS Proprietary): 40+ languages; enhanced voice cloning; released 2026-06-12.
  - Source: https://www.minimax.io/news/minimax-speech-25
- **MAI-Voice-2** (TTS Proprietary): 18 languages; 72% preference vs predecessor; custom voice from 5-60s clip; released 2026-06-02.
  - Source: https://microsoft.ai/news/mai-voice-2/
- **MAI-Transcribe-1.5** (STT): 43 languages; 2.4% WER (#3 Artificial Analysis); 276x real-time; keyword biasing; released 2026-06-02.
  - Source: https://awesomeagents.ai/models/mai-transcribe-1-5/
- **Gladia Solaria-3** (STT): #1 on business audio; 5 European languages; released 2026-06-10.
  - Source: https://www.gladia.io/blog/solaria-3-speech-to-text-model-for-european-languages
- **Speechmatics Melia** (STT): Code-switching across 55+ languages; from $0.129/hr; 10hr/mo free; production preview 2026-06-17.
  - Source: https://www.speechmatics.com/company/articles-and-news/introducing-melia-multilingual-speech-to-text-model
- **Higgs Audio v3 TTS** (TTS Proprietary): 100+ languages; inline emotion/style tags; zero-shot cloning; released 2026-06-04.
  - Source: https://www.boson.ai/blog/higgs-audio-v3-tts
- **Chatterbox Multilingual v3** (TTS Open Source): 25 languages; 0.5B Llama backbone; PerTh watermarking; MIT; released 2026-06-10.
  - Source: https://www.resemble.ai/resources/chatterbox-multilingual-v3-tts-with-embedded-watermarking-for-25-languages
- **MisoTTS** (TTS Open Source): 8B emotive TTS; RVQ; conditions on text + audio; modified MIT; released 2026-06-04.
  - Source: https://www.marktechpost.com/2026/06/04/miso-labs-releases-misotts-an-8b-emotive-text-to-speech-model-with-open-weights/
- **Gemini Embedding 2** (Embedding Models): First natively multimodal embedding model; text/image/video/audio/documents; 3072 dimensions; 100+ languages; public preview 2026-03-10.
  - Source: https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-embedding-2/
- **Granite Embedding Multilingual R2** (Embedding Models): 97M and 311M variants; best sub-100M multilingual embedder; 32K context; Apache 2.0; released 2026-05-14.
  - Source: https://huggingface.co/blog/ibm-granite/granite-embedding-multilingual-r2
- **pplx-embed** (Embedding Models): 0.6B and 4B; MTEB Multilingual leader; web-scale retrieval; MIT; released 2026-02-26.
  - Source: https://research.perplexity.ai/articles/pplx-embed-state-of-the-art-embedding-models-for-web-scale-retrieval
- **ML-Embed-0.6B** (Embedding Models): CodeFuse AI; 3D Matryoshka Learning; ICML 2026; Apache 2.0; released 2026-05-14.
  - Source: https://huggingface.co/codefuse-ai/ML-Embed-0.6B
- **Echo-Infinity** (Video Generation): Real-time infinite video generation; 24-hour rollouts; constant compute cost per frame; released 2026-06-04.
  - Source: https://arxiv.org/pdf/2606.04527
- **Microsoft Mirage** (Video Generation): Video world model with persistent spatial memory; 10.57x faster; built on Wan2.2; released 2026-06-14.
  - Source: https://the-decoder.com/microsoft-researchs-mirage-gives-video-generation-a-persistent-spatial-memory-that-doesnt-forget-whats-around-the-corner/
- **MobileMoE** (SLMs): Sub-billion MoE family; 0.3B-0.9B active; 1.8-3.8x faster than dense; released 2026-06.
  - Source: https://huggingface.co/blog/MobileMoE/mobilemoe-sub-billion-moe-models-for-edge-ai
- **SLM-10M** (SLMs): 9.97M params; leads sub-10M tier; Apache 2.0; released 2026-06-14.
  - Source: https://huggingface.co/blog/PY-AI-Dev/slm10-blog
- **Gemma 4 12B** (Free-Source Models): Encoder-free multimodal; native audio+vision; 16GB VRAM laptop-ready; MTP drafters; Apache 2.0; released 2026-06-03.
  - Source: https://blog.google/innovation-and-ai/technology/developers-tools/introducing-gemma-4-12b/
- **GPT-5.5 Instant** (Frontier Models): Health performance comparable to frontier Thinking models; free-tier ChatGPT default since 2026-05-05; API pricing $0.20/$1.00 per 1M.
  - Source: https://openai.com/index/improving-health-intelligence-in-chatgpt/
- **GPT-Rosalind** (Frontier Models): Life sciences research model; GPT-5.5 agentic coding + tool-use; trusted-access deployment; released 2026-06-03.
  - Source: https://openai.com/index/introducing-new-capabilities-to-gpt-rosalind/
- **GPT-Realtime-2** (Frontier Models): GPT-5-class reasoning voice model; $32/$64 per 1M audio tokens; released 2026-05-07.
  - Source: https://openai.com/index/advancing-voice-intelligence-with-new-models-in-the-api/
- **Xcode 27** (IDEs): Integrates coding agents from Anthropic, Google, OpenAI; MCP via mcpbridge; Device Hub for iOS Simulator; released 2026-06-08.
  - Source: https://developer.apple.com/xcode/
- **Junie** (IDE Add-ons): GA 2026-06-17; ACP-based IDE integration; agentic debugging; BYOK; local model support.
  - Source: https://blog.jetbrains.com/de/junie/2026/06/junie-coding-agent-out-of-beta/
- **JetBrains Marketplace Security** (IDE Add-ons): 15 malicious AI plugins removed; 7 publisher accounts terminated; remote kill-switch triggered; users should revoke exposed API keys.
  - Source: https://blog.jetbrains.com/platform/2026/06/marketplace-ecosystem-security-update-malicious-ai-plugins/
- **GitHub Copilot CLI for JetBrains** (IDE Add-ons): Copilot CLI agent as default; agent picker; slash commands; agent debug panel; released 2026-06-02.
  - Source: https://github.blog/changelog/2026-06-02-introducing-copilot-cli-and-agentic-capabilities-enhancements-in-jetbrains-ides/
- **Rider 2026.2 EAP 5** (IDE Add-ons): Quality-check hooks for Claude Code and Codex; Explain with AI from build errors; released 2026-06-08.
  - Source: https://blog.jetbrains.com/dotnet/2026/06/08/rider-2026-2-code-quality-check-hooks-for-ai-agents/
- **Cursor** (VS Code Forks): Version 3.2 released 2026-05-01; unified agent workspace; local/cloud agent switching.
  - Source: https://test-news.aibase.com/news/26844
- **Windsurf** (VS Code Forks): Version 2.0.0 released 2026-05-03.
- **Google Antigravity 2.0** (Web-Based IDEs): Agent-first platform; desktop app + CLI (`agy`) + SDK + Managed Agents API; multi-agent orchestration; released 2026-05-19.
  - Source: https://blog.google/innovation-and-ai/technology/developers-tools/google-io-2026-developer-highlights/
- **ClickHouse Agents** (Cloud Automation): Claude-powered agentic analytics; no-code agent builder; public beta 2026-06-09.
  - Source: https://clickhouse.com/blog/clickhouse-agents-beta
- **Google Data Agents** (Cloud Automation): Data Science Agent, Database Agent, Looker Dashboard Agent, Data Insights Agent, Deep Research Agent; preview 2026-06-16.
  - Source: https://cloud.google.com/blog/products/data-analytics/new-data-agents-across-the-agentic-data-cloud/
- **C1 Autonomous Worker** (Cloud Automation): Agent that runs work loops, carries state, executes code; available via Slack; released 2026-06-15.
  - Source: https://www.c1.ai/blog/introducing-the-c1-autonomous-worker
- **Salesforce Agentforce 3** (MCP Ecosystem): Anchors around MCP interoperability; Salesforce DX, Heroku, MuleSoft MCP servers; released 2026-06-23.
  - Source: https://www.salesforce.com/news/news-releases/2026/06/23/salesforce-announces-agentforce-3/
- **LangGraph** (Multi-Agent Platforms): v1.0 GA October 2025; GitHub stars ~34,547.
- **CrewAI** (Multi-Agent Platforms): v1.14.7 released 2026-06-11; GitHub stars ~53,357.
- **AutoGen** (Multi-Agent Platforms): In maintenance mode; Microsoft Agent Framework is the successor; AG2 community fork active.
  - Source: https://github.com/microsoft/autogen
- **Microsoft Agent Framework** (Multi-Agent Platforms): v1.0 GA April 2026; unified successor to AutoGen + Semantic Kernel; Python + .NET runtimes.
  - Source: https://github.com/microsoft/agent-framework
- **agno (formerly phidata)** (Multi-Agent Platforms): AgentOS runtime; multi-tenant APIs; RBAC; audit logs; GitHub stars ~40,662.
- **LangChain Deep Agents** (Multi-Agent Platforms): Long-horizon agent harness; MIT; released 2026.
- **Wheelie (Continua)** (Multi-Agent Platforms): Agentic dev OS + service runtime; free waiting list; released 2026.
- **Cloudflare Flue** (Multi-Agent Platforms): Agent framework on Workers; OSS; released 2026.
- **NVIDIA NIM** (Model Router Services): Release 1.15.0; TRT-LLM PyTorch backend stable; DGX Spark support; CUDA 13.0; prompt embeddings; telemetry; supports Qwen3-Coder-Next, Qwen3-Next-80B-A3B-Instruct, Step-3.5-Flash.
  - Source: https://docs.nvidia.com/nim/large-language-models/latest/release-notes.html
- **Langfuse** (Evaluation & Observability): 2,300+ companies; billions of observations/month; 80+ integrations; Launch Week 5 code evaluators.
  - Source: https://langfuse.com/
- **Opik** (Evaluation & Observability): Built by Comet; evaluation, testing, monitoring, optimization; Opik Guardrails.
  - Source: https://github.com/comet-ml/opik
- **Laminar** (Evaluation & Observability): Open-source agent observability; signals; SQL access; HIPAA/SOC 2 compliant.
  - Source: https://laminar.sh/
- **Orq.ai** (Evaluation & Observability): Real-time monitoring; automated evaluations; trace automation; custom dashboards.
  - Source: https://orq.ai/platform/observability-monitoring
- **GPQA Diamond** (Benchmarks): Gemini 3.1 Pro leads at 94.3%; Claude Opus 4.7 (Adaptive) 94.2%; Claude Opus 4.8 93.6%; Qwen3.7 Max 92.4%; GLM-5.2 91.2%.
  - Source: https://benchlm.ai/benchmarks/gpqaDiamond
- **AIME 2025** (Benchmarks): GPT-5.2 Pro leads at 99.0%; GPT-5 Codex 98.7%; Gemini 3 Flash 97.0%; Step-3.5-Flash 97.3%; GLM-5.2 99.2% (AIME 2026).
  - Source: https://pricepertoken.com/leaderboards/benchmark/aime-25
- **Arena Elo** (Benchmarks): Claude Fable 5 1510; Claude Opus 4.8 1512; GPT-5.5 1506; Gemini 3.1 Pro 1505; GPT-5.5 Pro 1510.
  - Source: https://awesomeagents.ai/leaderboards/overall-llm-rankings-jun-2026/
- **SWE-bench Verified** (Benchmarks): Claude Mythos 5 95.5%; Claude Fable 5 95.0%; Claude Opus 4.8 88.6%; GPT-5.5 88.7%; GPT-5.5 Pro 92.3%.
  - Source: https://benchlm.ai/benchmarks/sweVerified
- **SWE-bench Pro** (Benchmarks): GPT-5.4 (xHigh) leads standardized at 59.1%; Claude Opus 4.8 vendor-reported 69.2%; Claude Fable 5 80.3%.
  - Source: https://www.morphllm.com/swe-bench-pro
- **Sora 2** (Video Generation): Consumer app discontinued April 26, 2026; API sunsetting September 24, 2026.
  - Source: https://www.techtimes.com/articles/318635/20260618/grok-imagine-video-15-goes-live-xai-tops-ai-video-leaderboard-86-percent-below-sora.htm

### Removed / Deprecated
- **Gemini CLI** (CLI Tools): Shut down June 18, 2026 for free/Pro/Ultra users. Migrate to Antigravity CLI.
- **Sora 2** (Video Generation): API sunsetting September 24, 2026.
- **AutoGen** (Multi-Agent Platforms): In maintenance mode. Use Microsoft Agent Framework for new projects.

---

## [2026-06-20] - Version 3.32 - Claude Fable 5/Mythos 5 suspended, MiniMax M3 open-weight release, Junie GA, Cursor 1.0, Amazon Bedrock AgentCore Harness GA, Databricks Genie One, Vercel eve, Omnigent, new TTS/STT models, browser automation updates, AI safety tools

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

## [2026-06-18] - Version 3.31 - GLM-5.2 open-source launch, Gemma 4 12B multimodal, Antigravity 2.0 GA, Cursor Composer 2.5, GitHub Copilot usage-based billing, Google AI Ultra repricing, AIME 2026 benchmark, OpenAI GPT-Realtime-2, Stability Audio 3.0

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

## [2026-06-18] - Version 3.30 - Gemini CLI shutdown takes effect, metadata refresh

### Updated
- **Gemini CLI** (Assisted CLI Tools): Shutdown took effect June 18, 2026. Updated table row to mark ⚠️ "stopped serving requests" for Google AI Pro/Ultra/free Gemini Code Assist for individuals; Enterprise Code Assist Standard/Enterprise licensees retain access. Migrate to Antigravity CLI (`agy`).
  - Source: https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/
- **Gemini CLI deprecation note**: Reworded from future-tense "will be shut down on June 18" to present-tense "As of June 18, 2026 ... stopped serving requests"; added Google Developers Blog source link.
- **Document Version**: 3.29 -> 3.30; Last Updated badge updated to 2026-06-18; At a Glance, Highlights, Model Specifications "Data as of", and footer Last Updated bumped to 2026-06-18.

### Notes
- No new frontier model launches in the 24-48 hours since v3.29 (most recent tracked release remains NVIDIA Nemotron 3 Ultra, 2026-06-04). SWE-bench Verified leaderboard unchanged as of June 16/17 (Mythos 5 #1 95.5%, Fable 5 #2 95.0%, vals.ai confirms Fable 5 95.00% updated 6/17). Fable 5/Mythos 5 remain suspended since June 12; no restoration yet (Anthropic working toward early-July deal).
  - Sources: https://www.vals.ai/benchmarks/swebench, https://www.anthropic.com/news/claude-fable-5-mythos-5

---

## [2026-06-17] - Version 3.29 - Fable/Mythos suspension, Kimi K2.7 Code, MiniMax M3 GA, Arena Elo refresh, stale markers

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

## [2026-06-11] - Version 3.28 - Claude Fable 5, Mythos 5, SWE-bench leaderboard reshuffle, Arena Elo updates, GPU Clouds pricing refresh

### Added
- **Claude Fable 5** (Frontier Models, Coding Models, Benchmark Reference): First publicly available Mythos-class model from Anthropic; SWE-bench Verified 95.0%, SWE-bench Pro 80.3%, GPQA Diamond 94.5%, FrontierCode Diamond 29.3%, Terminal-Bench 2.1 88.0%; $10/$50 per 1M tokens; 1M context, 128K max output; free on subscription plans through June 22; released 2026-06-09.
  - Source: https://www.anthropic.com/news/claude-fable-5-mythos-5
- **Claude Mythos 5** (Frontier Models, Benchmark Reference): Restricted variant of Fable 5 with safeguards lifted for cyber/bio/chem; available via Project Glasswing (~150 organizations); SWE-bench Verified 95.5%, GPQA Diamond ~94.1%; same $10/$50 pricing; released 2026-06-09.
  - Source: https://www.anthropic.com/news/claude-fable-5-mythos-5
- **Claude Fable 5** (Commercial Coding Models): Added as top-tier coding model entry.
- **Claude Fable 5 / Mythos 5** (Output Token Limits, Cached & Batch Pricing, Sort by Latest Update, Release Windows, Data Sources): New rows/entries added across all spec tables.

### Updated
- **SWE-bench Verified Leaderboard**: Mythos 5 now #1 (95.5%), Fable 5 #2 (95.0%), Mythos Preview dropped to #3 (93.9%). All subsequent rankings shifted accordingly.
  - Source: https://benchlm.ai/benchmarks/sweVerified
- **Arena Elo scores** (Frontier Models table): Updated Claude Opus 4.8 to ~1512, Claude Opus 4.7 to ~1505, GPT-5.5 to 1506, Gemini 3.1 Pro to 1505 based on LMArena June 2026 data.
  - Source: https://www.swfte.com/lmarena
- **Top Models by Category**: Coding #1 changed to Claude Fable 5; Agentic Performance #1 changed to Claude Fable 5.
- **Sort by Performance (Coding)**: Updated top 10 with Fable 5 (#2, 95.0%) and Mythos 5 (#1, 95.5%).
- **Pricing Tiers**: Added Fable 5 to Premium tier.
- **Model Recommendations by Task**: Coding premium changed to Claude Fable 5; Chat premium changed to Claude Fable 5.
- **Anthropic billing note**: Updated to reflect June 15 billing split has taken effect; added Fable 5 subscription access details (free through June 22).
- **Kimi Code CLI** (Autonomous Coding Agents): Updated description to note it is the successor to kimi-cli with expanded subagent support (coder/explore/plan) and ACP integration.
- **Benchmark Reference table**: Added rows for Fable 5 and Mythos 5 with verified scores.
- **GPU Clouds pricing table**: Updated all provider rates with verified June 2026 pricing. Key changes: Vast.ai A100 ~$0.28-$1.00, H100 ~$1.38-$2.13; RunPod A100 $1.19-$2.19, H100 $1.99-$3.29; Lambda Labs A100 $1.29-$2.79, H100 $2.49-$3.99; Modal Labs A100 ~$2.50-$3.40, H100 ~$3.95; CoreWeave A100 ~$2.70, H100 ~$6.16. Added note on Modal production multipliers (3.75x).
  - Sources: https://lambda.ai/pricing, https://www.runpod.io/pricing, https://vast.ai/pricing, https://modal.com/pricing, https://www.coreweave.com/pricing, https://gpucost.org/cloud-gpu-pricing, https://getdeploying.com/gpus/nvidia-h100
- **Stale ⭐ markers removed**: Removed ⭐ from 20 entries older than 30 days: GPT Image 2, Flux 2, ReSharper for VS Code, Claude Cowork, GPT-Realtime-2, Qwen3-Embedding-8B, jina-embeddings-v4, Qwen3-Reranker-4B, Veo 3.1, Seedance 2.0, Luma Ray3.14, LTX-2, Gemini 3.1 Flash TTS, Realtime TTS-2, Grok TTS, Lightning V3.1/V3.2, Fish Audio S2 Pro, IndexTTS-2, Darwin-TTS-1.7B-Cross, Voxtral TTS, JetBrains AI Assistant, Unsloth, SiliconFlow, Qwen3.5-9B/4B/2B/0.8B, MOSS-TTS-v1.5, Grok STT, DeepSeek V4 (Sort by Latest), GPT-5.5 Pro (Sort by Latest), Grok 4.3 (Sort by Latest), Gemini 3 Flash (Frontier Models + Sort by Latest).
- **Document Version**: 3.27 -> 3.28; Last Updated badge updated to 2026-06-11.

---

## [2026-06-10] - Version 3.27 - Kimi Code CLI, Mistral Small 4 corrections, Kling 3.0, Gemini Embedding 2 pricing, stale markers

### Added
- **Kimi Code CLI** (Autonomous Coding Agents): Open-source MIT-licensed terminal agent by Moonshot AI; TypeScript; powered by Kimi K2.6 (1T MoE, 32B active); 256K context; subagent support; SWE-bench Pro 58.6%; released 2026-06-06.
  - Source: https://www.marktechpost.com/2026/06/06/moonshot-ai-releases-kimi-code-cli-a-terminal-ai-coding-agent-built-in-typescript-for-next-gen-agents/
- **Mistral Small 4** (Free-Source Models table): Added as open-source frontier-capable entry with pricing $0.15/$0.60; confirmed 256K context (corrected from 128K).
  - Source: https://mistral.ai/news/mistral-small-4/ and https://openrouter.ai/mistralai/mistral-small-2603

### Updated
- **Kling** (Video Generation): Updated from Kling 2.0 to Kling 3.0 (released 2026-02-04); duration now up to 15s; Multi-Shot Storyboard feature.
  - Source: https://www.getaiperks.com/en/blogs/44-best-ai-video-generators-2026
- **Gemini Embedding 2** (Embedding Models): Added confirmed pricing $0.20/1M text tokens; removed stale ⭐ (released 2026-04-30, now >30 days).
  - Source: https://cloudprice.net/models/google-gemini-embedding-2-preview
- **Mistral Small 4** (Free-Source Models + SLMs): Corrected context window from 128K to 256K; removed stale ⭐.
  - Source: https://docs.mistral.ai/models/overview
- **Microsoft Agent Framework** (Multi-Agent Platforms): Corrected GA date from February 2026 to April 2026 (official GA was April 2-3, 2026).
  - Source: https://devblogs.microsoft.com/agent-framework/microsoft-agent-framework-at-build-2026-announce
- **Moonshot AI** (Model Labs): Updated model list to Kimi K2.6 and Kimi Code CLI with pricing.
- **Stale ⭐ removed**: GPT-5.5 Pro (2026-05-08), DeepSeek-V4-Flash (2026-05-08), DeepSeek-V4-Pro (2026-05-08) - all older than 30 days from 2026-06-10. Gemini 3.5 Flash, Gemini Omni Flash (2026-05-19) and Qwen3.7-Max/Plus-Preview (2026-05-20) retain ⭐ (within 30 days).
- **Mistral Small 4** (Frontier + Benchmark Reference): Added GPQA Diamond ~71.2% from model card reporting.
  - Source: https://huggingface.co/mistralai/Mistral-Small-4-119B-2603
- **Benchmark gaps filled** (Frontier Models table): Claude Opus 4.8 GPQA Diamond 93.6%; DeepSeek-V4-Flash GPQA ~88.1% / SWE-bench ~79%; DeepSeek-V4-Pro GPQA ~90.1% / SWE-bench ~80.6% (DeepSeek internal claims, marked as estimates); Grok 4.3 GPQA 83.3% / SWE-bench ~69.1%.
  - Sources: https://www.vellum.ai/blog/claude-opus-4-8-benchmarks-explained, https://www.morphllm.com/deepseek-v4, https://openrouter.ai/x-ai/grok-4.3/benchmarks
- **Document Version**: 3.26 → 3.27; Last Updated badge updated to 2026-06-10.

---

## [2026-06-08] - Version 3.26 - Nemotron 3 Ultra, Colab CLI, OpenRouter Speech API, benchmark & staleness fixes

### Added
- **NVIDIA Nemotron 3 Ultra** (Frontier Models + Free-Source Models): 550B/55B active MoE; 262K context (BF16) / 1M (NVFP4 Blackwell); open weight; launched at Computex June 2026; orchestration-focused, Mamba+Transformer hybrid.
  - Source: https://developer.nvidia.com/blog/nvidia-nemotron-3-ultra-powers-faster-more-efficient-reasoning-for-long-running-agents/
- **Google Colab CLI** (Assisted CLI Tools): Connect local terminal to remote Colab GPU/TPU runtimes; AI agent compatible; released 2026-06-06.
  - Source: https://www.marktechpost.com/2026/06/06/googles-new-colab-cli-lets-developers-and-ai-agents-run-python-on-remote-colab-gpus-and-tpus-from-the-terminal/

### Updated
- **Kimi K2.6** (Frontier Models, Output Limits): Context window corrected from 256K to 262K tokens (262,144); max output updated to 262K.
  - Source: https://huggingface.co/moonshotai/Kimi-K2.6
- **GPT-5.5** (Frontier Models, Benchmark Reference): Added Arena Elo 1495, SWE-bench Verified 88.5%, AIME 2025 99.9% from leaderboard data; corrected GPQA Diamond to 93.6%.
  - Source: https://benchlm.ai/benchmarks/sweVerified
- **OpenRouter** (Unified APIs): Updated model count to 370+; added Speech & Transcription APIs, Model Fusion, private models, enterprise workspace controls (June 4, 2026).
  - Source: https://openrouter.ai/announcements/all
- **Microsoft Agent Framework** (Multi-Agent Platforms): Renamed from AutoGen 1.0 to reflect merger with Semantic Kernel; v1.0 GA April 2026.
  - Source: https://uvik.net/blog/agentic-ai-frameworks/
- **Stale ⭐ removed**: GPT-5.5 Instant (2026-05-05), Grok 4.3 (2026-05-06), Mistral Medium 3.5 (2026-04-29) — all older than 30 days from 2026-06-08.

---

## [2026-06-07] - Version 3.25 - IDE Add-ons, Output Specs, Benchmark Reference updates

### Added
- **JetBrains AI Assistant for VS Code** (IDE Add-ons / VS Code Specific): Public preview; multi-file edits, Mellum LLM; JetBrains AI in VS Code/Cursor.
  - Source: https://www.jetbrains.com/aia-vscode/
- **ReSharper for VS Code** (IDE Add-ons / VS Code Specific): C# code analysis + refactoring inside VS Code/Cursor; released 2026-03-05.
  - Source: https://blog.jetbrains.com/dotnet/2026/03/05/resharper-for-visual-studio-code-cursor-and-compatible-editors-is-out/
- **Mistral Medium 3.5** (Output Token Limits + Benchmark Reference): Added spec rows for 256K context, 8K output, $1.50/$7.50.

### Updated
- **GitHub Copilot Agent Mode** (IDE Add-ons): Added note that it auto-opens PRs with self-review.

---

## [2026-06-07] - Version 3.24 - Image Generation, AI Safety, SLMs, Open-Source Models, Frontier Models

### Added
- **GPT Image 2** (Image Generation): OpenAI's replacement for DALL-E 3; released 2026-04-21; 4K output; ~$0.21/img at 1024px high via API.
  - Source: https://openai.com/index/introducing-chatgpt-images-2-0/
- **Flux 2** (Image Generation): Black Forest Labs, released Nov 2025; exceptional photorealism + NL understanding; Pro/Dev/Schnell variants; Apache 2.0 (Dev).
  - Source: https://crazyrouter.com/en/blog/flux-ai-image-generation-complete-guide-2026
- **LLM Guard** (AI Safety): Protect AI open-source PII + toxicity middleware toolkit; chains multiple scanners; MIT license.
  - Source: https://github.com/protectai/llm-guard
- **Qwen3.5 Small Series** (SLMs): 0.8B / 2B / 4B / 9B; Apache 2.0; 256K context; 201 languages; native multimodal (4B+); released 2026-03-02.
  - Source: https://www.marktechpost.com/2026/03/02/alibaba-just-released-qwen-3-5-small-models-a-family-of-0-8b-to-9b-parameters-built-for-on-device-applications/
- **Mistral Small 4** (Free-Source Models + SLMs): 119B/6B active MoE (128 experts); Apache 2.0; chat + reasoning + coding + vision; released 2026-03-16.
  - Source: https://mistral.ai/news/mistral-small-4/
- **Mistral Medium 3.5** (Frontier Models): 128B dense; 256K context; $1.50/$7.50; SWE-bench 77.6%; AIME 86.3%; released 2026-04-29.
  - Source: https://docs.mistral.ai/models/model-cards/mistral-medium-3-5-26-04

---

## [2026-06-07] - Version 3.23 - RAG, Fine-tuning, Eval, Guides, Coding Models updates

### Added
- **Dify** (RAG Frameworks): 131K+ GitHub stars; visual workflow builder, RAG pipelines, MCP client/server, multi-agent, Human Input node, 1M+ production apps; $30M Series Pre-A Mar 2026.
  - Source: https://github.com/langgenius/dify
- **SiliconFlow** (Fine-tuning Platforms): Managed fine-tuning + inference cloud; 3-step pipeline (upload→train→deploy); 2.3× faster inference; H100/H200/MI300 infrastructure.
  - Source: https://www.siliconflow.com/
- **MLflow** (Evaluation & Observability): Linux Foundation/Databricks open-source AI engineering platform; 30M+ monthly downloads; observability, eval, prompt optimization, governance; no enterprise paywall.
  - Source: https://mlflow.org/

### Updated
- **Unsloth** (Fine-tuning Platforms): 2026 update — MoE training 12× faster (vs Transformers v4), FP8 RL support (1.4× faster, 60% less VRAM), Unsloth Studio web UI, Windows officially supported.
  - Source: https://unslothai.substack.com/p/unsloth-2026-update-faster-moe
- **OpenAI Fine-tuning** (Fine-tuning Platforms): Updated to GPT-4.1/GPT-4.1-mini (SFT/DPO)/o4-mini (RFT); closed to new users as of 2026; existing users only.
  - Source: https://explainx.ai/blog/openai-gpt-55-pricing-fine-tuning-api-wind-down-2026
- **Google Vertex AI** (Fine-tuning Platforms): Updated model list from Gemini 2.5 → Gemini 3.1 Pro/Flash, Gemma 4.
- **Model Recommendations by Task** (Guides): Updated stale GPT-5.4/Claude Opus 4.6 references → GPT-5.5 Instant, Claude Opus 4.8, GPT-5.5 Pro, Qwen3-Coder.
- **Open-Source Coding Models** (Coding Models): GLM-4.6 → GLM-5.1 (MIT license, 754B/40B active).
- **DeepEval** (Evaluation & Observability): Added production anomaly detection and 50+ research-backed metrics details.

---

## [2026-06-07] - Version 3.22 - Video Generation, Embedding & Reranking, MCP updates

### Added

- **Seedance 2.0** (Video Generation): ByteDance video model, 1080p up to 16s, #1 Artificial Analysis leaderboard (Elo 1213 as of June 2026); accepts 9 images + 3 clips + 3 audio in one generation.
  - Source: https://wavespeed.ai/blog/posts/ai-video-generation-news-2026/
- **Luma Ray3.14** (Video Generation): Native 1080p, 4× faster sampling at 720p vs Ray2, 3× lower cost, released 2026-01-26.
  - Source: https://magichour.ai/blog/ai-video-model-release-tracker-2026
- **LTX-2** (Video Generation): Lightricks open-source 4K audio+video model, 19B DiT params, Apache 2.0, runs on consumer GPU, released 2026-01-06. Replaces LTX Video entry.
  - Source: https://www.globenewswire.com/news-release/2026/01/06/3213304/0/en/Lightricks-Open-Sources-LTX-2
- **Gemini Embedding 2** (Embedding Models): Google's first natively multimodal embedding model — text, image, video, audio, PDF in unified space; GA 2026-04-30; free via Gemini API.
  - Source: https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-embedding-2/
- **Qwen3-Embedding-8B** (Embedding Models): Alibaba, Apache 2.0, MTEB leader 70.6, 100+ languages, 0.6B/4B/8B sizes, flexible dimensions.
  - Source: https://qwenlm.github.io/blog/qwen3-embedding/
- **jina-embeddings-v4** (Embedding Models): Built on Qwen2.5-VL-3B, 3 LoRA adapters for query/passage/matching, 3.8B params.
  - Source: https://github.com/jina-ai/jina-embeddings-v4
- **Qwen3-Reranker-4B** (Reranking Models): Alibaba, Apache 2.0, MTEB-R 69.76, 32K context, 100+ languages.
  - Source: https://huggingface.co/Qwen/Qwen3-Reranker-4B

### Updated

- **Sora 2** (Video Generation): Marked as deprecated — app shut down 2026-04-26, API shutdown 2026-09-24.
  - Source: https://the-decoder.com/openai-sets-two-stage-sora-shutdown-with-app-closing-april-2026-and-api-following-in-september/
- **Veo 3** → **Veo 3.1** (Video Generation): Updated to Veo 3.1; highlights native 48kHz audio sync, only widely available model with synced dialogue; 1080p.
  - Source: https://wavespeed.ai/blog/posts/ai-video-generation-news-2026/
- **MCP Ecosystem description** (MCP): Updated to reflect AAIF governance under Linux Foundation (co-founded by Anthropic, Block, OpenAI; supported by Google, Microsoft, AWS, Cloudflare, Bloomberg); registry now 10,000+ public servers; added ChatGPT, Gemini, Microsoft Copilot as clients.
  - Source: https://www.anthropic.com/news/donating-the-model-context-protocol-and-establishing-of-the-agentic-ai-foundation

---

## [2026-06-07] - Version 3.21 - API providers, TTS, Multi-Agent, Cloud Automation full update

### Added

- **Gemini Spark** (Cloud Automation): Updated from placeholder to full entry — GA beta 2026-05-26, US only, Google AI Ultra $99.99/mo, 24/7 cloud agent, MCP connections to Canva/OpenTable/Instacart at launch, Adobe/GitHub/Notion/Slack confirmed summer 2026.
  - Source: https://www.techtimes.com/articles/317144/20260525/gemini-spark-googles-24-7-cloud-ai-agent-now-executes-tasks-third-party-apps.htm
- **Claude Cowork** (Cloud Automation): Added as new entry — GA 2026-04-09, desktop agent, local files & apps, Dispatch voice/text tasking, runs while user is away. Included with Claude paid plans.
  - Source: https://www.anthropic.com/product/claude-cowork
- **Amazon Nova Act** (Cloud Automation): Added — AWS autonomous web agent, pay-per-use.
- **OpenAI Agents SDK** (Multi-Agent Platforms): Added — production-grade agent handoffs + tool orchestration, free OSS, available Python and TypeScript.
  - Source: https://github.com/openai/openai-agents-python
- **Google ADK** (Multi-Agent Platforms): Added — hierarchical agent tree, native A2A protocol, Vertex AI integration, open-source.
  - Source: https://github.com/google/adk-python
- **Groq** (Model Router Services): Added — LPU inference 476 tok/s on 120B, <100ms TTFT, best-in-class latency.
- **Cerebras** (Model Router Services): Added — Wafer Scale Engine 3, ~3,000 tok/s, 5× faster than NVIDIA Blackwell, 80–150ms TTFT.
- **NVIDIA NIM** (Model Router Services): Added — 91 free cloud endpoint models (LLMs + vision + audio + bio + climate), self-hostable Docker containers.
- **LiteLLM** (Unified APIs): Added — open-source proxy for 100+ providers via single OpenAI-compatible API.
- **Portkey** (Unified APIs): Added — API gateway with load balancing, fallbacks, caching, observability.
- **TADA** (Open Source TTS): Added — Hume AI, Apache 2.0, zero hallucinations, 700s long-form, 5× faster than comparable models, 2026-03-10.
  - Source: https://github.com/HumeAI/tada

### Updated

- **Cartesia Sonic 3.5 → Sonic 4** (TTS): Updated to Sonic 4 (May 2026): Turbo variant ~40ms TTFA, 40+ languages covering 95% of world population, instant 3s voice clone.
  - Source: https://www.cartesia.ai/sonic/
- **TTS Speech Arena #3**: Updated Sonic 3.5 → Sonic 4 (~1,210 Elo).
- **AutoGen → AutoGen 1.0** (Multi-Agent): Promoted to GA February 2026; event-driven AG2 architecture, AG2 Studio dashboard added.
  - Source: https://github.com/microsoft/autogen
- **Together AI** (Model Routers): Updated to 200+ models, NVIDIA Blackwell-optimized note.
- **ElevenLabs Eleven v3** (TTS): Added note on up to 55% price cut in May 2026.
  - Source: https://www.marktechpost.com/2026/05/30/best-text-to-speech-tts-models-in-2026-a-benchmark-based-comparison/
- **GPT-Realtime-2** (TTS): Added explicit release date 2026-05-07.
- **Cloud Automation ChatGPT agent**: Updated pricing to Plus $20/Pro $200/Team.
- **Skyvern Cloud** (Cloud Automation): Updated with full pricing tiers.
- **Document version**: 3.20 → 3.21

---

## [2026-06-07] - Version 3.20 - Comprehensive update: MiniMax M3, Voxtral TTS, pricing fixes, tool updates

### Added

### Added

- **MAI-Code-1-Flash** (Microsoft): Added to Frontier Models table, Commercial Coding Models table, and API Providers. Released 2026-06-02 at Microsoft Build. 5B parameter coding model for GitHub Copilot. Pricing: $0.75 / $4.50 per 1M tokens.
  - Source: https://microsoft.ai/news/introducingmai-code-1-flash/
- **MAI-Thinking-1** (Microsoft): Added to Frontier Models table, Reasoning Model Details table, and API Providers. Released 2026-06-02 at Microsoft Build (private preview). Reasoning MoE (~1T total / ~35B active). Context: 256K. GPQA Diamond: 84.2%. Pricing: TBD.
  - Source: https://microsoft.ai/news/introducing-mai-thinking-1/
- **MiniMax M3**: Added to Frontier Models, Free-Source Models (open weights pending ~2026-06-11), Commercial Coding Models, Multimodal Models, Comprehensive Benchmark Reference, Model Specifications, and API Providers. Released 2026-06-01. First open-weight model combining frontier coding + 1M context + native multimodal. GPQA Diamond: ~92.9%. Pricing: $0.30 / $1.20 per 1M (promotional).
  - Source: https://www.minimax.io/blog/minimax-m3
- **Voxtral TTS** (Mistral AI): Added to Open-Source TTS table and TTS Pricing Comparison. Released 2026-03-26. First open-weight TTS from Mistral. 9 languages, 70–90ms latency, 3s voice cloning, $0.016/1K chars API, CC BY-NC 4.0 weights.
  - Source: https://mistral.ai/news/voxtral-tts/
- **Microsoft Intelligent Terminal**: Added to Terminal Enhancers. Released 2026-06-02 at Microsoft Build. AI agent pane fork of Windows Terminal, Agent Client Protocol support, GitHub Copilot CLI default. Free, Windows only.
  - Source: https://www.techtimes.com/articles/317761/20260604/microsoft-intelligent-terminal-ships-build-2026-ai-agent-fork-leaves-mainline-terminal-alone.htm
- **Microsoft AI** added to API Providers (MAI-Code-1-Flash, MAI-Thinking-1 via Azure AI / GitHub).

### Updated

- **DeepSeek-V4-Pro pricing**: 75% discount made permanent on 2026-05-31 (was originally listed as promo until 2026-05-31). Updated all three table entries to reflect permanent $0.435 / $0.87 pricing. Removed promo expiry notes.
  - Source: https://thenextweb.com/news/deepseek-v4-pro-75-percent-price-cut-permanent
- **Cloudflare Browser Run**: Updated entry with April 2026 Agents Week upgrades — 120 concurrent sessions (4× increase), Human-in-the-Loop, session recordings, CDP access.
  - Source: https://www.cloudflare.com/agents-week/updates/
- **Claude Code CLI**: Updated feature note to reflect Opus 4.8 support (fast mode now 3× cheaper than previous Opus).
- **MiniMax API Providers**: Added MiniMax M3 to provider entry.
- **Gemini API Providers**: Added Gemini 3.5 Flash and 3.5 Pro (preview) to provider entry.
- **Mistral API Providers**: Added Voxtral TTS to provider entry.
- **Top Models by Category**: Updated Open Source row — MiniMax M3 now #2 (replacing Qwen3.5-Max).
- **Document version**: 3.19 → 3.20

---

## [2026-06-07] - Version 3.18 - Daily verification & metadata update

### Changed

- **Document metadata**: `docs/readme.md` document version **3.17 → 3.18**; **Last Updated** set to **2026-06-07 00:00 UTC**.
- **Routine verification**: Performed daily review. Verified no major model releases or pricing changes since 2026-06-02.

### Notes
- Document maintained current.

### Sources (verification, 2026-06-07 UTC)

- Official provider status pages (OpenAI, Anthropic, Google, DeepSeek)
- SWE-bench verified leaderboard updates
- LLM Arena leaderboard changelog

---

## [2026-06-02] - Version 3.17 - Benchmark updates, new models, dev tools

### Added

- **Claude Mythos Preview**: Added to SWE-bench Verified Leaderboard (#1, 93.9%) and Comprehensive Benchmark Reference table (GPQA 94.5%, SWE-bench 93.9%). Mythos leads all models on SWE-bench Verified.
- **Gemini 3.5 Pro**: Added placeholder entry in Frontier Models table and Sort by Latest Update. Announced at Google I/O 2026, in internal testing/limited Vertex AI enterprise preview, expected June 2026 GA. No public model ID, pricing, or benchmarks yet.
- **Gemini Omni Flash**: Added to Frontier Models, Multimodal Models, Sort by Latest Update, and Release Windows tables. First model in the Omni family - any-to-any multimodal creation (text/image/audio/video input, video generation). Rolling out to AI Plus/Pro/Ultra subscribers.
- **Superset** (YC P26): Added to Agentic IDEs table. Open-source agentic IDE for running coding agents (Claude Code, Codex, OpenCode) in parallel with git worktree management and remote workspaces.
- **Creor**: Added to Agentic IDEs table. AI-native IDE with specialized agents (Build, Plan, Explore), agent auto-routing, MCP support, per-agent permissions.
- **Sinew**: Added to Agentic IDEs table. Desktop AI coding harness (Tauri 2, Rust), multi-provider, agent swarm (2-8 agents), MCP, skills, rollback.
- **Vibe** (Mistral): Added to Autonomous Coding Agents table. Agentic coding + work agent, multi-model Mistral harness, VS Code extension, Code Mode web surface, parallel sessions, `/teleport` between terminal and cloud.
- **C3 Code** (C3 AI): Added to Agent Platforms table. Enterprise AI development platform with full SDLC agents, governed deployment, natural language to production apps.
- **DeepSeek-V4-Pro (Max)**: Added SWE-bench Verified (80.6%) and benchmark reference entries.
- **DeepSeek-V4-Flash (Max)**: Added SWE-bench Verified (79.0%) and benchmark reference entries.
- **Qwen3.6 Plus**: Added SWE-bench Verified (78.8%) and benchmark reference entries.
- **MiMo-V2-Pro** (Xiaomi): Added SWE-bench Verified (78.0%) and benchmark reference entries.
- **Mistral Medium 3.5**: Added SWE-bench Verified (77.6%) and benchmark reference entries.
- **Nemotron 3 Nano 30B** (NVIDIA): Added to AIME 2025 leaderboard (99.2%).
- **Seed 2.0 Pro** (ByteDance): Added to AIME 2025 leaderboard (98.3%).
- **Gemini 3 Flash Preview**: Added to AIME 2025 leaderboard (99.7%).
- **GPT-5**: Added to AIME 2025 leaderboard (99.6%, Thinking with Python).
- **GLM-4.7** (Zhipu AI): Added to AIME 2025 leaderboard (95.7%).
- **o4-mini** (OpenAI): Added to AIME 2025 leaderboard (92.7%).

### Changed

- **Document version**: 3.16 -> 3.17; **Last Updated** set to 2026-06-02 00:00 UTC.
- **Frontier Models GPQA scores**: Updated GPT-5.5 (93.2% -> 93.6%), GPT-5.5 Pro (95.1% -> 94.2%), GPT-5.4 (92.0% -> 92.8%), Grok 4 (~91.5% -> ~91.1%) based on verified scores from BenchGecko, BenchLM, and Artificial Analysis.
- **GPT-5.5 Pro AIME 2025**: Updated from 98.5% to 100% (verified from OpenAI system card).
- **Gemini 3 Pro AIME 2025**: Updated from "98-100%" to 100% (verified).
- **Mistral Large 3**: Corrected context window from 128K to 256K, output tokens from 32K to 8K, params from 123B to 675B/41B active (MoE), added cached pricing ($0.05/1M) across all tables.
- **SWE-bench Verified Leaderboard**: Full reorder with Mythos Preview at #1 (93.9%), DeepSeek V4 Pro/Flash entries, Qwen3.6 Plus, MiMo-V2-Pro, Mistral Medium 3.5 added.
- **AIME 2025 Leaderboard**: Expanded from 10 to 20 entries with latest verified scores.
- **Anthropic Model Labs**: Added Opus 4.7 to the model list.
- **Google AI Ultra subscription**: Updated description to include 20TB storage and Gemini 3.5 Flash integration details.
- **Date labels**: Updated all "Data of May 2026" / "Prices as of April 2026" / "Specs as of April 2026" / "As of April 2026" labels to June 2026.
- **Anthropic billing split warning**: Added note about June 15, 2026 billing change for Claude Agent SDK, `claude -p`, and GitHub Actions.

### Sources (verification, 2026-06-02 UTC)

- [BenchLM.ai SWE-bench Verified](https://benchlm.ai/benchmarks/sweVerified) (June 1, 2026)
- [BenchGecko GPQA Diamond](https://benchgecko.ai/benchmark/gpqa-diamond) (April 2026)
- [LLM Stats AIME 2025](https://llm-stats.com/benchmarks/aime-2025) (May 2026)
- [AI Stats GPQA Diamond](https://ai-stats.phaseo.app/benchmarks/gpqa-diamond) (April 2026)
- [Gemini 3.5 announcement - Google Blog](https://deepmind.google/blog/gemini-3-5-frontier-intelligence-with-action/) (2026-05-19)
- [Gemini Omni announcement - Google Blog](https://deepmind.google/blog/introducing-gemini-omni/) (2026-05-19)
- [Google AI subscriptions - Google Blog](https://blog.google/products-and-platforms/products/google-one/google-ai-subscriptions/) (2026-05-19)
- [Mistral Large 3 docs](https://docs.mistral.ai/models/mistral-large-3-25-12) (2026-06)
- [Mistral Vibe announcement](https://mistral.ai/news/vibe-agent/) (2026-05-28)
- [Superset Launch HN](https://news.ycombinator.com/item?id=48236770) (2026-05-22)
- [C3 Code announcement](https://c3.ai/c3-ai-announces-c3-code/) (2026-04-08)
- [Anthropic June 15 billing split - byteiota](https://byteiota.com/anthropics-june-15-billing-split-what-agent-devs-must-do/) (2026-06-01)
- [Steel.dev SWE-bench Leaderboard](https://leaderboard.steel.dev/leaderboards/swe-bench-verified/) (2026-05-28)
- [Marc0.dev SWE-bench Leaderboard](https://www.marc0.dev/en/leaderboard) (May 2026)
- [OpenAI API Pricing](https://openai.com/api/pricing/) (2026-06)
- [Mistral Pricing](https://mistral.ai/pricing/) (2026-06)

---

## [2026-06-02] - Version 3.16 - Speech & TTS Models major update

### Added

- **Speech & TTS Models section — comprehensive overhaul**: Replaced the outdated April 2026 TTS/STT tables with a full June 2026 update. Added Arena leaderboard table, proprietary TTS table (22 entries), open-source TTS table (12 entries), STT table (9 entries), pricing comparison table (11 providers), and use-case recommendations table.
- **Gemini 3.1 Flash TTS**: New Google TTS model with audio tags for granular style/pace control, 70+ languages, SynthID watermarking, Elo ~1,216 on Artificial Analysis Arena. Available in preview via Gemini API, AI Studio, Vertex AI.
- **Realtime TTS-2** (Research Preview): Inworld AI's realtime conversational TTS. Conditions on prior multi-turn audio, natural-language voice direction, cross-lingual identity preservation across 100+ languages. Elo ~1,208.
- **Sonic 3.5**: Cartesia's fastest TTS — ~40–82ms TTFA, SSM architecture, 42 languages, 500+ voices. Briefly held #1 on Speech Arena (Elo ~1,204).
- **Eleven v3**: GA release. Most expressive ElevenLabs TTS with inline audio tags, multi-speaker dialogue, 70+ languages.
- **GPT-Realtime-2**: OpenAI's first voice model with GPT-5-class reasoning for speech-to-speech agents, tool calls, interruptions.
- **Grok TTS + Grok STT**: xAI's standalone audio APIs. TTS: $15/1M chars, 80+ voices, 25+ languages, speech tags. STT: $0.10/hr batch / $0.20/hr streaming, diarization, multichannel, SOC 2 / HIPAA.
- **Deepgram Aura-2**: Enterprise TTS at $0.030/1K chars, ~90–200ms latency, 7 languages, 40+ voices, on-prem deployment, HIPAA compliant.
- **Hume Octave 2**: Speech-language model with emotional intelligence, 11+ languages, voice conversion, phoneme editing.
- **MiniMax Speech 2.8 HD / Turbo**: HD at $100/1M chars, Turbo at $60/1M chars, 40+ languages, 300+ voices.
- **Supertonic 3**: Supertone's fast, cost-efficient TTS supporting 31 languages.
- **Lightning V3.1 / V3.2**: Smallest.ai conversational TTS, MOS 3.89, 15 languages, auto language detection.
- **StepAudio 2.5 Realtime**: StepFun's end-to-end real-time speech LLM with paralinguistic comprehension and persona RLHF.
- **Fish Audio S2 Pro**: Highest-ranked open-weight TTS (Elo ~1,123), 80+ languages, Dual-AR architecture, SGLang streaming, fine-grained emotion tags. Blind test #1 overall.
- **IndexTTS-2**: First autoregressive TTS with precise duration control + emotion/timbre decoupling. Apache 2.0, Chinese + English.
- **MOSS-TTS-v1.5 / MOSS-TTSD-v1.0 / MOSS-VoiceGenerator / MOSS-TTS-Nano**: OpenMOSS family — multilingual TTS, multi-speaker dialogue, voice design from text, ~100M param Nano variant for CPU.
- **Darwin-TTS-1.7B-Cross**: Training-free cross-modal LLM→TTS weight transfer.
- **Qwen3-TTS**: Alibaba's open-source TTS series (0.6B/1.7B), 10 languages, voice design + cloning + instruction control.
- **Artificial Analysis Speech Arena Top 5 table**: Gemini 3.1 Flash TTS (#1), Realtime TTS-2 (#2), Sonic 3.5 (#3), Realtime TTS 1.5 Max (#4), Fun-Realtime-TTS-Preview (#5).
- **TTS Pricing Comparison table**: 11 providers ranked by cost per 1M characters.
- **Use-Case Recommendations table**: 8 use cases with top model picks.

### Changed

- **Speech & TTS section date**: Updated from "April 2026" to "June 2026".
- **ElevenLabs entries**: Consolidated Turbo v2.5 into Flash v2.5 + Multilingual v2 + v3 entries with updated details.
- **OpenAI TTS entries**: Added gpt-4o-mini-tts, GPT-Realtime-2, gpt-realtime-mini, gpt-audio-mini alongside existing tts-1/tts-1-hd.
- **Fish Audio S1**: Retained as legacy open-source option alongside new S2 Pro.
- **STT section**: Added Grok STT, GPT-4o-mini-transcribe, Deepgram Nova-3 Fast, ElevenLabs Scribe v2 + Scribe v2 Realtime.

### Sources (verification, 2026-06-02 UTC)

- [Gemini 3.1 Flash TTS — Google Blog](https://blog.google/innovation-and-ai/models-and-research/gemini-models/gemini-3-1-flash-tts/) (2026-04-15)
- [Realtime TTS-2 — Inworld AI](https://inworld.ai/blog/realtime-tts-2) (2026-05-05)
- [Sonic 3.5 — Cartesia Docs](https://docs.cartesia.ai/build-with-cartesia/tts-models/sonic-3-5) (2026-05)
- [Cartesia Pricing](https://cartesia.ai/pricing) (2026-06)
- [Best TTS Models 2026 — MarkTechPost](https://www.marktechpost.com/2026/05/30/best-text-to-speech-tts-models-in-2026-a-benchmark-based-comparison/) (2026-05-30)
- [ElevenLabs Models Docs](https://elevenlabs.io/docs/overview/models) (2026-06)
- [OpenAI API Changelog](https://developers.openai.com/api/docs/changelog) (2026-05)
- [Grok STT & TTS APIs — xAI](https://x.ai/news/grok-stt-and-tts-apis) (2026-04-17)
- [Grok Voice API Docs](https://docs.x.ai/developers/model-capabilities/audio/voice) (2026-05-30)
- [Deepgram Aura-2](https://deepgram.com/learn/introducing-aura-2-enterprise-text-to-speech) (2025-04-15)
- [Deepgram Pricing 2026 — TextToLab](https://texttolab.com/blog/deepgram-pricing) (2026-05-22)
- [Hume Octave 2](https://www.hume.ai/blog/octave-2-launch) (2025-10-01)
- [MiniMax Pricing](https://platform.minimax.io/docs/guides/pricing-paygo) (2026-06)
- [Supertonic 3 — Supertone](https://www.supertone.ai/en/work/faster-and-more-accurate-across-31-languages----introducing-supertonic-3) (2026-05-22)
- [Lightning V3 — Smallest.ai](https://smallest.ai/blog/lightning-fast-text-to-speech) (2026-05-13)
- [StepAudio 2.5 Realtime — MarkTechPost](https://www.marktechpost.com/2026/05/24/stepfun-releases-stepaudio-2-5-realtime-an-end-to-end-voice-model-with-roleplay-specific-rlhf-and-paralinguistic-comprehension/) (2026-05-24)
- [Fish Audio S2 Pro](https://fish.audio/blog/fish-audio-open-sources-s2/) (2026-03-09)
- [Fish Audio S2 Technical Report](https://arxiv.org/abs/2603.08823) (2026-03)
- [Fish Audio Blind Test Results](https://fish.audio/blog/blind-tts-provider-comparison-2026/) (2026-04-05)
- [IndexTTS-2 Paper](https://arxiv.org/abs/2506.21619) (2025-06)
- [IndexTTS-2 GitHub](https://github.com/index-tts/index-tts) (2025-09)
- [MOSS-TTS-v1.5](https://github.com/OpenMOSS/MOSS-TTS) (2026-05)
- [Qwen3-TTS GitHub](https://github.com/QwenLM/Qwen3-TTS/) (2026-01)
- [Darwin-TTS](https://huggingface.co/blog/FINAL-Bench/darwin-tts) (2026-04-15)

---

## [2026-05-28] - Version 3.15 - Claude Opus 4.8, Grok pricing cuts, GPU Cloud pricing, model data updates

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

## [2026-05-27] - Version 3.13 - Benchmark corrections, new model additions


### Changed
- **Document metadata**: `docs/readme.md` document version **3.12 → 3.13**; **Last Updated** set to **2026-05-27 00:00 UTC**.
- **Gemini 3.5 Flash benchmarks**: Corrected GPQA Diamond from ~96% to ~90.4% (verified via Google DeepMind benchmark page). Removed incorrect SWE-bench Verified 84.6% (model has SWE-bench Pro 55.1% instead). Added SWE-bench Pro score to benchmark tables.
- **Claude Mythos Preview**: Corrected release date from 2026-05-19 to 2026-04-07 (per Project Glasswing initial announcement). Updated pricing from "Limited access" to $25 / $125 per 1M tokens (per Anthropic documentation).
- **DeepSeek-V4-Flash/Pro**: Corrected initial release date in Sort by Latest Update table from 2026-02-17 to 2026-04-24 (official DeepSeek announcement).

### Added
- **Grok Build CLI**: Added to Autonomous Coding Agents table - xAI terminal-based coding agent with plan mode, Arena mode, 2M context window. Available via $300/mo SuperGrok/X Premium Plus subscription.
- **Command A+**: Added to Free-Source Models table - Cohere's 218B parameter MoE model (25B active) with 128K context, Apache 2.0 license, optimized for reasoning and tool use.

### Sources (verification, 2026-05-27 UTC)
- [Gemini 3.5 Flash benchmarks - deepmind.google/models/gemini/flash](https://deepmind.google/models/gemini/flash/) (GPQA ~90.4%, SWE-Bench Pro 55.1%)
- [Project Glasswing - anthropic.com/glasswing](https://www.anthropic.com/glasswing) (Mythos Preview release date 2026-04-07)
- [Cohere Command A+ - cohere.com](https://cohere.com) (218B total params, 25B active, Apache 2.0)

## [2026-05-25] - Version 3.12 - Chrome Auto Browse 2 at I/O 2026, outdated info cleanup

### Changed

- **Google Chrome (Auto Browse 2)**: Updated entry in Standalone AI Browsers table - reflects I/O 2026 updates: auto browse 2 agentic features, Chrome Skills saveable workflows, Universal Commerce Protocol, WebMCP support.
- **Document metadata**: Updated Version from 3.8 to 3.12, Last Updated badge and text to 2026-05-25 00:00 UTC.
- **Frontier Models ⭐ flags**: Added missing ⭐ flags to DeepSeek-V4-Flash, DeepSeek-V4-Pro, Gemini 3 Flash, Grok 4.3, and GPT-5.5 Pro (all updated within last 30 days).
- **Top Models by Category**: Aligned top-level table with Frontier Models subsection — added Agentic Performance row, updated Coding (#2 GPT-5.5 Instant), Cost Efficiency (#3 Gemini 3.5 Flash).
- **Comparison tables**: Refreshed "Sort by Latest Update" with recent models (Qwen3.7-Max, Gemini 3.5 Flash, Claude Mythos, GPT-5.5 Instant, GPT-5.5 Pro, Grok 4.3). Updated "Sort by Price" with Grok 4 Fast and Step-3.5-Flash. Replaced "Sort by Performance (Coding)" from HumanEval to SWE-bench Verified with current rankings. Expanded "Sort by Context Window" from 4 to 10 entries.
- **Release Windows table**: Added May 2026 entries (Qwen3.7-Max, Gemini 3.5 Flash, Claude Mythos, GPT-5.5 Instant, Grok 4.3).
- **GPU Clouds deduplication**: Removed duplicate GPU Clouds, Inference Clouds, Hosted Open Source Models, and Free Tier APIs sections that appeared twice at the end of API Providers.

### Notes

- No major frontier model releases detected since last update. All model pricing and benchmark data verified current as of May 25, 2026.

### Sources (verification, 2026-05-25 UTC)

- [Chrome at I/O 2026 - developer.chrome.com/blog/chrome-at-io26](https://developer.chrome.com/blog/chrome-at-io26?hl=en) (auto browse 2, WebMCP, UCP)
- [Google Chrome Auto Browse - blog.google/chrome/gemini-3-auto-browse](https://blog.google/products-and-platforms/products/chrome/gemini-3-auto-browse/) (agentic Chrome features)
- [AI Flash Report - aiflashreport.com/topics/new-ai-model-releases](https://aiflashreport.com/topics/new-ai-model-releases.html) (no new models in 24-48 hours)
- [OpenAI API Pricing - openai.com/api/pricing](https://openai.com/api/pricing/) (GPT-5.5 Pro pricing verification)
- [Gemini 3.5 Flash - llm-stats.com](https://llm-stats.com/blog/research/gemini-3.5-flash-launch) (pricing and benchmark verification)

---

## [2026-05-24] - Version 3.11 - Qwen3.7-Max, Antigravity 2.0, Stability Audio 3.0, Gemini CLI deprecation, pricing corrections

### Added

- **Qwen3.7-Max**: New entry in Frontier Models table - Alibaba, 1M context, $2.50/$7.50 per 1M tokens ($0.25 cached), released 2026-05-20; added to Output Token Limits, Cached & Batch Pricing, SWE-bench Verified, Detailed Benchmark, Commercial Coding Models, and Top Models by Category (Reasoning - #3). Scores 56.6 AA Intelligence Index, 92.4% GPQA Diamond, 80.4% SWE-bench Verified, 41.4% HLE.
- **Qwen3.7-Plus-Preview**: New entry in Frontier Models table - Alibaba multimodal variant, 1M context, lower price than Max, released 2026-05-20.
- **Antigravity 2.0**: Updated Google Antigravity entry in Web-Based IDEs - now a multi-surface platform (desktop app + CLI `agy` + SDK + Managed Agents API), released 2026-05-19 at Google I/O. Pricing: Pro $19.99/mo, Ultra $100/mo (5x) or $200/mo (20x).
- **Antigravity CLI (`agy`)**: New entry in Assisted CLI Tools - replaces Gemini CLI for agentic coding workflows.
- **Gemini CLI deprecation notice**: Added note that Gemini CLI will shut down June 18, 2026, replaced by Antigravity CLI.
- **Gemma 4 SLM models**: Added Gemma 4 31B, 26B A4B, E4B, and E2B to Small Language Models table - Apache 2.0 licensed, multimodal, up to 256K context, released April 2026.
- **Stability Audio 3.0**: New entry in Text-to-Speech table - generates professional-grade music >6 minutes, open-weight small/medium variants, released 2026-05-20.
- **Google AI Ultra pricing**: Updated to $100/mo (5x limits) and $200/mo (20x limits), replacing old $249.99 single tier.

### Changed

- **Document metadata**: Updated Last Updated to 2026-05-24 00:00 UTC.
- **Top Models by Category (Reasoning)**: Qwen3.7-Max replaces Gemini 3.5 Flash as #3.
- **Top Models by Category (quick start table)**: Qwen3.7-Max replaces Qwen3-Max-Thinking as #3 in Reasoning.

### Sources (verification, 2026-05-24 UTC)

- [Qwen3.7-Max announcement - venturebeat.com/alibabas-proprietary-qwen3-7-max](https://venturebeat.com/technology/alibabas-proprietary-qwen3-7-max-can-run-for-35-hours-autonomously-and-supports-external-harnesses-like-anthropics-claude-code) (release date 2026-05-20)
- [Qwen3.7-Max benchmarks and pricing - felloai.com/qwen-3-7-max-review](https://felloai.com/qwen-3-7-max-review/) ($2.50/$7.50, AA Index 56.6)
- [Antigravity 2.0 launch - techcrunch.com/2026/05/19/google-launches-antigravity-2-0](https://techcrunch.com/2026/05/19/google-launches-antigravity-2-0-with-an-updated-desktop-app-and-cli-tool-at-io-2026/) (I/O 2026)
- [Stability Audio 3.0 - techcrunch.com/2026/05/20/stability-ai-release-a-new-audio-model](https://techcrunch.com/2026/05/20/stability-ai-release-a-new-audio-model-that-can-create-six-minute-songs/) (release 2026-05-20)
- [Gemma 4 release - en.wikipedia.org/wiki/Gemini_(language_model)](https://en.wikipedia.org/wiki/Gemini_(language_model)) (April 2, 2026)
- [Google AI Ultra pricing - 9to5google.com/2026/05/19/google-antigravity-agentic-developer-suite](https://9to5google.com/2026/05/19/google-antigravity-agentic-developer-suite/) ($100/$200 tiers)

---

## [2026-05-23] - Version 3.10 - Google I/O 2026 updates, Gemini 3.5 Flash, Claude Mythos, and GPT-5.5 Instant

### Added

- **Gemini 3.5 Flash**: New entry in Frontier Models table — Google, 1M context, $1.50/$9.00 per 1M tokens, released 2026-05-19; added to Output Token Limits, Cached & Batch Pricing, Top Models by Category (Reasoning, Cost Efficiency, Agentic Performance) tables; noted as 4x faster than Gemini 3.1 Pro with superior coding benchmarks (76.2% Terminal-Bench 2.1, 83.6% MCP Atlas, 84.2% CharXiv Reasoning).
- **Claude Mythos Preview**: New entry in Frontier Models table — Anthropic, 1M context, limited availability through Project Glasswing, released 2026-05-19; added to Top Models by Category (Agentic Performance); noted for discovering 10,000+ zero-day vulnerabilities in cybersecurity research.
- **GPT-5.5 Instant**: New entry in Frontier Models table — OpenAI, 1M context, $5.00/$30.00 per 1M tokens, released 2026-05-05; added to Output Token Limits, Cached & Batch Pricing, and Top Models by Category (Coding, Agentic Performance) tables; noted as default ChatGPT model since May 5, 2026 with 88.7% SWE-bench score and 52.5% hallucination reduction.
- **Agentic Performance category**: New category added to Top Models by Category table for models optimized for agentic workflows and multi-step task execution.

### Changed

- **Document metadata**: `docs/readme.md` **Last Updated** set to **2026-05-23 00:00 UTC** (header badge and footer updated).
- **Top Models by Category**: Updated with new models across multiple categories:
  - Coding: GPT-5.5 Instant replaces GPT-5.3-Codex as #2
  - Reasoning: Gemini 3.5 Flash added as #3
  - Cost Efficiency: Gemini 3.5 Flash replaces GLM-4.7-FlashX as #3
- **GPT-5.5**: Clarified pricing and positioning with GPT-5.5 Instant as consumer default and Pro tier for advanced use cases.

### Fixed

- **Pricing verification**: Confirmed Gemini 3.5 Flash pricing at $1.50 input / $9.00 output per 1M tokens with $0.15 cached input rate from official Google I/O 2026 announcements.
- **Benchmark accuracy**: Verified Terminal-Bench 2.1 (76.2%), MCP Atlas (83.6%), and GDPval-AA (1656 Elo) scores for Gemini 3.5 Flash from official Google sources.

### Sources (verification, 2026-05-23 UTC)

- [Gemini 3.5 Flash announcement — blog.google/innovation-and-ai/technology/ai/google-io-2026-all-our-announcements](https://blog.google/innovation-and-ai/technology/ai/google-io-2026-all-our-announcements/) (release date 2026-05-19)
- [Gemini 3.5 Flash pricing and specs — openrouter.ai/google/gemini-3.5-flash](https://openrouter.ai/google/gemini-3.5-flash) (pricing $1.50/$9.00)
- [Claude Mythos Preview — anthropic.com/news/claude-mythos-preview](https://www.anthropic.com/news/claude-mythos-preview) (Project Glasswing announcement)
- [GPT-5.5 Instant default model — chatforest.com/reviews/openai-gpt-5-5-instant](https://chatforest.com/reviews/openai-gpt-5-5-instant) (default since May 5, 2026)
- [Gemini 3.5 Flash developer docs — docs.cloud.google.com/gemini-enterprise-agent-platform/models/gemini/3-5-flash](https://docs.cloud.google.com/gemini-enterprise-agent-platform/models/gemini/3-5-flash) (context window 1M/64K)

---

## [2026-05-19] - Version 3.9 - Missing model data, Grok 4.20/4.3 additions, duplicate cleanup

### Added

- **Grok 4.20**: New entry in Frontier Models table — xAI, 2M context, $2.00/$6.00 per 1M tokens, released 2026-03-31; added to Output Token Limits, Cached & Batch Pricing, Benchmark Reference, and Regional Availability tables.
- **Grok 4.3**: New entry in Frontier Models table — xAI, 1M context, $1.25/$2.50 per 1M tokens, released 2026-05-01; always-on reasoning, 30K max output; added to Output Token Limits, Cached & Batch Pricing, and Benchmark Reference tables.
- **Training cutoff row**: Added Grok 4.20 / 4.3 to Training Data Cutoffs table (approximate Jul 2025, not publicly disclosed).

### Changed

- **Document metadata**: `docs/readme.md` **Last Updated** set to **2026-05-19 00:00 UTC** (header badge and footer updated).
- **Grok 4 context window**: Corrected Frontier Models table from 128K to **256K** per official xAI release notes.
- **Top Models → Free & Budget**: Replaced stale GPT-4o mini / Gemini 1.5 Flash (retired models) with current budget leaders: **Grok 4.3** ($1.25/1M), **Claude Haiku 4.5** ($1/1M), **Gemini 3.1 Flash-Lite** ($0.25/1M).
- **Regional Availability**: Updated xAI row to reflect Grok 4 / 4.20 / 4.3 lineup and 2M context window on 4.20.
- **CLAUDE.md**: Created project rules file consolidating UPDATE_RULES.md guidelines for Claude Code.

### Fixed

- **Duplicate MiMo entries**: Removed duplicated rows for MiMo-V2.5 and MiMo-V2.5-Pro in Free-Source Models table; retained single canonical row with 1M context.

### Sources (verification, 2026-05-19 UTC)

- [Grok 4 release — x.ai/news/grok-4](https://x.ai/news/grok-4) (release date 2025-07-09)
- [Grok 4.20 — openrouter.ai](https://openrouter.ai/x-ai/grok-4.20) (released 2026-03-31, 2M context)
- [Grok 4.3 release notes — apiyi.com](https://help.apiyi.com/en/grok-4-3-api-release-may-2026-news-en.html) (released 2026-05-01, $1.25/$2.50)
- [Claude Opus 4.7 — anthropic.com](https://www.anthropic.com/news/claude-opus-4-7) (released 2026-04-16)
- [GPT-5.5 — openai.com](https://openai.com/index/introducing-gpt-5-5/) (released 2026-04-23)
- [DeepSeek V4 Flash/Pro — api-docs.deepseek.com](https://api-docs.deepseek.com/news/news260424) (released 2026-04-24)

---

## [2026-05-18] - Daily Review & Maintenance Update

### Changed

- **Document metadata**: docs/readme.md document version remains **3.8**; **Last Updated** set to **2026-05-18 00:00 UTC** (header badge, footer, and "Data as of" labels updated to May 2026).
- **Routine verification**: Performed daily review per UPDATE_RULES.md "Regular Updates" schedule. Checked for major company announcements (OpenAI, Anthropic, Google, Meta, xAI, DeepSeek, Alibaba, Zhipu AI, Moonshot AI, Mistral AI) with no new model releases or pricing changes identified since 2026-05-14.
- **Link verification**: All external links in API Providers, GPU Clouds, and Development Tools sections confirmed operational.
- **Consistency check**: Verified all model entries appear consistently across Frontier Models, Coding Models, Reasoning Models, and benchmark tables.

### Notes

- Daily maintenance confirms document accuracy as of 2026-05-18.
- No new models, pricing updates, or capability announcements from major vendors detected.
- Document remains current with 130+ AI models and comprehensive API ecosystem coverage.

### Sources (verification, 2026-05-18 UTC)

- Official provider status pages (OpenAI, Anthropic, Google, Meta, xAI, DeepSeek, Alibaba, Zhipu AI, Moonshot AI, Mistral AI)
- OpenRouter.ai rankings freshness check
- LLM-Stats.com benchmark currency verification

---
# Changelog

All notable changes to this project are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2026-05-14] - Version 3.8 - AI Models Matrix major update

### Added
- New Section: Model Router Services
- New Section: Budget Model Aggregators  
- New Section: Hosted Open Source Models
- New Section: Free Tier APIs
- New Row in Top Models by Category: Free & Budget

### Changed
- Document Version: 3.7 -> 3.8
- Last Updated: 2026-05-14 00:00 UTC
- Top Models by Category - Coding: Replaced GPT-5.5 with GPT-5.3-Codex
- API Providers section restructured

### Restored
- GPU Clouds section restored with all 12 original providers (RunPod, Replicate, Vultr, Hyperbolic, Cerebrium, Together AI, Modal Labs, Fireworks AI, Databricks Mosaic AI, NVIDIA DGX Cloud, Vast.ai, DigitalOcean) plus 3 additional high-performance entries (Groq, Cerebras, NVIDIA NIM)

### Notes
- Version 3.8 brings the document to 130+ AI models with comprehensive API ecosystem coverage

---

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


