---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-663"
status: "Draft"
---
# CWE-663: Use of a Non-reentrant Function in a Concurrent Context

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, C

## Description

The product calls a non-reentrant function in a concurrent context in which a competing code sequence (e.g. thread or signal handler) may have an opportunity to call the same function or otherwise influence its state.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** Use reentrant functions if available.
- **Implementation:** Add synchronization to your non-reentrant function.
- **Implementation:** In Java, use the ReentrantLock Class.

## Related weaknesses

- CWE-662 (ChildOf)

## Source

- [CWE-663 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/663.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
