# Shenbaga Lakshmi

I'm Shenba, a senior engineer based in Munich. I spent the better part of a decade shipping systems in Java, Angular, and Node.js. These days I'm building agent tooling in TypeScript: layers that make AI systems cheaper, more honest, and easier to trust.

Writing is a big part of how I think. I publish regularly on Medium about systems, architecture, and making hard ideas readable.

---

## Building now: [PromptMuster](https://github.com/shenba1712/prompt-muster)

Engineers treat prompts worse than any other production artifact: change one and you fly blind on whether outputs got better or worse, cost is invisible, and prompts live scattered across chat histories instead of where you work. PromptMuster is a git-native prompt engineering toolkit. Prompts live as files in a repo, get tested against expected outputs, are costed before and after every run, and are reachable inside your IDE through an MCP server. Local-first: no server ever holds your prompts or API keys.

What it does:

- **Prompts as files**: version history is `git log`, diffing is `git diff`, and prompt changes get reviewed in PRs like code
- **Eval runner**: assertions per prompt (exact, contains, schema, property, LLM-judge), run across models, with regressions measured against a committed baseline and cost deltas
- **MCP server**: your prompt library as native tools inside Claude Code, Cursor, and Claude Desktop
- **Cost intelligence**: token and cost preflight before you run, plus budget caps enforced in core

Built in strict TypeScript with a framework-free core and a Next.js dashboard. Pre-release, building in the open.

---

## [Context Compiler](https://github.com/shenba1712/context-compiler)

[![tests](https://github.com/shenba1712/context-compiler/actions/workflows/test.yml/badge.svg)](https://github.com/shenba1712/context-compiler/actions/workflows/test.yml)

Agents pay for whole files when the answer lives in a few sections. Context Compiler takes a file, a task, and a token budget, and returns only what looks relevant, plus a manifest of everything left out, so the agent can fetch more if it was wrong.

On long documents like novels, manuals, reports, and spreadsheets, that can mean **90%+ fewer tokens** with the answer still intact. How much you save depends on your token budget and how specific the question is.

**[Live demo](https://context-compiler.onrender.com)** · **[Repository](https://github.com/shenba1712/context-compiler)**

- **Local-first compile**: BM25 ranking, no model call required; works offline
- **Prove**: same question on the full file vs the compiled slice, side by side
- **MCP tools**: `compile_context` and `expand_section` for Cursor, Claude Code, Codex, and Claude Desktop
- **Recoverable omissions**: trimming is never silent; the agent always knows what was left out

---

## Writing

I publish on Medium about systems and architecture, and I edit [The Simplified CS Club](https://medium.com/the-simplified-computer-science-club), a publication about explaining computer science plainly.

My longest thread is a system-design series that builds a real URL shortener from the ground up, one hard decision at a time:

- [How to design a URL Shortener like Infrastructure](https://medium.com/the-simplified-computer-science-club/heres-how-to-design-a-url-shortener-like-a-staff-engineer-c065f9d498fd?sk=d7ea4883f47da207deb257a0579605d6)
- [The Girl Who Fell From the Sky and Walked out of the Jungle](https://medium.com/@shenbagalakshmi/juliane-koepcke-plane-crash-survival-b425c5206e8a?sk=51b496023ac3942aff21ec7c5ea4dc3e): Juliane Koepcke, the woman who chose the forest that almost killed her
- [What Is a Just-in-Time Compiler? A Beginner-Friendly Guide for Curious Developers](https://medium.com/techtrends-digest/what-is-a-just-in-time-compiler-a-beginner-friendly-guide-for-curious-developers-e8c72be5a583?sk=42c36f566edcc214a8abf21dfcae4aa8)
- [9 Not-So-Obscure Coding Rules That Every Senior Software Engineer Wants You To Know](https://medium.com/the-simplified-computer-science-club/9-not-so-obscure-coding-rules-that-every-senior-software-engineer-wants-you-to-know-0b21f7aae859?sk=34aeeb14797f54870ccca97eae8d9363)
- [What 18 Months Away From My Passion Taught Me About It](https://medium.com/swlh/how-to-find-your-passion-when-you-dont-know-a0e25ae1f4a9?sk=83d2a2607a9e7be8b0387d468f5a9610)

### Recently published

<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->

More across Medium and other engineering publications at [medium.com/@shenbagalakshmi](https://medium.com/@shenbagalakshmi).

---

## Other builds

Smaller things I built to learn a tool or scratch an itch:

- **[YouTube recommender](https://shenba1712.github.io/youtube-recommendation/)** (live): ranks search results by views, like ratio, and recency instead of relevance alone. Angular. ([Github](https://github.com/shenba1712/youtube-recommendation/))
- **[Morse code generator](https://shenba1712.github.io/morse-code-generator/)** (live): text to Morse and back, with WebAudio playback. Angular. ([Github](https://github.com/shenba1712/morse-code-generator))
- **[wctool](https://github.com/shenba1712/wctool)**: a from-scratch `wc` in Java, compiled to a native binary with GraalVM.
- **[JSONParser](https://github.com/shenba1712/JSONParser)**: a hand-written tokenizer and AST parser that validates JSON. Java.

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
