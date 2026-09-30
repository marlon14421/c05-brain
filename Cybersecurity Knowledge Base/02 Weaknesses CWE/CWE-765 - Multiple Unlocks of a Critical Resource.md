---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-765"
status: "Incomplete"
---
# CWE-765: Multiple Unlocks of a Critical Resource

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product unlocks a critical resource more times than intended, leading to an unexpected state in the system.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** When locking and unlocking a resource, try to be sure that all control paths through the code in which the resource is locked one or more times correspond to exactly as many unlocks. If the product acquires a lock and then determines it is not able to perform its intended behavior, be sure to release the lock(s) before waiting for conditions to improve. Reacquire the lock(s) before trying again.

## Related weaknesses

- CWE-667 (ChildOf)
- CWE-675 (ChildOf)

## Source

- [CWE-765 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/765.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
