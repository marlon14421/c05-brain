---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-498"
status: "Draft"
---
# CWE-498: Cloneable Class Containing Sensitive Information

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Object-Oriented, C++, Java, C#

## Description

The code contains a class with sensitive data, but the class is cloneable. The data can then be accessed by cloning the class.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** If you do make your classes clonable, ensure that your clone method is final and throw super.clone().

## Related weaknesses

- CWE-668 (ChildOf)
- CWE-200 (CanPrecede)

## Source

- [CWE-498 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/498.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
