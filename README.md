🌍 [English](README.md) | [Türkçe](README.tr.md)

# 🔓 OpenCode — Community Guide

> A practical, independent guide to the open-source OpenCode coding agent.

<div align="center">

![Guide License](https://img.shields.io/badge/guide%20license-MIT-green)
![OpenCode](https://img.shields.io/badge/OpenCode-v2-black)
![Platform](https://img.shields.io/badge/platform-Terminal-blue)

**Use an open-source coding agent from your terminal, desktop, or web workflow.**

</div>

---

## What is OpenCode?

**OpenCode** is an open-source AI coding agent. It is available as a terminal interface, desktop app, and web app, and can connect to multiple model providers.

This repository is an **independent community guide**. It is not the official OpenCode repository and is not affiliated with or endorsed by the OpenCode maintainers.

## Installation

### Install script

```bash
curl -fsSL https://opencode.ai/v2/install | bash
```

### npm

```bash
npm install -g @opencode/cli
```

### Homebrew

```bash
brew install anomalyco/tap/opencode-v2
```

Standalone binaries are also available from the official OpenCode download page. The current official documentation notes that Windows package managers are not supported for the v2 CLI.

Launch OpenCode:

```bash
opencode
```

## Connect a Model Provider

Inside OpenCode, use:

```text
/connect
```

Then select and configure the provider you want to use.

## Getting Started

Open a terminal in your project directory and run:

```bash
opencode
```

Example requests:

```text
Explain this repository and identify the most important files.
Fix the failing tests without changing the public API.
Refactor this function and keep its behavior unchanged.
Review the current diff for possible regressions.
```

## Useful Workflows

### Understand a project

```text
Summarize the architecture and show me where requests enter the application.
```

### Implement a feature

```text
Add pagination to this endpoint and update the tests.
```

### Review code

```text
Review the current changes for bugs, unsafe assumptions, and missing tests.
```

### Web pairing

OpenCode can expose a web interface with:

```bash
opencode pair
```

Follow the local URL and credentials printed by the command.

## Customization

OpenCode supports configuration, plugins, MCP servers, custom commands, themes, and keybindings. Use the official documentation for the current configuration format because these features evolve quickly.

## Safety Tips

- Review shell commands and file edits before accepting broad changes.
- Keep API keys and secrets outside version control.
- Use Git so edits can be inspected and reverted.
- Run project tests after agent-driven changes.
- Use containers or VMs when you need stronger isolation.

## Official Resources

- Official website: https://opencode.ai
- Official documentation: https://opencode.ai/v2/docs
- Official repository: https://github.com/anomalyco/opencode

## License

The **content of this guide** is licensed under the [MIT License](LICENSE).

OpenCode itself is maintained by its own project contributors and is distributed under its own license. See the official repository for current project terms.

---

If this guide is useful, starring the repository helps other developers discover it.
