---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-104"
status: "Draft"
---
# CWE-104: Struts: Form Bean Does Not Extend Validation Class

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

If a form bean does not extend an ActionForm subclass of the Validator framework, it can expose the application to other weaknesses related to insufficient input validation.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Ensure that all forms extend one of the Validation Classes.

## Related weaknesses

- CWE-573 (ChildOf)
- CWE-20 (ChildOf)

## Source

- [CWE-104 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/104.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
