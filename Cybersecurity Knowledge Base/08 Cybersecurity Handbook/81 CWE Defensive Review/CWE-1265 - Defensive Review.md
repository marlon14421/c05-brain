---
tags:
  - cybersecurity
  - defensive-security
  - weakness-review
cwe: "CWE-1265"
source: MITRE CWE
---
# CWE-1265: Unintended Reentrant Invocation of Non-reentrant Code Via Nested Calls — Defensive Review

## Source record

- Catalog entry: [[02 Weaknesses CWE/CWE-1265 - Unintended Reentrant Invocation of Non-reentrant Code Via Nested Calls|CWE-1265 source record]]
- Abstraction: Base
- Catalog status: Draft
- Applicable platforms: Not Language-Specific, Not Technology-Specific

## Weakness description

The product invokes code that is believed to be reentrant, but the code performs a call that unintentionally produces a nested invocation of the non-reentrant code.

## Defensive review questions

- Identify the affected component, trust boundary, data or operation, and accountable owner.
- Determine whether the described condition exists in the current implementation or configuration; a CWE classification alone is not proof.
- Trace relevant inputs, states, permissions, and downstream effects to establish reachability and realistic impact.
- Review whether existing validation, authorization, isolation, monitoring, and recovery controls change the risk.
- Check adjacent code paths and supported versions for the same underlying cause.

## Catalog mitigations

- **Architecture and Design:** When architecting a system that will execute untrusted code in response to events, consider executing the untrusted event handlers asynchronously (asynchronous message passing) as opposed to executing them synchronously at the time each event fires. The untrusted code should execute at the start of the next iteration of the thread's message loop. In this way, calls into non-reentrant code are strictly serialized, so that each operation completes fully before the next operation begins. Special attention must be paid to all places where type coercion may result in script execution. Performing all needed coercions at the very beginning of an operation can help reduce the chance of operations executing at unexpected junctures.
- **Implementation:** Make sure the code (e.g., function or class) in question is reentrant by not leveraging non-local data, not modifying its own code, and not calling other non-reentrant code.

Treat catalog guidance as a starting point. Confirm that each mitigation applies to the actual platform and version, does not introduce a new weakness, and addresses the root cause rather than only suppressing a symptom.

## Safe validation plan

Review source code, configuration, build settings, and test evidence first. If behavior testing is needed, use an owned local or staging system, synthetic data, dedicated test identities, and a non-destructive test case. Define the scope and stop condition in advance. Do not test third-party or production systems without explicit written authorization, and do not collect real credentials or personal data.

For regression coverage, express the security property as an expected allow/deny, validation, isolation, or failure behavior. Include a legitimate-use case and a negative case. Record environment, version, method, expected result, actual result, and remaining uncertainty.

## Remediation and verification

Assign an owner and select a fix based on the affected implementation, platform guidance, and the source mitigation above. Verify the corrected behavior at the relevant boundary, review comparable paths, and run regression tests for legitimate workflows. Track residual risk and exception expiry if remediation is incomplete.

## Provenance

This review companion interprets the linked MITRE CWE record for defensive learning. It does not assert that a particular product is vulnerable, that the weakness is exploitable, or that a security incident has occurred. Confirm catalog version and licensing against the original source before redistribution or training use.
