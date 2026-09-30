---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-272"
status: "Incomplete"
---
# CWE-272: Least Privilege Violation

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The elevated privilege level required to perform operations such as chroot() should be dropped immediately after the operation is performed.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Very carefully manage the setting, management, and handling of privileges. Explicitly manage trust zones in the software.
- **Architecture and Design:** Follow the principle of least privilege when assigning access rights to entities in a software system.

## Related weaknesses

- CWE-271 (ChildOf)

## Source

- [CWE-272 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/272.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
