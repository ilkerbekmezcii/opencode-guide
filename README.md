🌍 [English](README.md) | [Türkçe](README.tr.md) | [Español](README.es.md)

# 🔓 OpenCode — General User Guide

> **The open-source, terminal-native AI coding agent that executes tasks directly in your shell.**

<div align="center">

![Version](https://img.shields.io/badge/version-latest-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Platform](https://img.shields.io/badge/platform-Multi--LLM-darkgreen)

**⭐ Automate code generation, refactoring, and project tasks from the command line.**

</div>

---

## 📚 Table of Contents

- [What is OpenCode?](#what-is-opencode)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Interactive Mode (TUI)](#interactive-mode-tui)
- [Configuration](#configuration)
- [Slash Commands](#slash-commands)
- [Essential Keyboard Shortcuts](#essential-keyboard-shortcuts)
- [Tips & Tricks](#tips--tricks)
- [Resources](#resources)
- [Quick Reference Card](#quick-reference-card)

---

## What is OpenCode?

**OpenCode** is a terminal-native, open-source AI agent designed to automate codebase modifications, interact with Large Language Models (LLMs), and manage developer tasks. 

OpenCode operates inside your repository context, integrating with various LLM providers (supporting OpenAI, Anthropic, Gemini, local models, etc.) to perform actions, read files, edit code, and automate GitHub workflows with secure user controls.

---

## Installation

Install OpenCode globally depending on your operating system or preferred package manager:

### 🍎 macOS / 🐧 Linux (Homebrew)
```bash
brew install anomalyco/tap/opencode
```

### 🍎 macOS / 🐧 Linux (Install Script)
```bash
curl -fsSL https://opencode.ai/install | bash
```

### 🪟 Windows (WinGet)
```powershell
winget install SST.opencode
```

### 🪟 Windows (Chocolatey)
```powershell
choco install opencode
```

### Alternative (npm)
```bash
npm install -g opencode-ai@latest
```

---

## Getting Started

### 1. Launch the TUI

To start an interactive session with OpenCode, navigate to your project directory and run:

```bash
opencode
```

### 2. Enter Your Prompts

Once inside the interactive prompt, type your requests naturally:

```
> Check if there are syntax errors in src/main.py
> Refactor functions in utils.js to use modern ES6 syntax
> Add validation to the user email input field
```

### 3. Exit the Session

To exit the interactive shell:
* Type `/quit` or `/exit` in the prompt box.
* Or press **Ctrl+D** in the terminal.

---

## Interactive Mode (TUI)

### prompt box features

- **Reference Files:** Type `@` followed by a file name to search and inject the file contents into the agent's context.
- **Run Terminal Commands:** Start a prompt with `!your-command` to run a shell command directly and send its output to the agent.
- **Multi-line Input:** Press `Shift+Enter` to add a new line inside the prompt box.

---

## Configuration

OpenCode supports multiple LLMs and safety settings.

- **Configure Settings:** Type `/config` inside the TUI to open the settings interface.
- **Change Settings Directly:** Run `/config key=value` (e.g. `/config theme=dark`) to modify settings instantly.

---

## Slash Commands

Type `/` in the prompt box to open the command menu, or `/help` to see the full list of options.

| Command | Description |
|---------|-------------|
| `/new` | Clear the prompt area and start a new session |
| `/clear` | Wipe current conversation history and start fresh |
| `/compact` | Compress conversation history to save context window tokens |
| `/model <name>`| Switch active model mid-session |
| `/config` | Manage settings and configuration options |
| `/quit` | Exit OpenCode |

---

## Essential Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| **Ctrl + C** | Interrupt current operation / clear input |
| **Ctrl + D** | Exit the active session |
| **Ctrl + L** | Redraw the terminal screen |
| **Ctrl + O** | Toggle the transcript viewer (shows tool usage details) |

---

## Tips & Tricks

- **One-Shot Execution:** Run a prompt directly from your terminal shell without entering the TUI:
  ```bash
  opencode run "Explain the latest git commit changes"
  ```
- **Agent Orchestration:** Manage customized system prompt agents:
  ```bash
  opencode agent list
  ```
- **GitHub Automation:** Manage GitHub repository agent workflows directly:
  ```bash
  opencode github run
  ```

---

## Resources

- **GitHub Repository:** [github.com/anomalyco/opencode](https://github.com/anomalyco/opencode)
- **Official Website:** [opencode.ai](https://opencode.ai)

---

## Quick Reference Card

```
┌──────────────────────────────────────────────────────────┐
│                 🔓 OpenCode Quick Reference               │
├──────────────────────────────────────────────────────────┤
│                                                          │
│  START                     MANAGE                        │
│  opencode        .......  Launch TUI      /new           │
│  opencode run    .......  One-shot        /clear         │
│  opencode agent  .......  Manage Agents   /compact       │
│                                           /quit          │
│                                                          │
│  EDITOR                    KEYBINDINGS                   │
│  @file           .......  Reference file  Ctrl+C         │
│  !command        .......  Run shell       Ctrl+D         │
│  Shift+Enter     .......  New line        Ctrl+O         │
│                                           Ctrl+L         │
│                                                          │
│  CONFIG                                                  │
│  /config         .......  Settings Panel                 │
│  /model          .......  Change model                   │
│                                                          │
└──────────────────────────────────────────────────────────┘
```

---

> **OpenCode** — MIT Licensed — Developed with ❤️ by AnomalyCo
