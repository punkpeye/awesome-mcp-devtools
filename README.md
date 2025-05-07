# Awesome MCP DevTools [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

[![Discord](https://img.shields.io/discord/1312302100125843476?logo=discord&label=discord)](https://glama.ai/mcp/discord)
[![Subreddit subscribers](https://img.shields.io/reddit/subreddit-subscribers/mcp?style=flat&logo=reddit&label=subreddit)](https://www.reddit.com/r/mcp/)

A curated list of developer tools, SDKs, libraries, utilities, and resources for working with **Model Context Protocol (MCP)** servers.

## Contents

* [Contents](#contents)
* [Community](#community)
* [Legend](#legend)
* [SDKs](#sdks)
  * [JavaScript/TypeScript](#javascripttypescript)
  * [Python](#python)
  * [Java](#java)
  * [Go](#go)
  * [Rust](#rust)
  * [Kotlin](#kotlin)
  * [C#/.NET](#cnet)
  * [Scala](#scala)
  * [Dart](#dart)
* [Frameworks](#frameworks)
* [Testing Tools](#testing-tools)
* [Libraries](#libraries)
* [Utilities](#utilities)
  * [Proxies and Gateways](#proxies-and-gateways)
  * [Development Tools](#development-tools)
* [Hosting](#hosting)
* [Templates](#templates)
* [Resources](#resources)
* [Tutorials](#tutorials)
* [Related awesome lists:](#related-awesome-lists)

---

## Community

* [r/mcp Reddit](https://www.reddit.com/r/mcp)
* [Discord Server](https://glama.ai/mcp/discord)

## Legend

* 🎖️ official MCP resource
* programming language
  * #️⃣ - C# Codebase
  * 〽️ – Scala codebase
  * ☕ - Java codebase
  * 🏎️ – Go codebase
  * 🐍 – Python codebase
  * 📇 – TypeScript codebase
  * 🔶 - Kotlin codebase
  * 🦀 – Rust codebase
  * 🎯 - Dart codebase

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
- [easymcp](https://github.com/promptmesh/easymcp) 🐍 - A high level asyncio native client SDK with native support for namespaced servers and caching.
- [mcp-use]() 🐍 - Open source python library to very easily connect any LLM to any MCP server both locally and remotely.

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

### Dart

- [leehack/mcp_dart](https://github.com/leehack/mcp_dart/) 🎯 - This library aims to provide a simple and intuitive way to implement MCP servers and clients in Dart 

## Frameworks

> High-level frameworks for working with MCP servers

- [lastmile-ai/mcp-agent](https://github.com/lastmile-ai/mcp-agent) 🤖 🔌 - Build effective agents with MCP servers using simple, composable patterns
- [mcpdotdirect/template-mcp-server](https://github.com/mcpdotdirect/template-mcp-server) 📇 - A CLI tool to create a new MCP server project with TypeScript support
- [sendaifun/solana-agent-kit#agent-kit-mcp-server](https://github.com/sendaifun/solana-agent-kit/tree/main/examples/agent-kit-mcp-server) - Solana MCP SDK
- [stephencme/create-mcp-ts](https://github.com/stephencme/create-mcp-ts) 📇 - Create a new MCP server in TypeScript, batteries included - supports user-defined templates!
- [Upsonic/gpt-computer-assistant](https://github.com/Upsonic/gpt-computer-assistant) 🐍 – Framework to build vertical AI agent
- [p-funk/FEGIS](https://github.com/p-funk/FEGIS) 🐍 - Create interactive agents that transform simple ad-hoc prompting into augmented LLM interaction.

## Testing Tools 
> Tools for testing MCP servers and clients 

- [modelcontextprotocol/inspector](https://github.com/modelcontextprotocol/inspector) 📇 🎖️ - UI for testing MCP servers.
- [wong2/mcp-cli](https://github.com/wong2/mcp-cli) 🤖 - Command line inspector for manual testing
- [mclenhard/mcp-evals](https://github.com/mclenhard/mcp-evals) 🤖 - Package and Github action for running evals. 

## Libraries

> Reusable code libraries and components for MCP servers

- [marimo-team/codemirror-mcp](https://github.com/marimo-team/codemirror-mcp) 📇 - CodeMirror extension that implements MCP for resource mentions and prompt commands
- [jhgaylor/express-mcp-handlder](https://github.com/jhgaylor/express-mcp-handler) 📇 - Bind an MCP server to an express server using the StreamableHTTP Transport
- [JoshuaSiraj/mcp_auto_register](https://github.com/JoshuaSiraj/mcp_auto_register) 🐍 – Tool to automate the registration of functions and classes from a Python package into a FastMCP instance
- [isaacwasserman/mcp-langchain-ts-client](https://github.com/isaacwasserman/mcp-langchain-ts-client) 📇 – Use MCP provided tools in LangChain.js

## Utilities

> Useful tools for debugging, proxying, testing, and working with MCP servers

### Proxies and Gateways

- [adiom-data/grpcmcp](https://github.com/adiom-data/grpcmcp) 🏎️ - A MCP Server that allows access to gRPC API services.
- [boilingdata/mcp-server-and-gw](https://github.com/boilingdata/mcp-server-and-gw) 📇 - An MCP stdio to HTTP SSE transport gateway
- [emicklei/mcp-log-proxy](https://github.com/emicklei/mcp-log-proxy) 🏎️ - An MCP proxy server that offers a Web UI to see the complete message flow.
- [EvalsOne/MCP-Connect](https://github.com/EvalsOne/MCP-Connect) 📇 - A tiny tool that enables cloud-based AI services to access local Stdio based MCP servers via HTTP/HTTPS
- [hamidra/yamcp](https://github.com/hamidra/yamcp) 📇 - An MCP workspace manager to bundle and manage MCP servers in dedicated local workspaces (e.g., for coding, design, research).
- [lightconetech/mcp-gateway](https://github.com/lightconetech/mcp-gateway) 📇 - A gateway demo for MCP SSE Server
- [multi-mcp](https://github.com/kfirtoledo/multi-mcp) 🐍 - A flexible and dynamic Multi-MCP Proxy Server that acts as a single MCP server while connecting to and routing between multiple backend MCP servers over STDIO or SSE. Deployable on Kubernetes by exposing a single port, and supports dynamic addition and removal of MCP servers at runtime.
- [punkpeye/mcp-proxy](https://github.com/punkpeye/mcp-proxy) 📇 - A TypeScript SSE proxy for MCP servers that use `stdio` transport
- [SecretiveShell/MCP-Bridge](https://github.com/SecretiveShell/MCP-Bridge) 🐍 – An openAI middleware proxy to use MCP in any existing openAI compatible client
- [sparfenyuk/mcp-proxy](https://github.com/sparfenyuk/mcp-proxy) 🐍 – An MCP stdio to SSE transport gateway
- [TBXark/mcp-proxy](https://github.com/TBXark/mcp-proxy) 🏎️ - An MCP proxy server that aggregates multiple MCP resource servers through a single HTTP server

### Development Tools

- [f/MCPTools](https://github.com/f/mcptools) 🏎️ - A command-line development tool for inspecting and interacting with MCP servers
- [flux159/mcp-chat](https://github.com/flux159/mcp-chat) 📇 - A CLI based client to chat and connect with any MCP server
- [mark3labs/mcphost](https://github.com/mark3labs/mcphost) 🏎️ - A CLI host application that enables LLMs to interact with external tools through MCP
- [strowk/mcp-autotest](https://github.com/strowk/mcp-autotest) 🏎️ - A command-line tool for running YAML based language-agnostic autotests
- [strowk/synf](https://github.com/strowk/synf) 🦀 - Tool to hot-reload MCP server on changes to saved files
- [strowk/mcptee](https://github.com/strowk/mcptee/) 🏎️ - Tool to proxy MCP and log inputs and outputs to YAML file
- [StacklokLabs/toolhive](https://github.com/StacklokLabs/toolhive) 🏎️ - A lightweight utility designed to simplify the deployment and management of MCP servers, ensuring ease of use, consistency, and security through containerization
- [addozhang/spring-rest-to-mcp](https://github.com/addozhang/spring-rest-to-mcp) 🏎️ - An [OpenRewrite](https://docs.openrewrite.org/) recipe collection that automatically converts Spring Web REST APIs to Spring AI Model Context Protocol (MCP) server tools.

## Hosting

> Libraries & platforms for hosting MCP servers.

- [Glama](https://glama.ai/mcp/servers) – offers hosting of open-source MCP servers, enabling developers and enterprises to easily discover build, manage MCP servers.
- [Smithery](https://smithery.ai/) - cloud hosting MCP servers as a service via docker containers

## Templates

> Example code ready to be made into a component of an MCP system.

- [dart-mcp-server-template](https://github.com/jhgaylor/dart-mcp-server-template) 🎯 - A template repository for creating Dart MCP servers. Provides a starting point with Docker configuration, http+stdio transport bindings, and a standard Dart project structure


## Resources

> Documentation, guides, standards, and learning materials for Model Context Protocol and MCP server development.

- [Model Context Protocol Specification](https://modelcontextprotocol.io/) — Official MCP specification
- [Model Context Protocol (MCP) Quickstart](https://glama.ai/blog/2024-11-25-model-context-protocol-quickstart)

## Tutorials

* [Setup Claude Desktop App to Use a SQLite Database](https://youtu.be/wxCCzo9dGj0)
* [amirshk/mcp-secrets-plugin](https://github.com/amirshk/mcp-secrets-plugin) 🐍 - A reference code to securely store and retrieve sensitive information using the system's native keychain

---

## Related awesome lists:

- [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers)
- [awesome-mcp-clients](https://github.com/punkpeye/awesome-mcp-clients)
