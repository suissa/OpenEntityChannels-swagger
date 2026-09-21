# RFC-OEC-0140 — Streaming and Observation Channels

Status: Draft
Category: Semantic
Version: 0.1.0
Depends-On: RFC-OEC-0000

- Observation consumers MUST identify stream format.
- SSE and NDJSON are canonical initial serializations.
- gRPC streaming and WebSocket MAY be additional bindings.
- Stream payloads MUST preserve trace and Entity identity.
- Reconnect, replay, ordering, heartbeat, and backpressure MUST be explicit when supported.
