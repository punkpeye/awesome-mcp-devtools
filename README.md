# Awesome MCP DevTools [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

A curated list of developer tools, SDKs, libraries, utilities, and resources for working with **Model Context Protocol (MCP)** servers.

---

## Contents

- [SDKs](#sdks)
- [Libraries](#libraries)
- [Frameworks](#frameworks)
- [Testing Tools](#testing-tools)
- [Build Tools](#build-tools)
- [Utilities](#utilities)
- [Resources](#resources)

---

## Legend

* programming language
  * 🐍 – Python codebase
  * 📇 – TypeScript codebase
  * 🏎️ – Go codebase
  * 🦀 – Rust codebase
  * #️⃣ - C# Codebase
  * ☕ - Java codebase

## SDKs

> Software Development Kits for MCP server development.

### JavaScript/TypeScript
- [LiteMCP](https://github.com/wong2/litemcp) 📇 - A high-level framework for building MCP servers in JavaScript/TypeScript
- [FastMCP](https://github.com/punkpeye/fastmcp) 📇 - A high-level framework for building MCP servers in TypeScript
- [Genkit MCP](https://github.com/firebase/genkit/tree/main/js/plugins/mcp) 📇 – Provides integration between [Genkit](https://github.com/firebase/genkit/tree/main) and the Model Context Protocol (MCP)
- [ribeirogab/simple-mcp](https://github.com/ribeirogab/simple-mcp) 📇 - A simple TypeScript library for creating MCP servers
- [mcp-framework](https://github.com/QuantGeekDev/mcp-framework) 📇 - Fast and elegant TypeScript framework for building MCP servers

### Python
- [FastMCP](https://github.com/jlowin/fastmcp) 🐍 - A high-level framework for building MCP servers in Python
- [rectalogic/langchain-mcp](https://github.com/rectalogic/langchain-mcp) 🐍 - Provides MCP tool calling support in LangChain

### Java
- [quarkiverse/quarkus-mcp-server](https://github.com/quarkiverse/quarkus-mcp-server) ☕ - Java SDK for building MCP servers using Quarkus
- [spring-ai-mcp](https://github.com/spring-projects-experimental/spring-ai-mcp) ☕ 🌱 - Java SDK and Spring Framework integration for building MCP client and MCP servers

### Go
- [Foxy Contexts](https://github.com/strowk/foxy-contexts) 🏎️ - Golang library to write MCP Servers declaratively with functional testing included
- [mark3labs/mcp-go](https://github.com/mark3labs/mcp-go) 🏎️ - Golang SDK for building MCP Servers and Clients
- [metoro-io/mcp-golang](https://github.com/metoro-io/mcp-golang) 🏎️ - Golang framework for building MCP Servers, focussed on type safety

### Rust
- [mcp-rs-template](https://github.com/linux-china/mcp-rs-template) 🦀 - MCP CLI server template for Rust
- [poem-web/poem-mcpserver](https://github.com/poem-web/poem/tree/master/poem-mcpserver) 🦀 - MCP Server implementation for Poem

### Kotlin
- [http4k MCP SDK](https://mcp.http4k.org) 🐍 - Functional, testable Kotlin SDK based around the popular [http4k](https://http4k.org) Web toolkit

### C#/.NET
- [salty-flower/ModelContextProtocol.NET](https://github.com/salty-flower/ModelContextProtocol.NET) #️⃣ 🏠 - A C# SDK for building MCP servers on .NET 9 with NativeAOT compatibility ⚡ 🔌

### Scala
- [mullerhai/sakura-mcp](https://github.com/mullerhai/sakura-mcp) 🦀 ☕ - Scala MCP Framework for Building effective agents with MCP servers and clients

## Frameworks

> High-level frameworks for working with MCP servers

- [Template MCP Server](https://github.com/mcpdotdirect/template-mcp-server) 📇 - A CLI tool to create a new MCP server project with TypeScript support
- [lastmile-ai/mcp-agent](https://github.com/lastmile-ai/mcp-agent) 🤖 🔌 - Build effective agents with MCP servers using simple, composable patterns
- [upsonic/gpt-computer-assistant](https://github.com/Upsonic/gpt-computer-assistant) 🐍 – Framework to build vertical AI agent
- [sendaifun/solana-mcp-kit](https://github.com/sendaifun/solana-agent-kit/tree/main/examples/agent-kit-mcp-server) - Solana MCP SDK

## Libraries

> Reusable code libraries and components for MCP servers

- [marimo-team/codemirror-mcp](https://github.com/marimo-team/codemirror-mcp) - CodeMirror extension that implements MCP for resource mentions and prompt commands
- [isaacwasserman/mcp-langchain-ts-client](https://github.com/isaacwasserman/mcp-langchain-ts-client) 📇 – Use MCP provided tools in LangChain.js
- [JoshuaSiraj/mcp_auto_register](https://github.com/JoshuaSiraj/mcp_auto_register) 🐍 – Tool to automate the registration of functions and classes from a Python package into a FastMCP instance

## Example Servers

> Example implementations of MCP servers

- [gabfr/waha-api-mcp-server](https://github.com/gabfr/waha-api-mcp-server) 📇 - An MCP server with openAPI specs for using the WhatsApp unofficial API
- [paulotaylor/voyp-mcp](https://github.com/paulotaylor/voyp-mcp) 📇 - VOYP - Voice Over Your Phone MCP Server for making calls
- [kukapay/whattimeisit-mcp](https://github.com/kukapay/whattimeisit-mcp) 🐍 ☁️ - A lightweight MCP server that tells you exactly what time it is
- [kukapay/whereami-mcp](https://github.com/kukapay/whereami-mcp) 🐍 ☁️ - A lightweight MCP server that tells you exactly where you are based on your current IP
- [kukapay/whoami-mcp](https://github.com/kukapay/whoami-mcp) 🐍 🏠 - A lightweight MCP server that tells you exactly who you are

## Utilities

> Useful tools for debugging, proxying, testing, and working with MCP servers

### Proxies and Gateways

- [mcp-proxy](https://github.com/punkpeye/mcp-proxy) 📇 - A TypeScript SSE proxy for MCP servers that use `stdio` transport
- [boilingdata/mcp-server-and-gw](https://github.com/boilingdata/mcp-server-and-gw) 📇 - An MCP stdio to HTTP SSE transport gateway
- [sparfenyuk/mcp-proxy](https://github.com/sparfenyuk/mcp-proxy) 🐍 – An MCP stdio to SSE transport gateway
- [TBXark/mcp-proxy](https://github.com/TBXark/mcp-proxy) 🏎️ - An MCP proxy server that aggregates multiple MCP resource servers through a single HTTP server
- [lightconetech/mcp-gateway](https://github.com/lightconetech/mcp-gateway) 📇 - A gateway demo for MCP SSE Server
- [MCP-Connect](https://github.com/EvalsOne/MCP-Connect) 📇 - A tiny tool that enables cloud-based AI services to access local Stdio based MCP servers via HTTP/HTTPS
- [SecretiveShell/MCP-Bridge](https://github.com/SecretiveShell/MCP-Bridge) 🐍 – An openAI middleware proxy to use MCP in any existing openAI compatible client

### Development Tools

- [f/MCPTools](https://github.com/f/mcptools) 🔨 - A command-line development tool for inspecting and interacting with MCP servers
- [flux159/mcp-chat](https://github.com/flux159/mcp-chat) 📇🖥️ - A CLI based client to chat and connect with any MCP server
- [mark3labs/mcphost](https://github.com/mark3labs/mcphost) 🏎️ - A CLI host application that enables LLMs to interact with external tools through MCP

## Resources

> Documentation, guides, standards, and learning materials for Model Context Protocol and MCP server development.

- [Model Context Protocol Specification](https://modelcontextprotocol.io/) — Official MCP specification
- [MCP Website](https://modelcontextprotocol.io/) - The official website for the Model Context Protocol

---

## Related awesome lists:

- [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers)
- [awesome-mcp-clients](https://github.com/punkpeye/awesome-mcp-clients)
