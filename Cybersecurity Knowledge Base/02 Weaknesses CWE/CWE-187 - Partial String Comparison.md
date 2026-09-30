---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-187"
status: "Incomplete"
---
# CWE-187: Partial String Comparison

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific

## Description

The product performs a comparison that only examines a portion of a factor before determining whether there is a match, such as a substring, leading to resultant weaknesses.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Testing:** Thoroughly test the comparison scheme before deploying code into production. Perform positive testing as well as negative testing.

## Related weaknesses

- CWE-1023 (ChildOf)

## Source

- [CWE-187 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/187.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
