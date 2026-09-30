---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1260"
status: "Stable"
---
# CWE-1260: Improper Handling of Overlap Between Protected Memory Ranges

**Abstraction:** Base  
**Status in catalog:** Stable  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Memory Hardware, Processor Hardware

## Description

The product allows address regions to overlap, which can result in the bypassing of intended memory protection.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-284 (ChildOf)
- CWE-119 (CanPrecede)

## Source

- [CWE-1260 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1260.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
