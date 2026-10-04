# awesome-grokhack

Curated, verified list of open-source projects that integrate **Grok / the xAI API**, each forked into
[github.com/Blockchains](https://github.com/Blockchains) for [The Grok Hack](https://grokhack.com/). Machine-readable: [`grok-forge.json`](grok-forge.json).
Every fork's Grok/xAI integration surface (endpoints, models, tool calling, streaming, env vars, SDK exports) is indexed nightly in
[Blockchains/grokhack-index](https://github.com/Blockchains/grokhack-index) ([search](https://blockchains.github.io/grokhack-index/)) and used by
the [grokhack-forge composer](https://github.com/Blockchains/grokhack-forge) to compose new apps.

**99 repos** · generated 2026-10-04T16:20:05Z · stars/licence/last push read from the GitHub API at generation time.

## Selection criteria

- **licence**: OSI open-source licence (custom/source-available/non-commercial excluded; xai-org/xai-cookbook kept as official with its MIT-style xAI licence)
- **activity**: upstream pushed within 90 days of 2026-10-03 (official xai-org repos included regardless)
- **stars**: >= 500 (official xai-org repos included regardless)
- **grok_integration**: GitHub code search finds "api.x.ai" or XAI_API_KEY in non-doc files of the default branch (official repos exempt)
- **excluded**: awesome/list/prompt-leak repos, account-pooling / reverse-engineered consumer-app access (ToS risk)
- **cap**: ~100 forks; official first, then Grok-specific repos, then by stars

## Contents

- [Official xAI repos](#official-xai-repos) (9)
- [SDKs and framework providers](#sdks-and-framework-providers) (7)
- [Gateways, routers and proxies](#gateways-routers-and-proxies) (8)
- [Agent frameworks](#agent-frameworks) (15)
- [Coding agents and CLI tools](#coding-agents-and-cli-tools) (23)
- [Chat UIs and desktop clients](#chat-uis-and-desktop-clients) (9)
- [Observability and evals](#observability-and-evals) (2)
- [Voice and realtime](#voice-and-realtime) (3)
- [Apps built on Grok](#apps-built-on-grok) (23)

## Official xAI repos

| Project | Fork | Stars | Licence | Last push | Description |
|---|---|---:|---|---|---|
| [xai-org/x-algorithm](https://github.com/xai-org/x-algorithm) | [Blockchains/x-algorithm](https://github.com/Blockchains/x-algorithm) | 33,506 | Apache-2.0 | 2026-10-03 | Algorithm powering the For You feed on X |
| [xai-org/grok-build](https://github.com/xai-org/grok-build) | [Blockchains/grok-build](https://github.com/Blockchains/grok-build) | 27,218 | Apache-2.0 | 2026-09-29 | SpaceXAI's coding agent harness and TUI. Fullscreen, mouse interactive, extensible. |
| [xai-org/grok-prompts](https://github.com/xai-org/grok-prompts) | [Blockchains/grok-prompts](https://github.com/Blockchains/grok-prompts) | 4,503 | AGPL-3.0 | 2025-11-17 | Prompts for our Grok chat assistant and the `@grok` bot on X. |
| [xai-org/xai-cookbook](https://github.com/xai-org/xai-cookbook) | [Blockchains/xai-cookbook](https://github.com/Blockchains/xai-cookbook) | 592 | xAI Beta Testing License (MIT-style, official) | 2026-10-02 | A collection of pragmatic, real-world examples guiding you from basic to advanced use of xAI's Grok APIs. |
| [xai-org/xai-sdk-python](https://github.com/xai-org/xai-sdk-python) | [Blockchains/xai-sdk-python](https://github.com/Blockchains/xai-sdk-python) | 582 | Apache-2.0 | 2026-09-28 | The official Python SDK for the xAI API |
| [xai-org/grok-build-plugin-cc](https://github.com/xai-org/grok-build-plugin-cc) | [Blockchains/grok-build-plugin-cc](https://github.com/Blockchains/grok-build-plugin-cc) | 257 | Apache-2.0 | 2026-08-04 | Claude Code plugin that delegates reviews, rescue tasks, and session transfer to the Grok Build CLI |
| [xai-org/xai-proto](https://github.com/xai-org/xai-proto) | [Blockchains/xai-proto](https://github.com/Blockchains/xai-proto) | 150 | Apache-2.0 | 2026-09-28 | Public protobuf definitions for xAI's gRPC APIs |
| [xai-org/xai-sdk-ts](https://github.com/xai-org/xai-sdk-ts) | [Blockchains/xai-sdk-ts](https://github.com/Blockchains/xai-sdk-ts) | 52 | Apache-2.0 | 2026-10-02 | The official TypeScript SDK for the SpaceXAI API |
| [xai-org/community-writer](https://github.com/xai-org/community-writer) | [Blockchains/community-writer](https://github.com/Blockchains/community-writer) | 1 | Apache-2.0 | 2026-10-01 | Community driven AI writer for Community Notes |

## SDKs and framework providers

| Project | Fork | Stars | Licence | Last push | Description |
|---|---|---:|---|---|---|
| [langchain-ai/langchain](https://github.com/langchain-ai/langchain) | [Blockchains/langchain](https://github.com/Blockchains/langchain) | 147,435 | MIT | 2026-10-04 | The agent engineering platform. |
| [run-llama/llama_index](https://github.com/run-llama/llama_index) | [Blockchains/llama_index](https://github.com/Blockchains/llama_index) | 52,408 | MIT | 2026-10-01 | LlamaIndex is the document processing platform for AI |
| [stanfordnlp/dspy](https://github.com/stanfordnlp/dspy) | [Blockchains/dspy](https://github.com/Blockchains/dspy) | 38,499 | MIT | 2026-10-04 | DSPy: The framework for programming—not prompting—language models |
| [vercel/ai](https://github.com/vercel/ai) | [Blockchains/ai](https://github.com/Blockchains/ai) | 27,118 | Apache-2.0 | 2026-10-04 | The AI Toolkit for TypeScript. From the creators of Next.js, the AI SDK is a free open-source library for building AI-powered applications a |
| [pydantic/pydantic-ai](https://github.com/pydantic/pydantic-ai) | [Blockchains/pydantic-ai](https://github.com/Blockchains/pydantic-ai) | 20,401 | MIT | 2026-10-04 | How Python does AI. Agents, realtime voice, image generation, embeddings. Every model, every interface, typed end to end. |
| [langchain-ai/langchainjs](https://github.com/langchain-ai/langchainjs) | [Blockchains/langchainjs](https://github.com/Blockchains/langchainjs) | 18,246 | MIT | 2026-10-03 | The agent engineering platform |
| [567-labs/instructor](https://github.com/567-labs/instructor) | [Blockchains/instructor](https://github.com/Blockchains/instructor) | 13,974 | MIT | 2026-10-01 | structured outputs for llms  |

## Gateways, routers and proxies

| Project | Fork | Stars | Licence | Last push | Description |
|---|---|---:|---|---|---|
| [farion1231/cc-switch](https://github.com/farion1231/cc-switch) | [Blockchains/cc-switch](https://github.com/Blockchains/cc-switch) | 139,968 | MIT | 2026-10-04 | A cross-platform desktop All-in-One assistant for Claude Code, Codex, OpenCode, OpenClaw, Grok Build & Hermes Agent. Only official website:  |
| [diegosouzapw/OmniRoute](https://github.com/diegosouzapw/OmniRoute) | [Blockchains/OmniRoute](https://github.com/Blockchains/OmniRoute) | 72,867 | MIT | 2026-10-02 | Never stop coding. Free MIT AI gateway: one endpoint, 359 providers (150+ free), 1200+ models Kimi, Claude, GPT, Gemini, GLM, DeepSeek, Mini |
| [BerriAI/litellm](https://github.com/BerriAI/litellm) | [Blockchains/litellm](https://github.com/Blockchains/litellm) | 60,122 | MIT (enterprise/ dir excluded) | 2026-10-04 | The fastest, litest AI Gateway. Rust core with Python SDK. Call 100+ LLM APIs in OpenAI (or native) format with cost tracking, guardrails, l |
| [lidge-jun/opencodex](https://github.com/lidge-jun/opencodex) | [Blockchains/opencodex](https://github.com/Blockchains/opencodex) | 16,910 | MIT | 2026-10-04 | Universal provider proxy for OpenAI Codex & Claude Code — use any LLM (Claude, Gemini, Grok, DeepSeek, Ollama…) with Codex CLI, App, SDK, an |
| [ENTERPILOT/GoModel](https://github.com/ENTERPILOT/GoModel) | [Blockchains/GoModel](https://github.com/Blockchains/GoModel) | 1,212 | MIT | 2026-10-04 | AI gateway / AI control plane / AI proxy written in Go. Unified OpenAI-compatible and Anthropic-compatible API for OpenAI, Anthropic, Gemini |
| [jeremychone/rust-genai](https://github.com/jeremychone/rust-genai) | [Blockchains/rust-genai](https://github.com/Blockchains/rust-genai) | 896 | Apache-2.0 | 2026-09-27 | Rust multiprovider generative AI client (Ollama, OpenAi, Anthropic, Gemini, DeepSeek, ZAI, OpenRouter, FireworksAI, xAI/Grok, Groq,, ...) |
| [hex/claude-council](https://github.com/hex/claude-council) | [Blockchains/claude-council](https://github.com/Blockchains/claude-council) | 827 | MIT | 2026-10-01 | Claude Code plugin that asks several AI coding agents the same question and shows their answers side by side. Gemini, OpenAI, Grok, Perplexi |
| [askimo-ai/askimo](https://github.com/askimo-ai/askimo) | [Blockchains/askimo](https://github.com/Blockchains/askimo) | 512 | AGPL-3.0 | 2026-10-04 | AI desktop app for chat, RAG, Skills, MCP tools, and agents. Support multiple LLMs (Anthropic, OpenAI, VertexAI, vLLM, Nvidia NIM, Gemini, O |

## Agent frameworks

| Project | Fork | Stars | Licence | Last push | Description |
|---|---|---:|---|---|---|
| [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) | [Blockchains/hermes-agent](https://github.com/Blockchains/hermes-agent) | 251,145 | MIT | 2026-10-04 | The agent that grows with you |
| [browser-use/browser-use](https://github.com/browser-use/browser-use) | [Blockchains/browser-use](https://github.com/Blockchains/browser-use) | 117,120 | MIT | 2026-10-03 | Agents that use the browser. |
| [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents) | [Blockchains/TradingAgents](https://github.com/Blockchains/TradingAgents) | 109,730 | Apache-2.0 | 2026-10-03 | TradingAgents: Multi-Agents LLM Financial Trading Framework |
| [mem0ai/mem0](https://github.com/mem0ai/mem0) | [Blockchains/mem0](https://github.com/Blockchains/mem0) | 66,563 | Apache-2.0 | 2026-10-01 | The Memory Layer for AI Agents - Drop-in memory infrastructure for AI agents and apps. Context that persists. Built for production. |
| [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) | [Blockchains/crewAI](https://github.com/Blockchains/crewAI) | 59,341 | MIT | 2026-10-03 | Framework for orchestrating role-playing, autonomous AI agents. By fostering collaborative intelligence, CrewAI empowers agents to work toge |
| [agno-agi/agno](https://github.com/agno-agi/agno) | [Blockchains/agno](https://github.com/Blockchains/agno) | 42,551 | Apache-2.0 | 2026-10-04 | Build, run, and manage agent platforms. |
| [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope) | [Blockchains/agentscope](https://github.com/Blockchains/agentscope) | 32,752 | Apache-2.0 | 2026-09-30 | Build and run agents you can see, understand and trust. |
| [mastra-ai/mastra](https://github.com/mastra-ai/mastra) | [Blockchains/mastra](https://github.com/Blockchains/mastra) | 28,552 | Apache-2.0 (ee/ dirs excluded) | 2026-10-04 | Mastra is the modern TypeScript framework for AI-powered applications and agents. |
| [Skyvern-AI/skyvern](https://github.com/Skyvern-AI/skyvern) | [Blockchains/skyvern](https://github.com/Blockchains/skyvern) | 23,131 | AGPL-3.0 | 2026-10-04 | Automate browser based workflows with AI |
| [camel-ai/camel](https://github.com/camel-ai/camel) | [Blockchains/camel](https://github.com/Blockchains/camel) | 17,811 | Apache-2.0 | 2026-09-30 | 🐫 CAMEL: The first and the best multi-agent framework. Finding the Scaling Law of Agents. https://www.camel-ai.org |
| [MemoriLabs/Memori](https://github.com/MemoriLabs/Memori) | [Blockchains/Memori](https://github.com/Blockchains/Memori) | 17,067 | Apache-2.0 | 2026-10-03 | Memori is agent-native memory infrastructure. A LLM-agnostic layer that turns agent execution and conversation into structured, persistent s |
| [GreyDGL/PentestGPT](https://github.com/GreyDGL/PentestGPT) | [Blockchains/PentestGPT](https://github.com/Blockchains/PentestGPT) | 15,710 | MIT | 2026-07-14 | Automated Penetration Testing Agentic Framework Powered by Large Language Models |
| [omnigent-ai/omnigent](https://github.com/omnigent-ai/omnigent) | [Blockchains/omnigent](https://github.com/Blockchains/omnigent) | 10,486 | Apache-2.0 | 2026-10-04 | Omnigent is an open-source AI agent framework and meta-harness: orchestrate Claude Code, Codex, Cursor, Pi, and custom agents — swap harness |
| [droidrun/mobilerun](https://github.com/droidrun/mobilerun) | [Blockchains/mobilerun](https://github.com/Blockchains/mobilerun) | 9,570 | MIT | 2026-10-02 | Automate your mobile devices with natural language commands - an LLM agnostic mobile Agent 🤖 |
| [MervinPraison/PraisonAI](https://github.com/MervinPraison/PraisonAI) | [Blockchains/PraisonAI](https://github.com/Blockchains/PraisonAI) | 9,133 | MIT | 2026-10-04 | PraisonAI 🦞 — Hire a 24/7 AI Workforce. Stop writing boilerplate and start shipping autonomous self-improving agents that research, plan, co |

## Coding agents and CLI tools

| Project | Fork | Stars | Licence | Last push | Description |
|---|---|---:|---|---|---|
| [anomalyco/opencode](https://github.com/anomalyco/opencode) | [Blockchains/opencode](https://github.com/Blockchains/opencode) | 211,716 | MIT | 2026-10-04 | The open source coding agent. |
| [earendil-works/pi](https://github.com/earendil-works/pi) | [Blockchains/pi](https://github.com/Blockchains/pi) | 112,385 | MIT | 2026-10-04 | AI agent toolkit: unified LLM API, agent loop, TUI, coding agent CLI |
| [cline/cline](https://github.com/cline/cline) | [Blockchains/cline](https://github.com/Blockchains/cline) | 69,834 | Apache-2.0 | 2026-10-03 | Autonomous coding agent as an SDK, IDE extension, or CLI assistant. |
| [aaif-goose/goose](https://github.com/aaif-goose/goose) | [Blockchains/goose](https://github.com/Blockchains/goose) | 54,938 | Apache-2.0 | 2026-10-02 | an open source, extensible AI agent that goes beyond code suggestions - install, execute, edit, and test with any LLM |
| [continuedev/continue](https://github.com/continuedev/continue) | [Blockchains/continue](https://github.com/Blockchains/continue) | 36,111 | Apache-2.0 | 2026-10-04 | open-source coding agent |
| [can1357/oh-my-pi](https://github.com/can1357/oh-my-pi) | [Blockchains/oh-my-pi](https://github.com/Blockchains/oh-my-pi) | 34,265 | MIT | 2026-10-04 | ⌥ Coding agent with the IDE wired in. Built by Stencil Labs. |
| [QwenLM/qwen-code](https://github.com/QwenLM/qwen-code) | [Blockchains/qwen-code](https://github.com/Blockchains/qwen-code) | 28,305 | Apache-2.0 | 2026-10-04 | An open-source AI coding agent that lives in your terminal. |
| [Kilo-Org/kilocode](https://github.com/Kilo-Org/kilocode) | [Blockchains/kilocode](https://github.com/Blockchains/kilocode) | 27,491 | MIT | 2026-10-04 | Kilo is the all-in-one agentic engineering platform. Build, ship, and iterate faster with the most popular open source coding agent. |
| [EveryInc/compound-engineering-plugin](https://github.com/EveryInc/compound-engineering-plugin) | [Blockchains/compound-engineering-plugin](https://github.com/Blockchains/compound-engineering-plugin) | 25,389 | MIT | 2026-10-02 | Official Compound Engineering plugin for Claude Code, Codex, Cursor, and more |
| [steipete/CodexBar](https://github.com/steipete/CodexBar) | [Blockchains/CodexBar](https://github.com/Blockchains/CodexBar) | 22,176 | MIT | 2026-10-04 | Show usage stats for OpenAI Codex and Claude Code, without having to login. |
| [1jehuang/jcode](https://github.com/1jehuang/jcode) | [Blockchains/jcode](https://github.com/Blockchains/jcode) | 20,298 | MIT | 2026-10-04 | High performance coding agent harness written in rust |
| [YishenTu/claudian](https://github.com/YishenTu/claudian) | [Blockchains/claudian](https://github.com/Blockchains/claudian) | 15,579 | MIT | 2026-10-04 | An Obsidian plugin that embeds Claude Code/Codex as an AI collaborator in your vault |
| [XiaomiMiMo/MiMo-Code](https://github.com/XiaomiMiMo/MiMo-Code) | [Blockchains/MiMo-Code](https://github.com/Blockchains/MiMo-Code) | 13,598 | MIT | 2026-10-03 | MiMo Code: Where Models and Agents Co-Evolve |
| [Nutlope/aicommits](https://github.com/Nutlope/aicommits) | [Blockchains/aicommits](https://github.com/Blockchains/aicommits) | 9,104 | MIT | 2026-09-05 | A CLI that writes your git commit messages for you with AI |
| [tailcallhq/forgecode](https://github.com/tailcallhq/forgecode) | [Blockchains/forgecode](https://github.com/Blockchains/forgecode) | 7,639 | Apache-2.0 | 2026-10-03 | AI enabled pair programmer for Claude, GPT, O Series, Grok, Deepseek, Gemini and 300+ models |
| [tiann/hapi](https://github.com/tiann/hapi) | [Blockchains/hapi](https://github.com/Blockchains/hapi) | 5,178 | AGPL-3.0 | 2026-09-27 | App for Codex / Claude Code / Pi / OpenCode / Kimi Code / Grok Build, vibe coding anytime, anywhere |
| [xintaofei/codeg](https://github.com/xintaofei/codeg) | [Blockchains/codeg](https://github.com/Blockchains/codeg) | 3,789 | Apache-2.0 | 2026-10-03 | Collaborative multi-agent AI coding workspace: aggregate sessions from Claude Code, Codex, OpenCode, Pi, Grok Build, etc. Desktop app, self- |
| [superagent-ai/grok-cli](https://github.com/superagent-ai/grok-cli) | [Blockchains/grok-cli](https://github.com/Blockchains/grok-cli) | 3,485 | MIT | 2026-07-06 | An open-source coding agent for the Grok API |
| [happier-dev/happier](https://github.com/happier-dev/happier) | [Blockchains/happier](https://github.com/Blockchains/happier) | 1,856 | MIT | 2026-10-04 | Web, Desktop & Mobile client and orchestrator for Codex, Claude Code, OpenCode, Pi, Cursor, Grok, Antigravity, Kimi, Augment Code, Qwen, ful |
| [fynnfluegge/agtx](https://github.com/fynnfluegge/agtx) | [Blockchains/agtx](https://github.com/Blockchains/agtx) | 1,700 | Apache-2.0 | 2026-10-02 | 🏄🏼‍♂️ The blackboard for coding agents - agentic development environment for claude code, codex, cursor, opencode, grok and more. |
| [RongleCat/grok-app](https://github.com/RongleCat/grok-app) | [Blockchains/grok-app](https://github.com/Blockchains/grok-app) | 1,392 | MIT | 2026-10-04 | Open-source Grok App — desktop workbench (GUI) for the local Grok Build CLI: sessions, projects, media, automations. Tauri 2. |
| [aeonfun/aeon](https://github.com/aeonfun/aeon) | [Blockchains/aeon](https://github.com/Blockchains/aeon) | 763 | MIT | 2026-10-04 | The most autonomous AI agent framework: runs unattended on GitHub Actions, self-healing skills, drives Claude Code, Grok, Codex & more. No a |
| [firstintent/ccteam](https://github.com/firstintent/ccteam) | [Blockchains/ccteam](https://github.com/Blockchains/ccteam) | 631 | MIT | 2026-10-04 | ccteam turns the coding agents you already run (Claude Code, Codex, Grok, DeepSeek Harness, Kimi, Pi) into one team — any session can spawn, |

## Chat UIs and desktop clients

| Project | Fork | Stars | Licence | Last push | Description |
|---|---|---:|---|---|---|
| [ChatGPTNextWeb/NextChat](https://github.com/ChatGPTNextWeb/NextChat) | [Blockchains/NextChat](https://github.com/Blockchains/NextChat) | 88,833 | MIT | 2026-08-11 | ✨ Zero-config AI chat assistant. No API key needed — sign up and instantly chat with GPT-5, Claude 4, Gemini 2.5, DeepSeek & 100+ top models |
| [Mintplex-Labs/anything-llm](https://github.com/Mintplex-Labs/anything-llm) | [Blockchains/anything-llm](https://github.com/Blockchains/anything-llm) | 66,708 | MIT | 2026-10-04 | Stop renting your intelligence. Own it with AnythingLLM. Everything you need for a powerful local-first agent experience  |
| [CherryHQ/cherry-studio](https://github.com/CherryHQ/cherry-studio) | [Blockchains/cherry-studio](https://github.com/Blockchains/cherry-studio) | 52,361 | AGPL-3.0 | 2026-10-04 | AI productivity studio with smart chat, autonomous agents, and 300+ assistants. Unified access to frontier LLMs |
| [moeru-ai/airi](https://github.com/moeru-ai/airi) | [Blockchains/airi](https://github.com/Blockchains/airi) | 50,022 | MIT | 2026-10-04 | 💖🧸 Self hosted, you-owned Grok Companion, a container of souls of waifu, cyber livings to bring them into our worlds, wishing to achieve Neu |
| [LibreChat-AI/LibreChat](https://github.com/LibreChat-AI/LibreChat) | [Blockchains/LibreChat](https://github.com/Blockchains/LibreChat) | 45,255 | MIT | 2026-10-04 | Enhanced ChatGPT Clone: Features Agents, MCP, Skills, DeepSeek, Anthropic, AWS, OpenAI, Responses API, Azure, Groq, o1, GPT-5, Mistral, Open |
| [chatboxai/chatbox](https://github.com/chatboxai/chatbox) | [Blockchains/chatbox](https://github.com/Blockchains/chatbox) | 41,938 | GPL-3.0 | 2026-09-24 | Powerful AI Client |
| [iOfficeAI/AionUi](https://github.com/iOfficeAI/AionUi) | [Blockchains/AionUi](https://github.com/Blockchains/AionUi) | 33,308 | Apache-2.0 | 2026-09-09 | Open-source 24/7 Cowork app for OpenClaw, Hermes, Claude Code, Codex, OpenCode and 20+ more CLI Agent \| Customize your assistants \| Team t |
| [fathah/hermes-desktop](https://github.com/fathah/hermes-desktop) | [Blockchains/hermes-desktop](https://github.com/Blockchains/hermes-desktop) | 14,355 | MIT | 2026-09-24 | Desktop Companion for Hermes Agent |
| [szczyglis-dev/py-gpt](https://github.com/szczyglis-dev/py-gpt) | [Blockchains/py-gpt](https://github.com/Blockchains/py-gpt) | 1,971 | MIT | 2026-10-03 | Desktop AI Assistant powered by GPT-6, GPT-5, Gemini, Claude, Grok, Ollama, DeepSeek, Perplexity, and more - chat, agents, tools, MCP, plugi |

## Observability and evals

| Project | Fork | Stars | Licence | Last push | Description |
|---|---|---:|---|---|---|
| [mlflow/mlflow](https://github.com/mlflow/mlflow) | [Blockchains/mlflow](https://github.com/Blockchains/mlflow) | 28,252 | Apache-2.0 | 2026-10-04 | The open source AI engineering platform for agents, LLMs, and ML models. MLflow enables teams of all sizes to debug, evaluate, monitor, and  |
| [promptfoo/promptfoo](https://github.com/promptfoo/promptfoo) | [Blockchains/promptfoo](https://github.com/Blockchains/promptfoo) | 25,699 | MIT | 2026-10-04 | Test your prompts, agents, and RAGs. Red teaming/pentesting/vulnerability scanning for AI. Compare performance of GPT, Claude, Gemini, DeepS |

## Voice and realtime

| Project | Fork | Stars | Licence | Last push | Description |
|---|---|---:|---|---|---|
| [pipecat-ai/pipecat](https://github.com/pipecat-ai/pipecat) | [Blockchains/pipecat](https://github.com/Blockchains/pipecat) | 16,173 | BSD-2-Clause | 2026-10-03 | Open Source framework for voice agents, multimodal apps, and realtime AI. Maintained by Daily and the community. |
| [livekit/agents](https://github.com/livekit/agents) | [Blockchains/agents](https://github.com/Blockchains/agents) | 14,507 | Apache-2.0 | 2026-10-04 | A framework for building realtime voice AI agents 🤖🎙️📹  |
| [GetStream/Vision-Agents](https://github.com/GetStream/Vision-Agents) | [Blockchains/Vision-Agents](https://github.com/Blockchains/Vision-Agents) | 8,151 | Apache-2.0 | 2026-10-04 | Open Vision Agents by Stream. Build voice and vision agents quickly with any model or video provider. Uses Stream's edge network for ultra-l |

## Apps built on Grok

| Project | Fork | Stars | Licence | Last push | Description |
|---|---|---:|---|---|---|
| [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl) | [Blockchains/firecrawl](https://github.com/Blockchains/firecrawl) | 188,510 | AGPL-3.0 | 2026-10-04 | Supercharge your AI agents with data from the web and beyond. Building the library for superintelligence. 🔥 |
| [harry0703/MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) | [Blockchains/MoneyPrinterTurbo](https://github.com/Blockchains/MoneyPrinterTurbo) | 128,400 | MIT | 2026-10-04 | 利用 AI 大模型和自动化工作流，根据主题或关键词一键生成高清短视频。Generate HD short videos from a topic or keyword with an automated AI workflow. |
| [virattt/ai-hedge-fund](https://github.com/virattt/ai-hedge-fund) | [Blockchains/ai-hedge-fund](https://github.com/Blockchains/ai-hedge-fund) | 63,857 | MIT | 2026-10-02 | An AI Hedge Fund Team |
| [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage) | [Blockchains/OpenMontage](https://github.com/Blockchains/OpenMontage) | 62,980 | AGPL-3.0 | 2026-10-03 | World's first open-source, agentic video production system. 12 production pipelines, 100+ tools, 700+ agent skill and production-knowledge f |
| [KeygraphHQ/shannon](https://github.com/KeygraphHQ/shannon) | [Blockchains/shannon](https://github.com/Blockchains/shannon) | 48,571 | AGPL-3.0 | 2026-10-01 | Shannon is an AI pentester for web applications and APIs. It analyzes your source code, identifies attack vectors, and executes real exploit |
| [HKUDS/DeepTutor](https://github.com/HKUDS/DeepTutor) | [Blockchains/DeepTutor](https://github.com/Blockchains/DeepTutor) | 40,782 | Apache-2.0 | 2026-10-04 | DeepTutor: Lifelong Personalized Tutoring. https://deeptutor.info/. |
| [THU-MAIC/OpenMAIC](https://github.com/THU-MAIC/OpenMAIC) | [Blockchains/OpenMAIC](https://github.com/Blockchains/OpenMAIC) | 39,932 | MIT | 2026-10-04 | Open Multi-Agent Interactive Classroom — Get an immersive, multi-agent learning experience in just one click |
| [lfnovo/open-notebook](https://github.com/lfnovo/open-notebook) | [Blockchains/open-notebook](https://github.com/Blockchains/open-notebook) | 39,798 | MIT | 2026-10-04 | An Open Source implementation of Notebook LM with more flexibility and features |
| [khoj-ai/khoj](https://github.com/khoj-ai/khoj) | [Blockchains/khoj](https://github.com/Blockchains/khoj) | 37,560 | AGPL-3.0 | 2026-08-02 | Your AI second brain. Self-hostable. Get answers from the web or your docs. Build custom agents, schedule automations, do deep research. Tur |
| [Anil-matcha/Open-Generative-AI](https://github.com/Anil-matcha/Open-Generative-AI) | [Blockchains/Open-Generative-AI](https://github.com/Blockchains/Open-Generative-AI) | 29,612 | MIT | 2026-10-03 | Unrestricted Open-source alternative to AI video platforms — Free AI image & video generation studio with 600+ models (Flux, Midjourney, Kli |
| [bagisto/bagisto](https://github.com/bagisto/bagisto) | [Blockchains/bagisto](https://github.com/Blockchains/bagisto) | 28,206 | MIT | 2026-10-01 | Open Source eCommerce & Multi-Vendor Marketplace Platform Built with Laravel for Enterprise-Scale Commerce, Supporting 10M+ SKUs |
| [vxcontrol/pentagi](https://github.com/vxcontrol/pentagi) | [Blockchains/pentagi](https://github.com/Blockchains/pentagi) | 25,242 | MIT | 2026-10-03 | Fully autonomous AI Agents system capable of performing complex penetration testing tasks |
| [andrewyng/openworker](https://github.com/andrewyng/openworker) | [Blockchains/openworker](https://github.com/Blockchains/openworker) | 18,422 | MIT | 2026-10-04 |  |
| [langbot-app/LangBot](https://github.com/langbot-app/LangBot) | [Blockchains/LangBot](https://github.com/Blockchains/LangBot) | 18,002 | Apache-2.0 | 2026-10-03 | Production-grade platform for building agentic IM bots - 生产级多平台智能机器人开发平台/ Agent、知识库编排、插件系统 / Bots for Discord / Slack / LINE / Telegram / We |
| [zaidmukaddam/scira](https://github.com/zaidmukaddam/scira) | [Blockchains/scira](https://github.com/Blockchains/scira) | 11,905 | AGPL-3.0 | 2026-08-12 | Scira (Formerly MiniPerplx) is a minimalistic AI-powered search engine that helps you find information on the internet and cites it too. Pow |
| [spinabot/brigade](https://github.com/spinabot/brigade) | [Blockchains/brigade](https://github.com/Blockchains/brigade) | 11,250 | MIT | 2026-10-03 | Brigade — Your personal intelligence, built enterprise-grade |
| [nexmoe/VidBee](https://github.com/nexmoe/VidBee) | [Blockchains/VidBee](https://github.com/Blockchains/VidBee) | 10,749 | MIT | 2026-09-30 | Download video and audio from  YouTube ,  TikTok ,  Twitter ,  Instagram ,  Facebook ,  Twitch ,  Bilibili , and 1000+ sites—or import local |
| [simplifaisoul/osiris](https://github.com/simplifaisoul/osiris) | [Blockchains/osiris](https://github.com/Blockchains/osiris) | 10,447 | MIT | 2026-10-03 | Open Source Global Intelligence Platform - Real-Time OSINT Dashboard - A Palantir Alternative -                            2nZNHm3Lr9umG3DVr |
| [mengxi-ream/read-frog](https://github.com/mengxi-ream/read-frog) | [Blockchains/read-frog](https://github.com/Blockchains/read-frog) | 9,966 | GPL-3.0 | 2026-10-04 | 🐸 Read Frog - Language Learning & Translate \| 🐸 陪读蛙 - 语言学习与翻译 |
| [yihong0618/bilingual_book_maker](https://github.com/yihong0618/bilingual_book_maker) | [Blockchains/bilingual_book_maker](https://github.com/Blockchains/bilingual_book_maker) | 9,828 | MIT | 2026-09-30 | Make bilingual epub books Using AI translate |
| [zilliztech/deep-searcher](https://github.com/zilliztech/deep-searcher) | [Blockchains/deep-searcher](https://github.com/Blockchains/deep-searcher) | 8,293 | Apache-2.0 | 2026-09-22 | Open Source Deep Research Alternative to Reason and Search on Private Data. Written in Python. |
| [xixu-me/xget](https://github.com/xixu-me/xget) | [Blockchains/xget](https://github.com/Blockchains/xget) | 8,196 | AGPL-3.0 | 2026-10-04 | Ultra-high-performance, secure, all-in-one acceleration engine for developer resources |
| [milind-soni/OpenMausBot](https://github.com/milind-soni/OpenMausBot) | [Blockchains/OpenMausBot](https://github.com/Blockchains/OpenMausBot) | 4,027 | Apache-2.0 | 2026-10-04 | Open-source Grok Bot alternative with a virtual machine that bots can use |

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

## Archived

Forks archived on 2026-10-04 because their upstream had no push in the 12 months before that date. The fork stays readable (and can be unarchived); it is no longer in the list above or the index.

- [xai-org/grok-1](https://github.com/xai-org/grok-1) (fork: Blockchains/grok-1, archived): upstream last pushed 2024-08-30.

## Licence

This list: CC0-1.0. Each project keeps its own licence (column above); forks are unmodified mirrors of the upstream default branch.

## Contributing

Issues and pull requests are welcome. Please read the [contributing guide](https://github.com/Blockchains/.github/blob/main/CONTRIBUTING.md), [code of conduct](https://github.com/Blockchains/.github/blob/main/CODE_OF_CONDUCT.md) and [security policy](https://github.com/Blockchains/.github/blob/main/SECURITY.md) first.

---
Built by Blockchain Lab — [blockchainlab.com](https://blockchainlab.com/?utm_source=github&utm_medium=readme&utm_campaign=awesome-grokhack)
