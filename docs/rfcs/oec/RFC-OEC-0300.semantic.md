# RFC-OEC-0300 — Schema References and Entity Model Resolution

Status: Draft
Category: Schema
Version: 0.1.0
Depends-On: RFC-OEC-0001

- schemaRef MUST identify the canonical Entity schema.
- idField MUST resolve to a field in that schema.
- canonicalLabel MUST resolve to a field or documented computed label.
- Generators MUST preserve schemaRef and use resolved schemas when available.
- Failure to resolve a required schemaRef MUST be reported.
