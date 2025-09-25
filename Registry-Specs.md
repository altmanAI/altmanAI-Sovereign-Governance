# Registry Specs
**System:** Proof-of-Impact Registry • **Version:** v1.0.0 • **Date:** September 24, 2025

## Hashing
- Algorithm: SHA-256 (min)  
- Payload: Canonical JSON of document metadata + content hash

## Certificate
- Fields: id, title, author, timestamp, sha256, repository, signature (optional)

## Example
```json
{
  "id": "AFG-CONST-092425",
  "title": "Sovereign-Constitution.md",
  "author": "Blake Hunter Altman",
  "timestamp": "2025-09-25T03:34:19.596087Z",
  "sha256": "<fill-after-build>",
  "repository": "Sovereign-Governance"
}
```
