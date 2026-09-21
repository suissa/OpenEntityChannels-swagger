# RFC-OEC-0120 — gRPC Channel Binding

Status: Draft
Category: Channel Binding
Version: 0.1.0
Depends-On: RFC-OEC-0000, RFC-OEC-0004

- gRPC channel MUST declare a service.
- RPC methods SHOULD be explicit or deterministically derived.
- Required OEC metadata maps to gRPC metadata.
- Request and response schemas MUST preserve OEC body semantics.
- Streaming mode MUST be explicit.
- Generators MUST NOT fabricate empty Behavior bindings.
