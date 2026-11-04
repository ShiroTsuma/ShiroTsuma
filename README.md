# Tomasz Góralski

I build self-hosted applications, developer tools, and game tooling. My projects span .NET services, React interfaces, native instrumentation, and integrations for local AI assistants.

## Selected projects

### [Voice-MCP](https://github.com/ShiroTsuma/Voice-MCP)

A local MCP server that gives Claude Code and Codex a voice on Windows. Agents announce finished turns and questions aloud, each session as its own character, and you answer by dictation that reaches the agent you name. Speech synthesis and recognition run offline on the CPU through sherpa-onnx, with voice cloning from a short recording. A single Go binary that installs itself.

### [Tsundoku](https://github.com/ShiroTsuma/Tsundoku)

A self-hosted library for web novels, light novels, manga, and manhwa. Tracks reading progress, imports book metadata, manages EPUB collections, and supports private libraries with selective sharing. Built with ASP.NET Core, React, TypeScript, and PostgreSQL, with OpenTelemetry observability and local or S3-compatible storage.

### [Isaac Doctor](https://github.com/ShiroTsuma/Isaac-Doctor)

A local performance profiler for The Binding of Isaac: Repentance+ with REPENTOGON. Native instrumentation records callback timings and frame context; a TypeScript viewer provides timeline analysis, source inspection, and recording comparisons. Available as a portable Windows release, with a separate headless analysis workflow.

### [AMP-MCP](https://github.com/ShiroTsuma/AMP-MCP)

A Go MCP server connecting AI assistants to CubeCoders AMP. Supports game-server operations, configuration, console access, files, and scoped account roles. Distributed as a Windows executable with credentials encrypted through Windows DPAPI.

### [Gachabot](https://github.com/ShiroTsuma/Gachabot)

A self-hosted Discord bot and dashboard for game announcements and event reminders. Each guild controls its channels, games, subjects, and reminder schedule. The .NET service stores publication state in PostgreSQL, archives media in S3-compatible storage, and handles deduplication and delivery retries.

## Technologies

C# / .NET · TypeScript / React · Go · C++ · PostgreSQL · Docker · OpenTelemetry
