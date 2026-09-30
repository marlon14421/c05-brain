---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-196"
status: "Draft"
---
# CWE-196: Unsigned to Signed Conversion Error

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** C, C++

## Description

The product uses an unsigned primitive and performs a cast to a signed primitive, which can produce an unexpected value if the value of the unsigned primitive can not be represented using a signed primitive.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Requirements:** Choose a language which is not subject to these casting flaws.
- **Architecture and Design:** Design object accessor functions to implicitly check values for valid sizes. Ensure that all functions which will be used as a size are checked previous to use as a size. If the language permits, throw exceptions rather than using in-band errors.
- **Implementation:** Error check the return values of all functions. Be aware of implicit casts made, and use unsigned variables for sizes if at all possible.

## Related weaknesses

- CWE-681 (ChildOf)
- CWE-681 (ChildOf)
- CWE-681 (ChildOf)
- CWE-124 (CanAlsoBe)
- CWE-120 (CanAlsoBe)

## Source

- [CWE-196 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/196.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
