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
- **Video & Image Editing** — Edit images and videos directly within your mindmap. No need to switch between apps.
- **Import / Export** — JSON import/export, CLI tooling, and MCP server for programmatic access.

## AI Native

Light Mindmap is built from the ground up as an AI-native editor — not an afterthought integration, but a core architectural decision.

- **Built-in Terminal Nodes** — Spawn terminal nodes directly in your mindmap. Run any AI coding agent — Claude Code, Codex, Cursor, Aider, or anything else that runs in a CLI. You are not locked into any single provider. Every agent that works in a terminal works here.
- **Swarm AI Coding** — Run multiple AI agents in parallel across terminal nodes. Assign different tasks to different agents, monitor their progress side by side, and orchestrate a swarm of coding agents — all within a single canvas. The editor is designed for multi-agent workflows from the start.
- **Prompt Injection to Any Agent** — Built-in prompt queue lets you send prompts to any running terminal agent. Queue up instructions, feed context, and steer agents without switching windows.
- **Skills** — Reusable, composable skill commands invoked via slash commands from the CLI. Define once, run anywhere. Skills integrate naturally with the slash-command-first workflow.
- **MCP (Model Context Protocol)** — First-class MCP support. Connect AI agents to external tools and data sources through a standardized protocol. Extend what your agents can do without writing glue code.
- **Local LLM Compatible** — Run Ollama, LM Studio, llama.cpp, or any local model from terminal nodes. Full AI-assisted coding with zero data leakage — your prompts and code never leave your machine.

## Security

Light Mindmap is designed with a local-first, zero-trust architecture. Your data never leaves your machine.

- **100% Local Storage** — All project data lives in a local SQLite database on your device. No cloud sync, no remote servers, no telemetry. Nothing is sent anywhere.
- **No Unnecessary Dependencies** — Minimal attack surface. No Electron, no bundled Chromium. Tauri leverages the OS-native webview, keeping the binary lean and the dependency tree small.
- **Offline by Default** — The app is fully functional without an internet connection. Network access is only used when *you* explicitly connect to external services (e.g., AI APIs via terminal).
- **You Own Your Data** — No accounts, no sign-ups, no vendor lock-in. Your files are plain SQLite. Export anytime, take your data anywhere.
