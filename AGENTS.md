# AGENTS.md: awesome-grokhack

Instructions for AI coding agents (Grok, Cursor, Claude Code, Codex, Copilot and others) working **in** this repo or **using it as a building block**. Humans: see [README.md](README.md).

## What this is

Curated list of 99 open-source Grok/xAI integrations (official xAI repos, SDKs, gateways, agent frameworks, coding agents, chat UIs, observability, voice, apps) forked under Blockchains, with machine-readable grok-forge.json.

- Kind: curated-list, dataset · stability: `stable` · licence: MIT
- Machine-readable manifest: [`blocks.json`](blocks.json) (schema: [BLOCKS-SCHEMA](https://github.com/Blockchains/.github/blob/main/docs/BLOCKS-SCHEMA.md))
- How it fits with the other Blockchains repos: [Build with Blocks](https://github.com/Blockchains/.github/blob/main/docs/BUILD-WITH-BLOCKS.md)

## Setup

```bash
python3 --version
```

## Build and test

```bash
# CI: validates grok-forge.json fields, README links and that every fork + upstream exists (gh api)
```

Tests hit **live** public networks/APIs (the org rule is no mocks). A failure can be an upstream outage: re-run before changing code.

## Structure

| Path | What |
|---|---|
| `README.md` | the list + criteria + Archived note |
| `grok-forge.json` | machine-readable list (consumed nightly by grokhack-index) |
| `skipped.json` | rejected candidates |

## Conventions

- Every repo in grok-forge.json must be linked from README.md (CI checks).
- Criteria live in grok-forge.json `criteria` and the README.

## Extension points

- Add a repo: fork it, add it to grok-forge.json (all required fields) and the README table; grokhack-index picks it up nightly.

## Do

- Keep `count` in sync.

## Don't

- Add a fork that fails the list's criteria (licence, stars, activity, not archived) without updating the criteria text.
- Commit secrets, keys or `.env` files. Run `gitleaks` before pushing; CI and the org policy reject leaks.

## Using it from another project

- **grok-forge.json** (file): `https://raw.githubusercontent.com/Blockchains/awesome-grokhack/main/grok-forge.json`
- **skipped.json** (file): `candidates rejected, with reasons`

See the README section [Use as a building block](README.md#use-as-a-building-block) for a copy-paste example.

## Related blocks

- [Blockchains/grokhack-index](https://github.com/Blockchains/grokhack-index): nightly index of these forks' Grok surface (reads grok-forge.json)
- [Blockchains/grokhack-forge](https://github.com/Blockchains/grokhack-forge): composes apps from the index
- [Blockchains/grokhack-submissions](https://github.com/Blockchains/grokhack-submissions): entry template for The Grok Hack
