---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-123"
status: "Draft"
---
# CWE-123: Write-what-where Condition

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Memory-Unsafe, C, C++

## Description

Any condition where the attacker has the ability to write an arbitrary value to an arbitrary location, often as the result of a buffer overflow.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use a language that provides appropriate memory abstractions.
- **Operation:** Use OS-level preventative functionality integrated after the fact. Not a complete solution.

## Related weaknesses

- CWE-787 (ChildOf)
- CWE-787 (ChildOf)
- CWE-119 (ChildOf)

## Source

- [CWE-123 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/123.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
