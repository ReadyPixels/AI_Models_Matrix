# Awesome AI Desktop Automation

 _Last updated: 2026-01-17 16:55 UTC_

Quick link: [Awesome Browser Automation](./awesome-browser-automation.md)

## Contents

- [AI Agents (Computer Use)](#ai-agents-computer-use-)
- [RPA & Visual Frameworks](#rpa--visual-frameworks-)
- [Scripting Libraries](#scripting-libraries-)

---

## AI Agents (Computer Use) 🧠

> **Next-gen "Computer Use" agents that can see the screen and control the OS autonomously.**

### Anthropic Computer Use 🤖
- **Description**: Beta capability of Claude 3.5 Sonnet to control mouse/keyboard via screenshot analysis.
- **Key AI Features**: Vision-based planning, direct tool execution, reasoning loop.
- **Latest Version**: Beta (Nov 2024)
- **Supported Platforms**: API (Client-side Cross-platform); Docker (Reference implementation).
- **Status**: ✅ Public Beta (API)
- **Sources**: https://docs.anthropic.com/en/docs/build-with-claude/computer-use
- **Verified**: 2026-01-10

### Agent S 🚀
- **Description**: Open-source agent framework capable of autonomous computer interaction via GUI. **First to surpass human-level performance on OSWorld.**
- **Key AI Features**: Learns from open-ended tasks, achieves 72.6% on OSWorld benchmark (Dec 2025), experience-augmented hierarchical planning.
- **Latest Version**: Agent S3 (Dec 15, 2025)
- **Supported Platforms**: Cross-platform (Python-based).
- **Status**: ✅ Active Maintenance (Open Source)
- **Sources**: https://github.com/simular-ai/Agent-S
- **Verified**: 2026-01-10

### Computer (trycua) 🖥️
- **Description**: A "Computer Use Interface" (CUI) enabling agents to control secure macOS/Linux sandboxes.
- **Key AI Features**: Secure environment for agent execution, standard interaction protocol.
- **Latest Version**: v0.1.8 CLI (Dec 23, 2025)
- **Supported Platforms**: macOS, Linux (Dockerized).
- **Status**: Open Source.
- **Sources**: https://github.com/trycua/computer
- **Verified**: 2026-01-10

### UI-TARS Desktop 🦎
- **Description**: Next-gen multimodal GUI agent based on VLM, capable of human-like interaction.
- **Key AI Features**: End-to-end vision-action model, cross-platform SDK.
 - **Latest Version**: v0.3.0 (Nov 5, 2025)
- **Supported Platforms**: Windows, macOS, Linux.
- **Status**: Open Source.
- **Sources**: https://github.com/bytedance/UI-TARS-desktop
- **Verified**: 2026-01-10

### Cradle 🎮
- **Description**: General Computer Control (GCC) framework capable of playing complex games (RDR2) and using software.
- **Key AI Features**: Six-module architecture (reflection, memory, planning) for mastering any desktop task.
 - **Latest Version**: Updated (Jun 27, 2024)
- **Supported Platforms**: Windows, macOS, Linux (Game/Software agnostic).
- **Status**: Open Source.
- **Sources**: https://github.com/BAAI-Agents/Cradle
- **Verified**: 2026-01-10

### AppAgent (on Desktop via ADB) 📱
- **Description**: Multimodal agent designed for smartphone apps but runs on desktop via Android emulators.
- **Key AI Features**: Learns by watching or exploring, no backend access needed.
 - **Latest Version**: Updated (Mar 5, 2025)
- **Supported Platforms**: Windows, macOS, Linux (Requires Android Emulator/ADB).
- **Status**: Open Source.
- **Sources**: https://github.com/TencentQQGYLab/AppAgent
- **Verified**: 2026-01-10

### UFO (Microsoft) 🛸
- **Description**: UI-Focused Agent for Windows interaction using dual-agent framework (AppSelection + ActionSelection).
- **Key AI Features**: GPT-Vision powered, deeply integrated with Windows accessibility/UI automation.
 - **Latest Version**: v3.0.0 (Nov 5, 2025)
- **Supported Platforms**: Windows (Exclusive).
- **Status**: Open Source (MIT).
- **Sources**: https://github.com/microsoft/UFO
- **Verified**: 2026-01-10

### OpenAdapt 🦾
- **Description**: Generative Process Automation (GPA) that learns from demonstration.
- **Key AI Features**: Privacy-preserving (PII redaction), runs on desktop to automate repetitive tasks via LLMs.
- **Latest Version**: v0.46.0 (2025-02-20)
- **Supported Platforms**: Windows, macOS.
- **Status**: Open Source (MIT).
- **Sources**: https://github.com/OpenAdaptAI/OpenAdapt
- **Verified**: 2026-01-10

### OS-Copilot / FRIDAY 🤖
- **Description**: Self-improving generalist computer agent framework.
- **Key AI Features**: Capable of interacting with OS, web, and code terminals. "FRIDAY" is the reference implementation.
 - **Latest Version**: Updated (Sep 1, 2024)
- **Supported Platforms**: Windows, macOS, Linux.
- **Status**: Open Source.
- **Sources**: https://github.com/OS-Copilot/FRIDAY
- **Verified**: 2026-01-10

### Self-Operating Computer (HyperWrite) ⌨️
- **Description**: Framework enabling multimodal models (GPT-4V, Gemini, etc.) to view the screen and click/type.
- **Key AI Features**: Accurate coordinate prediction, simple Python interface to "surrender control" to AI.
 - **Latest Version**: v1.5.8 (Feb 28, 2025)
- **Supported Platforms**: Windows, macOS, Linux.
- **Status**: Open Source (MIT).
- **Sources**: https://github.com/OthersideAI/self-operating-computer
- **Verified**: 2026-01-10

### ShowUI 👁️
- **Description**: End-to-end lightweight vision-language-action model (based on Qwen2-VL) for GUI agents.
- **Key AI Features**: Fast local inference, optimized visual token selection (15-20s/step locally).
 - **Latest Version**: Updated (Mar 2, 2025)
- **Supported Platforms**: Cross-platform (Python/Pytorch).
- **Status**: Open Source.
- **Sources**: https://github.com/Show-UI/ShowUI
- **Verified**: 2026-01-10

### OpenInterpreter 🗣️
- **Description**: Open-source code interpreter that runs locally to control your computer.
- **Key AI Features**: "OS Mode" for GUI interaction via generated Python code.
 - **Latest Version**: v0.4.2 pre-release (Oct 24, 2024)
- **Supported Platforms**: Windows, macOS, Linux.
- **Status**: Open Source.
- **Sources**: https://openinterpreter.com/
- **Verified**: 2026-01-10

---

## RPA & Visual Frameworks 👁️

> **Tools that use Computer Vision or OCR to automate without deep code hooks.**

### Ui.Vision RPA 👁️
- **Description**: Visual automation combining OCR and computer vision.
- **Key AI Features**: "XModules" for visual recognition of buttons/text.
- **Latest Version**: v9.5.9 (Oct 25, 2025)
- **Supported Platforms**: Windows, macOS, Linux (Browser Extension + Desktop Core).
- **Status**: Open Source Core.
- **Sources**: https://ui.vision/
- **Verified**: 2026-01-10

### OmniParser V2 (Microsoft) 🔍
- **Description**: A screen parsing tool that converts UI screenshots into structured, clickable elements for agents.
- **Key AI Features**: Fine-tuned YOLOv8 + Florence-2 for element detection and captioning. Enabler for other agents.
- **Latest Version**: v2.0 (Feb 2025)
- **Supported Platforms**: Cross-platform (Python).
- **Status**: Open Source (MIT).
- **Sources**: https://github.com/microsoft/OmniParser
- **Verified**: 2026-01-10

---

## Scripting Libraries 📜

> **Code libraries for building custom automation tools.**

### Nut.js 🌰
- **Description**: Node.js ecosystem for desktop automation.
- **Latest Version**: v4.2.0 (2025)
- **Supported Platforms**: Windows, macOS, Linux.
- **Key Features**: Visual search, cross-platform inputs.
- **Status**: ✅ Active Maintenance
- **Sources**: https://nutjs.dev/
- **Verified**: 2026-01-10

### PyAutoGUI 🐍
- **Description**: Simple Python cross-platform GUI automation.
- **Latest Version**: v0.9.54 (2023-05-24, actively maintained as of 2025)
- **Supported Platforms**: Windows, macOS, Linux.
- **Key Features**: Fail-safe mechanisms, simple API.
- **Status**: ✅ Active Maintenance
- **Sources**: https://pyautogui.readthedocs.io/
- **Verified**: 2026-01-10

---



## 🛡️ Security Considerations
- **Sandboxing**: Always run desktop automation agents in a VM or container.
- **Human-in-the-loop**: Use approvals for critical actions.
- **Credentials**: Never hardcode passwords; use environment variables.

---

## 📋 Methodology Notes
- **Research Date**: January 10, 2026
- **MCP Brave Search Usage**: Used for gathering latest pricing and feature information
- **Query Strings**: "Google AI Studio Gemini API pricing 2025", "Brave Search API enterprise pricing"
- **Timezone Policy**: All timestamps in UTC

---

Made with ❤️ by ReadyPixels LLC
