# RFC-OEC-0110 — WebSocket Channel Binding

Status: Draft
Category: Channel Binding
Version: 0.1.0
Depends-On: RFC-OEC-0000, RFC-OEC-0004

- Channel MUST declare base endpoint.
- Required metadata MUST be validated before Behavior execution.
- Messages SHOULD use the canonical payload envelope unless another schema is declared.
- Message routing MUST resolve Entity, operation/Behavior, trace identity, and payload.
- Disabled channels MUST reject new sessions.
