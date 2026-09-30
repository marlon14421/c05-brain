---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-109"
status: "Draft"
---
# CWE-109: Struts: Validator Turned Off

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

Automatic filtering via a Struts bean has been turned off, which disables the Struts Validator and custom validation logic. This exposes the application to other weaknesses related to insufficient input validation.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Ensure that an action form mapping enables validation. Set the validate field to true.

## Related weaknesses

- CWE-1173 (ChildOf)
- CWE-20 (ChildOf)

## Source

- [CWE-109 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/109.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
