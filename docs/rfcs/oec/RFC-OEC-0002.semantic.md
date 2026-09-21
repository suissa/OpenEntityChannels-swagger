# RFC-OEC-0002 — Payload Envelopes and Body Kinds

Status: Draft
Category: Semantic
Version: 0.1.0
Depends-On: RFC-OEC-0000

Body kinds: payloadEnvelope, entitySchema, none, stream.

- An operation without a declared body MUST be interpreted as none.
- A generator MUST NOT invent payloadEnvelope for an operation whose body is absent.
- Stream representation is independent from request body.
- Bindings MAY encode body kinds differently but MUST preserve semantics.
