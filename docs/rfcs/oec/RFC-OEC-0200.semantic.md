# RFC-OEC-0200 — Magic Link Authentication Behavior

Status: Draft
Category: Behavior Profile
Version: 0.1.0
Depends-On: RFC-OEC-0003, RFC-OEC-0006

## Purpose
Standardize magic-link request and consumption.

## Normative Requirements
- Request MUST declare required and allowed identity fields.
- Normalization MUST happen before validation.
- Challenge lifetime MUST be explicit.
- Token algorithm, secret reference, storage representation, and binding inputs MUST be declared.
- Consume MUST validate signature, challenge existence, expiry, consumption state, and verifier match before effects.
- Effects MAY include session, DPoP challenge, and Entity capability issuance.

## Conformance
Each declared validation predicate MUST have a negative test.
