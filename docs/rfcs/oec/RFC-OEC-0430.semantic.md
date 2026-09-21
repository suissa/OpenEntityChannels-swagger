# RFC-OEC-0430 — Canonical Fixture and Invalid-Case Generation

Status: Draft
Category: Conformance
Version: 0.1.0
Depends-On: RFC-OEC-0410

- Fixtures MUST distinguish schema-derived values from generator defaults.
- Path parameters MUST use concrete fixture values.
- Required fields MUST receive valid representative values.
- Invalid cases SHOULD be minimal mutations of valid fixtures.
- Each invalid case SHOULD violate one primary invariant.
- Sensitive values MUST be synthetic.
- Unknown validators MAY produce INCONCLUSIVE templates rather than fabricated semantics.
