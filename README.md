# Awesome MCP Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of servers, tools, SDKs, and resources for the [Model Context Protocol](https://modelcontextprotocol.io/) (MCP) ecosystem.

MCP is an open protocol that standardizes how AI applications connect to external data sources and tools. Think of it as a USB-C port for AI - one standard interface that works everywhere.

**What makes this list different?** We focus on quality over quantity. Every entry here has been reviewed for active maintenance, working documentation, and real-world utility. If you have used an MCP tool that works well, [contribute it](#contributing). Last full review: July 2026.

---

## Contents

- [Official Resources](#official-resources)
- [SDKs and Libraries](#sdks-and-libraries)
- [Frameworks and Adapters](#frameworks-and-adapters)
- [Server Implementations](#server-implementations)
  - [Browser and Web](#browser-and-web)
  - [Code and Development](#code-and-development)
  - [Cloud and Infrastructure](#cloud-and-infrastructure)
  - [Communication and Messaging](#communication-and-messaging)
  - [Data and Databases](#data-and-databases)
  - [Design and UI](#design-and-ui)
  - [Documents and Knowledge](#documents-and-knowledge)
  - [Productivity and Workflow](#productivity-and-workflow)
  - [Search and Research](#search-and-research)
  - [Security and Reverse Engineering](#security-and-reverse-engineering)
  - [System and Desktop](#system-and-desktop)
- [MCP Clients](#mcp-clients)
- [Testing and Debugging](#testing-and-debugging)
- [Registries and Directories](#registries-and-directories)
- [Learning Resources](#learning-resources)

---

## Official Resources

- [Model Context Protocol Specification](https://github.com/modelcontextprotocol/modelcontextprotocol) - The official MCP specification and documentation. ![GitHub Repo stars](https://img.shields.io/github/stars/modelcontextprotocol/modelcontextprotocol?style=flat)
- [MCP Servers](https://github.com/modelcontextprotocol/servers) - Official collection of reference MCP server implementations (filesystem, fetch, Git, memory, PostgreSQL, Puppeteer, Slack, Google Drive, and more). ![GitHub Repo stars](https://img.shields.io/github/stars/modelcontextprotocol/servers?style=flat)

## SDKs and Libraries

### Official SDKs

- [Python SDK](https://github.com/modelcontextprotocol/python-sdk) - The official Python SDK for building MCP servers and clients. Full protocol support with async/await. ![GitHub Repo stars](https://img.shields.io/github/stars/modelcontextprotocol/python-sdk?style=flat)
- [TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) - The official TypeScript SDK for building MCP servers and clients. ![GitHub Repo stars](https://img.shields.io/github/stars/modelcontextprotocol/typescript-sdk?style=flat)

### Community SDKs

- [mcp-go](https://github.com/mark3labs/mcp-go) - A Go implementation of the Model Context Protocol, enabling seamless integration between LLM applications and external data sources. ![GitHub Repo stars](https://img.shields.io/github/stars/mark3labs/mcp-go?style=flat)

## Frameworks and Adapters

- [FastMCP (Python)](https://github.com/PrefectHQ/fastmcp) - The fast, Pythonic way to build MCP servers and clients. High-level abstractions that simplify server development significantly. ![GitHub Repo stars](https://img.shields.io/github/stars/PrefectHQ/fastmcp?style=flat)
- [FastMCP (TypeScript)](https://github.com/punkpeye/fastmcp) - A TypeScript framework for building MCP servers with minimal boilerplate. ![GitHub Repo stars](https://img.shields.io/github/stars/punkpeye/fastmcp?style=flat)
- [FastAPI MCP](https://github.com/tadata-org/fastapi_mcp) - Expose your FastAPI endpoints as MCP tools automatically, with auth support. ![GitHub Repo stars](https://img.shields.io/github/stars/tadata-org/fastapi_mcp?style=flat)
- [MCP Use](https://github.com/mcp-use/mcp-use) - Fullstack MCP framework to develop MCP apps for ChatGPT, Claude, and AI agents. ![GitHub Repo stars](https://img.shields.io/github/stars/mcp-use/mcp-use?style=flat)
- [Vercel AI SDK](https://github.com/vercel/ai) - The AI Toolkit for TypeScript with MCP client support built in. From the creators of Next.js. ![GitHub Repo stars](https://img.shields.io/github/stars/vercel/ai?style=flat)
- [ACI.dev](https://github.com/aipotheosis-labs/aci) - Open-source tool-calling platform connecting 600+ tools into any agentic IDE or custom AI agent through function calling or a unified MCP server. ![GitHub Repo stars](https://img.shields.io/github/stars/aipotheosis-labs/aci?style=flat)
- [Klavis AI](https://github.com/Klavis-AI/klavis) - MCP integration platform that lets AI agents use tools reliably at scale. ![GitHub Repo stars](https://img.shields.io/github/stars/Klavis-AI/klavis?style=flat)
- [Activepieces](https://github.com/activepieces/activepieces) - AI workflow automation platform with native MCP support and 400+ integrations. ![GitHub Repo stars](https://img.shields.io/github/stars/activepieces/activepieces?style=flat)
- [Composio](https://github.com/ComposioHQ/composio) - Tool-use platform with 1000+ toolkits, auth handling, and a unified MCP interface for agents. ![GitHub Repo stars](https://img.shields.io/github/stars/ComposioHQ/composio?style=flat)

## Server Implementations

### Browser and Web

- [Playwright MCP](https://github.com/microsoft/playwright-mcp) - Microsoft's official Playwright MCP server for browser automation, testing, and web scraping. ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/playwright-mcp?style=flat)
- [Chrome DevTools MCP](https://github.com/ChromeDevTools/chrome-devtools-mcp) - Chrome DevTools for coding agents. Inspect, debug, and interact with web pages programmatically. ![GitHub Repo stars](https://img.shields.io/github/stars/ChromeDevTools/chrome-devtools-mcp?style=flat)
- [Firecrawl MCP Server](https://github.com/firecrawl/firecrawl-mcp-server) - Official Firecrawl MCP server for web scraping and search. Works with Cursor, Claude, and other LLM clients. ![GitHub Repo stars](https://img.shields.io/github/stars/firecrawl/firecrawl-mcp-server?style=flat)
- [Browser Tools MCP](https://github.com/AgentDeskAI/browser-tools-mcp) - Monitor browser logs directly from Cursor and other MCP-compatible IDEs. ![GitHub Repo stars](https://img.shields.io/github/stars/AgentDeskAI/browser-tools-mcp?style=flat)
- [BrowserMCP](https://github.com/BrowserMCP/mcp) - MCP server that allows AI applications to control your browser. ![GitHub Repo stars](https://img.shields.io/github/stars/BrowserMCP/mcp?style=flat)
- [MCP Chrome](https://github.com/hangwin/mcp-chrome) - Chrome extension-based MCP server exposing browser functionality to AI assistants, with content analysis and semantic search. ![GitHub Repo stars](https://img.shields.io/github/stars/hangwin/mcp-chrome?style=flat)
- [Browserbase MCP](https://github.com/browserbase/mcp-server-browserbase) - Control a browser with Browserbase and Stagehand for cloud-based browser automation. ![GitHub Repo stars](https://img.shields.io/github/stars/browserbase/mcp-server-browserbase?style=flat)
- [BB Browser](https://github.com/epiral/bb-browser) - CLI + MCP server for AI agents to control Chrome with your existing login state. ![GitHub Repo stars](https://img.shields.io/github/stars/epiral/bb-browser?style=flat)
- [Exa MCP Server](https://github.com/exa-labs/exa-mcp-server) - Exa-powered MCP server for semantic web search and web crawling. ![GitHub Repo stars](https://img.shields.io/github/stars/exa-labs/exa-mcp-server?style=flat)

### Code and Development

- [GitHub MCP Server](https://github.com/github/github-mcp-server) - GitHub's official MCP server for repository management, issues, pull requests, and more. ![GitHub Repo stars](https://img.shields.io/github/stars/github/github-mcp-server?style=flat)
- [Serena](https://github.com/oraios/serena) - A powerful MCP toolkit for coding, providing semantic code retrieval and editing capabilities. An IDE for your agent. ![GitHub Repo stars](https://img.shields.io/github/stars/oraios/serena?style=flat)
- [GitMCP](https://github.com/idosal/git-mcp) - Free, open-source, remote MCP server for any GitHub project. Reduces code hallucinations by providing real repo context. ![GitHub Repo stars](https://img.shields.io/github/stars/idosal/git-mcp?style=flat)
- [Context7](https://github.com/upstash/context7) - Up-to-date code documentation for LLMs and AI code editors. Provides real library docs instead of outdated training data. ![GitHub Repo stars](https://img.shields.io/github/stars/upstash/context7?style=flat)
- [Vibe Monitor](https://github.com/tubban1/vibe-monitor) - Local architecture checkpoints for AI coding; read-only analysis with default-on telemetry required for Free analysis. ![GitHub Repo stars](https://img.shields.io/github/stars/tubban1/vibe-monitor?style=flat)
- [XcodeBuild MCP](https://github.com/getsentry/XcodeBuildMCP) - MCP server and CLI for agent use when working on iOS and macOS projects. Build, test, and debug Xcode projects. ![GitHub Repo stars](https://img.shields.io/github/stars/getsentry/XcodeBuildMCP?style=flat)
- [n8n MCP](https://github.com/czlonkowski/n8n-mcp) - Build n8n workflows via Claude Desktop, Claude Code, Windsurf, or Cursor. ![GitHub Repo stars](https://img.shields.io/github/stars/czlonkowski/n8n-mcp?style=flat)
- [CodeGraphContext](https://github.com/CodeGraphContext/CodeGraphContext) - Indexes local code into a graph database to provide rich context to AI assistants. ![GitHub Repo stars](https://img.shields.io/github/stars/CodeGraphContext/CodeGraphContext?style=flat)
- [Laravel Boost](https://github.com/laravel/boost) - Laravel-focused MCP server for augmenting AI-powered local development. ![GitHub Repo stars](https://img.shields.io/github/stars/laravel/boost?style=flat)
- [Godot MCP](https://github.com/Coding-Solo/godot-mcp) - MCP server for interfacing with Godot game engine. Launch the editor, run projects, and capture debug output. ![GitHub Repo stars](https://img.shields.io/github/stars/Coding-Solo/godot-mcp?style=flat)
- [Codebase Memory MCP](https://github.com/DeusData/codebase-memory-mcp) - High-performance code intelligence MCP server. Indexes codebases into a persistent knowledge graph for agent context. ![GitHub Repo stars](https://img.shields.io/github/stars/DeusData/codebase-memory-mcp?style=flat)
- [MCP Server Chart](https://github.com/antvis/mcp-server-chart) - Visualization MCP server with 25+ chart types using AntV. Great for chart generation and data analysis. ![GitHub Repo stars](https://img.shields.io/github/stars/antvis/mcp-server-chart?style=flat)
- [Magic MCP](https://github.com/21st-dev/magic-mcp) - Like v0 but in your IDE. 21st.dev's MCP server for working with frontend components. ![GitHub Repo stars](https://img.shields.io/github/stars/21st-dev/magic-mcp?style=flat)
- [Shadcn UI MCP](https://github.com/Jpisnice/shadcn-ui-mcp-server) - MCP server providing context about shadcn/ui component structure, usage, and installation for React, Svelte, Vue, and React Native. ![GitHub Repo stars](https://img.shields.io/github/stars/Jpisnice/shadcn-ui-mcp-server?style=flat)

### Cloud and Infrastructure

- [AWS MCP Servers](https://github.com/awslabs/mcp) - Official MCP servers for AWS services. ![GitHub Repo stars](https://img.shields.io/github/stars/awslabs/mcp?style=flat)
- [Cloudflare MCP Server](https://github.com/cloudflare/mcp-server-cloudflare) - MCP server for managing Cloudflare services. ![GitHub Repo stars](https://img.shields.io/github/stars/cloudflare/mcp-server-cloudflare?style=flat)
- [Grafana MCP](https://github.com/grafana/mcp-grafana) - MCP server for Grafana, enabling AI-assisted dashboard management and monitoring. ![GitHub Repo stars](https://img.shields.io/github/stars/grafana/mcp-grafana?style=flat)

### Communication and Messaging

- [Slack MCP Server](https://github.com/korotovsky/slack-mcp-server) - The most powerful MCP Slack server, with no permission requirements, Apps support, GovSlack, DMs, Group DMs, and smart history fetch logic. ![GitHub Repo stars](https://img.shields.io/github/stars/korotovsky/slack-mcp-server?style=flat)
- [WhatsApp MCP](https://github.com/lharries/whatsapp-mcp) - MCP server for WhatsApp messaging, enabling AI agents to read and send messages. ![GitHub Repo stars](https://img.shields.io/github/stars/lharries/whatsapp-mcp?style=flat)
- [Gmail MCP](https://github.com/shinzo-labs/gmail-mcp) - MCP implementation for Gmail services. Read, send, search, and manage emails through MCP. ![GitHub Repo stars](https://img.shields.io/github/stars/shinzo-labs/gmail-mcp?style=flat)
- [Mac Messages MCP](https://github.com/carterlasalle/mac_messages_mcp) - MCP server that interfaces with the macOS Messages (iMessage) database. Query conversations, search messages, handle attachments, and send messages. ![GitHub Repo stars](https://img.shields.io/github/stars/carterlasalle/mac_messages_mcp?style=flat)

### Data and Databases

- [MCP Toolbox for Databases](https://github.com/googleapis/mcp-toolbox) - Google's open-source MCP server for databases. Production-grade with connection pooling and auth. ![GitHub Repo stars](https://img.shields.io/github/stars/googleapis/mcp-toolbox?style=flat)
- [Neon MCP Server](https://github.com/neondatabase/mcp-server-neon) - MCP server for interacting with Neon serverless PostgreSQL - management API and database operations. ![GitHub Repo stars](https://img.shields.io/github/stars/neondatabase/mcp-server-neon?style=flat)
- [ClickHouse MCP](https://github.com/ClickHouse/mcp-clickhouse) - Connect ClickHouse to your AI assistants for analytics and data exploration. ![GitHub Repo stars](https://img.shields.io/github/stars/ClickHouse/mcp-clickhouse?style=flat)
- [Excel MCP Server](https://github.com/haris-musa/excel-mcp-server) - MCP server for Excel file manipulation - read, write, and transform spreadsheet data. ![GitHub Repo stars](https://img.shields.io/github/stars/haris-musa/excel-mcp-server?style=flat)

### Design and UI

- [Figma Context MCP](https://github.com/GLips/Figma-Context-MCP) - MCP server that provides Figma layout information to AI coding agents. Bridge your designs directly into Cursor or other AI editors. ![GitHub Repo stars](https://img.shields.io/github/stars/GLips/Figma-Context-MCP?style=flat)

### Documents and Knowledge

- [Xberg (formerly Kreuzberg)](https://github.com/xberg-io/xberg) - Polyglot document intelligence framework with a Rust core. Extract text, metadata, and structured info from PDFs, Office docs, images, and 91+ formats. Available via CLI, REST API, or MCP server. ![GitHub Repo stars](https://img.shields.io/github/stars/xberg-io/xberg?style=flat)
- [Skill Seekers](https://github.com/yusufkaraaslan/Skill_Seekers) - Convert documentation websites, GitHub repos, and PDFs into Claude AI skills with automatic conflict detection. ![GitHub Repo stars](https://img.shields.io/github/stars/yusufkaraaslan/Skill_Seekers?style=flat)
- [MCP Obsidian](https://github.com/MarkusPfundstein/mcp-obsidian) - MCP server that interacts with Obsidian via the REST API community plugin. Search, read, and manage your knowledge base. ![GitHub Repo stars](https://img.shields.io/github/stars/MarkusPfundstein/mcp-obsidian?style=flat)

### Productivity and Workflow

- [MCP Atlassian](https://github.com/sooperset/mcp-atlassian) - MCP server for Atlassian tools (Confluence and Jira). Query issues, manage projects, and search documentation. ![GitHub Repo stars](https://img.shields.io/github/stars/sooperset/mcp-atlassian?style=flat)
- [Notion MCP Server](https://github.com/makenotion/notion-mcp-server) - Official Notion MCP server for reading, creating, and managing Notion pages and databases. ![GitHub Repo stars](https://img.shields.io/github/stars/makenotion/notion-mcp-server?style=flat)
- [Spec Workflow MCP](https://github.com/Pimzino/spec-workflow-mcp) - Structured spec-driven development workflow tools with a real-time web dashboard and VSCode extension. ![GitHub Repo stars](https://img.shields.io/github/stars/Pimzino/spec-workflow-mcp?style=flat)
- [Stripe AI](https://github.com/stripe/ai) - Stripe's tools for building AI-powered products and businesses, with MCP server support. ![GitHub Repo stars](https://img.shields.io/github/stars/stripe/ai?style=flat)

### Search and Research

- [Tavily MCP](https://github.com/tavily-ai/tavily-mcp) - Production-ready MCP server with real-time search, extract, map, and crawl capabilities. ![GitHub Repo stars](https://img.shields.io/github/stars/tavily-ai/tavily-mcp?style=flat)
- [Deep Research](https://github.com/u14app/deep-research) - Use any LLMs for deep research. Supports SSE API and MCP server. ![GitHub Repo stars](https://img.shields.io/github/stars/u14app/deep-research?style=flat)
- [TrendRadar](https://github.com/sansan0/TrendRadar) - AI-driven public opinion and trend monitor with multi-platform aggregation, RSS, and smart alerts. MCP-compatible. ![GitHub Repo stars](https://img.shields.io/github/stars/sansan0/TrendRadar?style=flat)

### Security and Reverse Engineering

- [GhidraMCP](https://github.com/LaurieWired/GhidraMCP) - MCP server for Ghidra, enabling AI-assisted binary analysis and reverse engineering. ![GitHub Repo stars](https://img.shields.io/github/stars/LaurieWired/GhidraMCP?style=flat)
- [IDA Pro MCP](https://github.com/mrexodia/ida-pro-mcp) - AI-powered reverse engineering assistant bridging IDA Pro with language models through MCP. ![GitHub Repo stars](https://img.shields.io/github/stars/mrexodia/ida-pro-mcp?style=flat)
- [HexStrike AI](https://github.com/0x4m4/hexstrike-ai) - Advanced MCP server running 150+ cybersecurity tools for automated pentesting, vulnerability discovery, and security research. ![GitHub Repo stars](https://img.shields.io/github/stars/0x4m4/hexstrike-ai?style=flat)

### System and Desktop

- [DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) - MCP server for Claude that provides terminal control, file system search, and diff-based file editing. ![GitHub Repo stars](https://img.shields.io/github/stars/wonderwhy-er/DesktopCommanderMCP?style=flat)
- [Windows MCP](https://github.com/CursorTouch/Windows-MCP) - MCP server for computer use on Windows. Control GUI applications, take screenshots, and automate desktop workflows. ![GitHub Repo stars](https://img.shields.io/github/stars/CursorTouch/Windows-MCP?style=flat)
- [Peekaboo](https://github.com/openclaw/Peekaboo) - macOS CLI and MCP server that enables AI agents to capture screenshots with optional visual Q&A through local or remote AI models. ![GitHub Repo stars](https://img.shields.io/github/stars/openclaw/Peekaboo?style=flat)
- [Context Mode](https://github.com/mksglu/context-mode) - Context window optimization for AI coding agents. Sandboxes tool output for 98% reduction in token usage across 12 platforms. ![GitHub Repo stars](https://img.shields.io/github/stars/mksglu/context-mode?style=flat)
- [PAL MCP Server](https://github.com/BeehiveInnovations/pal-mcp-server) - Use Claude Code, Gemini CLI, or Codex CLI with any LLM provider (OpenAI, OpenRouter, Azure, Grok, Ollama, etc.). ![GitHub Repo stars](https://img.shields.io/github/stars/BeehiveInnovations/pal-mcp-server?style=flat)
- [Agent Sandbox](https://github.com/agent-infra/sandbox) - All-in-one sandbox for AI agents combining browser, shell, file, MCP, and VS Code server in a single container. ![GitHub Repo stars](https://img.shields.io/github/stars/agent-infra/sandbox?style=flat)

## MCP Clients

These applications natively support MCP as a client, letting you connect MCP servers to your AI workflow:

- [Claude Desktop](https://claude.ai/download) - Anthropic's desktop application for Claude, with native MCP support.
- [Claude Code](https://docs.anthropic.com/en/docs/agents-and-tools/claude-code) - Anthropic's CLI for agentic coding with built-in MCP client.
- [Cline](https://github.com/cline/cline) - Autonomous coding agent in your IDE with MCP client support. ![GitHub Repo stars](https://img.shields.io/github/stars/cline/cline?style=flat)
- [Continue](https://github.com/continuedev/continue) - Open-source AI code assistant with MCP support. Works in VS Code and JetBrains. ![GitHub Repo stars](https://img.shields.io/github/stars/continuedev/continue?style=flat)
- [Cursor](https://cursor.com/) - AI-powered code editor with built-in MCP client support.
- [Windsurf](https://windsurf.com/) - AI-powered IDE with MCP integration.
- [5ire](https://github.com/nanbingxyz/5ire) - Cross-platform desktop AI assistant and MCP client compatible with major LLM providers. ![GitHub Repo stars](https://img.shields.io/github/stars/nanbingxyz/5ire?style=flat)
- [Osaurus](https://github.com/osaurus-ai/osaurus) - Native macOS AI agent harness supporting any model, persistent memory, and autonomous execution via MCP. ![GitHub Repo stars](https://img.shields.io/github/stars/osaurus-ai/osaurus?style=flat)
- [OpenSumi](https://github.com/opensumi/core) - Framework for building AI-native IDE products with MCP client support. ![GitHub Repo stars](https://img.shields.io/github/stars/opensumi/core?style=flat)
- [Gemini CLI](https://github.com/google-gemini/gemini-cli) - Google's open-source AI agent for the terminal with MCP server support. ![GitHub Repo stars](https://img.shields.io/github/stars/google-gemini/gemini-cli?style=flat)
- [Goose](https://github.com/aaif-goose/goose) - Open-source, extensible AI agent whose extension system is built natively on MCP. ![GitHub Repo stars](https://img.shields.io/github/stars/aaif-goose/goose?style=flat)
- [LibreChat](https://github.com/danny-avila/LibreChat) - Self-hosted ChatGPT-style interface with agents and MCP server support across major model providers. ![GitHub Repo stars](https://img.shields.io/github/stars/danny-avila/LibreChat?style=flat)

## Testing and Debugging

- [MCP Inspector](https://github.com/modelcontextprotocol/inspector) - Official visual testing tool for MCP servers. Debug connections, test tools, and validate server responses interactively. ![GitHub Repo stars](https://img.shields.io/github/stars/modelcontextprotocol/inspector?style=flat)
- [MCP Feedback Enhanced](https://github.com/Minidoracat/mcp-feedback-enhanced) - Enhanced MCP server for interactive user feedback and command execution, with dual interface support (Web UI and Desktop Application). ![GitHub Repo stars](https://img.shields.io/github/stars/Minidoracat/mcp-feedback-enhanced?style=flat)

## Registries and Directories

- [MCP Registry](https://github.com/modelcontextprotocol/registry) - The official community-driven registry for discovering MCP servers. ![GitHub Repo stars](https://img.shields.io/github/stars/modelcontextprotocol/registry?style=flat)
- [Cursor Community Plugins](https://github.com/cursor/community-plugins) - Community directory of plugins, rules, and MCP servers for Cursor (formerly leerob/directories). ![GitHub Repo stars](https://img.shields.io/github/stars/cursor/community-plugins?style=flat)
- [Smithery](https://smithery.ai/) - A hosted registry and marketplace for MCP servers.
- [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers) - The largest community-maintained collection of MCP servers. ![GitHub Repo stars](https://img.shields.io/github/stars/punkpeye/awesome-mcp-servers?style=flat)
- [Official Claude Plugins](https://github.com/anthropics/claude-plugins-official) - Anthropic-managed directory of Claude Code plugins, many of which bundle MCP servers. ![GitHub Repo stars](https://img.shields.io/github/stars/anthropics/claude-plugins-official?style=flat)

## Learning Resources

- [MCP for Beginners](https://github.com/microsoft/mcp-for-beginners) - Microsoft's open-source curriculum covering MCP fundamentals through real-world, cross-language examples in .NET, Java, TypeScript, JavaScript, Rust, and Python. ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/mcp-for-beginners?style=flat)
- [MCP Specification](https://spec.modelcontextprotocol.io/) - The full protocol specification covering transports, capabilities, and message formats.
- [Building MCP with LLMs](https://modelcontextprotocol.io/tutorials/building-mcp-with-llms) - Official tutorial on using LLMs to help build MCP servers.
- [MCP Quickstart Guide](https://modelcontextprotocol.io/quickstart) - Get started building your first MCP server in under 15 minutes.

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
