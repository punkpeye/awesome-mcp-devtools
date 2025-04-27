# Awesome MCP DevTools [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

[![Discord](https://img.shields.io/discord/1312302100125843476?logo=discord&label=discord)](https://glama.ai/mcp/discord)
[![Subreddit subscribers](https://img.shields.io/reddit/subreddit-subscribers/mcp?style=flat&logo=reddit&label=subreddit)](https://www.reddit.com/r/mcp/)

A curated list of developer tools, SDKs, libraries, utilities, and resources for working with **Model Context Protocol (MCP)** servers.

## Contents

- [SDKs](#sdks)
- [Libraries](#libraries)
- [Frameworks](#frameworks)
- [Testing Tools](#testing-tools)
- [Build Tools](#build-tools)
- [Utilities](#utilities)
- [Hosting](#hosting)
- [Resources](#resources)
- [Tutorials](#tutorials)

---

## Community

* [r/mcp Reddit](https://www.reddit.com/r/mcp)
* [Discord Server](https://glama.ai/mcp/discord)

## Legend

* programming language
  * #️⃣ - C# Codebase
  * 〽️ – Scala codebase
  * ☕ - Java codebase
  * 🏎️ – Go codebase
  * 🐍 – Python codebase
  * 📇 – TypeScript codebase
  * 🔶 - Kotlin codebase
  * 🦀 – Rust codebase

## SDKs

> Software Development Kits for MCP server development.

<details><summary>How are SDKs ordered?</summary>

SDKs are ordered by their popularity as determined by GitHub stars.

If an SDK is part of a monorepo, it should have a name in the form of `github-owner/github-repo#project-name`.

If an SDK is part of a monorepo, its popularity is counted as 0 stars.
</details>

### JavaScript/TypeScript

- [FastMCP](https://github.com/punkpeye/fastmcp) 📇 - A high-level framework for building MCP servers in TypeScript
- [QuantGeekDev/mcp-framework](https://github.com/QuantGeekDev/mcp-framework) 📇 - Fast and elegant TypeScript framework for building MCP servers
- [wong2/LiteMCP](https://github.com/wong2/litemcp) 📇 - A high-level framework for building MCP servers in JavaScript/TypeScript
- [ribeirogab/simple-mcp](https://github.com/ribeirogab/simple-mcp) 📇 - A simple TypeScript library for creating MCP servers
- [firebase/genkit#mcp](https://github.com/firebase/genkit/tree/main/js/plugins/mcp) 📇 – Provides integration between [Genkit](https://github.com/firebase/genkit/tree/main) and the Model Context Protocol (MCP)

### Python

- [FastMCP](https://github.com/jlowin/fastmcp) 🐍 - A high-level framework for building MCP servers in Python
- [langchain-mcp](https://github.com/rectalogic/langchain-mcp) 🐍 - Provides MCP tool calling support in LangChain

### Java

- [quarkus-mcp-server](https://github.com/quarkiverse/quarkus-mcp-server) ☕ - Java SDK for building MCP servers using Quarkus
- [spring-ai-mcp](https://github.com/spring-projects-experimental/spring-ai-mcp) ☕ - Java SDK and Spring Framework integration for building MCP client and MCP servers

### Go

- [strowk/foxy-contexts](https://github.com/strowk/foxy-contexts) 🏎️ - Golang library to write MCP Servers declaratively with functional testing included
- [mark3labs/mcp-go](https://github.com/mark3labs/mcp-go) 🏎️ - Golang SDK for building MCP Servers and Clients
- [metoro-io/mcp-golang](https://github.com/metoro-io/mcp-golang) 🏎️ - Golang framework for building MCP Servers, focussed on type safety

### Rust

- [linux-china/mcp-rs-template](https://github.com/linux-china/mcp-rs-template) 🦀 - MCP CLI server template for Rust
- [poem-web/poem#poem-mcpserver](https://github.com/poem-web/poem/tree/master/poem-mcpserver) 🦀 - MCP Server implementation for Poem

### Kotlin
- [http4k MCP SDK](https://mcp.http4k.org) 🔶 - Functional, testable Kotlin SDK based around the popular [http4k](https://http4k.org) Web toolkit

### C#/.NET
- [salty-flower/ModelContextProtocol.NET](https://github.com/salty-flower/ModelContextProtocol.NET) #️⃣ - A C# SDK for building MCP servers on .NET 9 with NativeAOT compatibility ⚡ 🔌

### Scala

- [mullerhai/sakura-mcp](https://github.com/mullerhai/sakura-mcp) 〽️ - Scala MCP Framework for Building effective agents with MCP servers and clients

## Frameworks

> High-level frameworks for working with MCP servers

- [Upsonic/gpt-computer-assistant](https://github.com/Upsonic/gpt-computer-assistant) 🐍 – Framework to build vertical AI agent
- [lastmile-ai/mcp-agent](https://github.com/lastmile-ai/mcp-agent) 🤖 🔌 - Build effective agents with MCP servers using simple, composable patterns
- [sendaifun/solana-agent-kit#agent-kit-mcp-server](https://github.com/sendaifun/solana-agent-kit/tree/main/examples/agent-kit-mcp-server) - Solana MCP SDK
- [mcpdotdirect/template-mcp-server](https://github.com/mcpdotdirect/template-mcp-server) 📇 - A CLI tool to create a new MCP server project with TypeScript support

## Libraries

> Reusable code libraries and components for MCP servers

- [marimo-team/codemirror-mcp](https://github.com/marimo-team/codemirror-mcp) 📇 - CodeMirror extension that implements MCP for resource mentions and prompt commands
- [JoshuaSiraj/mcp_auto_register](https://github.com/JoshuaSiraj/mcp_auto_register) 🐍 – Tool to automate the registration of functions and classes from a Python package into a FastMCP instance
- [isaacwasserman/mcp-langchain-ts-client](https://github.com/isaacwasserman/mcp-langchain-ts-client) 📇 – Use MCP provided tools in LangChain.js

## Utilities

> Useful tools for debugging, proxying, testing, and working with MCP servers

### Proxies and Gateways

- [punkpeye/mcp-proxy](https://github.com/punkpeye/mcp-proxy) 📇 - A TypeScript SSE proxy for MCP servers that use `stdio` transport
- [boilingdata/mcp-server-and-gw](https://github.com/boilingdata/mcp-server-and-gw) 📇 - An MCP stdio to HTTP SSE transport gateway
- [sparfenyuk/mcp-proxy](https://github.com/sparfenyuk/mcp-proxy) 🐍 – An MCP stdio to SSE transport gateway
- [TBXark/mcp-proxy](https://github.com/TBXark/mcp-proxy) 🏎️ - An MCP proxy server that aggregates multiple MCP resource servers through a single HTTP server
- [lightconetech/mcp-gateway](https://github.com/lightconetech/mcp-gateway) 📇 - A gateway demo for MCP SSE Server
- [EvalsOne/MCP-Connect](https://github.com/EvalsOne/MCP-Connect) 📇 - A tiny tool that enables cloud-based AI services to access local Stdio based MCP servers via HTTP/HTTPS
- [SecretiveShell/MCP-Bridge](https://github.com/SecretiveShell/MCP-Bridge) 🐍 – An openAI middleware proxy to use MCP in any existing openAI compatible client

### Development Tools

- [f/MCPTools](https://github.com/f/mcptools) 🏎️ - A command-line development tool for inspecting and interacting with MCP servers
- [flux159/mcp-chat](https://github.com/flux159/mcp-chat) 📇 - A CLI based client to chat and connect with any MCP server
- [mark3labs/mcphost](https://github.com/mark3labs/mcphost) 🏎️ - A CLI host application that enables LLMs to interact with external tools through MCP
- [strowk/mcp-autotest](https://github.com/strowk/mcp-autotest) 🏎️ - A command-line tool for running YAML based language-agnostic autotests
- [strowk/synf](https://github.com/strowk/synf) 🦀 - Tool to hot-reload MCP server on changes to saved files
- [strowk/mcptee](https://github.com/strowk/mcptee/) 🏎️ - Tool to proxy MCP and log inputs and outputs to YAML file
- [mclenhard/mcp-evals](https://github.com/mclenhard/mcp-evals) 🤖 - Package and Github action for running evals. 

## Hosting

> Libraries & platforms for hosting MCP servers.

- [Glama](https://glama.ai/mcp/servers) – offers hosting of open-source MCP servers, enabling developers and enterprises to easily discover build, manage MCP servers.

## Resources

> Documentation, guides, standards, and learning materials for Model Context Protocol and MCP server development.

- [Model Context Protocol Specification](https://modelcontextprotocol.io/) — Official MCP specification
- [Model Context Protocol (MCP) Quickstart](https://glama.ai/blog/2024-11-25-model-context-protocol-quickstart)

## Tutorials

* [Setup Claude Desktop App to Use a SQLite Database](https://youtu.be/wxCCzo9dGj0)

---

## Related awesome lists:

- [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers)
- [awesome-mcp-clients](https://github.com/punkpeye/awesome-mcp-clients)
