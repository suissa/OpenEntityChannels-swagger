# RFC-OEC-0320 — Error Envelope and Failure Semantics

Status: Draft
Category: Semantic
Version: 0.1.0
Depends-On: RFC-OEC-0000

Canonical failures include MissingRequiredMetadata, MethodMismatch, PathMismatch, InvalidBody, MissingRequiredField, UnexpectedField, ValidationFailed, ChannelDisabled, ServiceMismatch, NameMismatch, VisibilityMismatch, StreamNegotiationFailed, AuthenticationFailed, AuthorizationFailed, Expired, Consumed, and ReplayDetected.

Bindings MAY map these to transport-specific statuses, but MUST preserve a canonical machine-readable error identity and trace reference.
