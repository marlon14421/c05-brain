---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-833"
status: "Incomplete"
---
# CWE-833: Deadlock

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific

## Description

The product contains multiple threads or executable segments that are waiting for each other to release a necessary lock, resulting in deadlock.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-667 (ChildOf)
- CWE-662 (ChildOf)

## Source

- [CWE-833 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/833.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
