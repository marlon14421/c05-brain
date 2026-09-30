---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-614"
status: "Draft"
---
# CWE-614: Sensitive Cookie in HTTPS Session Without 'Secure' Attribute

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Web Based

## Description

The Secure attribute for sensitive cookies in HTTPS sessions is not set.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Always set the secure attribute when the cookie should be sent via HTTPS only.

## Related weaknesses

- CWE-319 (ChildOf)

## Source

- [CWE-614 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/614.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
