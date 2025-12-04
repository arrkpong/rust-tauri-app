# Tauri + React + Typescript

This template should help get you started developing with Tauri, React and Typescript in Vite.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)

## Prerequisites

- [Deno](https://deno.com/) (v2.0+)
- [Rust](https://www.rust-lang.org/tools/install)
- [Tauri Prerequisites](https://tauri.app/start/prerequisites/)

## Installation

```bash
deno install
```

## Development

Run the app in development mode:

```bash
deno task tauri dev
```

Run only the frontend (without Tauri):

```bash
deno task dev
```

## Build

Build the app for production:

```bash
deno task tauri build
```

The built application will be in `src-tauri/target/release/`.

