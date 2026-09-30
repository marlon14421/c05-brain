---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-283"
status: "Draft"
---
# CWE-283: Unverified Ownership

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product does not properly verify that a critical resource is owned by the proper entity.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Very carefully manage the setting, management, and handling of privileges. Explicitly manage trust zones in the software.
- **Architecture and Design:** Consider following the principle of separation of privilege. Require multiple conditions to be met before permitting access to a system resource.

## Related weaknesses

- CWE-282 (ChildOf)

## Source

- [CWE-283 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/283.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
