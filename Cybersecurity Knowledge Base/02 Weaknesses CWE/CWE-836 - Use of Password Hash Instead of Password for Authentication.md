---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-836"
status: "Incomplete"
---
# CWE-836: Use of Password Hash Instead of Password for Authentication

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product records password hashes in a data store, receives a hash of a password from a client, and compares the supplied hash to the hash obtained from the data store.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-1390 (ChildOf)
- CWE-602 (PeerOf)

## Source

- [CWE-836 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/836.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
