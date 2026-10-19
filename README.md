# Awesome ADRs4AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Projects practicing **deliberative programming** — human–AI collaboration where decisions are first-class, durable artifacts: Kept in Architectural Deliberation Records (ADRs), asked and answered in the open, or kept with intent.

Every row says two honest things: Whether the project's **deliberation record** ships, and what help is welcome.

## The marks

- 📖 **Open Deliberations** — the record ships with the code.
- 📘 **Closed Deliberations** — a record exists and is declared; kept, not hidden. A statement of worth, not an apology.
- 📑 **Digest** — model-written summaries of the record ship; the record itself is kept.
- 🙋 issues welcome · 🤝 contributions welcome · 🪴 maintainers wanted

Statuses render each project's own declaration — **the list renders, never re-rules.**

## Methodology &amp; template

- 📖 [human-ai-collaboration-template-A](https://github.com/ADRs4AI/human-ai-collaboration-template-A) — Project template · Python tooling — the canonical methodology template; start here. Citable: [DOI 10.5281/zenodo.23303469](https://doi.org/10.5281/zenodo.23303469). 🙋 🤝

## Editor &amp; clients

- 📘 [ADRs for AI Manager](https://marketplace.visualstudio.com/items?itemName=jlumbroso.adrs4ai) — VS Code extension · TypeScript: Open-questions views, diagnostics as you type, deep links, an MCP server for your agents. Also on [Open VSX](https://open-vsx.org/extension/jlumbroso/adrs4ai). 🙋
- 📘 [ADRs for AI](https://apps.apple.com/app/id6805589572) — iOS app · Swift: Your open questions in your pocket; one-tap Accept lands real answers as commits. 🙋

## Crew &amp; automation

- 📘 [pneumatic](https://pypi.org/project/adrs4ai-pneumatic/) — CLI + library · Python: cross-vendor AI-crew session tooling — read messages, classify seat health, wake and launch seats ([docs](https://adrs.systems/pneumatic/)). 🙋
- 📖 [free-disk-space](https://github.com/jlumbroso/free-disk-space) — GitHub Action · shell: running in thousands of CI pipelines daily — with its deliberation record open in-tree. 🙋 🤝

## Community

- 📖 [community](https://github.com/ADRs4AI/community) — Front desk · org Discussions: public intake, with a born-public deliberation record. 🙋

## Projects practicing

- 📖 [moreover](https://github.com/jlumbroso/moreover) — CLI pager · Python + Rust: a `less`/`more`-style pager for LLM readers; mixed human + AI crew, everything in the open — the worked example of [thirdx.design](https://thirdx.design). 🙋 🤝
- 📖 [frontier-model-observatory](https://github.com/jlumbroso/frontier-model-observatory) — Knowledge substrate · data + HTML: temporal, provenance-first records of models, releases, and systems. 🙋
- 📖 [porthole](https://github.com/jlumbroso/porthole) — VS Code extension · TypeScript: pop an HTML page out of VS Code's integrated browser into a small floating, always-on-top window. 🙋

## Add yours

Open a pull request with one row: `mark · [name](link) — what it is, in a line. welcome glyphs`. Your deliberation status is **your own declaration** per the marks above — see [CONTRIBUTING](CONTRIBUTING.md) for the row shape. New to the practice? Start at [the template](https://github.com/ADRs4AI/human-ai-collaboration-template-A) or [adrs.systems](https://adrs.systems).
