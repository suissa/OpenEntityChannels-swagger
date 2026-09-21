# RFC-OEC-0004 — Headers, Metadata, and Request Authority

Status: Draft
Category: Semantic
Version: 0.1.0
Depends-On: RFC-OEC-0000

- Protocol defaults MAY define required metadata.
- Operations MAY override required metadata.
- REST maps metadata to HTTP headers.
- WebSocket maps metadata to handshake/message metadata.
- gRPC maps metadata to gRPC metadata.
- MCP maps metadata to request context or transport metadata.
- Missing required metadata MUST fail before Behavior execution.
