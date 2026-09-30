---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-197"
status: "Incomplete"
---
# CWE-197: Numeric Truncation Error

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** C, C++, Java, C#

## Description

Truncation errors occur when a primitive is cast to a primitive of a smaller size and data is lost in the conversion.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Ensure that no casts, implicit or explicit, take place that move from a larger size primitive or a smaller size primitive.

## Related weaknesses

- CWE-681 (ChildOf)
- CWE-681 (ChildOf)
- CWE-681 (ChildOf)
- CWE-195 (CanAlsoBe)
- CWE-196 (CanAlsoBe)
- CWE-192 (CanAlsoBe)
- CWE-194 (CanAlsoBe)

## Source

- [CWE-197 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/197.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
