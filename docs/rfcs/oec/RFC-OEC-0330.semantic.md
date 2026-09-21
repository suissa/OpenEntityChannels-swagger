# RFC-OEC-0330 — Versioning and Compatibility

Status: Draft
Category: Governance
Version: 0.1.0
Depends-On: RFC-OEC-0000

- OEC versions MUST use semantic versioning.
- Patch versions MUST NOT introduce breaking semantics.
- Minor versions MAY add optional fields, channels, or extensions.
- Major versions MAY redefine required semantics.
- Unknown optional fields MUST be ignored unless marked critical.
- Generators SHOULD record the protocol version used for derived artifacts.
