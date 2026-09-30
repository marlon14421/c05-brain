---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-537"
status: "Incomplete"
---
# CWE-537: Java Runtime Error Message Containing Sensitive Information

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Java

## Description

In many cases, an attacker can leverage the conditions that cause unhandled exception errors in order to gain unauthorized access to the system.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Do not expose sensitive error information to the user.

## Related weaknesses

- CWE-211 (ChildOf)

## Source

- [CWE-537 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/537.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
