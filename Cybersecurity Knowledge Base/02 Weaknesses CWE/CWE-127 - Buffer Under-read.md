---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-127"
status: "Draft"
---
# CWE-127: Buffer Under-read

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Memory-Unsafe, C, C++

## Description

The product reads from a buffer using buffer access mechanisms such as indexes or pointers that reference memory locations prior to the targeted buffer.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-125 (ChildOf)
- CWE-786 (ChildOf)

## Source

- [CWE-127 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/127.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
