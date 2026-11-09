# Using this repo with Antigravity

This project includes a **Antigravity project rule** so the Karpathy-inspired behavioral guidelines apply automatically when you work here.

## In this repository

1. Open the folder in Antigravity.
2. The rule [`.Antigravity/rules/karpathy-guidelines.mdc`](.agent/rules/karpathy-guidelines.mdc) is committed with `alwaysApply: true`, so you do not need extra installation steps.
3. In Antigravity, you can confirm it under **Settings → Rules** (or the project rules UI), where `karpathy-guidelines` should appear.

## Use the same guidelines in another project

**Antigravity (recommended):** Copy `.Antigravity/rules/karpathy-guidelines.mdc` into that project’s `.Antigravity/rules/` directory (create the folders if needed). Adjust or merge with existing rules as you like.

**Other tools:** If a stack only supports a root instruction file, copy [`CLAUDE.md`](CLAUDE.md) into that project instead (or merge its contents into your existing instructions).

## Optional: personal Agent Skills

If you want the same content as a reusable skill under `~/.Antigravity/skills`, use [`skills/karpathy-guidelines/SKILL.md`](skills/karpathy-guidelines/SKILL.md). You can copy or symlink it into your personal skills directory; use whatever layout you use for other skills.

## Claude Code vs Antigravity

- **Claude Code:** Install via the plugin marketplace and [`README.md`](README.md) instructions; the plugin exposes the skill from this repo. Per-project use can also rely on `CLAUDE.md`.
- **Antigravity:** Use the committed `.Antigravity/rules/` file as described above. Antigravity does not read `.claude-plugin/` or `CLAUDE.md` by default.

## For contributors

When you change the four principles, keep **[`CLAUDE.md`](CLAUDE.md)** and **[`.Antigravity/rules/karpathy-guidelines.mdc`](.Antigravity/rules/karpathy-guidelines.mdc)** in sync. If the published skill/plugin text should match, update **[`skills/karpathy-guidelines/SKILL.md`](skills/karpathy-guidelines/SKILL.md)** as well.
