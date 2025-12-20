# Awesome AI Add-ons

Last updated: 2025-12-20 15:00 UTC

## Contents

- [VS Code Add-ons](#vs-code-add-ons-)
- [JetBrains Add-ons](#jetbrains-add-ons-)

## VS Code Add-ons 🧩

### GitHub Copilot ✈️
- 📝 **Description**: AI code completion and Copilot Chat/Agent Mode inside VS Code and Codespaces.
- 🧠 **Key AI Features**: Completion, chat, agent mode for multi-file changes, tests, refactors.
- ⚙️ **Configuration**: 
  - Enable/Disable globally or per language in `settings.json`: `"github.copilot.enable": { "*": true }`.
  - Configure "Agent Mode" settings in VS Code settings.
- 💡 **Usage Examples**:
  - **Ghost Text**: Type code and press `Tab` to accept suggestions.
  - **Inline Chat**: Press `Ctrl+I` (Cmd+I) to ask Copilot to generate or refactor code inline.
  - **Chat Panel**: Press `Ctrl+Alt+I` (Cmd+Opt+I) to open the chat sidebar.
  - **Context**: Use `@workspace` to query the entire project, `@vscode` for editor commands.
- 🔧 **Troubleshooting**:
  - **Not working?**: Check the Output panel (View > Output > Select "GitHub Copilot") for auth errors.
  - **Network**: Ensure firewall allows connections to `api.github.com`.
  - **Auth**: Try signing out and back in via the Accounts icon.
- 🌐 **Platforms**: VS Code (Desktop, Codespaces).
- 💰 **Pricing Model**: Subscription (individual/business tiers).
- 🔗 **Sources**: https://github.com/features/copilot, https://code.visualstudio.com/docs/copilot/chat/chat-agent-mode
- 🕒 **Verified**: 2025-11-28 17:38 UTC

### Cline (VS Code) 🧩
- 📝 **Description**: Open-source autonomous coding agent extension for VS Code with MCP integration.
- 🧠 **Key AI Features**: Create/edit files, run commands, browser use; add custom MCP tools from chat; auto-create MCP servers via "add a tool".
- ⚙️ **Configuration**:
  - Open Cline sidebar > Settings (gear icon).
  - Select **API Provider** (Anthropic, OpenRouter, OpenAI, etc.) and enter API Key.
  - **Custom Instructions**: Add project-specific rules in `.clinerules` file in your root directory.
- 💡 **Usage Examples**:
  - **Task Execution**: "Create a new React component for the login form with Tailwind styling."
  - **Browser Use**: "Go to localhost:3000 and verify the login button works." (requires headless browser permission).
  - **MCP Tools**: "Add a tool to search the web" (Cline can create/install tools).
- 🔧 **Troubleshooting**:
  - **API Errors**: Check your credit balance with the provider (e.g., Anthropic Console).
  - **Context Limit**: If context fills up, Cline may lose track; use "Clear Context" to reset.
  - **Permissions**: Ensure you approve file edits/command execution if not set to "Always Allow".
- 🌐 **Platforms**: VS Code (Desktop).
- 💰 **Pricing Model**: Free (OSS); BYO model/API.
- 🔗 **Sources**: https://github.com/cline/cline, https://github.com/cline/cline/releases/tag/v2.2.0
- 🕒 **Verified**: 2025-12-20 14:40 UTC

### Supermaven ⚡
- 📝 **Description**: Ultra-fast AI code completions with 1M token context window.
- 🧠 **Key AI Features**: Real-time suggestions, massive context, chat with GPT-4o/Claude 3.5 Sonnet.
- ⚙️ **Configuration**:
  - Install from VS Code marketplace.
  - Sign in for Pro features (optional).
- 💡 **Usage Examples**:
  - **Completion**: Ghost text while typing, `Tab` to accept.
  - **Chat**: Open Supermaven panel for AI conversations.
- 🔧 **Troubleshooting**:
  - **Slow?**: Check internet connection. Large context may have brief delays.
- 🌐 **Platforms**: VS Code, JetBrains, Vim/Neovim.
- 💰 **Pricing Model**: Free tier; Pro $10/month.
- 🔗 **Sources**: https://supermaven.com
- 🕒 **Verified**: 2025-12-20 14:40 UTC

### Blackbox AI 📦
- 📝 **Description**: Specialized AI code generator with high accuracy and OCR capabilities.
- 🧠 **Key AI Features**: Code from images (OCR), natural language to code, high speed (96% on repetitive tasks).
- ⚙️ **Configuration**:
  - **Install**: VS Code / JetBrains extension.
  - **Auth**: Blackbox account login.
- 💡 **Usage Examples**:
  - **OCR**: Paste an image of code to get text.
  - **Chat**: "Write a Python script to parse this CSV."
- 🔧 **Troubleshooting**:
  - **OCR**: Ensure image is high resolution.
- 💻 **Supported Programming Languages**: 20+.
- 🌐 **Platforms**: VS Code, JetBrains, Web.
- 💰 **Pricing Model**: Freemium.
- 🔗 **Sources**: https://www.blackbox.ai
- 🕒 **Verified**: 2025-12-20 15:00 UTC

### Bito AI 🛡️
- 📝 **Description**: AI Code Review Agent focusing on privacy and security.
- 🧠 **Key AI Features**: Automated Line-by-line code review, security vulnerability detection, performance checks.
- ⚙️ **Configuration**:
  - **Install**: VS Code / JetBrains extension.
  - **Models**: Uses Claude Sonnet 3.5 / GPT-4.
- 💡 **Usage Examples**:
  - **Review**: Auto-runs on PR or manual trigger to find code smells.
- 🔧 **Troubleshooting**:
  - **Privacy**: Check enterprise settings for data retention policies.
- 💻 **Supported Programming Languages**: Major languages.
- 🌐 **Platforms**: VS Code, JetBrains, CLI.
- 💰 **Pricing Model**: Free / Enterprise.
- 🔗 **Sources**: https://bito.ai
- 🕒 **Verified**: 2025-12-20 15:00 UTC

### Mutable.ai 🔮
- 📝 **Description**: AI coding assistant focused on refactoring and maintenance ("Auto-Wiki").
- 🧠 **Key AI Features**: Semantic search, multi-file transformations, "Auto-Wiki" documentation generation.
- ⚙️ **Configuration**:
  - **Install**: VS Code / JetBrains extension.
- 💡 **Usage Examples**:
  - **Refactor**: "Convert this entire module to TypeScript."
  - **Docs**: Auto-generate repo documentation.
- 🔧 **Troubleshooting**:
  - **Indexing**: Large repos make take time to index.
- 💻 **Supported Programming Languages**: Major languages.
- 🌐 **Platforms**: VS Code, JetBrains.
- 💰 **Pricing Model**: Subscription.
- 🔗 **Sources**: https://mutable.ai
- 🕒 **Verified**: 2025-12-20 15:00 UTC

### Continue (VS Code & JetBrains) 🔄
- 📝 **Description**: Open-source AI coding assistant that brings chat and autocomplete to editors.
- 🧠 **Key AI Features**: Chat, code completion, codebase-aware context, BYO/local models (Ollama, LM Studio).
- ⚙️ **Configuration**:
  - Edit `~/.continue/config.json` (accessible via gear icon).
  - **Models**: Add providers like `"provider": "ollama", "model": "llama3"`.
  - **Tab Autocomplete**: Configure a separate small model (e.g., `starcoder2:3b`) for low latency.
- 💡 **Usage Examples**:
  - **Edit Code**: Highlight code + `Ctrl+I` (Cmd+I) -> "Refactor this to use async/await".
  - **Chat**: `Ctrl+L` (Cmd+L) to toggle chat.
  - **Context**: Use `@file`, `@folder`, `@docs` to reference context in chat.
  - **Docs**: "@docs React" to query documentation.
- 🔧 **Troubleshooting**:
  - **Local Models**: Ensure Ollama/LM Studio is running (`ollama serve`).
  - **Indexing**: If `@codebase` is slow, check if indexing is complete (status in bottom bar).
  - **Logs**: View `~/.continue/continue.log` for error details.
- 🌐 **Platforms**: VS Code, JetBrains.
- 💰 **Pricing Model**: Free (open-source).
- 🔗 **Sources**: https://continue.dev, https://docs.continue.dev/troubleshooting
- 🕒 **Verified**: 2025-11-28 17:38 UTC

### Cody (Sourcegraph) 🔍
- 📝 **Description**: Open-source AI assistant focused on code search and repo-scale understanding.
- 🧠 **Key AI Features**: Semantic code search, completion, explanations, refactors.
- ⚙️ **Configuration**:
  - Select LLM model (e.g., Claude 3.5 Sonnet, GPT-4o) in the chat interface.
  - Enable "Codebase context" to allow Cody to index your repo.
- 💡 **Usage Examples**:
  - **Chat**: "Where is the authentication logic defined?" (uses semantic search).
  - **Commands**: Right-click code > Cody > "Explain Code" or "Generate Unit Tests".
  - **Fix**: Click "Fix" on linter errors to get AI suggestions.
- 🔧 **Troubleshooting**:
  - **Context Issues**: Run command `Cody: Re-index Codebase` if answers seem outdated.
  - **Auth**: Re-authenticate via `Cody: Sign In` if disconnected.
- 🌐 **Platforms**: VS Code, JetBrains.
- 💰 **Pricing Model**: Free tier; paid team plans.
- 🔗 **Sources**: https://sourcegraph.com/cody, https://docs.sourcegraph.com/cody
- 🕒 **Verified**: 2025-11-28 17:38 UTC

### Codeium 🚀
- 📝 **Description**: Fast AI code completion and chat.
- 🧠 **Key AI Features**: Autocomplete, code generation, chat.
- ⚙️ **Configuration**:
  - **API Key**: Automatically managed after sign-in.
  - **Settings**: Customize autocomplete delay and accepted languages in Extension Settings.
- 💡 **Usage Examples**:
  - **Autocomplete**: Gray text appears as you type; `Tab` to accept.
  - **Chat**: Open Codeium panel to ask general coding questions.
- 🔧 **Troubleshooting**:
  - **No suggestions?**: Check if the Codeium status icon is active (no red X).
  - **Restart**: Run `Codeium: Restart Language Server` from Command Palette.
- 🌐 **Platforms**: VS Code, JetBrains, Vim/Neovim.
- 💰 **Pricing Model**: Free for individuals; paid teams.
- 🔗 **Sources**: https://codeium.com, https://codeium.com/pricing
- 🕒 **Verified**: 2025-11-28 17:38 UTC

### RooCode 🚀
- 📝 **Description**: AI-powered coding assistant for VS Code with advanced chat and automation.
- 🧠 **Key AI Features**: Code completion, chat, refactoring, multi-file edits.
- ⚙️ **Configuration**:
  - Set up API keys (OpenRouter, Anthropic, etc.).
  - Configure "Custom Modes" for specific tasks (e.g., "QA Engineer", "Architect").
- 💡 **Usage Examples**:
  - **Modes**: Switch to "Architect" mode to plan a feature before coding.
  - **Chat**: Use natural language to request complex refactors.
- 🔧 **Troubleshooting**:
  - **API Issues**: Verify API key credits.
  - **Updates**: Check GitHub releases for breaking changes in this fast-moving fork.
- 🌐 **Platforms**: VS Code; cross-platform.
- 💰 **Pricing Model**: Freemium; pro features available.
- ⚖️ **Notable Pros/Cons or Unique Aspects**: Pros: Seamless VS Code integration. Cons: Proprietary. Unique: Agentic coding workflows.
- 🕒 **Verified**: 2025-11-28 17:38 UTC

### Tabnine 🤝
- 📝 **Description**: AI-assisted code completion with team knowledge.
- 🧠 **Key AI Features**: Autocomplete, code generation, team learning.
- ⚙️ **Configuration**:
  - Click "Tabnine" in status bar to open Hub.
  - **Local Mode**: Enable for offline privacy (Pro feature).
  - **Team Learning**: Connect to your team's repo for context.
- 💡 **Usage Examples**:
  - **Completion**: Short, fast completions as you type.
  - **Whole Line**: Predicts entire function calls based on patterns.
- 🔧 **Troubleshooting**:
  - **Performance**: If slowing down VS Code, try disabling "cloud" completions in settings.
  - **Logs**: output channel "Tabnine".
- 🌐 **Platforms**: VS Code, JetBrains.
- 💰 **Pricing Model**: Freemium; enterprise tiers.
- 🔗 **Sources**: https://www.tabnine.com, https://www.tabnine.com/pricing
- 🕒 **Verified**: 2025-11-28 17:38 UTC

### Tabby 🗃️
- 📝 **Description**: Self-hosted AI completion server with editor plugins.
- 🧠 **Key AI Features**: On-prem autocomplete, privacy-first team suggestions.
- ⚙️ **Configuration**:
  - **Endpoint**: Set `Tabby: API Endpoint` to your server URL (e.g., `http://localhost:8080`).
  - **Token**: Add authentication token if configured on server.
- 💡 **Usage Examples**:
  - **Self-Hosted**: Complete control over data and model (e.g., StarCoder).
  - **Dashboard**: View usage stats on your local Tabby instance.
- 🔧 **Troubleshooting**:
  - **Connection**: Verify server is reachable via `curl http://localhost:8080`.
  - **GPU**: Ensure Docker has GPU access for reasonable latency.
- 🌐 **Platforms**: Server + VS Code/JetBrains plugins.
- 💰 **Pricing Model**: Free (open-source); commercial support.
- 🔗 **Sources**: https://github.com/TabbyML/tabby, https://tabbyml.github.io
- 🕒 **Verified**: 2025-11-28 17:38 UTC

### Keploy 🐰
- 📝 **Description**: Open-source AI-powered API testing platform that auto-generates test cases.
- 🧠 **Key AI Features**: Auto-generates tests from API traffic, mocks dependencies, regression testing.
- ⚙️ **Configuration**:
  - Install extension and follow setup to capture traffic.
  - **Record Mode**: Run app with Keploy to record API calls.
  - **Test Mode**: Replay traffic to verify API behavior.
- 💡 **Usage Examples**:
  - **Auto-Test**: "Generate tests for the user login flow."
  - **Mocking**: Automatically mocks database/external service calls during testing.
- 🔧 **Troubleshooting**:
  - **Connection**: Ensure Keploy server is running locally.
  - **Docker**: Check Docker permissions if running in container mode.
- 🌐 **Platforms**: VS Code.
- 💰 **Pricing Model**: Free (open-source); enterprise cloud.
- 🔗 **Sources**: https://keploy.io, https://github.com/keploy/keploy
- 🕒 **Verified**: 2025-12-05 08:35 UTC

## JetBrains Add-ons 🧠

### JetBrains AI Assistant 🧠
- 📝 **Description**: Built-in AI assistant across JetBrains IDEs.
- 🧠 **Key AI Features**: Chat, refactoring suggestions, code generation, docs explanations.
- ⚙️ **Configuration**:
  - **Settings**: Tools > AI Assistant.
  - **Data Sharing**: Configure what code context is sent to the cloud.
- 💡 **Usage Examples**:
  - **Chat**: Open "AI Assistant" tool window on the right.
  - **Refactor**: Select code > Alt+Enter > "Refactor with AI".
  - **Commit Messages**: Click "Generate Commit Message" with AI sparkles icon in Commit window.
- 🔧 **Troubleshooting**:
  - **License**: Ensure your organization has assigned an AI license to your account.
  - **Region**: Some features may be restricted by region (check JetBrains policy).
- 🌐 **Platforms**: JetBrains IDEs.
- 💰 **Pricing Model**: Subscription (add-on).
- 🔗 **Sources**: https://www.jetbrains.com/ai/
- 🕒 **Verified**: 2025-11-28 17:38 UTC

### JetBrains Claude Agent 🧠
- 📝 **Description**: Agent integrated via AI Assistant; agentic coding inside JetBrains IDEs.
- 🧠 **Key AI Features**: Deep project context, planning/execution, terminal integration.
- ⚙️ **Configuration**:
  - Select "Claude" as the model/provider in AI Assistant settings (if available).
- 💡 **Usage Examples**:
  - **Complex Tasks**: "Refactor the entire module X to use pattern Y."
- 🔧 **Troubleshooting**:
  - **Availability**: Check if your IDE version supports the latest AI features (update often).
- 🌐 **Platforms**: JetBrains IDEs.
- 💰 **Pricing Model**: Subscription (JetBrains AI).
- 🔗 **Sources**: https://blog.jetbrains.com/ai/2025/09/introducing-claude-agent-in-jetbrains-ides/, https://docs.claude.com/en/docs/claude-code/jetbrains
- 🕒 **Verified**: 2025-11-28 17:38 UTC

---

Made with ❤️ by ReadyPixels LLC
