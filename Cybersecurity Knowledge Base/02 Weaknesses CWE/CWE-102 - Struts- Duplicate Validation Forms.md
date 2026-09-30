---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-102"
status: "Incomplete"
---
# CWE-102: Struts: Duplicate Validation Forms

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Java

## Description

The product uses multiple validation forms with the same name, which might cause the Struts Validator to validate a form that the programmer does not expect.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** The DTD or schema validation will not catch the duplicate occurrence of the same form name. To find the issue in the implementation, manual checks or automated static analysis could be applied to the xml configuration files.

## Related weaknesses

- CWE-694 (ChildOf)
- CWE-1173 (ChildOf)
- CWE-20 (ChildOf)

## Source

- [CWE-102 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/102.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
