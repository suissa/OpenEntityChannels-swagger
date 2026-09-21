# RFC-OEC-0410 — Generated Test Contract

Status: Draft
Category: Conformance
Version: 0.1.0
Depends-On: RFC-OEC-0400

- Every enabled channel MUST receive at least one happy-path test.
- Every mechanically derivable constraint MUST receive an invalid-path test.
- REST SHOULD cover method, concrete path matching, required metadata, body kind, validation, and stream negotiation.
- WebSocket SHOULD cover handshake/address, metadata, disabled channel, and message contract.
- gRPC SHOULD cover service/method, metadata, request schema, and stream mode.
- MCP SHOULD cover name, visibility, tool binding, metadata, and input schema.
- Security Behaviors MUST generate one negative test per declared validation predicate.
- Generated tests validate the contract; they MUST NOT redefine it.
