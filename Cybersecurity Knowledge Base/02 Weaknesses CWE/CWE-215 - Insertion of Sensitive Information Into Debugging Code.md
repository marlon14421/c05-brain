---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-215"
status: "Draft"
---
# CWE-215: Insertion of Sensitive Information Into Debugging Code

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product inserts sensitive information into debugging code, which could expose this information if the debugging code is not disabled in production.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Do not leave debug statements that could be executed in the source code. Ensure that all debug information is eradicated before releasing the software.

## Related weaknesses

- CWE-200 (ChildOf)

## Source

- [CWE-215 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/215.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
