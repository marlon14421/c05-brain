---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-14"
status: "Draft"
---
# CWE-14: Compiler Removal of Code to Clear Buffers

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** C, C++, Compiled

## Description

Sensitive memory is cleared according to the source code, but compiler optimizations leave the memory untouched when it is not read from again, aka "dead store removal."

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Store the sensitive data in a "volatile" memory location if available.
- **Build and Compilation:** If possible, configure your compiler so that it does not remove dead stores.
- **Architecture and Design:** Where possible, encrypt sensitive data that are used by a software system.

## Related weaknesses

- CWE-733 (ChildOf)

## Source

- [CWE-14 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/14.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
