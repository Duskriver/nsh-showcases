# zniff

zniff is an HTTP(S) debugging proxy that combines a Rust proxy engine and a Native Shell interface in one process. It offers a native desktop app for macOS, Windows and Linux, plus a WebAssembly console for browser-based inspection.

- Inspect HTTP/2, WebSocket and server-sent event traffic, with formatted JSON, GraphQL, Protobuf/gRPC and MessagePack bodies.
- Filter captured flows, rewrite requests and responses, and pause traffic at request or response breakpoints.
- Explore connection timing, waterfall and sequence diagrams, then export sessions or copy requests into application code.
- Connect AI clients through the built-in MCP server to inspect, annotate and replay captured flows.

The previews show GraphQL response inspection in dark mode and a light-mode session summary with paused requests.
