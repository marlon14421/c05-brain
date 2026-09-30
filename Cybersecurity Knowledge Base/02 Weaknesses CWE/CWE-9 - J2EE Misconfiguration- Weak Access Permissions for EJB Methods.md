---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-9"
status: "Draft"
---
# CWE-9: J2EE Misconfiguration: Weak Access Permissions for EJB Methods

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Java

## Description

If elevated access rights are assigned to EJB methods, then an attacker can take advantage of the permissions to exploit the product.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Follow the principle of least privilege when assigning access rights to EJB methods. Permission to invoke EJB methods should not be granted to the ANYONE role.

## Related weaknesses

- CWE-266 (ChildOf)

## Source

- [CWE-9 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/9.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
