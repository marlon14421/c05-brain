---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-786"
status: "Incomplete"
---
# CWE-786: Access of Memory Location Before Start of Buffer

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Memory-Unsafe, C, C++

## Description

The product reads or writes to a buffer using an index or pointer that references a memory location prior to the beginning of the buffer.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-119 (ChildOf)
- CWE-119 (ChildOf)
- CWE-119 (ChildOf)

## Source

- [CWE-786 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/786.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
