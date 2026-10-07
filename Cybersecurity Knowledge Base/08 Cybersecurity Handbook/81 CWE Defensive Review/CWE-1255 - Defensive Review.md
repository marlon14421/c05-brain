---
tags:
  - cybersecurity
  - defensive-security
  - weakness-review
cwe: "CWE-1255"
source: MITRE CWE
---
# CWE-1255: Comparison Logic is Vulnerable to Power Side-Channel Attacks — Defensive Review

## Source record

- Catalog entry: [[02 Weaknesses CWE/CWE-1255 - Comparison Logic is Vulnerable to Power Side-Channel Attacks|CWE-1255 source record]]
- Abstraction: Variant
- Catalog status: Draft
- Applicable platforms: Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Weakness description

A device's real time power consumption may be monitored during security token evaluation and the information gleaned may be used to determine the value of the reference token.

## Defensive review questions

- Identify the affected component, trust boundary, data or operation, and accountable owner.
- Determine whether the described condition exists in the current implementation or configuration; a CWE classification alone is not proof.
- Trace relevant inputs, states, permissions, and downstream effects to establish reachability and realistic impact.
- Review whether existing validation, authorization, isolation, monitoring, and recovery controls change the risk.
- Check adjacent code paths and supported versions for the same underlying cause.

## Catalog mitigations

- **Architecture and Design:** The design phase must consider each check of a security token against a standard and the amount of power consumed during the check of a good token versus a bad token. The alternative is an all at once check where a retry counter is incremented PRIOR to the check.
- **Architecture and Design:** Another potential mitigation is to parallelize shifting of secret data (see example 2 below). Note that the wider the bus the more effective the result.
- **Architecture and Design:** An additional potential mitigation is to add random data to each crypto operation then subtract it out afterwards. This is highly effective but costly in performance, area, and power consumption. It also requires a random number generator.
- **Implementation:** If the architecture is unable to prevent the attack, using filtering components may reduce the ability to implement an attack, however, consideration must be given to the physical removal of the filter elements.
- **Integration:** During integration, avoid use of a single secret for an extended period (e.g. frequent key updates). This limits the amount of data compromised but at the cost of complexity of use.

Treat catalog guidance as a starting point. Confirm that each mitigation applies to the actual platform and version, does not introduce a new weakness, and addresses the root cause rather than only suppressing a symptom.

## Safe validation plan

Review source code, configuration, build settings, and test evidence first. If behavior testing is needed, use an owned local or staging system, synthetic data, dedicated test identities, and a non-destructive test case. Define the scope and stop condition in advance. Do not test third-party or production systems without explicit written authorization, and do not collect real credentials or personal data.

For regression coverage, express the security property as an expected allow/deny, validation, isolation, or failure behavior. Include a legitimate-use case and a negative case. Record environment, version, method, expected result, actual result, and remaining uncertainty.

## Remediation and verification

Assign an owner and select a fix based on the affected implementation, platform guidance, and the source mitigation above. Verify the corrected behavior at the relevant boundary, review comparable paths, and run regression tests for legitimate workflows. Track residual risk and exception expiry if remediation is incomplete.

## Provenance

This review companion interprets the linked MITRE CWE record for defensive learning. It does not assert that a particular product is vulnerable, that the weakness is exploitable, or that a security incident has occurred. Confirm catalog version and licensing against the original source before redistribution or training use.
