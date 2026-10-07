---
tags:
  - cybersecurity
  - defensive-security
  - weakness-review
cwe: "CWE-1311"
source: MITRE CWE
---
# CWE-1311: Improper Translation of Security Attributes by Fabric Bridge — Defensive Review

## Source record

- Catalog entry: [[02 Weaknesses CWE/CWE-1311 - Improper Translation of Security Attributes by Fabric Bridge|CWE-1311 source record]]
- Abstraction: Base
- Catalog status: Draft
- Applicable platforms: Verilog, VHDL, Not Technology-Specific

## Weakness description

The bridge incorrectly translates security attributes from either trusted to untrusted or from untrusted to trusted when converting from one fabric protocol to another.

## Defensive review questions

- Identify the affected component, trust boundary, data or operation, and accountable owner.
- Determine whether the described condition exists in the current implementation or configuration; a CWE classification alone is not proof.
- Trace relevant inputs, states, permissions, and downstream effects to establish reachability and realistic impact.
- Review whether existing validation, authorization, isolation, monitoring, and recovery controls change the risk.
- Check adjacent code paths and supported versions for the same underlying cause.

## Catalog mitigations

- **Architecture and Design:** The translation must map signals in such a way that untrusted agents cannot map to trusted agents or vice-versa.
- **Implementation:** Ensure that the translation maps signals in such a way that untrusted agents cannot map to trusted agents or vice-versa.

Treat catalog guidance as a starting point. Confirm that each mitigation applies to the actual platform and version, does not introduce a new weakness, and addresses the root cause rather than only suppressing a symptom.

## Safe validation plan

Review source code, configuration, build settings, and test evidence first. If behavior testing is needed, use an owned local or staging system, synthetic data, dedicated test identities, and a non-destructive test case. Define the scope and stop condition in advance. Do not test third-party or production systems without explicit written authorization, and do not collect real credentials or personal data.

For regression coverage, express the security property as an expected allow/deny, validation, isolation, or failure behavior. Include a legitimate-use case and a negative case. Record environment, version, method, expected result, actual result, and remaining uncertainty.

## Remediation and verification

Assign an owner and select a fix based on the affected implementation, platform guidance, and the source mitigation above. Verify the corrected behavior at the relevant boundary, review comparable paths, and run regression tests for legitimate workflows. Track residual risk and exception expiry if remediation is incomplete.

## Provenance

This review companion interprets the linked MITRE CWE record for defensive learning. It does not assert that a particular product is vulnerable, that the weakness is exploitable, or that a security incident has occurred. Confirm catalog version and licensing against the original source before redistribution or training use.
