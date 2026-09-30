---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-90"
status: "Draft"
---
# CWE-90: Improper Neutralization of Special Elements used in an LDAP Query ('LDAP Injection')

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Database Server

## Description

The product constructs all or part of an LDAP query using externally-influenced input from an upstream component, but it does not neutralize or incorrectly neutralizes special elements that could modify the intended LDAP query when it is sent to a downstream component.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-943 (ChildOf)

## Source

- [CWE-90 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/90.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
