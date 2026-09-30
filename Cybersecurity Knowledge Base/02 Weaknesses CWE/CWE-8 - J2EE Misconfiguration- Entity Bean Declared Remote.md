---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-8"
status: "Incomplete"
---
# CWE-8: J2EE Misconfiguration: Entity Bean Declared Remote

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Java

## Description

When an application exposes a remote interface for an entity bean, it might also expose methods that get or set the bean's data. These methods could be leveraged to read sensitive information, or to change data in ways that violate the application's expectations, potentially leading to other vulnerabilities.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Declare Java beans "local" when possible. When a bean must be remotely accessible, make sure that sensitive information is not exposed, and ensure that the application logic performs appropriate validation of any data that might be modified by an attacker.

## Related weaknesses

- CWE-668 (ChildOf)

## Source

- [CWE-8 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/8.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
