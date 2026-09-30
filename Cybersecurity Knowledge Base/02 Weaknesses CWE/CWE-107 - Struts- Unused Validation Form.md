---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-107"
status: "Draft"
---
# CWE-107: Struts: Unused Validation Form

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

An unused validation form indicates that validation logic is not up-to-date.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Remove the unused Validation Form from the validation.xml file.

## Related weaknesses

- CWE-1164 (ChildOf)
- CWE-20 (ChildOf)

## Source

- [CWE-107 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/107.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
