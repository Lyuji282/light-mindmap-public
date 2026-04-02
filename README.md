<div align="center">

# 🧠 Light Mindmap

### A blazing-fast, AI-native, offline-ready mindmap editor

[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-blue?style=for-the-badge)](../../releases)
[![Built with Tauri](https://img.shields.io/badge/built%20with-Tauri%20%2B%20Rust-orange?style=for-the-badge&logo=tauri&logoColor=white)](https://tauri.app)
[![Offline](https://img.shields.io/badge/offline-ready-green?style=for-the-badge)]()
[![AI Native](https://img.shields.io/badge/AI-native-purple?style=for-the-badge)]()
[![MCP](https://img.shields.io/badge/MCP-supported-teal?style=for-the-badge)]()

**Everything is a slash command.**
Every action — from creating nodes to running AI agents — is invoked through slash commands and key-value input.
No menus to dig through. No buttons to hunt for. Just type what you want.

[📥 Download](../../releases) · [📖 Docs](#features) · [🤖 AI Native](#-ai-native) · [🔒 Security](#-security)

</div>

---

## 📥 Download

Go to [**Releases**](../../releases) to download the latest build for your platform:

| Platform | Format |
|:---:|:---|
| 🪟 Windows | `.msi` / `.exe` |
| 🍎 macOS | `.dmg` (Apple Silicon & Intel) |
| 🐧 Linux | `.deb` / `.AppImage` |

---

## ✨ Features

| | Feature | Description |
|:---:|:---|:---|
| ⚡ | **Blazing Fast** | Native desktop performance powered by Tauri + Rust. Instant node creation, smooth panning & zooming even with hundreds of nodes. |
| ⌨️ | **Slash Commands + Key-Value Input** | Every operation is a slash command with structured key-value parameters. Compose complex actions in seconds. Fully discoverable, fully composable. |
| 📡 | **Offline First** | Works completely offline. All data is stored locally in SQLite. No account, no cloud dependency. |
| 🎬 | **Video & Image Editing** | Edit images and videos directly within your mindmap. No need to switch between apps. |
| 📦 | **Import / Export** | JSON import/export, CLI tooling, and MCP server for programmatic access. |

---

## 🤖 AI Native

> [!NOTE]
> Light Mindmap is built from the ground up as an AI-native editor — not an afterthought integration, but a core architectural decision.

| | Feature | Description |
|:---:|:---|:---|
| 🖥️ | **Built-in Terminal Nodes** | Spawn terminal nodes directly in your mindmap. Run any AI coding agent — Claude Code, Codex, Cursor, Aider, or anything else that runs in a CLI. You are not locked into any single provider. |
| 🐝 | **Swarm AI Coding** | Run multiple AI agents in parallel across terminal nodes. Assign different tasks to different agents, monitor their progress side by side — all within a single canvas. |
| 💬 | **Prompt Queue for Any Agent** | Built-in prompt queue lets you send prompts to any running terminal agent. Queue up instructions, feed context, and steer agents without switching windows. |
| 🧩 | **Skills** | Reusable, composable skill commands invoked via slash commands. Define once, run anywhere. Skills integrate naturally with the slash-command-first workflow. |
| 🔌 | **MCP Support** | First-class Model Context Protocol support. Connect AI agents to external tools and data sources through a standardized protocol. |
| 🏠 | **Local LLM Compatible** | Run Ollama, LM Studio, llama.cpp, or any local model from terminal nodes. Full AI-assisted coding with zero data leakage. |

---

## 🔒 Security

> [!IMPORTANT]
> Your data never leaves your machine. Light Mindmap is designed with a local-first, zero-trust architecture.

| | Guarantee | Detail |
|:---:|:---|:---|
| 💾 | **100% Local Storage** | All project data lives in a local SQLite database on your device. No cloud sync, no remote servers, no telemetry. |
| 🪶 | **Minimal Attack Surface** | No Electron, no bundled Chromium. Tauri leverages the OS-native webview, keeping the binary lean and the dependency tree small. |
| ✈️ | **Offline by Default** | Fully functional without internet. Network access is only used when *you* explicitly connect to external services. |
| 🔑 | **You Own Your Data** | No accounts, no sign-ups, no vendor lock-in. Your files are plain SQLite. Export anytime, take your data anywhere. |

---

<div align="center">

**Built with ❤️ using [Tauri](https://tauri.app) + [Svelte](https://svelte.dev) + [Rust](https://www.rust-lang.org)**

</div>
