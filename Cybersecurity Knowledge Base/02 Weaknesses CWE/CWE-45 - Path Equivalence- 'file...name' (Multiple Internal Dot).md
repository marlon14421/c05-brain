---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-45"
status: "Incomplete"
---
# CWE-45: Path Equivalence: 'file...name' (Multiple Internal Dot)

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product accepts path input in the form of multiple internal dot ('file...dir') without appropriate validation, which can lead to ambiguous path resolution and allow an attacker to traverse the file system to unintended locations or access arbitrary files.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-44 (ChildOf)
- CWE-165 (ChildOf)

## Source

- [CWE-45 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/45.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
