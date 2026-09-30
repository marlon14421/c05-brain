---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-364"
status: "Incomplete"
---
# CWE-364: Signal Handler Race Condition

**Abstraction:** Base  
**Status in catalog:** Incomplete  
**Applicable platforms:** C, C++

## Description

The product uses a signal handler that introduces a race condition.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Requirements:** Use a language that does not allow this weakness to occur or provides constructs that make this weakness easier to avoid.
- **Architecture and Design:** Design signal handlers to only set flags, rather than perform complex functionality. These flags can then be checked and acted upon within the main program loop.
- **Implementation:** Only use reentrant functions within signal handlers. Also, use validation to ensure that state is consistent while performing asynchronous actions that affect the state of execution.

## Related weaknesses

- CWE-362 (ChildOf)
- CWE-415 (CanPrecede)
- CWE-416 (CanPrecede)
- CWE-123 (CanPrecede)

## Source

- [CWE-364 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/364.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
