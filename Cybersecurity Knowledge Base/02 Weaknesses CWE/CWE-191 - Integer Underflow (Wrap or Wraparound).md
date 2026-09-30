---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-191"
status: "Draft"
---
# CWE-191: Integer Underflow (Wrap or Wraparound)

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** C, C++, Java, C#

## Description

The product subtracts one value from another, such that the result is less than the minimum allowable integer value, which produces a value that is not equal to the correct result.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-682 (ChildOf)
- CWE-682 (ChildOf)

## Source

- [CWE-191 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/191.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
