---
tags:
  - cybersecurity
  - defensive-security
  - weakness-review
cwe: "CWE-1310"
source: MITRE CWE
---
# CWE-1310: Missing Ability to Patch ROM Code — Defensive Review

## Source record

- Catalog entry: [[02 Weaknesses CWE/CWE-1310 - Missing Ability to Patch ROM Code|CWE-1310 source record]]
- Abstraction: Base
- Catalog status: Draft
- Applicable platforms: Not Language-Specific, Not OS-Specific, Not Architecture-Specific, System on Chip

## Weakness description

Missing an ability to patch ROM code may leave a System or System-on-Chip (SoC) in a vulnerable state.

## Defensive review questions

- Identify the affected component, trust boundary, data or operation, and accountable owner.
- Determine whether the described condition exists in the current implementation or configuration; a CWE classification alone is not proof.
- Trace relevant inputs, states, permissions, and downstream effects to establish reachability and realistic impact.
- Review whether existing validation, authorization, isolation, monitoring, and recovery controls change the risk.
- Check adjacent code paths and supported versions for the same underlying cause.

## Catalog mitigations

- **Architecture and Design:** Secure patch support to allow ROM code to be patched on the next boot.
- **Architecture and Design:** Support patches that can be programmed in-field or during manufacturing through hardware fuses. This feature can be used for limited patching of devices after shipping, or for the next batch of silicon devices manufactured, without changing the full device ROM.

Treat catalog guidance as a starting point. Confirm that each mitigation applies to the actual platform and version, does not introduce a new weakness, and addresses the root cause rather than only suppressing a symptom.

## Safe validation plan

Review source code, configuration, build settings, and test evidence first. If behavior testing is needed, use an owned local or staging system, synthetic data, dedicated test identities, and a non-destructive test case. Define the scope and stop condition in advance. Do not test third-party or production systems without explicit written authorization, and do not collect real credentials or personal data.

For regression coverage, express the security property as an expected allow/deny, validation, isolation, or failure behavior. Include a legitimate-use case and a negative case. Record environment, version, method, expected result, actual result, and remaining uncertainty.

## Remediation and verification

Assign an owner and select a fix based on the affected implementation, platform guidance, and the source mitigation above. Verify the corrected behavior at the relevant boundary, review comparable paths, and run regression tests for legitimate workflows. Track residual risk and exception expiry if remediation is incomplete.

## Provenance

This review companion interprets the linked MITRE CWE record for defensive learning. It does not assert that a particular product is vulnerable, that the weakness is exploitable, or that a security incident has occurred. Confirm catalog version and licensing against the original source before redistribution or training use.
