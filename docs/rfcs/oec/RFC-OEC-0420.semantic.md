# RFC-OEC-0420 — Swagger/OpenAPI Generator Contract

Status: Draft
Category: Documentation Generation
Version: 0.1.0
Depends-On: RFC-OEC-0310

- Output MUST be valid OpenAPI 3.1.
- Shared REST paths MUST group methods under one path object.
- :param MUST become {param}.
- Missing body MUST NOT inherit a synthetic body.
- Standard OpenAPI fields MUST be preferred for HTTP semantics.
- OEC-only semantics MUST use x-oec-* extensions.
- x-oec-channels MUST describe WebSocket, gRPC, MCP, and future non-REST channels.
- Output MUST be deterministic for identical canonical input.
