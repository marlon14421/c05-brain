---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1264"
status: "Incomplete"
---
# CWE-1264: Hardware Logic with Insecure De-Synchronization between Control and Data Channels

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

The hardware logic for error handling and security checks can incorrectly forward data before the security check is complete.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-821 (ChildOf)
- CWE-1037 (PeerOf)

## Source

- [CWE-1264 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1264.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
