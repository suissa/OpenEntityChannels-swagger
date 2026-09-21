# RFC-OEC-0230 — Session and DPoP Challenge Issuance

Status: Draft
Category: Security
Version: 0.1.0
Depends-On: RFC-OEC-0220

- Session issuance and DPoP challenge issuance MUST be distinct effects.
- DPoP MUST bind proof to the intended request context.
- Replay-sensitive proofs MUST carry freshness and unique request material.
- Channel bindings MAY transport session state differently while preserving semantics.
