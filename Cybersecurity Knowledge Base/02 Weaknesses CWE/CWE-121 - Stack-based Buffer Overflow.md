---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-121"
status: "Draft"
---
# CWE-121: Stack-based Buffer Overflow

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Memory-Unsafe, C, C++, Not Technology-Specific

## Description

A stack-based buffer overflow condition is a condition where the buffer being overwritten is allocated on the stack (i.e., is a local variable or, rarely, a parameter to a function).

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use an abstraction library to abstract away risky APIs. Not a complete solution.
- **Implementation:** Implement and perform bounds checking on input.
- **Implementation:** Do not use dangerous functions such as gets. Use safer, equivalent functions which check for boundary errors.

## Related weaknesses

- CWE-788 (ChildOf)
- CWE-787 (ChildOf)

## Source

- [CWE-121 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/121.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
