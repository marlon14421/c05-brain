---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-403"
status: "Draft"
---
# CWE-403: Exposure of File Descriptor to Unintended Control Sphere ('File Descriptor Leak')

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** C, Not Language-Specific, Unix

## Description

A process does not close sensitive file descriptors before invoking a child process, which allows the child to perform unauthorized I/O operations using those descriptors.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-402 (ChildOf)

## Source

- [CWE-403 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/403.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
