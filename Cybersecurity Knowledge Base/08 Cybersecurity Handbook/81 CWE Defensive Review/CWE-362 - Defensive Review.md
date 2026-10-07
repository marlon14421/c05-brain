---
tags:
  - cybersecurity
  - defensive-security
  - weakness-review
cwe: "CWE-362"
source: MITRE CWE
---
# CWE-362: Concurrent Execution using Shared Resource with Improper Synchronization ('Race Condition') — Defensive Review

## Source record

- Catalog entry: [[02 Weaknesses CWE/CWE-362 - Concurrent Execution using Shared Resource with Improper Synchronization ('Race Condition')|CWE-362 source record]]
- Abstraction: Class
- Catalog status: Draft
- Applicable platforms: C, C++, Java, Mobile, ICS/OT

## Weakness description

The product contains a concurrent code sequence that requires temporary, exclusive access to a shared resource, but a timing window exists in which the shared resource can be modified by another code sequence operating concurrently.

## Defensive review questions

- Identify the affected component, trust boundary, data or operation, and accountable owner.
- Determine whether the described condition exists in the current implementation or configuration; a CWE classification alone is not proof.
- Trace relevant inputs, states, permissions, and downstream effects to establish reachability and realistic impact.
- Review whether existing validation, authorization, isolation, monitoring, and recovery controls change the risk.
- Check adjacent code paths and supported versions for the same underlying cause.

## Catalog mitigations

- **Architecture and Design:** In languages that support it, use synchronization primitives. Only wrap these around critical code to minimize the impact on performance.
- **Architecture and Design:** Use thread-safe capabilities such as the data access abstraction in Spring.
- **Implementation:** When using multithreading and operating on shared variables, only use thread-safe functions.
- **Implementation:** Use atomic operations on shared variables. Be wary of innocent-looking constructs such as "x++". This may appear atomic at the code layer, but it is actually non-atomic at the instruction layer, since it involves a read, followed by a computation, followed by a write.
- **Implementation:** Use a mutex if available, but be sure to avoid related weaknesses such as CWE-412.
- **Implementation:** Avoid double-checked locking (CWE-609) and other implementation errors that arise when trying to avoid the overhead of synchronization.
- **Implementation:** Disable interrupts or signals over critical parts of the code, but also make sure that the code does not go into a large or infinite loop.
- **Implementation:** Use the volatile type modifier for critical variables to avoid unexpected compiler optimization or reordering. This does not necessarily solve the synchronization problem, but it can help.
- **Architecture and Design:** Run your code using the lowest privileges that are required to accomplish the necessary tasks [REF-76]. If possible, create isolated accounts with limited privileges that are only used for a single task. That way, a successful attack will not immediately give the attacker access to the rest of the software or its environment. For example, database applications rarely need to run as the database administrator, especially in day-to-day operations.

Treat catalog guidance as a starting point. Confirm that each mitigation applies to the actual platform and version, does not introduce a new weakness, and addresses the root cause rather than only suppressing a symptom.

## Safe validation plan

Review source code, configuration, build settings, and test evidence first. If behavior testing is needed, use an owned local or staging system, synthetic data, dedicated test identities, and a non-destructive test case. Define the scope and stop condition in advance. Do not test third-party or production systems without explicit written authorization, and do not collect real credentials or personal data.

For regression coverage, express the security property as an expected allow/deny, validation, isolation, or failure behavior. Include a legitimate-use case and a negative case. Record environment, version, method, expected result, actual result, and remaining uncertainty.

## Remediation and verification

Assign an owner and select a fix based on the affected implementation, platform guidance, and the source mitigation above. Verify the corrected behavior at the relevant boundary, review comparable paths, and run regression tests for legitimate workflows. Track residual risk and exception expiry if remediation is incomplete.

## Provenance

This review companion interprets the linked MITRE CWE record for defensive learning. It does not assert that a particular product is vulnerable, that the weakness is exploitable, or that a security incident has occurred. Confirm catalog version and licensing against the original source before redistribution or training use.
