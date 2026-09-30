---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-210"
status: "Draft"
---
# CWE-210: Self-generated Error Message Containing Sensitive Information

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product identifies an error condition and creates its own diagnostic or error messages that contain sensitive information.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Debugging information should not make its way into a production release.
- **Implementation:** Debugging information should not make its way into a production release.

## Related weaknesses

- CWE-209 (ChildOf)

## Source

- [CWE-210 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/210.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
