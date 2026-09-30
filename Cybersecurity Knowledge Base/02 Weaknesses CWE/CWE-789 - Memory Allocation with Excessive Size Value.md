---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-789"
status: "Draft"
---
# CWE-789: Memory Allocation with Excessive Size Value

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** C, C++, Not Language-Specific

## Description

The product allocates memory based on an untrusted, large size value, but it does not ensure that the size is within expected limits, allowing arbitrary amounts of memory to be allocated.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Perform adequate input validation against any value that influences the amount of memory that is allocated. Define an appropriate strategy for handling requests that exceed the limit, and consider supporting a configuration option so that the administrator can extend the amount of memory to be used if necessary.
- **Operation:** Run your program using system-provided resource limits for memory. This might still cause the program to crash or exit, but the impact to the rest of the system will be minimized.

## Related weaknesses

- CWE-770 (ChildOf)
- CWE-476 (CanPrecede)

## Source

- [CWE-789 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/789.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
