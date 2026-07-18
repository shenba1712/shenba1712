# Shenbaga Lakshmi

I'm Shenba — a senior engineer based in Munich. I spent years shipping systems in Java, Angular, and Node.js. These days I'm building agent tooling in TypeScript: layers that make AI systems cheaper, more honest, and easier to trust.

Writing is part of how I think. I publish on [Medium](https://medium.com/@shenbagalakshmi), usually about systems, architecture, and making hard ideas readable.

---

## Current work: [Context Compiler](https://github.com/shenba1712/context-compiler)

[![tests](https://github.com/shenba1712/context-compiler/actions/workflows/test.yml/badge.svg)](https://github.com/shenba1712/context-compiler/actions/workflows/test.yml)

Agents pay for whole files when the answer lives in a few sections. Context Compiler takes a file, a task, and a token budget, and returns only what looks relevant — plus a manifest of everything left out, so the agent can fetch more if it was wrong.

On long documents — novels, manuals, reports, spreadsheets — that routinely means **90–97% fewer tokens** with the answer still intact.

**[Live demo](https://context-compiler.onrender.com)** · **[Repository](https://github.com/shenba1712/context-compiler)**

What it actually does:

- **Local-first compile** — BM25 ranking, no model call required; works offline
- **Prove** — same question on the full file vs the compiled slice, side by side
- **MCP tools** — `compile_context` and `expand_section` for Cursor, Claude Code, Codex, and Claude Desktop
- **Recoverable omissions** — trimming is never silent; the agent always knows what was left out

---

## Skills

| Area | Tools |
| --- | --- |
| Building now | TypeScript, Node.js, MCP |
| Background | Java, Angular, system design |
| Tooling | Python, Docker |

---

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/shenbaga-lakshmi-srinivasan/) · [Medium](https://medium.com/@shenbagalakshmi) · [Email](mailto:shenbawrites@gmail.com)
