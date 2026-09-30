---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1325"
status: "Incomplete"
---
# CWE-1325: Improperly Controlled Sequential Memory Allocation

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** C, C++, Not Language-Specific

## Description

The product manages a group of objects or resources and performs a separate memory allocation for each object, but it does not properly limit the total amount of memory that is consumed by all of the combined objects.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Ensure multiple allocations of the same kind of object are properly tracked - possibly across multiple sessions, requests, or messages. Define an appropriate strategy for handling requests that exceed the limit, and consider supporting a configuration option so that the administrator can extend the amount of memory to be used if necessary.
- **Operation:** Run the program using system-provided resource limits for memory. This might still cause the program to crash or exit, but the impact to the rest of the system will be minimized.

## Related weaknesses

- CWE-770 (ChildOf)
- CWE-789 (PeerOf)
- CWE-476 (CanPrecede)

## Source

- [CWE-1325 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1325.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
