---
tags:
  - cybersecurity
  - defensive-security
  - weakness-review
cwe: "CWE-502"
source: MITRE CWE
---
# CWE-502: Deserialization of Untrusted Data — Defensive Review

## Source record

- Catalog entry: [[02 Weaknesses CWE/CWE-502 - Deserialization of Untrusted Data|CWE-502 source record]]
- Abstraction: Base
- Catalog status: Draft
- Applicable platforms: Java, Ruby, PHP, Python, JavaScript, Not Technology-Specific, ICS/OT, AI/ML

## Weakness description

The product deserializes untrusted data without sufficiently ensuring that the resulting data will be valid.

## Defensive review questions

- Identify the affected component, trust boundary, data or operation, and accountable owner.
- Determine whether the described condition exists in the current implementation or configuration; a CWE classification alone is not proof.
- Trace relevant inputs, states, permissions, and downstream effects to establish reachability and realistic impact.
- Review whether existing validation, authorization, isolation, monitoring, and recovery controls change the risk.
- Check adjacent code paths and supported versions for the same underlying cause.

## Catalog mitigations

- **Architecture and Design:** If available, use the signing/sealing features of the programming language to assure that deserialized data has not been tainted. For example, a hash-based message authentication code (HMAC) could be used to ensure that data has not been modified.
- **Implementation:** When deserializing data, populate a new object rather than just deserializing. The result is that the data flows through safe input validation and that the functions are safe.
- **Implementation:** Explicitly define a final object() to prevent deserialization.
- **Implementation:** Avoid having unnecessary types or gadgets (a sequence of instances and method invocations that can self-execute during the deserialization process, often found in libraries) available that can be leveraged for malicious ends. This limits the potential for unintended or unauthorized types and gadgets to be leveraged by the attacker. Add only acceptable classes to an allowlist. Note: new gadgets are constantly being discovered, so this alone is not a sufficient mitigation.
- **Architecture and Design:** Employ cryptography of the data or code for protection. However, it's important to note that it would still be client-side security. This is risky because if the client is compromised then the security implemented on the client (the cryptography) can be bypassed.
- **Operation:** Use an application firewall that can detect attacks against this weakness. It can be beneficial in cases in which the code cannot be fixed (because it is controlled by a third party), as an emergency prevention measure while more comprehensive software assurance measures are applied, or to provide defense in depth [REF-1481].

Treat catalog guidance as a starting point. Confirm that each mitigation applies to the actual platform and version, does not introduce a new weakness, and addresses the root cause rather than only suppressing a symptom.

## Safe validation plan

Review source code, configuration, build settings, and test evidence first. If behavior testing is needed, use an owned local or staging system, synthetic data, dedicated test identities, and a non-destructive test case. Define the scope and stop condition in advance. Do not test third-party or production systems without explicit written authorization, and do not collect real credentials or personal data.

For regression coverage, express the security property as an expected allow/deny, validation, isolation, or failure behavior. Include a legitimate-use case and a negative case. Record environment, version, method, expected result, actual result, and remaining uncertainty.

## Remediation and verification

Assign an owner and select a fix based on the affected implementation, platform guidance, and the source mitigation above. Verify the corrected behavior at the relevant boundary, review comparable paths, and run regression tests for legitimate workflows. Track residual risk and exception expiry if remediation is incomplete.

## Provenance

This review companion interprets the linked MITRE CWE record for defensive learning. It does not assert that a particular product is vulnerable, that the weakness is exploitable, or that a security incident has occurred. Confirm catalog version and licensing against the original source before redistribution or training use.
