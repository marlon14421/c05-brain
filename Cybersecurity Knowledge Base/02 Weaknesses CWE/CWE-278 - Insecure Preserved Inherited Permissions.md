---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-278"
status: "Incomplete"
---
# CWE-278: Insecure Preserved Inherited Permissions

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

A product inherits a set of insecure permissions for an object, e.g. when copying from an archive file, without user awareness or involvement.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Very carefully manage the setting, management, and handling of privileges. Explicitly manage trust zones in the software.

## Related weaknesses

- CWE-732 (ChildOf)

## Source

- [CWE-278 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/278.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
