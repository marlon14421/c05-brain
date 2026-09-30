---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-585"
status: "Draft"
---
# CWE-585: Empty Synchronized Block

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

The product contains an empty synchronized block.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** When you come across an empty synchronized statement, or a synchronized statement in which the code has been commented out, try to determine what the original intentions were and whether or not the synchronized block is still necessary.

## Related weaknesses

- CWE-1071 (ChildOf)

## Source

- [CWE-585 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/585.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
