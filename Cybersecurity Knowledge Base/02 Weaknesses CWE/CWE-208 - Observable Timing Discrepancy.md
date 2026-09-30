---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-208"
status: "Incomplete"
---
# CWE-208: Observable Timing Discrepancy

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific

## Description

Two separate operations in a product require different amounts of time to complete, in a way that is observable to an actor and reveals security-relevant information about the state of the product, such as whether a particular operation was successful or not.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-203 (ChildOf)
- CWE-385 (CanPrecede)
- CWE-327 (CanPrecede)

## Source

- [CWE-208 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/208.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
