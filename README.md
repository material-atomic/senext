# @senext/cli

**Software Engineering Next Generation** — CLI for the [Senext School](https://senext.school) & Ecosy agentic ecosystem.

> **Status**: placeholder package (v0.0.1). Full CLI in development.

## Vision (Q4-2026)

```bash
npx @senext/cli prompts list
npx @senext/cli skills add <package>
npx @senext/cli agents dispatch <us-id>
npx @senext/cli providers test <id>
npx @senext/cli llm generate "<prompt>"
```

## Current behavior

```bash
npx @senext/cli
# prints placeholder banner
```

## Installation (when shipped)

```bash
npm install -g @senext/cli
# or use directly:
npx @senext/cli <command>
```

> Tip: alias `senext='npx @senext/cli'` trong `~/.zshrc` cho convenience.

## Roadmap

- **Phase 0** (now): npm name reservation under @senext namespace
- **Phase 1** (Q4-2026): MCP socket client, prompts/skills/agents/providers/models commands
- **Phase 2** (2027): Senext School auth, cloud deploy, plugin system

## Why scoped @senext

Reserves entire `@senext` namespace for future packages: `@senext/sdk`, `@senext/agents`, `@senext/types`, etc. Standard pattern aligned with `@vercel/cli`, `@aws-sdk/*`, etc.

## License

MIT — Material Atomic
