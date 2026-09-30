---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-422"
status: "Draft"
---
# CWE-422: Unprotected Windows Messaging Channel ('Shatter')

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product does not properly verify the source of a message in the Windows Messaging System while running at elevated privileges, creating an alternate channel through which an attacker can directly send a message to the product.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Always verify and authenticate the source of the message.

## Related weaknesses

- CWE-420 (ChildOf)
- CWE-360 (ChildOf)

## Source

- [CWE-422 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/422.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
