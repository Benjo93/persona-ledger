# Persona Ledger

**Cryptographic action log for Persona MCP server.**

## Contents

- `identity/public_key.pem` — Public key for signature verification
- `log/actions.jsonl` — Hash-chained, signed action log (append-only)
- `log/tree_head.json` — Signed Merkle tree checkpoint

## Stats

- **Total entries**: 9

## Verification

```bash
persona audit --ledger https://github.com/Benjo93/persona-ledger
```

All log entries are cryptographically signed and hash-chained for tamper evidence.

---

*Published by [Persona](https://github.com/anthropics/persona)*
