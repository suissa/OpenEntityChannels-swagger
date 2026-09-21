# RFC-OEC-0410 — Zig 0.16 Test Generator Implementation

Status: Draft
Category: Implementation
Version: 0.1.0
Semantic-RFC: RFC-OEC-0410

## Reference Profile
- parser reads the supported OEC YAML subset
- model owns normalized protocol structures
- test writer emits Zig test blocks
- validators cover REST, WebSocket, gRPC, MCP
- CLI emits generated test source

## Zig 0.16 Requirements
- Build modules use root_module/createModule.
- ArrayList ownership MUST be explicitly released.
- Parser-owned slices MUST have one clear owner.
- DebugAllocator leak reports are failures.

## Generation Rules
- Route placeholders MUST become concrete fixture values in happy-path tests.
- Missing body means .none.
- Defaults MUST be inherited deterministically.
- Validation predicates MUST map to stable Zig errors.
- Generated code SHOULD compile under zig build test in CI.
