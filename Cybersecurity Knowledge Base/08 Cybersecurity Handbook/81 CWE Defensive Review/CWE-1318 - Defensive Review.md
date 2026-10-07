---
tags:
  - cybersecurity
  - defensive-security
  - weakness-review
cwe: "CWE-1318"
source: MITRE CWE
---
# CWE-1318: Missing Support for Security Features in On-chip Fabrics or Buses — Defensive Review

## Source record

- Catalog entry: [[02 Weaknesses CWE/CWE-1318 - Missing Support for Security Features in On-chip Fabrics or Buses|CWE-1318 source record]]
- Abstraction: Base
- Catalog status: Incomplete
- Applicable platforms: Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Processor Hardware, Not Technology-Specific

## Weakness description

On-chip fabrics or buses either do not support or are not configured to support privilege separation or other security features, such as access control.

## Defensive review questions

- Identify the affected component, trust boundary, data or operation, and accountable owner.
- Determine whether the described condition exists in the current implementation or configuration; a CWE classification alone is not proof.
- Trace relevant inputs, states, permissions, and downstream effects to establish reachability and realistic impact.
- Review whether existing validation, authorization, isolation, monitoring, and recovery controls change the risk.
- Check adjacent code paths and supported versions for the same underlying cause.

## Catalog mitigations

- **Architecture and Design:** If fabric does not support security features, implement security checks in a bridge or any component that is between the master and the fabric. Alternatively, connect all fabric slaves that do not have any security assets under one such fabric and connect peripherals with security assets to a different fabric that supports security features.

Treat catalog guidance as a starting point. Confirm that each mitigation applies to the actual platform and version, does not introduce a new weakness, and addresses the root cause rather than only suppressing a symptom.

## Safe validation plan

Review source code, configuration, build settings, and test evidence first. If behavior testing is needed, use an owned local or staging system, synthetic data, dedicated test identities, and a non-destructive test case. Define the scope and stop condition in advance. Do not test third-party or production systems without explicit written authorization, and do not collect real credentials or personal data.

For regression coverage, express the security property as an expected allow/deny, validation, isolation, or failure behavior. Include a legitimate-use case and a negative case. Record environment, version, method, expected result, actual result, and remaining uncertainty.

## Remediation and verification

Assign an owner and select a fix based on the affected implementation, platform guidance, and the source mitigation above. Verify the corrected behavior at the relevant boundary, review comparable paths, and run regression tests for legitimate workflows. Track residual risk and exception expiry if remediation is incomplete.

## Provenance

This review companion interprets the linked MITRE CWE record for defensive learning. It does not assert that a particular product is vulnerable, that the weakness is exploitable, or that a security incident has occurred. Confirm catalog version and licensing against the original source before redistribution or training use.
