---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-271"
status: "Incomplete"
---
# CWE-271: Privilege Dropping / Lowering Errors

**Abstraction:** Class  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product does not drop privileges before passing control of a resource to an actor that does not have those privileges.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Very carefully manage the setting, management, and handling of privileges. Explicitly manage trust zones in the software.
- **Architecture and Design:** Consider following the principle of separation of privilege. Require multiple conditions to be met before permitting access to a system resource.

## Related weaknesses

- CWE-269 (ChildOf)

## Source

- [CWE-271 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/271.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
