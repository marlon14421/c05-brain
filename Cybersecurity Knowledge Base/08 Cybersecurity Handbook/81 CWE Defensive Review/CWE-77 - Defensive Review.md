---
tags:
  - cybersecurity
  - defensive-security
  - weakness-review
cwe: "CWE-77"
source: MITRE CWE
---
# CWE-77: Improper Neutralization of Special Elements used in a Command ('Command Injection') — Defensive Review

## Source record

- Catalog entry: [[02 Weaknesses CWE/CWE-77 - Improper Neutralization of Special Elements used in a Command ('Command Injection')|CWE-77 source record]]
- Abstraction: Class
- Catalog status: Draft
- Applicable platforms: Not Language-Specific, AI/ML

## Weakness description

The product constructs all or part of a command using externally-influenced input from an upstream component, but it does not neutralize or incorrectly neutralizes special elements that could modify the intended command when it is sent to a downstream component.

## Defensive review questions

- Identify the affected component, trust boundary, data or operation, and accountable owner.
- Determine whether the described condition exists in the current implementation or configuration; a CWE classification alone is not proof.
- Trace relevant inputs, states, permissions, and downstream effects to establish reachability and realistic impact.
- Review whether existing validation, authorization, isolation, monitoring, and recovery controls change the risk.
- Check adjacent code paths and supported versions for the same underlying cause.

## Catalog mitigations

- **Architecture and Design:** If at all possible, use library calls rather than external processes to recreate the desired functionality.
- **Implementation:** If possible, ensure that all external commands called from the program are statically created.
- **Operation:** Run time: Run time policy enforcement may be used in an allowlist fashion to prevent use of any non-sanctioned commands.
- **System Configuration:** Assign permissions that prevent the user from accessing/opening privileged files.

Treat catalog guidance as a starting point. Confirm that each mitigation applies to the actual platform and version, does not introduce a new weakness, and addresses the root cause rather than only suppressing a symptom.

## Safe validation plan

Review source code, configuration, build settings, and test evidence first. If behavior testing is needed, use an owned local or staging system, synthetic data, dedicated test identities, and a non-destructive test case. Define the scope and stop condition in advance. Do not test third-party or production systems without explicit written authorization, and do not collect real credentials or personal data.

For regression coverage, express the security property as an expected allow/deny, validation, isolation, or failure behavior. Include a legitimate-use case and a negative case. Record environment, version, method, expected result, actual result, and remaining uncertainty.

## Remediation and verification

Assign an owner and select a fix based on the affected implementation, platform guidance, and the source mitigation above. Verify the corrected behavior at the relevant boundary, review comparable paths, and run regression tests for legitimate workflows. Track residual risk and exception expiry if remediation is incomplete.

## Provenance

This review companion interprets the linked MITRE CWE record for defensive learning. It does not assert that a particular product is vulnerable, that the weakness is exploitable, or that a security incident has occurred. Confirm catalog version and licensing against the original source before redistribution or training use.
