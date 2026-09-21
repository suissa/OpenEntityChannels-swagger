# RFC-OEC-0220 — Entity Capability Issuance

Status: Draft
Category: Security
Version: 0.1.0
Depends-On: RFC-OEC-0001, RFC-OEC-0003

- A capability MUST bind subject, Entity/scope, authorized operations or Behaviors, expiry, and issuer.
- Cross-channel capabilities SHOULD be audience-bound.
- Capability verification MUST occur before Behavior execution.
- Capability identity MUST be transport-independent.
- Revocation semantics MUST be explicit.
