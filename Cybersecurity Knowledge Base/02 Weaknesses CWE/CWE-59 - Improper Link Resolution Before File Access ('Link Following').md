---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-59"
status: "Draft"
---
# CWE-59: Improper Link Resolution Before File Access ('Link Following')

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Windows, Unix, Not Technology-Specific

## Description

The product attempts to access a file based on the filename, but it does not properly prevent that filename from identifying a link or shortcut that resolves to an unintended resource.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-706 (ChildOf)
- CWE-706 (ChildOf)

## Source

- [CWE-59 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/59.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
