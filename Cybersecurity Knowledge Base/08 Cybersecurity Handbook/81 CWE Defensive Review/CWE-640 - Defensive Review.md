---
tags:
  - cybersecurity
  - defensive-security
  - weakness-review
cwe: "CWE-640"
source: MITRE CWE
---
# CWE-640: Weak Password Recovery Mechanism for Forgotten Password — Defensive Review

## Source record

- Catalog entry: [[02 Weaknesses CWE/CWE-640 - Weak Password Recovery Mechanism for Forgotten Password|CWE-640 source record]]
- Abstraction: Base
- Catalog status: Incomplete
- Applicable platforms: Not Language-Specific

## Weakness description

The product contains a mechanism for users to recover or change their passwords without knowing the original password, but the mechanism is weak.

## Defensive review questions

- Identify the affected component, trust boundary, data or operation, and accountable owner.
- Determine whether the described condition exists in the current implementation or configuration; a CWE classification alone is not proof.
- Trace relevant inputs, states, permissions, and downstream effects to establish reachability and realistic impact.
- Review whether existing validation, authorization, isolation, monitoring, and recovery controls change the risk.
- Check adjacent code paths and supported versions for the same underlying cause.

## Catalog mitigations

- **Architecture and Design:** Make sure that all input supplied by the user to the password recovery mechanism is thoroughly filtered and validated.
- **Architecture and Design:** Do not use standard weak security questions and use several security questions.
- **Architecture and Design:** Make sure that there is throttling on the number of incorrect answers to a security question. Disable the password recovery functionality after a certain (small) number of incorrect guesses.
- **Architecture and Design:** Require that the user properly answers the security question prior to resetting their password and sending the new password to the e-mail address of record.
- **Architecture and Design:** Never allow the user to control what e-mail address the new password will be sent to in the password recovery mechanism.
- **Architecture and Design:** Assign a new temporary password rather than revealing the original password.

Treat catalog guidance as a starting point. Confirm that each mitigation applies to the actual platform and version, does not introduce a new weakness, and addresses the root cause rather than only suppressing a symptom.

## Safe validation plan

Review source code, configuration, build settings, and test evidence first. If behavior testing is needed, use an owned local or staging system, synthetic data, dedicated test identities, and a non-destructive test case. Define the scope and stop condition in advance. Do not test third-party or production systems without explicit written authorization, and do not collect real credentials or personal data.

For regression coverage, express the security property as an expected allow/deny, validation, isolation, or failure behavior. Include a legitimate-use case and a negative case. Record environment, version, method, expected result, actual result, and remaining uncertainty.

## Remediation and verification

Assign an owner and select a fix based on the affected implementation, platform guidance, and the source mitigation above. Verify the corrected behavior at the relevant boundary, review comparable paths, and run regression tests for legitimate workflows. Track residual risk and exception expiry if remediation is incomplete.

## Provenance

This review companion interprets the linked MITRE CWE record for defensive learning. It does not assert that a particular product is vulnerable, that the weakness is exploitable, or that a security incident has occurred. Confirm catalog version and licensing against the original source before redistribution or training use.
