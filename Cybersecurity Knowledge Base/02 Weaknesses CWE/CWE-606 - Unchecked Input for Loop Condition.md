---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-606"
status: "Draft"
---
# CWE-606: Unchecked Input for Loop Condition

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product does not properly check inputs that are used for loop conditions, potentially leading to a denial of service or other consequences because of excessive looping.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Do not use user-controlled data for loop conditions.
- **Implementation:** Perform input validation.

## Related weaknesses

- CWE-1284 (ChildOf)
- CWE-834 (CanPrecede)

## Source

- [CWE-606 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/606.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
