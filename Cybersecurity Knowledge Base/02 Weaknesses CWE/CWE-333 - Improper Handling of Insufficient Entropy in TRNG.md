---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-333"
status: "Draft"
---
# CWE-333: Improper Handling of Insufficient Entropy in TRNG

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

True random number generators (TRNG) generally have a limited source of entropy and therefore can fail or block.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Rather than failing on a lack of random numbers, it is often preferable to wait for more numbers to be created.

## Related weaknesses

- CWE-331 (ChildOf)
- CWE-755 (ChildOf)

## Source

- [CWE-333 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/333.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
