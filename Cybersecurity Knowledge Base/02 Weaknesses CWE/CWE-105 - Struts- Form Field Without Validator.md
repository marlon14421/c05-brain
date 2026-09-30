---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-105"
status: "Draft"
---
# CWE-105: Struts: Form Field Without Validator

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

The product has a form field that is not validated by a corresponding validation form, which can introduce other weaknesses related to insufficient input validation.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Validate all form fields. If a field is unused, it is still important to constrain it so that it is empty or undefined.

## Related weaknesses

- CWE-1173 (ChildOf)
- CWE-20 (ChildOf)

## Source

- [CWE-105 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/105.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
