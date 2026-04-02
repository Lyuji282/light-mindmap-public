# Light Mindmap

A blazing-fast, offline-ready mindmap editor built with Tauri.

**Everything is a slash command.** Every action — from creating nodes to running AI agents — is invoked through slash commands and key-value input. No menus to dig through, no buttons to hunt for. Just type what you want. This design principle maximizes operational speed and keeps your hands on the keyboard.

## Download

Go to [Releases](../../releases) to download the latest build for your platform:

- **Windows**: `.msi` / `.exe`
- **macOS**: `.dmg`
- **Linux**: `.deb` / `.AppImage`

## Features

- **Blazing Fast** — Native desktop performance powered by Tauri + Rust. Instant node creation, smooth panning & zooming even with hundreds of nodes.
- **Slash Commands + Key-Value Input** — Every operation is a slash command with structured key-value parameters. Compose complex actions in seconds. Fully discoverable, fully composable.
- **Offline First** — Works completely offline. All data is stored locally in SQLite. No account, no cloud dependency.
- **Built-in Terminal** — Spawn terminal nodes directly in your mindmap. Run any CLI tool, any AI coding agent — Claude Code, Codex, Cursor, Aider, or anything else that runs in a terminal. You are not locked into any single AI provider.
- **Swarm AI Coding** — Run multiple AI agents in parallel across terminal nodes. Orchestrate a swarm of coding agents, all visible and manageable within your mindmap.
- **Video & Image Editing** — Edit images and videos directly within your mindmap. No need to switch between apps.
- **Skills & MCP Support** — Extensible through Skills and Model Context Protocol (MCP). Connect to external tools and services seamlessly.
- **Import / Export** — JSON import/export, CLI tooling, and MCP server for programmatic access.

## Security

Light Mindmap is designed with a local-first, zero-trust architecture. Your data never leaves your machine.

- **100% Local Storage** — All project data lives in a local SQLite database on your device. No cloud sync, no remote servers, no telemetry. Nothing is sent anywhere.
- **No Unnecessary Dependencies** — Minimal attack surface. No Electron, no bundled Chromium. Tauri leverages the OS-native webview, keeping the binary lean and the dependency tree small.
- **Offline by Default** — The app is fully functional without an internet connection. Network access is only used when *you* explicitly connect to external services (e.g., AI APIs via terminal).
- **Local LLM Ready** — Run local LLMs (Ollama, LM Studio, llama.cpp, etc.) from built-in terminal nodes and use them for AI-assisted coding — entirely on your machine, with zero data leakage. Your code and prompts never leave your local environment.
- **You Own Your Data** — No accounts, no sign-ups, no vendor lock-in. Your files are plain SQLite. Export anytime, take your data anywhere.
