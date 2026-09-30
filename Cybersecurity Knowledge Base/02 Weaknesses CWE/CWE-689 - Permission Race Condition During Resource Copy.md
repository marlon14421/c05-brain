---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-689"
status: "Draft"
---
# CWE-689: Permission Race Condition During Resource Copy

**Abstraction:** Compound  
**Status in catalog:** Draft  
**Applicable platforms:** C, Perl

## Description

The product, while copying or cloning a resource, does not set the resource's permissions or access control until the copy is complete, leaving the resource exposed to other spheres while the copy is taking place.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-362 (ChildOf)
- CWE-362 (Requires)
- CWE-732 (Requires)

## Source

- [CWE-689 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/689.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
