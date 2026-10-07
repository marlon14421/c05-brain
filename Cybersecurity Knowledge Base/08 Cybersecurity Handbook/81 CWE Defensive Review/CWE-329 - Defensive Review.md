---
tags:
  - cybersecurity
  - defensive-security
  - weakness-review
cwe: "CWE-329"
source: MITRE CWE
---
# CWE-329: Generation of Predictable IV with CBC Mode — Defensive Review

## Source record

- Catalog entry: [[02 Weaknesses CWE/CWE-329 - Generation of Predictable IV with CBC Mode|CWE-329 source record]]
- Abstraction: Variant
- Catalog status: Draft
- Applicable platforms: Not Language-Specific, ICS/OT

## Weakness description

The product generates and uses a predictable initialization Vector (IV) with Cipher Block Chaining (CBC) Mode, which causes algorithms to be susceptible to dictionary attacks when they are encrypted under the same key.

## Defensive review questions

- Identify the affected component, trust boundary, data or operation, and accountable owner.
- Determine whether the described condition exists in the current implementation or configuration; a CWE classification alone is not proof.
- Trace relevant inputs, states, permissions, and downstream effects to establish reachability and realistic impact.
- Review whether existing validation, authorization, isolation, monitoring, and recovery controls change the risk.
- Check adjacent code paths and supported versions for the same underlying cause.

## Catalog mitigations

- **Implementation:** NIST recommends two methods of generating unpredictable IVs for CBC mode [REF-1172]. The first is to generate the IV randomly. The second method is to encrypt a nonce with the same key and cipher to be used to encrypt the plaintext. In this case the nonce must be unique but can be predictable, since the block cipher will act as a pseudo random permutation.

Treat catalog guidance as a starting point. Confirm that each mitigation applies to the actual platform and version, does not introduce a new weakness, and addresses the root cause rather than only suppressing a symptom.

## Safe validation plan

Review source code, configuration, build settings, and test evidence first. If behavior testing is needed, use an owned local or staging system, synthetic data, dedicated test identities, and a non-destructive test case. Define the scope and stop condition in advance. Do not test third-party or production systems without explicit written authorization, and do not collect real credentials or personal data.

For regression coverage, express the security property as an expected allow/deny, validation, isolation, or failure behavior. Include a legitimate-use case and a negative case. Record environment, version, method, expected result, actual result, and remaining uncertainty.

## Remediation and verification

Assign an owner and select a fix based on the affected implementation, platform guidance, and the source mitigation above. Verify the corrected behavior at the relevant boundary, review comparable paths, and run regression tests for legitimate workflows. Track residual risk and exception expiry if remediation is incomplete.

## Provenance

This review companion interprets the linked MITRE CWE record for defensive learning. It does not assert that a particular product is vulnerable, that the weakness is exploitable, or that a security incident has occurred. Confirm catalog version and licensing against the original source before redistribution or training use.
