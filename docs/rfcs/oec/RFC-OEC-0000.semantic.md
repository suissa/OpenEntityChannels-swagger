# RFC-OEC-0000 — OpenEntity Channels Core Architecture

Status: Draft
Category: Semantic
Version: 0.1.0

## Purpose
Define OEC as a transport-neutral contract for exposing the same Entity semantics over REST, WebSocket, gRPC, MCP, and future bindings.

## Normative Requirements
- Entity identity MUST be transport-independent.
- Channel bindings MUST NOT redefine Entity meaning.
- Each operation SHOULD resolve to a Behavior or explicit Entity operation.
- Defaults MAY be overridden at channel or operation scope.
- Generated documentation and tests MUST be derived from the canonical OEC contract.

## Invariants
1. Same Entity id means same logical Entity across every channel.
2. Same Behavior identifier means same semantic action across every channel.
3. Transport details are bindings, not domain semantics.
4. Documentation artifacts are derived views, not sources of truth.
