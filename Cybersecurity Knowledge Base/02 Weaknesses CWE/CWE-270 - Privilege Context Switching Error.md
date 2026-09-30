---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-270"
status: "Draft"
---
# CWE-270: Privilege Context Switching Error

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific

## Description

The product does not properly manage privileges while it is switching between different contexts that have different privileges or spheres of control.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Very carefully manage the setting, management, and handling of privileges. Explicitly manage trust zones in the software.
- **Architecture and Design:** Run your code using the lowest privileges that are required to accomplish the necessary tasks [REF-76]. If possible, create isolated accounts with limited privileges that are only used for a single task. That way, a successful attack will not immediately give the attacker access to the rest of the software or its environment. For example, database applications rarely need to run as the database administrator, especially in day-to-day operations.
- **Architecture and Design:** Consider following the principle of separation of privilege. Require multiple conditions to be met before permitting access to a system resource.

## Related weaknesses

- CWE-269 (ChildOf)

## Source

- [CWE-270 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/270.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
