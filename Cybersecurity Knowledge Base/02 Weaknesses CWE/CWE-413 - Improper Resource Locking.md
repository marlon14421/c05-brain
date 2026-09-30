---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-413"
status: "Draft"
---
# CWE-413: Improper Resource Locking

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product does not lock or does not correctly lock a resource when the product must have exclusive access to the resource.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use a non-conflicting privilege scheme.
- **Architecture and Design:** Use synchronization when locking a resource.

## Related weaknesses

- CWE-667 (ChildOf)

## Source

- [CWE-413 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/413.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
