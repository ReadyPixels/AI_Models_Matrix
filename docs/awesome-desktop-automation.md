# Awesome AI Desktop Automation

_Last updated: 2025-12-20 17:20 UTC_

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
- **Status**: Public Beta (API).
- **Sources**: https://docs.anthropic.com/en/docs/build-with-claude/computer-use

### Agent S 🚀
- **Description**: Open-source agent framework capable of autonomous computer interaction via GUI.
- **Key AI Features**: Learns from open-ended tasks, achieves high performance on OSWorld benchmark.
- **Status**: Open Source.
- **Sources**: https://github.com/simular-ai/Agent-S

### Computer (trycua) 🖥️
- **Description**: A "Computer Use Interface" (CUI) enabling agents to control secure macOS/Linux sandboxes.
- **Key AI Features**: Secure environment for agent execution, standard interaction protocol.
- **Status**: Open Source.
- **Sources**: https://github.com/trycua/computer

- **Sources**: https://github.com/trycua/computer

### UFO (Microsoft) 🛸
- **Description**: UI-Focused Agent for Windows interaction using dual-agent framework (AppSelection + ActionSelection).
- **Key AI Features**: GPT-Vision powered, deeply integrated with Windows accessibility/UI automation.
- **Status**: Open Source (MIT).
- **Sources**: https://github.com/microsoft/UFO

### Self-Operating Computer (HyperWrite) ⌨️
- **Description**: Framework enabling multimodal models (GPT-4V, Gemini, etc.) to view the screen and click/type.
- **Key AI Features**: Accurate coordinate prediction, simple Python interface to "surrender control" to AI.
- **Status**: Open Source (MIT).
- **Sources**: https://github.com/OthersideAI/self-operating-computer

### ShowUI 👁️
- **Description**: End-to-end lightweight vision-language-action model (based on Qwen2-VL) for GUI agents.
- **Key AI Features**: Fast local inference, optimized visual token selection (15-20s/step locally).
- **Status**: Open Source.
- **Sources**: https://github.com/Show-UI/ShowUI

### OpenInterpreter 🗣️
- **Description**: Open-source code interpreter that runs locally to control your computer.
- **Key AI Features**: "OS Mode" for GUI interaction via generated Python code.
- **Status**: Open Source.
- **Sources**: https://openinterpreter.com/

---

## RPA & Visual Frameworks 👁️

> **Tools that use Computer Vision or OCR to automate without deep code hooks.**

### Ui.Vision RPA 👁️
- **Description**: Visual automation combining OCR and computer vision.
- **Key AI Features**: "XModules" for visual recognition of buttons/text.
- **Status**: Open Source Core.
- **Sources**: https://ui.vision/

### OmniParser V2 (Microsoft) 🔍
- **Description**: A screen parsing tool that converts UI screenshots into structured, clickable elements for agents.
- **Key AI Features**: Fine-tuned YOLOv8 + Florence-2 for element detection and captioning. Enabler for other agents.
- **Status**: Open Source (MIT).
- **Sources**: https://github.com/microsoft/OmniParser

---

## Scripting Libraries 📜

> **Code libraries for building custom automation tools.**

### Nut.js 🌰
- **Description**: Node.js ecosystem for desktop automation.
- **Key Features**: Visual search, cross-platform inputs.
- **Sources**: https://nutjs.dev/

### PyAutoGUI 🐍
- **Description**: Simple Python cross-platform GUI automation.
- **Key Features**: Fail-safe mechanisms, simple API.
- **Sources**: https://pyautogui.readthedocs.io/

---

## 🛡️ Security Considerations
- **Sandboxing**: Always run desktop automation agents in a VM or container.
- **Human-in-the-loop**: Use approvals for critical actions.
- **Credentials**: Never hardcode passwords; use environment variables.

---

Made with ❤️ by ReadyPixels LLC
