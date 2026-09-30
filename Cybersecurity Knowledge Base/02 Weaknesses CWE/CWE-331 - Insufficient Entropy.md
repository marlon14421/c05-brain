---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-331"
status: "Draft"
---
# CWE-331: Insufficient Entropy

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product uses an algorithm or scheme that produces insufficient entropy, leaving patterns or clusters of values that are more likely to occur than others.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Determine the necessary entropy to adequately provide for randomness and predictability. This can be achieved by increasing the number of bits of objects such as keys and seeds.

## Related weaknesses

- CWE-330 (ChildOf)
- CWE-330 (ChildOf)

## Source

- [CWE-331 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/331.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
