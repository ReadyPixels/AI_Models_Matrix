# Awesome AI CLI Tools

Last updated: 2025-12-20 15:00 UTC

Quick link: [Awesome AI IDEs](./awesome-ai-ides.md)

## Contents

- [Open-Source CLI Tools](#open-source-cli-tools-)
- [Proprietary CLI Tools](#proprietary-cli-tools-)

## Open-Source CLI Tools 🧠🔓

### Aider 🛠️
- 📝 **Description**: Open-source CLI assistant that edits code directly via chat.
- 🧠 **Key AI Features**: Code editing, refactoring, bug fixing with file diffs.
- ⚙️ **Configuration**:
  - **API Keys**: `export ANTHROPIC_API_KEY=sk-...` or `export OPENAI_API_KEY=sk-...`
  - **Config File**: `.aider.conf.yml` in project root or home directory.
- 💡 **Usage Examples**:
  - **Start**: `aider` (opens chat in current git repo).
  - **With Files**: `aider src/main.py src/utils.py` (adds files to context).
  - **Command**: `/add <file>` to add files during session, `/commit` to commit changes.
  - **Architect Mode**: `aider --architect` (uses reasoning model for planning, smaller model for editing).
- 🔧 **Troubleshooting**:
  - **Git Issues**: Aider works best with a clean git state. If stuck, stash changes.
  - **Context**: If context is full, use `/drop` to remove files.
- 💻 **Supported Programming Languages**: Python, JavaScript, plus many via connected LLMs.
- 🌐 **Platforms**: Command-line; cross-platform.
- 🧱 **Underlying Platform**: CLI tool
- 📅 **Release**: 2023
- 💰 **Pricing Model**: Free (uses external LLM APIs; user pays API costs).
- ⚖️ **Notable Pros/Cons or Unique Aspects**: Pros: Precise diffs, repo-aware. Cons: Requires API keys/config. Unique: Terminal-first automation.
- 🔗 **Sources**: https://aider.chat, https://github.com/paul-gauthier/aider
- 🕒 **Verified**: 2025-11-28 17:40 UTC

### Qwen Code 🧠
- 📝 **Description**: Alibaba's open-source AI coding assistant based on Qwen models.
- 🧠 **Key AI Features**: Code generation, completion, explanations.
- ⚙️ **Configuration**:
  - **Models**: Optimized for Qwen-Coder models (e.g., Qwen2.5-Coder).
  - **API**: Configure access to Alibaba Cloud Qwen API or local Qwen endpoints.
- 💡 **Usage Examples**:
  - **Chat**: `qwen` (starts interactive session).
  - **Code Generation**: `qwen "Create a Python script to parse CSV"`
- 🔧 **Troubleshooting**:
  - **Dependencies**: Ensure Node.js version matches requirements (often >= 18).
- 💻 **Supported Programming Languages**: Broad (major languages).
- 🌐 **Platforms**: CLI/API; cross-platform.
- 🧱 **Underlying Platform**: CLI tool (Gemini CLI Fork)
- 📅 **Release**: 2024
- 💰 **Pricing Model**: Free (open-source).
- ⚖️ **Notable Pros/Cons or Unique Aspects**: Pros: Open-source, customizable. Cons: Less mainstream, manual setup. Unique: Based on Qwen large language models.
- 🔗 **Sources**: https://github.com/QwenLM/qwen-code, https://qwenlm.github.io
- 🕒 **Verified**: 2025-11-28 17:40 UTC

### Gemini CLI 🌟
- 📝 **Description**: Google's command-line interface for Gemini AI coding assistance.
- 🧠 **Key AI Features**: Code generation, chat, explanations, repo-level context.
- ⚙️ **Configuration**:
  - **Auth**: Run `gemini auth login` to authenticate with Google Cloud/AI Studio.
  - **Project**: Set default project with `gemini config set project <PROJECT_ID>`.
- 💡 **Usage Examples**:
  - **Chat**: `gemini chat`
  - **Prompt**: `gemini prompt "Explain this file" --context src/index.js`
  - **Pipe**: `cat log.txt | gemini prompt "Find errors"`
- 🔧 **Troubleshooting**:
  - **Auth Errors**: Ensure `gcloud` CLI is installed and authenticated if using Cloud vertex AI.
  - **Quota**: Check Google Cloud quota limits for Gemini API.
- 💻 **Supported Programming Languages**: Broad (major languages).
- 🌐 **Platforms**: Command-line; cross-platform.
- 🧱 **Underlying Platform**: CLI tool
- 💰 **Pricing Model**: Free (open-source, requires Google account/API).
- ⚖️ **Notable Pros/Cons or Unique Aspects**: Pros: Access to Gemini models. Cons: Requires setup. Unique: Direct CLI integration with Google AI.
- 🔗 **Sources**: https://github.com/google-gemini/gemini-cli, https://ai.google.dev
- 🕒 **Verified**: 2025-11-28 17:40 UTC

### Mentat 🧠
- 📝 **Description**: Open-source coding agent that coordinates edits across multiple files.
- 🧠 **Key AI Features**: Context-aware editing, file coordination, "cloud-native" agent capabilities for CI fixes.
- ⚙️ **Configuration**:
  - **Install**: `pip install mentat`.
  - **API Keys**: Requires OpenAI/Anthropic keys.
- 💡 **Usage Examples**:
  - **Run**: `mentat <files>` to start session.
  - **Prompt**: "Refactor class X to use the singleton pattern."
- 🔧 **Troubleshooting**:
  - **Git**: Works best in a clean git repo.
- 💻 **Supported Programming Languages**: Python, JS, etc.
- 🌐 **Platforms**: CLI; cross-platform.
- 🧱 **Underlying Platform**: CLI tool
- 📅 **Release**: 2023
- 💰 **Pricing Model**: Free (open-source).
- ⚖️ **Notable Pros/Cons or Unique Aspects**: Pros: Excellent multi-file handling. Cons: Setup required. Unique: "Cloud-native" focus.
- 🔗 **Sources**: https://github.com/AbanteAI/mentat, https://mentat.ai
- 🕒 **Verified**: 2025-12-20 15:00 UTC

### GPT-Pilot ✈️
- 📝 **Description**: AI developer tool that writes scalable apps from scratch.
- 🧠 **Key AI Features**: Simulates a dev team (Planner, Designer, Architect), writes 95% of code autonomously.
- ⚙️ **Configuration**:
  - **Install**: `pip install gpt-pilot`.
  - **Setup**: `python main.py` triggers the wizard.
- 💡 **Usage Examples**:
  - **New App**: "Build a real-time chat app with Node.js and Socket.io." (Wizard guides the rest).
- 🔧 **Troubleshooting**:
  - **Database**: Ensure local DB services are running as requested by Pilot.
- 💻 **Supported Programming Languages**: Node, Python, PHP, etc.
- 🌐 **Platforms**: CLI; cross-platform.
- 🧱 **Underlying Platform**: CLI tool
- 📅 **Release**: 2023
- 💰 **Pricing Model**: Free (open-source).
- ⚖️ **Notable Pros/Cons or Unique Aspects**: Pros: Generates full apps. Cons: Can be expensive on API costs for large apps. Unique: "Pythagora" engine.
- 🔗 **Sources**: https://github.com/Pythagora-io/gpt-pilot, https://www.pythagora.ai
- 🕒 **Verified**: 2025-12-20 15:00 UTC

## Proprietary CLI Tools 🧠💼

### Claude Code 🧠
- 📝 **Description**: Anthropic's CLI tool for AI-assisted coding with Claude.
- 🧠 **Key AI Features**: Chat, code generation, editing, refactoring, autonomous agent capabilities.
- ⚙️ **Configuration**:
  - **Auth**: Run `claude` and follow the browser authentication flow.
  - **Project**: Automatically detects project context from current directory.
- 💡 **Usage Examples**:
  - **Start**: `claude` (interactive session).
  - **Task**: "Refactor the `login` function in `auth.js` to use async/await."
  - **Files**: `claude --print src/main.py` (print file content with syntax highlighting - verify flag availability).
  - **Slash Commands**: `/help` to see available commands inside the tool.
- 🔧 **Troubleshooting**:
  - **Permissions**: If Claude cannot edit files, check OS write permissions.
  - **Beta Status**: Tool is in beta; update frequently with `npm update -g @anthropic-ai/claude-code`.
- 💻 **Supported Programming Languages**: Broad (major languages).
- 🌐 **Platforms**: Command-line; cross-platform.
- 🧱 **Underlying Platform**: CLI tool
- 📅 **Release**: 2024
- 💰 **Pricing Model**: Free (uses Claude API; user pays API costs via Anthropic Max plan or API).
- ⚖️ **Notable Pros/Cons or Unique Aspects**: Pros: Deep codebase understanding, autonomous editing, CI integration. Cons: CLI-only, requires API key. Unique: Seamless AI chat in terminal with checkpoints.
- 🔗 **Sources**: https://claude.ai/code, https://docs.anthropic.com
- 🕒 **Verified**: 2025-12-20 14:40 UTC

### Cursor CLI 💻
- 📝 **Description**: Terminal-based AI assistant from Cursor for coding without leaving the command line.
- 🧠 **Key AI Features**: Multi-model support (GPT-5, Claude 4, Gemini), context-aware suggestions, interactive and headless modes.
- ⚙️ **Configuration**:
  - **Install**: Download from Cursor website or use `curl`.
  - **Models**: Configure preferred AI model via settings.
- 💡 **Usage Examples**:
  - **Chat**: `cursor chat` (interactive session).
  - **Task**: `cursor "refactor this function"` with file context.
- 🔧 **Troubleshooting**:
  - **Auth**: Ensure Cursor account is linked.
- 💻 **Supported Programming Languages**: Broad (major languages).
- 🌐 **Platforms**: Command-line; cross-platform.
- 🧱 **Underlying Platform**: CLI tool
- 📅 **Release**: 2025
- 💰 **Pricing Model**: Free tier; Pro for advanced models.
- ⚖️ **Notable Pros/Cons or Unique Aspects**: Pros: Multi-model, IDE integration. Cons: Subscription for full features. Unique: Terminal meets AI IDE.
- 🔗 **Sources**: https://cursor.com
- 🕒 **Verified**: 2025-12-20 14:40 UTC

### Refact.ai CLI 🔧
- 📝 **Description**: CLI integration for Refact.ai's Autonomous AI Agent.
- 🧠 **Key AI Features**: End-to-end task execution, planning, deployment, SWE-bench verified.
- ⚙️ **Configuration**:
  - **Install**: Via Refact plugin or standalone.
  - **API**: Connects to Refact Cloud or self-hosted enterprise server.
- 💡 **Usage Examples**:
  - **Agent**: Let the agent run shell commands, run tests, and fix code iteratively.
- 🔧 **Troubleshooting**:
  - **Permissions**: Grant explicit permission for shell execution.
- 💻 **Supported Programming Languages**: Broad.
- 🌐 **Platforms**: CLI; cross-platform.
- 🧱 **Underlying Platform**: CLI tool
- 📅 **Release**: 2025
- 💰 **Pricing Model**: Free tier / Enterprise.
- ⚖️ **Notable Pros/Cons or Unique Aspects**: Pros: Autonomous agent in CLI. Cons: Enterprise focus. Unique: SWE-bench verified performance.
- 🔗 **Sources**: https://refact.ai
- 🕒 **Verified**: 2025-12-20 15:00 UTC

### Qodo CLI 🧰
- 📝 **Description**: AI agent framework for injecting purpose-specific agents into development workflows.
- 🧠 **Key AI Features**: Custom agent creation, workflow automation, testing focus.
- ⚙️ **Configuration**:
  - **Install**: `pip install qodo` or via npm.
  - **Agents**: Define custom agents for specific tasks.
- 💡 **Usage Examples**:
  - **Test**: `qodo test --generate` (auto-generate tests).
  - **Review**: `qodo review src/` (code review).
- 🔧 **Troubleshooting**:
  - **Config**: Ensure agent definitions are valid.
- 💻 **Supported Programming Languages**: Broad (major languages).
- 🌐 **Platforms**: Command-line; cross-platform.
- 🧱 **Underlying Platform**: CLI tool
- 📅 **Release**: 2024
- 💰 **Pricing Model**: Free tier; Enterprise plans.
- ⚖️ **Notable Pros/Cons or Unique Aspects**: Pros: Flexible agent framework. Cons: Learning curve. Unique: Invent purpose-specific agents.
- 🔗 **Sources**: https://qodo.ai
- 🕒 **Verified**: 2025-12-20 14:40 UTC
### Amazon Q CLI ☁️
- 📝 **Description**: AWS command-line assistant for cloud infrastructure and scripting.
- 🧠 **Key AI Features**: Shell script generation, AWS resource management, best practice suggestions.
- ⚙️ **Configuration**:
  - **Install**: `brew install amazon-q` or via AWS CLI v2.
  - **Auth**: `q login` with AWS Builder ID.
- 💡 **Usage Examples**:
  - **Scripting**: "Write a script to list all S3 buckets older than 30 days."
  - **Explain**: "Explain this IAM policy."
- 🔧 **Troubleshooting**:
  - **Auth**: Ensure AWS Builder ID is active.
- 💻 **Supported Programming Languages**: Shell, Python, etc.
- 🌐 **Platforms**: Command-line (macOS, Linux, Windows).
- 🧱 **Underlying Platform**: CLI tool
- 📅 **Release**: 2024
- 💰 **Pricing Model**: Free tier; Pro subscription.
- ⚖️ **Notable Pros/Cons or Unique Aspects**: Pros: Deep AWS integration. Cons: AWS-focused. Unique: Infrastructure-as-Code assistance.
- 🔗 **Sources**: https://aws.amazon.com/q/
- 🕒 **Verified**: 2025-12-05 08:40 UTC

### Warp Terminal ⚡
- 📝 **Description**: AI-powered terminal emulator (Rust-based) with integrated AI assistant.
- 🧠 **Key AI Features**: Natural language to command, error explanation, workflow automation.
- ⚙️ **Configuration**:
  - **AI Access**: Enabled by default (Warp AI).
  - **Agent**: Warp Drive allows sharing workflows.
- 💡 **Usage Examples**:
  - **Command Gen**: Type "undo last git commit" -> Warp suggests `git reset --soft HEAD~1`.
  - **Error Fix**: Click "Explain" on any error output.
- 🔧 **Troubleshooting**:
  - **Login**: Requires login to use AI features.
- 💻 **Supported Programming Languages**: Shell/Terminal.
- 🌐 **Platforms**: macOS, Linux (Windows in beta).
- 🧱 **Underlying Platform**: Terminal Emulator
- 📅 **Release**: 2023
- 💰 **Pricing Model**: Free for individuals; Team plans.
- ⚖️ **Notable Pros/Cons or Unique Aspects**: Pros: Modern UI, fast. Cons: Requires login. Unique: Terminal as an IDE.
- 🔗 **Sources**: https://www.warp.dev
- 🕒 **Verified**: 2025-12-05 08:40 UTC

---

Made with ❤️ by ReadyPixels LLC
