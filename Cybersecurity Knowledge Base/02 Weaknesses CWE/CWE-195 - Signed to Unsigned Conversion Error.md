---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-195"
status: "Draft"
---
# CWE-195: Signed to Unsigned Conversion Error

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** C, C++

## Description

The product uses a signed primitive and performs a cast to an unsigned primitive, which can produce an unexpected value if the value of the signed primitive can not be represented using an unsigned primitive.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-681 (ChildOf)
- CWE-681 (ChildOf)
- CWE-681 (ChildOf)
- CWE-119 (CanPrecede)

## Source

- [CWE-195 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/195.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
