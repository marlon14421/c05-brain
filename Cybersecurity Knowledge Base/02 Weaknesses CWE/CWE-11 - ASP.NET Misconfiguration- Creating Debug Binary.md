---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-11"
status: "Draft"
---
# CWE-11: ASP.NET Misconfiguration: Creating Debug Binary

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** ASP.NET

## Description

Debugging messages help attackers learn about the system and plan a form of attack.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **System Configuration:** Avoid releasing debug binaries into the production environment. Change the debug mode to false when the application is deployed into production.

## Related weaknesses

- CWE-489 (ChildOf)

## Source

- [CWE-11 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/11.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
