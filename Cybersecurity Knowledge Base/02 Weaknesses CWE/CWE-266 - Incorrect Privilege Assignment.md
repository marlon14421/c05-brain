---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-266"
status: "Draft"
---
# CWE-266: Incorrect Privilege Assignment

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

A product incorrectly assigns a privilege to a particular actor, creating an unintended sphere of control for that actor.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Very carefully manage the setting, management, and handling of privileges. Explicitly manage trust zones in the software.
- **Architecture and Design:** Run your code using the lowest privileges that are required to accomplish the necessary tasks [REF-76]. If possible, create isolated accounts with limited privileges that are only used for a single task. That way, a successful attack will not immediately give the attacker access to the rest of the software or its environment. For example, database applications rarely need to run as the database administrator, especially in day-to-day operations.

## Related weaknesses

- CWE-269 (ChildOf)
- CWE-286 (CanAlsoBe)

## Source

- [CWE-266 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/266.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
