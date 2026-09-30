---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-680"
status: "Draft"
---
# CWE-680: Integer Overflow to Buffer Overflow

**Abstraction:** Compound  
**Status in catalog:** Draft  
**Applicable platforms:** Memory-Unsafe, C, C++

## Description

The product performs a calculation to determine how much memory to allocate, but an integer overflow can occur that causes less memory to be allocated than expected, leading to a buffer overflow.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-190 (StartsWith)
- CWE-190 (ChildOf)

## Source

- [CWE-680 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/680.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
