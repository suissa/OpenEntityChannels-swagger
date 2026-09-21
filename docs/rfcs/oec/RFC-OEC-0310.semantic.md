# RFC-OEC-0310 — OpenAPI 3.1 and x-oec Extensions

Status: Draft
Category: Documentation Binding
Version: 0.1.0
Depends-On: RFC-OEC-0100, RFC-OEC-0110, RFC-OEC-0120, RFC-OEC-0130

- REST operations MUST use standard OpenAPI paths.
- Non-HTTP channels MUST use x-oec-* extensions until superseded by a standard binding.
- x-oec-channels MUST preserve Entity, channel type, enabled state, addressing, required metadata, operations, Behavior bindings, and schemas.
- :param MUST map to {param}.
- Operations without body MUST omit requestBody.
- SSE MUST advertise text/event-stream.
- gRPC and MCP operations MUST preserve explicit Behavior bindings.
- The generated OpenAPI document is a derived artifact, never the source of truth.
