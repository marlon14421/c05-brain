---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-279"
status: "Draft"
---
# CWE-279: Incorrect Execution-Assigned Permissions

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

While it is executing, the product sets the permissions of an object in a way that violates the intended permissions that have been specified by the user.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Very carefully manage the setting, management, and handling of privileges. Explicitly manage trust zones in the software.

## Related weaknesses

- CWE-732 (ChildOf)

## Source

- [CWE-279 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/279.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
