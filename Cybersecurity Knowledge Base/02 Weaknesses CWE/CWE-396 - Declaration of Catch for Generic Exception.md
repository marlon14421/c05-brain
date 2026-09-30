---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-396"
status: "Draft"
---
# CWE-396: Declaration of Catch for Generic Exception

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** C++, Java, C#, Python

## Description

Catching overly broad exceptions promotes complex error handling code that is more likely to contain security vulnerabilities.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

No mitigation text was provided in this record. Consult the linked CWE page and platform-specific secure development guidance.

## Related weaknesses

- CWE-705 (ChildOf)
- CWE-755 (ChildOf)
- CWE-221 (ChildOf)

## Source

- [CWE-396 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/396.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
