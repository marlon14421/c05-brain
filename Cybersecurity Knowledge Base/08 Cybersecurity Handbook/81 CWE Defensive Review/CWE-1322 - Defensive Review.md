---
tags:
  - cybersecurity
  - defensive-security
  - weakness-review
cwe: "CWE-1322"
source: MITRE CWE
---
# CWE-1322: Use of Blocking Code in Single-threaded, Non-blocking Context — Defensive Review

## Source record

- Catalog entry: [[02 Weaknesses CWE/CWE-1322 - Use of Blocking Code in Single-threaded, Non-blocking Context|CWE-1322 source record]]
- Abstraction: Base
- Catalog status: Incomplete
- Applicable platforms: Not Language-Specific

## Weakness description

The product uses a non-blocking model that relies on a single threaded process for features such as scalability, but it contains code that can block when it is invoked.

## Defensive review questions

- Identify the affected component, trust boundary, data or operation, and accountable owner.
- Determine whether the described condition exists in the current implementation or configuration; a CWE classification alone is not proof.
- Trace relevant inputs, states, permissions, and downstream effects to establish reachability and realistic impact.
- Review whether existing validation, authorization, isolation, monitoring, and recovery controls change the risk.
- Check adjacent code paths and supported versions for the same underlying cause.

## Catalog mitigations

- **Implementation:** Generally speaking, blocking calls should be replaced with non-blocking alternatives that can be used asynchronously. Expensive computations should be passed off to worker threads, although the correct approach depends on the framework being used.
- **Implementation:** For expensive computations, consider breaking them up into multiple smaller computations. Refer to the documentation of the framework being used for guidance.

Treat catalog guidance as a starting point. Confirm that each mitigation applies to the actual platform and version, does not introduce a new weakness, and addresses the root cause rather than only suppressing a symptom.

## Safe validation plan

Review source code, configuration, build settings, and test evidence first. If behavior testing is needed, use an owned local or staging system, synthetic data, dedicated test identities, and a non-destructive test case. Define the scope and stop condition in advance. Do not test third-party or production systems without explicit written authorization, and do not collect real credentials or personal data.

For regression coverage, express the security property as an expected allow/deny, validation, isolation, or failure behavior. Include a legitimate-use case and a negative case. Record environment, version, method, expected result, actual result, and remaining uncertainty.

## Remediation and verification

Assign an owner and select a fix based on the affected implementation, platform guidance, and the source mitigation above. Verify the corrected behavior at the relevant boundary, review comparable paths, and run regression tests for legitimate workflows. Track residual risk and exception expiry if remediation is incomplete.

## Provenance

This review companion interprets the linked MITRE CWE record for defensive learning. It does not assert that a particular product is vulnerable, that the weakness is exploitable, or that a security incident has occurred. Confirm catalog version and licensing against the original source before redistribution or training use.
