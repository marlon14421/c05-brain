---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1291"
status: "Draft"
---
# CWE-1291: Public Key Re-Use for Signing both Debug and Production Code

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

The same public key is used for signing both debug and production code.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Use different keys for Production and Debug.

## Related weaknesses

- CWE-693 (ChildOf)
- CWE-321 (PeerOf)

## Source

- [CWE-1291 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1291.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
