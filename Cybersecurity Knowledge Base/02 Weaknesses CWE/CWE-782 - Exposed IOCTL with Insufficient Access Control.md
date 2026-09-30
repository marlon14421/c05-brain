---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-782"
status: "Draft"
---
# CWE-782: Exposed IOCTL with Insufficient Access Control

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** C, C++, Unix, Windows

## Description

The product implements an IOCTL with functionality that should be restricted, but it does not properly enforce access control for the IOCTL.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** In Windows environments, use proper access control for the associated device or device namespace. See References.

## Related weaknesses

- CWE-749 (ChildOf)
- CWE-781 (CanPrecede)

## Source

- [CWE-782 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/782.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
