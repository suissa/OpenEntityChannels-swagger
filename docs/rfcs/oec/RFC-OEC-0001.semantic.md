# RFC-OEC-0001 — Entity Identity and Canonical Labels

Status: Draft
Category: Semantic
Version: 0.1.0
Depends-On: RFC-OEC-0000

- Every Entity MUST define an id field.
- The system identity MUST be the Entity id.
- A human-facing canonical label MAY be declared separately.
- If configured, successful Entity responses MUST return both id and canonicalLabel.
- UI clients SHOULD display canonicalLabel.
- Routing, persistence, authorization, and joins MUST use id.
