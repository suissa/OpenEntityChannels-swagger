# RFC-OEC-0006 — Lease, TTL, and Linear Auto-Destroy

Status: Draft
Category: Semantic
Version: 0.1.0
Depends-On: RFC-OEC-0000

- A lease MAY define idle TTL.
- linearAutoDestroy is a one-way lifecycle to destruction.
- destroyOnExpire MUST destroy state after expiry.
- destroyOnConsume MUST destroy state after successful one-time consumption.
- oneTimeUse resources MUST reject subsequent consumption.
- zeroizeSecrets requires best-effort removal of secret material before release.
