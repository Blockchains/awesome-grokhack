# awesome-grokhack

Curated, verified list of open-source projects that integrate **Grok / the xAI API**, each forked into
[github.com/Blockchains](https://github.com/Blockchains) for [The Grok Hack](https://grokhack.com/). Machine-readable: [`grok-forge.json`](grok-forge.json).
Every fork's Grok/xAI integration surface (endpoints, models, tool calling, streaming, env vars, SDK exports) is indexed nightly in
[Blockchains/grokhack-index](https://github.com/Blockchains/grokhack-index) ([search](https://blockchains.github.io/grokhack-index/)) and used by
[grokhack.com /forge](https://grokhack.com/forge) ([composer](https://github.com/Blockchains/grokhack-forge)) to compose new apps.

**42 repos** · generated 2026-10-04T14:50:26Z · stars/licence/last push read from the GitHub API at generation time.

## Selection criteria

- **licence**: OSI open-source licence (custom/source-available/non-commercial excluded; xai-org/xai-cookbook kept as official with its MIT-style xAI licence)
- **activity**: upstream pushed within 90 days of 2026-10-03 (official xai-org repos included regardless)
- **stars**: >= 500 (official xai-org repos included regardless)
- **grok_integration**: GitHub code search finds "api.x.ai" or XAI_API_KEY in non-doc files of the default branch (official repos exempt)
- **excluded**: awesome/list/prompt-leak repos, account-pooling / reverse-engineered consumer-app access (ToS risk)
- **cap**: ~100 forks; official first, then Grok-specific repos, then by stars

## Contents

- [Official xAI repos](#official-xai-repos) (10)
- [SDKs and framework providers](#sdks-and-framework-providers) (1)
- [Gateways, routers and proxies](#gateways-routers-and-proxies) (7)
- [Agent frameworks](#agent-frameworks) (4)
- [Coding agents and CLI tools](#coding-agents-and-cli-tools) (12)
- [Chat UIs and desktop clients](#chat-uis-and-desktop-clients) (5)
- [Apps built on Grok](#apps-built-on-grok) (3)

## Official xAI repos

| Project | Fork | Stars | Licence | Last push | Description |
|---|---|---:|---|---|---|
| [xai-org/grok-1](https://github.com/xai-org/grok-1) | [Blockchains/grok-1](https://github.com/Blockchains/grok-1) | 52,233 | Apache-2.0 | 2024-08-30 | Grok open release |
| [xai-org/x-algorithm](https://github.com/xai-org/x-algorithm) | [Blockchains/x-algorithm](https://github.com/Blockchains/x-algorithm) | 33,505 | Apache-2.0 | 2026-10-03 | Algorithm powering the For You feed on X |
| [xai-org/grok-build](https://github.com/xai-org/grok-build) | [Blockchains/grok-build](https://github.com/Blockchains/grok-build) | 27,217 | Apache-2.0 | 2026-09-29 | SpaceXAI's coding agent harness and TUI. Fullscreen, mouse interactive, extensible. |
| [xai-org/grok-prompts](https://github.com/xai-org/grok-prompts) | [Blockchains/grok-prompts](https://github.com/Blockchains/grok-prompts) | 4,503 | AGPL-3.0 | 2025-11-17 | Prompts for our Grok chat assistant and the `@grok` bot on X. |
| [xai-org/xai-cookbook](https://github.com/xai-org/xai-cookbook) | [Blockchains/xai-cookbook](https://github.com/Blockchains/xai-cookbook) | 592 | xAI Beta Testing License (MIT-style, official) | 2026-10-02 | A collection of pragmatic, real-world examples guiding you from basic to advanced use of xAI's Grok APIs. |
| [xai-org/xai-sdk-python](https://github.com/xai-org/xai-sdk-python) | [Blockchains/xai-sdk-python](https://github.com/Blockchains/xai-sdk-python) | 582 | Apache-2.0 | 2026-09-28 | The official Python SDK for the xAI API |
| [xai-org/grok-build-plugin-cc](https://github.com/xai-org/grok-build-plugin-cc) | [Blockchains/grok-build-plugin-cc](https://github.com/Blockchains/grok-build-plugin-cc) | 257 | Apache-2.0 | 2026-08-04 | Claude Code plugin that delegates reviews, rescue tasks, and session transfer to the Grok Build CLI |
| [xai-org/xai-proto](https://github.com/xai-org/xai-proto) | [Blockchains/xai-proto](https://github.com/Blockchains/xai-proto) | 150 | Apache-2.0 | 2026-09-28 | Public protobuf definitions for xAI's gRPC APIs |
| [xai-org/xai-sdk-ts](https://github.com/xai-org/xai-sdk-ts) | [Blockchains/xai-sdk-ts](https://github.com/Blockchains/xai-sdk-ts) | 51 | Apache-2.0 | 2026-10-02 | The official TypeScript SDK for the SpaceXAI API |
| [xai-org/community-writer](https://github.com/xai-org/community-writer) | [Blockchains/community-writer](https://github.com/Blockchains/community-writer) | 1 | Apache-2.0 | 2026-10-01 | Community driven AI writer for Community Notes |

## SDKs and framework providers

| Project | Fork | Stars | Licence | Last push | Description |
|---|---|---:|---|---|---|
| [langchain-ai/langchain](https://github.com/langchain-ai/langchain) | [Blockchains/langchain](https://github.com/Blockchains/langchain) | 147,433 | MIT | 2026-10-04 | The agent engineering platform. |

## Gateways, routers and proxies

| Project | Fork | Stars | Licence | Last push | Description |
|---|---|---:|---|---|---|
| [farion1231/cc-switch](https://github.com/farion1231/cc-switch) | [Blockchains/cc-switch](https://github.com/Blockchains/cc-switch) | 139,947 | MIT | 2026-10-04 | A cross-platform desktop All-in-One assistant for Claude Code, Codex, OpenCode, OpenClaw, Grok Build & Hermes Agent. Only official website:  |
| [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute) | [Blockchains/OmniRoute](https://github.com/Blockchains/OmniRoute) | 72,847 | MIT | 2026-10-02 | Never stop coding. Free MIT AI gateway: one endpoint, 359 providers (150+ free), 1200+ models Kimi, Claude, GPT, Gemini, GLM, DeepSeek, Mini |
| [lidge-jun/opencodex](https://github.com/lidge-jun/opencodex) | [Blockchains/opencodex](https://github.com/Blockchains/opencodex) | 16,907 | MIT | 2026-10-04 | Universal provider proxy for OpenAI Codex & Claude Code — use any LLM (Claude, Gemini, Grok, DeepSeek, Ollama…) with Codex CLI, App, SDK, an |
| [ENTERPILOT/GoModel](https://github.com/ENTERPILOT/GoModel) | [Blockchains/GoModel](https://github.com/Blockchains/GoModel) | 1,212 | MIT | 2026-10-04 | AI gateway / AI control plane / AI proxy written in Go. Unified OpenAI-compatible and Anthropic-compatible API for OpenAI, Anthropic, Gemini |
| [jeremychone/rust-genai](https://github.com/jeremychone/rust-genai) | [Blockchains/rust-genai](https://github.com/Blockchains/rust-genai) | 896 | Apache-2.0 | 2026-09-27 | Rust multiprovider generative AI client (Ollama, OpenAi, Anthropic, Gemini, DeepSeek, ZAI, OpenRouter, FireworksAI, xAI/Grok, Groq,, ...) |
| [hex/claude-council](https://github.com/hex/claude-council) | [Blockchains/claude-council](https://github.com/Blockchains/claude-council) | 826 | MIT | 2026-10-01 | Claude Code plugin that asks several AI coding agents the same question and shows their answers side by side. Gemini, OpenAI, Grok, Perplexi |
| [askimo-ai/askimo](https://github.com/askimo-ai/askimo) | [Blockchains/askimo](https://github.com/Blockchains/askimo) | 512 | AGPL-3.0 | 2026-10-04 | AI desktop app for chat, RAG, Skills, MCP tools, and agents. Support multiple LLMs (Anthropic, OpenAI, VertexAI, vLLM, Nvidia NIM, Gemini, O |

## Agent frameworks

| Project | Fork | Stars | Licence | Last push | Description |
|---|---|---:|---|---|---|
| [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) | [Blockchains/hermes-agent](https://github.com/Blockchains/hermes-agent) | 251,123 | MIT | 2026-10-04 | The agent that grows with you |
| [browser-use/browser-use](https://github.com/browser-use/browser-use) | [Blockchains/browser-use](https://github.com/Blockchains/browser-use) | 117,116 | MIT | 2026-10-03 | Agents that use the browser. |
| [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents) | [Blockchains/TradingAgents](https://github.com/Blockchains/TradingAgents) | 109,719 | Apache-2.0 | 2026-10-03 | TradingAgents: Multi-Agents LLM Financial Trading Framework |
| [mem0ai/mem0](https://github.com/mem0ai/mem0) | [Blockchains/mem0](https://github.com/Blockchains/mem0) | 66,558 | Apache-2.0 | 2026-10-01 | The Memory Layer for AI Agents - Drop-in memory infrastructure for AI agents and apps. Context that persists. Built for production. |

## Coding agents and CLI tools

| Project | Fork | Stars | Licence | Last push | Description |
|---|---|---:|---|---|---|
| [anomalyco/opencode](https://github.com/anomalyco/opencode) | [Blockchains/opencode](https://github.com/Blockchains/opencode) | 211,703 | MIT | 2026-10-04 | The open source coding agent. |
| [earendil-works/pi](https://github.com/earendil-works/pi) | [Blockchains/pi](https://github.com/Blockchains/pi) | 112,367 | MIT | 2026-10-04 | AI agent toolkit: unified LLM API, agent loop, TUI, coding agent CLI |
| [cline/cline](https://github.com/cline/cline) | [Blockchains/cline](https://github.com/Blockchains/cline) | 69,829 | Apache-2.0 | 2026-10-03 | Autonomous coding agent as an SDK, IDE extension, or CLI assistant. |
| [tailcallhq/forgecode](https://github.com/tailcallhq/forgecode) | [Blockchains/forgecode](https://github.com/Blockchains/forgecode) | 7,639 | Apache-2.0 | 2026-10-03 | AI enabled pair programmer for Claude, GPT, O Series, Grok, Deepseek, Gemini and 300+ models |
| [tiann/hapi](https://github.com/tiann/hapi) | [Blockchains/hapi](https://github.com/Blockchains/hapi) | 5,177 | AGPL-3.0 | 2026-09-27 | App for Codex / Claude Code / Pi / OpenCode / Kimi Code / Grok Build, vibe coding anytime, anywhere |
| [xintaofei/codeg](https://github.com/xintaofei/codeg) | [Blockchains/codeg](https://github.com/Blockchains/codeg) | 3,789 | Apache-2.0 | 2026-10-03 | Collaborative multi-agent AI coding workspace: aggregate sessions from Claude Code, Codex, OpenCode, Pi, Grok Build, etc. Desktop app, self- |
| [superagent-ai/grok-cli](https://github.com/superagent-ai/grok-cli) | [Blockchains/grok-cli](https://github.com/Blockchains/grok-cli) | 3,486 | MIT | 2026-07-06 | An open-source coding agent for the Grok API |
| [happier-dev/happier](https://github.com/happier-dev/happier) | [Blockchains/happier](https://github.com/Blockchains/happier) | 1,854 | MIT | 2026-10-04 | Web, Desktop & Mobile client and orchestrator for Codex, Claude Code, OpenCode, Pi, Cursor, Grok, Antigravity, Kimi, Augment Code, Qwen, ful |
| [fynnfluegge/agtx](https://github.com/fynnfluegge/agtx) | [Blockchains/agtx](https://github.com/Blockchains/agtx) | 1,700 | Apache-2.0 | 2026-10-02 | 🏄🏼‍♂️ The blackboard for coding agents - agentic development environment for claude code, codex, cursor, opencode, grok and more. |
| [RongleCat/grok-app](https://github.com/RongleCat/grok-app) | [Blockchains/grok-app](https://github.com/Blockchains/grok-app) | 1,391 | MIT | 2026-10-04 | Open-source Grok App — desktop workbench (GUI) for the local Grok Build CLI: sessions, projects, media, automations. Tauri 2. |
| [aeonfun/aeon](https://github.com/aeonfun/aeon) | [Blockchains/aeon](https://github.com/Blockchains/aeon) | 763 | MIT | 2026-10-03 | The most autonomous AI agent framework: runs unattended on GitHub Actions, self-healing skills, drives Claude Code, Grok, Codex & more. No a |
| [firstintent/ccteam](https://github.com/firstintent/ccteam) | [Blockchains/ccteam](https://github.com/Blockchains/ccteam) | 631 | MIT | 2026-10-03 | ccteam turns the coding agents you already run (Claude Code, Codex, Grok, DeepSeek Harness, Kimi, Pi) into one team — any session can spawn, |

## Chat UIs and desktop clients

| Project | Fork | Stars | Licence | Last push | Description |
|---|---|---:|---|---|---|
| [ChatGPTNextWeb/NextChat](https://github.com/ChatGPTNextWeb/NextChat) | [Blockchains/NextChat](https://github.com/Blockchains/NextChat) | 88,833 | MIT | 2026-08-11 | ✨ Zero-config AI chat assistant. No API key needed — sign up and instantly chat with GPT-5, Claude 4, Gemini 2.5, DeepSeek & 100+ top models |
| [Mintplex-Labs/anything-llm](https://github.com/Mintplex-Labs/anything-llm) | [Blockchains/anything-llm](https://github.com/Blockchains/anything-llm) | 66,708 | MIT | 2026-10-04 | Stop renting your intelligence. Own it with AnythingLLM. Everything you need for a powerful local-first agent experience  |
| [moeru-ai/airi](https://github.com/moeru-ai/airi) | [Blockchains/airi](https://github.com/Blockchains/airi) | 50,019 | MIT | 2026-10-04 | 💖🧸 Self hosted, you-owned Grok Companion, a container of souls of waifu, cyber livings to bring them into our worlds, wishing to achieve Neu |
| [chatboxai/chatbox](https://github.com/chatboxai/chatbox) | [Blockchains/chatbox](https://github.com/Blockchains/chatbox) | 41,937 | GPL-3.0 | 2026-09-24 | Powerful AI Client |
| [szczyglis-dev/py-gpt](https://github.com/szczyglis-dev/py-gpt) | [Blockchains/py-gpt](https://github.com/Blockchains/py-gpt) | 1,971 | MIT | 2026-10-03 | Desktop AI Assistant powered by GPT-6, GPT-5, Gemini, Claude, Grok, Ollama, DeepSeek, Perplexity, and more - chat, agents, tools, MCP, plugi |

## Apps built on Grok

| Project | Fork | Stars | Licence | Last push | Description |
|---|---|---:|---|---|---|
| [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl) | [Blockchains/firecrawl](https://github.com/Blockchains/firecrawl) | 188,479 | AGPL-3.0 | 2026-10-03 | Supercharge your AI agents with data from the web and beyond. Building the library for superintelligence. 🔥 |
| [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | [Blockchains/MoneyPrinterTurbo](https://github.com/Blockchains/MoneyPrinterTurbo) | 128,374 | MIT | 2026-10-04 | 利用 AI 大模型和自动化工作流，根据主题或关键词一键生成高清短视频。Generate HD short videos from a topic or keyword with an automated AI workflow. |
| [milind-soni/OpenMausBot](https://github.com/milind-soni/OpenMausBot) | [Blockchains/OpenMausBot](https://github.com/Blockchains/OpenMausBot) | 4,022 | Apache-2.0 | 2026-10-04 | Open-source Grok Bot alternative with a virtual machine that bots can use |

## Considered but not forked

284 candidates from GitHub search were skipped:

- 126 × no Grok/xAI reference found by code search
- 107 × over the ~100 fork cap (lower stars)
- 21 × no OSI open-source licence detected
- 13 × account-pooling / reverse-engineered access / ToS risk
- 10 × below 500 stars
- 6 × Grok/xAI only mentioned in docs, not code
- 1 × no licence

Full list with reasons: [`skipped.json`](skipped.json).

## Licence

This list: CC0-1.0. Each project keeps its own licence (column above); forks are unmodified mirrors of the upstream default branch.
