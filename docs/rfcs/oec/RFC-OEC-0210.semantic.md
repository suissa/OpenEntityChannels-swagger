# RFC-OEC-0210 — Challenge and Token Lifecycle

Status: Draft
Category: Security
Version: 0.1.0
Depends-On: RFC-OEC-0006

- Challenge identity MUST be unique.
- Expiration MUST be checked before use.
- One-time challenges MUST atomically transition active -> consumed.
- Verifier material SHOULD be stored instead of reusable plaintext token material.
- Destroyed or expired state MUST NOT become valid again.
- Concurrent consumption SHOULD prove at-most-once success.
