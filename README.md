# Weave

Weave is a local desktop task continuity manager for AI coding agents. It is
designed to keep one task moving across Claude Code and Codex while preserving
the session, queued corrections, and handoff context.

## v0.5 scope

- Tauri v2 desktop shell with Vue 3 and TypeScript
- Claude Code and Codex process adapters
- Persistent Weave sessions
- Correction queue with explicit interrupt and resume
- Agent handoff within the same task
- Optional isolated Headroom runtime bridge

The repository currently contains the initial application scaffold. Runtime
features will be implemented incrementally against the v0.5 plan.

## Development

Prerequisites: Node.js, Rust, and the platform requirements for Tauri v2.

```bash
npm install
npm run tauri dev
```

Build the web frontend:

```bash
npm run build
```

Build the desktop application:

```bash
npm run tauri build
```

## License

[MIT](LICENSE)
