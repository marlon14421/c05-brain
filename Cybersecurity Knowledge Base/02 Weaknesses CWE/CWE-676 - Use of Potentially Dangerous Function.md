---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-676"
status: "Draft"
---
# CWE-676: Use of Potentially Dangerous Function

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** C, C++

## Description

The product invokes a potentially dangerous function that could introduce a vulnerability if it is used incorrectly, but the function can also be used safely.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Build and Compilation:** Identify a list of prohibited API functions and prohibit developers from using these functions, providing safer alternatives. In some cases, automatic code analysis tools or the compiler can be instructed to spot use of prohibited functions, such as the "banned.h" include file from Microsoft's SDL. [REF-554] [REF-1009] [REF-7]

## Related weaknesses

- CWE-1177 (ChildOf)

## Source

- [CWE-676 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/676.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
