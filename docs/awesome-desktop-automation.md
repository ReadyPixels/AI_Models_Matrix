# Awesome AI Desktop Automation

> **A curated list of AI-powered desktop automation frameworks, RPA tools, and libraries.**  
> *Part of the [AI Models Matrix](https://github.com/ReadyPixels/AI_Models_Matrix) project.*

---

## 📋 Overview
This list covers tools and frameworks that enable AI agents to interact with desktop environments (Windows, macOS, Linux). It includes traditional RPA (Robotic Process Automation) tools enhanced with AI, scriptable automation libraries, and next-generation "Computer Use" agents.

**Key Categories:**
- **Open-Source Frameworks**: Libraries for building custom desktop automation scripts.
- **AI Agents & Integrations**: Models and tools specifically designed to control computers autonomously.

---

## 📑 Table of Contents
- [Open-Source Frameworks 🔓](#open-source-frameworks-)
  - [Ui.Vision](#uivision-rpa-)
  - [Nut.js](#nutjs-)
  - [PyAutoGUI](#pyautogui-)
- [AI Agents & Integrations 🧠](#ai-agents--integrations-)
  - [Anthropic Computer Use](#anthropic-computer-use-)
  - [OpenInterpreter](#openinterpreter-)

---

## Open-Source Frameworks 🔓

### Ui.Vision RPA 👁️
- 📝 **Description**: Open-source RPA software that combines visual web automation with desktop automation using OCR and computer vision.
- 🧠 **Key AI Features**: AI-powered computer vision (XModules) to recognize text and images on screen, bypassing DOM limitations.
- ⚙️ **Configuration**:
  - **Storage Mode**: Set to "File System" to save macros locally.
  - **OCR**: Configure built-in OCR engine or API keys for cloud OCR.
- 🔧 **Troubleshooting**:
  - **Calibration**: If clicks are offset, check OS display scaling settings (set to 100% or recalibrate).
  - **Permissions**: Ensure the browser/app has screen recording permissions on macOS.
- 💻 **Supported Platforms**: Windows, macOS, Linux.
- 🔗 **Sources**: [Official Site](https://ui.vision/), [GitHub](https://github.com/A9T9/RPA)
- 🕒 **Verified**: 2025-11-28 17:55 UTC

### Nut.js 🌰
- 📝 **Description**: "Native UI Toolkit" for Node.js. A powerful library for desktop automation with image search and cross-platform support.
- 🧠 **Key AI Features**: Visual search (finding images on screen) used as anchors for automation.
- ⚙️ **Configuration**:
  - **Speed**: Adjust execution delay for stability.
- 🔧 **Troubleshooting**:
  - **Dependencies**: Ensure build tools (Python, C++ compiler) are installed for native modules.
  - **Headless**: Requires a display server (Xvfb on Linux) if running in CI/CD.
- 💻 **Supported Platforms**: Windows, macOS, Linux.
- 🔗 **Sources**: [Nut.js Website](https://nutjs.dev/), [GitHub](https://github.com/nut-tree/nut.js)
- 🕒 **Verified**: 2025-11-28 17:55 UTC

### PyAutoGUI 🐍
- 📝 **Description**: A simple cross-platform Python module for programmatically controlling the mouse and keyboard.
- 🧠 **Key AI Features**: Often used as the "action layer" for Python-based AI agents.
- ⚙️ **Configuration**:
  - **Failsafe**: Move mouse to corner to abort.
  - **Pause**: Configure pauses between actions for stability.
- 🔧 **Troubleshooting**:
  - **Wayland**: On Linux Wayland, PyAutoGUI may have limited functionality (use X11).
  - **Permissions**: Grant "Accessibility" and "Screen Recording" permissions on macOS.
- 💻 **Supported Platforms**: Windows, macOS, Linux.
- 🔗 **Sources**: [Documentation](https://pyautogui.readthedocs.io/), [GitHub](https://github.com/asweigart/pyautogui)
- 🕒 **Verified**: 2025-11-28 17:55 UTC

---

## AI Agents & Integrations 🧠

### Anthropic Computer Use 🤖
- 📝 **Description**: A beta capability of Claude 3.5 Sonnet that allows the model to use a computer (mouse, keyboard, screen) like a human.
- 🧠 **Key AI Features**: Visual understanding of screenshots, coordinate planning, and direct tool execution (click, type, scroll).
- ⚙️ **Configuration**:
  - **Tools**: Define appropriate computer interaction tools in requests.
  - **Display**: Use controlled resolution to minimize token usage.
- 🔧 **Troubleshooting**:
  - **Latency**: Screen capture and upload can be slow; optimize image size.
  - **Security**: Run in a sandboxed environment (VM or Docker) to prevent accidental data loss or unauthorized actions.
- 💻 **Supported Platforms**: Any OS (via API integration), Reference implementation runs in Docker (Linux).
- 🔗 **Sources**: [Anthropic Docs](https://docs.anthropic.com/en/docs/build-with-claude/computer-use), [GitHub Quickstarts](https://github.com/anthropics/anthropic-quickstarts)
- 🕒 **Verified**: 2025-11-28 17:55 UTC

### OpenInterpreter 🗣️
- 📝 **Description**: An open-source, locally running code interpreter that lets LLMs run code on your computer to complete tasks.
- 🧠 **Key AI Features**: "OS Mode" enables the agent to control the mouse and keyboard to interact with GUI applications.
- ⚙️ **Configuration**:
  - Configure model selection and OS mode according to documentation.
- 🔧 **Troubleshooting**:
  - **Permissions**: Requires extensive system permissions. Run with caution.
  - **Vision Model**: OS mode requires a vision-capable model (e.g., GPT-4o, Claude 3.5 Sonnet) for best results.
- 💻 **Supported Platforms**: Windows, macOS, Linux.
- 🔗 **Sources**: [OpenInterpreter](https://openinterpreter.com/), [GitHub](https://github.com/OpenInterpreter/open-interpreter)
- 🕒 **Verified**: 2025-11-28 17:55 UTC

---

## 🛡️ Security Considerations
- **Sandboxing**: Always run desktop automation agents in a virtual machine (VM) or Docker container when possible, especially if they have internet access.
- **Human-in-the-loop**: Use "approvals" for critical actions (e.g., deleting files, sending emails).
- **Credentials**: Avoid hardcoding passwords in scripts. Use environment variables or secure vaults.
- **Rate Limiting**: Implement pauses to prevent "runaway" scripts from spamming inputs.
