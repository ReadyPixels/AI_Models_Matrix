# Awesome Browser Automation

_Last updated: 2026-01-08 08:40 UTC_

## Contents

- [Standalone AI Browsers](#standalone-ai-browsers-)
- [Browser Extensions & Co-Pilots](#browser-extensions--co-pilots-)
- [Developer Libraries & Frameworks](#developer-libraries--frameworks-)
- [Cloud & API Automation](#cloud--api-automation-)

---

## Standalone AI Browsers 🌐

> **Full-fledged web browsers reimagined with native AI integration and agentic capabilities.**

### BrowserOS 🌐
- **Description**: Open‑source Chromium‑based agentic browser with native AI agents and MCP server integration.
- **Key AI Features**: Local/bring‑your‑own models, agentic browsing, form filling, scraping, MCP server for use from agents like Claude Code/Gemini CLI.
- **Supported Platforms**: Windows, macOS, Linux.
- **Pricing**: Free (open‑source, AGPL‑3.0).
- **Pros/Cons**: Privacy‑first, local agents; early‑stage, evolving feature set.
- **Sources**: https://github.com/browseros-ai/BrowserOS, https://www.browseros.com/

### Browser Operator 🤖
- **Description**: Open-source AI browser with built-in multi-agent platform.
- **Key AI Features**: Multi-agent coordination, locally hosted alternative to proprietary "Atlas" style browsers.
- **Supported Platforms**: Windows, macOS, Linux.
- **Pricing**: Free (Open Source).
- **Sources**: https://github.com/BrowserOperator/browser-operator-core

### Perplexity Comet 🚀
- **Description**: AI‑powered web browser with an embedded assistant that automates tasks across tabs and apps.
- **Key AI Features**: Agentic browsing, cross‑tab actions (forms, email, calendar), page content understanding, AI on every tab (Dec 2025).
- **Latest Updates**: Mobile-first agentic browsing (Android), voice mode, smart summarization.
- **Supported Platforms**: Windows, macOS, Android (v1.5+).
- **Pricing**: Free.
- **Status**: ✅ Active Maintenance
- **Pros/Cons**: Powerful agentic workflows; privacy concerns regarding web content ingestion.
- **Sources**: https://www.perplexity.ai/comet
- **Verified**: 2026-01-08

### Dia AI Browser 💎
- **Description**: AI-powered context-aware browser from the creators of Arc. Primary focus of The Browser Company in 2026. **Successor to Arc Browser.**
- **Key AI Features**: Conversational AI, cross-tab reasoning, shopping cart automation, sidebar mode.
- **Supported Platforms**: macOS (M1+), Windows, iOS, Android (Planned 2026).
- **Pricing**: Free.
- **Status**: ✅ Active Development (Arc discontinued May 2025)
- **Sources**: https://diabrowser.com
- **Verified**: 2026-01-08

### Opera Neon / Opera One AI ⭕
- **Description**: Experimental AI concept browser with native "Aria" assistant.
- **Key AI Features**: Split screen, AI-generated "Surflets", deeply integrated chat.
- **Supported Platforms**: Windows, macOS.
- **Pricing**: Free.
- **Sources**: https://www.opera.com
- **Verified**: 2025-12-24

### ChatGPT Atlas (macOS) 🍎
- **Description**: AI‑focused browser for macOS with deep ChatGPT integration.
- **Key AI Features**: Agent mode, side‑by‑side browsing, context-aware assistance.
- **Supported Platforms**: macOS (Windows planned).
- **Pricing**: Free.
- **Pros/Cons**: Innovative UX; macOS‑only currently.
- **Sources**: https://openai.com

### Deta Surf 🗒️
- **Description**: Open‑source personal AI notebook/browser that brings web content into structured notes.
- **Key AI Features**: Web search integration, citations/deeplinks, Surflets (generated applets).
- **Supported Platforms**: Windows, macOS, Linux.
- **Pricing**: Free (Apache‑2.0).
- **Pros/Cons**: Local‑first research tool; not a general-purpose browser.
- **Sources**: https://github.com/deta/surf

### Open DeepResearch (Hugging Face) 🔬
- **Description**: Open-source agentic framework for deep web research and browsing.
- **Key AI Features**: Autonomous browsing, summarization, Q&A, attempting to replicate OpenAI Deep Research.
- **Supported Platforms**: Cross-platform (Python environment).
- **Status**: Open Source.
- **Sources**: https://huggingface.co/posts/open-deep-research



### OpenAI Operator / ChatGPT Agent Mode 🧠
- **Description**: Unified agentic system integrated into ChatGPT (and likely a browser frame) that can browse, interact, and generate artifacts.
- **Key AI Features**: Autonomous browsing, secure login prompts, code execution, artifact generation.
- **Supported Platforms**: Web/Browser-based (All modern browsers).
- **Pricing**: Requires ChatGPT Pro (varies).
- **Pros/Cons**: Massive scale and capability; specific availability rolling out.
- **Sources**: https://openai.com

---

## Browser Extensions & Co-Pilots 🧩

> **Extensions that add agentic powers to Chrome, Edge, and other standard browsers.**

### MultiOn 🚀
- **Description**: Autonomous AI agent extension that acts as a "personal intern" to complete web tasks.
- **Key AI Features**: Handles complex multi-step workflows (booking flights, ordering food, filling forms), API for developers.
- **Supported Platforms**: Chrome Extension (Chromium), Mobile App.
- **Pricing**: Free tier, Paid tiers (API per-request pricing for devs).
- **Pros/Cons**: highly capable "do it for me" agent; requires trust with accounts.
- **Sources**: https://www.multion.ai

### Harpa AI 🦸‍♂️
- **Description**: Hybrid AI co-pilot and automation agent for Chrome, integrating multiple LLMs (GPT, Claude, Gemini).
- **Key AI Features**: Page monitoring, data extraction, IFTTT-style automation recipes, write-for-me, SEO analysis.
- **Supported Platforms**: Chrome Extension (Chrome, Edge, Brave, Opera).
- **Pricing**: Freemium (Free tier + S1/S2 subscriptions).
- **Pros/Cons**: Huge library of pre-built automations; runs locally in browser.
- **Sources**: https://harpa.ai

### HyperWrite Personal Assistant ✍️
- **Description**: AI writing and productivity assistant with an "Agent" mode for browser tasks.
- **Key AI Features**: "Write Anywhere", autonomous research, email drafting, travel booking.
- **Supported Platforms**: Chrome Extension (Chromium Browsers).
- **Pricing**: Freemium ($19.99/mo for Premium).
- **Pros/Cons**: Excellent for writing-heavy workflows; strong agent capabilities.
- **Sources**: https://hyperwriteai.com

### NanoBrowser 🔬
- **Description**: Open-source Chrome extension for AI web automation, supporting local and cloud LLMs.
- **Key AI Features**: Multi-agent support, flexible LLM integration, "Run" button customization.
- **Supported Platforms**: Chrome Extension (Chromium).
- **Pricing**: Free (Open Source).
- **Pros/Cons**: Lightweight, fully control your model; limited by extension sandbox.
- **Sources**: https://github.com/Start-Nano/NanoBrowser

### Microsoft Edge Copilot 🟦
- **Description**: Built-in AI sidebar in Edge with deep OS integration.
- **Key AI Features**: Page summarization, rewrite, browser control.
- **Supported Platforms**: Microsoft Edge (Built-in Sidebar).
- **Pricing**: Free.
- **Sources**: https://www.microsoft.com/edge

---

## Developer Libraries & Frameworks 🛠️

> **SDKs and engines for building custom browser agents and scrapers.**

### Browser-use 🐍
- **Description**: Python library for agentic automation using LangChain/AI agents and Chrome DevTools Protocol.
- **Key AI Features**: Self-correcting agents, vision capabilities, handling of complex dynamic sites.
- **Supported Platforms**: Python (Windows, macOS, Linux).
- **Pricing**: Free (Open Source).
- **Sources**: https://github.com/browser-use/browser-use

### LaVague 🌊
- **Description**: Large Action Model (LAM) framework designed to translate natural language into Selenium/Playwright code.
- **Key AI Features**: Dedicated alignment for "World Model" -> Action, strictly for agentic use.
- **Supported Platforms**: Python.
- **Pricing**: Free (MIT).
- **Sources**: https://lavague.ai

### Stagehand 🎭
- **Description**: AI-first automation framework built on top of Playwright.
- **Key AI Features**: `act()`, `extract()`, and `observe()` primitives powered by LLMs.
- **Supported Platforms**: Node.js/TypeScript.
- **Pricing**: Free (Open Source).
- **Sources**: https://stagehand.dev

### Skyvern (Library) ☁️
- **Description**: Automates browser workflows using LLMs and Computer Vision, resilient to layout changes.
- **Supported Platforms**: Python SDK / Cloud API.
- **Sources**: https://github.com/Skyvern-AI/skyvern

### OpenWebUI + Browser Use 🤝
- **Description**: The specific integration of Browser-use inside the OpenWebUI interface.
- **Key AI Features**: UI-based agent control, local LLM support (Ollama).
- **Supported Platforms**: Web-based (Docker/Self-hosted).
- **Sources**: https://github.com/OpenWebUI/OpenWebUI

### Standard Engines (Playwright / Selenium / Cypress)
- **Playwright**: Best modern headless browser engine. Supports all major browsers (Windows, Linux, macOS).
- **Selenium**: The classic standard, compatible with almost everything (Cross-platform).
- **Cypress**: Great for testing, less so for general purpose agentic automation due to architecture.

### Steel Browser 🛡️
- **Description**: Open-source browser API and infrastructure designed for building AI agents.
- **Key AI Features**: High-fidelity browser control, built for agentic reliability.
- **Supported Platforms**: Cloud/Self-hosted.
- **Pricing**: Open Source core / Cloud pricing.
- **Sources**: https://github.com/steel-dev/steel-browser

### toMCP 🔌
- **Description**: Middleware that converts public websites into Model Context Protocol (MCP) servers.
- **Key AI Features**: Clean context extraction for agents.
- **Supported Platforms**: Local Server.
- **Pricing**: Open Source.
- **Sources**: https://github.com/Ami3466/tomcp

---

## Cloud & API Automation 🌩️

> **Managed services that run browser agents in the cloud.**

### Skyvern Cloud
- **Description**: Managed version of Skyvern Project.
- **Supported Platforms**: Cloud API.
- **Pricing**: Usage-based.

### Browserbase
- **Description**: Serverless browser infrastructure for AI agents.
- **Supported Platforms**: Cloud API (Connect via Puppeteer/Playwright).
- **Key Features**: Stealth mode, session recording, debug access.
- **Sources**: https://browserbase.com

---

Made with ❤️ by ReadyPixels LLC
