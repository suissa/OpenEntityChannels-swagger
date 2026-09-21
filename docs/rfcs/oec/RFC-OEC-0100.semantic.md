# RFC-OEC-0100 — REST Channel Binding

Status: Draft
Category: Channel Binding
Version: 0.1.0
Depends-On: RFC-OEC-0000, RFC-OEC-0002, RFC-OEC-0004

- REST channels MUST declare base path.
- Routes MUST declare method and path.
- :param MUST map to {param} in OpenAPI.
- Runtime matching MUST accept concrete path values.
- Required OEC metadata maps to HTTP headers.
- SSE MUST use text/event-stream.
- body none MUST NOT generate requestBody.
- GET SHOULD avoid body unless explicitly required by profile.
