## Personal Projects

### 🔬 dap-gui — Standalone DAP Client GUI for PHP/Xdebug

Built a standalone DAP client GUI with Electron, React, TypeScript, and PrismJS. Provides IDE-like debugging for PHP/Xdebug without the overhead of a full IDE. Features include protocol parsing, session management, breakpoint gutter with persistent state, call stack / variables / watch expressions, debug adapter manager, remote path mapping, and collapsible layout with keyboard-driven controls.

**Repository:** [guzmandrade-dev/dap-gui](https://github.com/guzmandrade-dev/dap-gui)

---

### 💻 Ollama FIM — AI-Powered Inline Completions (VS Code & Vim)

Developed inline (ghost-text) code-completion extensions using Fill-In-the-Middle (FIM) models via a local Ollama instance.

- **VS Code:** `fim-completions` leverages the CompletionItemProvider API, supports multiple model families (rnj-1, DeepSeek, Qwen, Gemma, Mistral), injects file-level context, and uses debounced/cancellable requests. Released on the VS Code Marketplace.
- **Vim:** `ollama-fim.vim` ports the same UX and prompt engineering to pure Vim script with an async `curl` backend, ghost-text via `textprop`, and zero Python/Node/LSP dependencies.

**Repositories:** [VS Code Extension](https://github.com/guzmandrade-dev/fim-completions) · [Vim Plugin](https://github.com/guzmandrade-dev/ollama-fim.vim)

---

### 🤖 AI Provider for Ollama — WordPress 7.0 AI Connector Plugin

Open-source WordPress plugin implementing the upcoming WordPress 7.0 AI Connector interface, routing AI requests to a local Ollama instance instead of cloud providers.

**Repository:** [guzmandrade-dev/ai-provider-for-ollama](https://github.com/guzmandrade-dev/ai-provider-for-ollama)

---

### 📑 Visual Research Pal — AI-Assisted Visual PDF Review

Node.js/TypeScript workbench for researchers who want to discuss and improve their papers visually from the compiled PDF. It renders PDF pages to images, extracts text, and connects to an external agent via the Agent Client Protocol (ACP) to produce grounded, page-level suggestions as Markdown/JSON reports.

**Repository:** [guzmandrade-dev/visual-research-pal](https://github.com/guzmandrade-dev/visual-research-pal)

---
