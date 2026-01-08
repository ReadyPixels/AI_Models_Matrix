# Awesome AI Desktop Automation

_Last updated: 2026-01-08 08:40 UTC_

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
- **Latest Version**: -
- **Supported Platforms**: API (Client-side Cross-platform); Docker (Reference implementation).
- **Status**: ✅ Public Beta (API)
- **Sources**: https://docs.anthropic.com/en/docs/build-with-claude/computer-use
- **Verified**: 2026-01-08

### Agent S 🚀
- **Description**: Open-source agent framework capable of autonomous computer interaction via GUI. **First to surpass human-level performance on OSWorld.**
- **Key AI Features**: Learns from open-ended tasks, achieves 72.6% on OSWorld benchmark (Dec 2025), experience-augmented hierarchical planning.
- **Latest Version**: Agent S3 (Dec 15, 2025)
- **Supported Platforms**: Cross-platform (Python-based).
- **Status**: ✅ Active Maintenance (Open Source)
- **Sources**: https://github.com/simular-ai/Agent-S
- **Verified**: 2026-01-08

### Computer (trycua) 🖥️
- **Description**: A "Computer Use Interface" (CUI) enabling agents to control secure macOS/Linux sandboxes.
- **Key AI Features**: Secure environment for agent execution, standard interaction protocol.
- **Latest Version**: -
- **Supported Platforms**: macOS, Linux (Dockerized).
- **Status**: Open Source.
- **Sources**: https://github.com/trycua/computer
- **Verified**: 2026-01-08

### UI-TARS Desktop 🦎
- **Description**: Next-gen multimodal GUI agent based on VLM, capable of human-like interaction.
- **Key AI Features**: End-to-end vision-action model, cross-platform SDK.
- **Latest Version**: -
- **Supported Platforms**: Windows, macOS, Linux.
- **Status**: Open Source.
- **Sources**: https://github.com/bytedance/UI-TARS-desktop
- **Verified**: 2026-01-08

### Cradle 🎮
- **Description**: General Computer Control (GCC) framework capable of playing complex games (RDR2) and using software.
- **Key AI Features**: Six-module architecture (reflection, memory, planning) for mastering any desktop task.
- **Latest Version**: -
- **Supported Platforms**: Windows, macOS, Linux (Game/Software agnostic).
- **Status**: Open Source.
- **Sources**: https://github.com/BAAI-Agents/Cradle
- **Verified**: 2026-01-08

### AppAgent (on Desktop via ADB) 📱
- **Description**: Multimodal agent designed for smartphone apps but runs on desktop via Android emulators.
- **Key AI Features**: Learns by watching or exploring, no backend access needed.
- **Latest Version**: -
- **Supported Platforms**: Windows, macOS, Linux (Requires Android Emulator/ADB).
- **Status**: Open Source.
- **Sources**: https://github.com/TencentQQGYLab/AppAgent
- **Verified**: 2026-01-08

### UFO (Microsoft) 🛸
- **Description**: UI-Focused Agent for Windows interaction using dual-agent framework (AppSelection + ActionSelection).
- **Key AI Features**: GPT-Vision powered, deeply integrated with Windows accessibility/UI automation.
- **Latest Version**: -
- **Supported Platforms**: Windows (Exclusive).
- **Status**: Open Source (MIT).
- **Sources**: https://github.com/microsoft/UFO
- **Verified**: 2026-01-08

### OpenAdapt 🦾
- **Description**: Generative Process Automation (GPA) that learns from demonstration.
- **Key AI Features**: Privacy-preserving (PII redaction), runs on desktop to automate repetitive tasks via LLMs.
- **Latest Version**: -
- **Supported Platforms**: Windows, macOS.
- **Status**: Open Source (MIT).
- **Sources**: https://github.com/OpenAdaptAI/OpenAdapt
- **Verified**: 2026-01-08

### OS-Copilot / FRIDAY 🤖
- **Description**: Self-improving generalist computer agent framework.
- **Key AI Features**: Capable of interacting with OS, web, and code terminals. "FRIDAY" is the reference implementation.
- **Latest Version**: -
- **Supported Platforms**: Windows, macOS, Linux.
- **Status**: Open Source.
- **Sources**: https://github.com/OS-Copilot/FRIDAY
- **Verified**: 2026-01-08

### Self-Operating Computer (HyperWrite) ⌨️
- **Description**: Framework enabling multimodal models (GPT-4V, Gemini, etc.) to view the screen and click/type.
- **Key AI Features**: Accurate coordinate prediction, simple Python interface to "surrender control" to AI.
- **Latest Version**: -
- **Supported Platforms**: Windows, macOS, Linux.
- **Status**: Open Source (MIT).
- **Sources**: https://github.com/OthersideAI/self-operating-computer
- **Verified**: 2026-01-08

### ShowUI 👁️
- **Description**: End-to-end lightweight vision-language-action model (based on Qwen2-VL) for GUI agents.
- **Key AI Features**: Fast local inference, optimized visual token selection (15-20s/step locally).
- **Latest Version**: -
- **Supported Platforms**: Cross-platform (Python/Pytorch).
- **Status**: Open Source.
- **Sources**: https://github.com/Show-UI/ShowUI
- **Verified**: 2026-01-08

### OpenInterpreter 🗣️
- **Description**: Open-source code interpreter that runs locally to control your computer.
- **Key AI Features**: "OS Mode" for GUI interaction via generated Python code.
- **Latest Version**: -
- **Supported Platforms**: Windows, macOS, Linux.
- **Status**: Open Source.
- **Sources**: https://openinterpreter.com/
- **Verified**: 2026-01-08

---

## RPA & Visual Frameworks 👁️

> **Tools that use Computer Vision or OCR to automate without deep code hooks.**

### Ui.Vision RPA 👁️
- **Description**: Visual automation combining OCR and computer vision.
- **Key AI Features**: "XModules" for visual recognition of buttons/text.
- **Latest Version**: -
- **Supported Platforms**: Windows, macOS, Linux (Browser Extension + Desktop Core).
- **Status**: Open Source Core.
- **Sources**: https://ui.vision/
- **Verified**: 2026-01-08

### OmniParser V2 (Microsoft) 🔍
- **Description**: A screen parsing tool that converts UI screenshots into structured, clickable elements for agents.
- **Key AI Features**: Fine-tuned YOLOv8 + Florence-2 for element detection and captioning. Enabler for other agents.
- **Latest Version**: -
- **Supported Platforms**: Cross-platform (Python).
- **Status**: Open Source (MIT).
- **Sources**: https://github.com/microsoft/OmniParser
- **Verified**: 2026-01-08

---

## Scripting Libraries 📜

> **Code libraries for building custom automation tools.**

### Nut.js 🌰
- **Description**: Node.js ecosystem for desktop automation.
- **Latest Version**: -
- **Supported Platforms**: Windows, macOS, Linux.
- **Key Features**: Visual search, cross-platform inputs.
- **Status**: ✅ Active Maintenance
- **Sources**: https://nutjs.dev/
- **Verified**: 2026-01-08

### PyAutoGUI 🐍
- **Description**: Simple Python cross-platform GUI automation.
- **Latest Version**: -
- **Supported Platforms**: Windows, macOS, Linux.
- **Key Features**: Fail-safe mechanisms, simple API.
- **Status**: ✅ Active Maintenance
- **Sources**: https://pyautogui.readthedocs.io/
- **Verified**: 2026-01-08

---

## 🛡️ Security Considerations
- **Sandboxing**: Always run desktop automation agents in a VM or container.
- **Human-in-the-loop**: Use approvals for critical actions.
- **Credentials**: Never hardcode passwords; use environment variables.

---

Made with ❤️ by ReadyPixels LLC
