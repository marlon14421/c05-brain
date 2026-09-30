---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-362"
status: "Draft"
---
# CWE-362: Concurrent Execution using Shared Resource with Improper Synchronization ('Race Condition')

**Abstraction:** Class  
**Status in catalog:** Draft  
**Applicable platforms:** C, C++, Java, Mobile, ICS/OT

## Description

The product contains a concurrent code sequence that requires temporary, exclusive access to a shared resource, but a timing window exists in which the shared resource can be modified by another code sequence operating concurrently.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** In languages that support it, use synchronization primitives. Only wrap these around critical code to minimize the impact on performance.
- **Architecture and Design:** Use thread-safe capabilities such as the data access abstraction in Spring.
- **Implementation:** When using multithreading and operating on shared variables, only use thread-safe functions.
- **Implementation:** Use atomic operations on shared variables. Be wary of innocent-looking constructs such as "x++". This may appear atomic at the code layer, but it is actually non-atomic at the instruction layer, since it involves a read, followed by a computation, followed by a write.
- **Implementation:** Use a mutex if available, but be sure to avoid related weaknesses such as CWE-412.
- **Implementation:** Avoid double-checked locking (CWE-609) and other implementation errors that arise when trying to avoid the overhead of synchronization.
- **Implementation:** Disable interrupts or signals over critical parts of the code, but also make sure that the code does not go into a large or infinite loop.
- **Implementation:** Use the volatile type modifier for critical variables to avoid unexpected compiler optimization or reordering. This does not necessarily solve the synchronization problem, but it can help.
- **Architecture and Design:** Run your code using the lowest privileges that are required to accomplish the necessary tasks [REF-76]. If possible, create isolated accounts with limited privileges that are only used for a single task. That way, a successful attack will not immediately give the attacker access to the rest of the software or its environment. For example, database applications rarely need to run as the database administrator, especially in day-to-day operations.

## Related weaknesses

- CWE-662 (ChildOf)
- CWE-416 (CanPrecede)
- CWE-476 (CanPrecede)

## Source

- [CWE-362 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/362.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
