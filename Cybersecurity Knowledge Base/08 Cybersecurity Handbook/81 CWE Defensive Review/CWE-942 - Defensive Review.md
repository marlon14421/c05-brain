---
tags:
  - cybersecurity
  - defensive-security
  - weakness-review
cwe: "CWE-942"
source: MITRE CWE
---
# CWE-942: Permissive Cross-domain Security Policy with Untrusted Domains — Defensive Review

## Source record

- Catalog entry: [[02 Weaknesses CWE/CWE-942 - Permissive Cross-domain Security Policy with Untrusted Domains|CWE-942 source record]]
- Abstraction: Variant
- Catalog status: Incomplete
- Applicable platforms: Not Language-Specific, Web Based, Web Server

## Weakness description

The product uses a web-client protection mechanism such as a Content Security Policy (CSP) or cross-domain policy file, but the policy includes untrusted domains with which the web client is allowed to communicate.

## Defensive review questions

- Identify the affected component, trust boundary, data or operation, and accountable owner.
- Determine whether the described condition exists in the current implementation or configuration; a CWE classification alone is not proof.
- Trace relevant inputs, states, permissions, and downstream effects to establish reachability and realistic impact.
- Review whether existing validation, authorization, isolation, monitoring, and recovery controls change the risk.
- Check adjacent code paths and supported versions for the same underlying cause.

## Catalog mitigations

- **Architecture and Design:** Define a restrictive Content Security Policy [REF-1486] or cross-domain policy file.
- **Architecture and Design:** Avoid using wildcards in the CSP / cross-domain policy file. Any domain matching the wildcard expression will be implicitly trusted, and can perform two-way interaction with the target server.
- **Architecture and Design:** For Flash, modify crossdomain.xml to use meta-policy options such as 'master-only' or 'none' to reduce the possibility of an attacker planting extraneous cross-domain policy files on a server.

Treat catalog guidance as a starting point. Confirm that each mitigation applies to the actual platform and version, does not introduce a new weakness, and addresses the root cause rather than only suppressing a symptom.

## Safe validation plan

Review source code, configuration, build settings, and test evidence first. If behavior testing is needed, use an owned local or staging system, synthetic data, dedicated test identities, and a non-destructive test case. Define the scope and stop condition in advance. Do not test third-party or production systems without explicit written authorization, and do not collect real credentials or personal data.

For regression coverage, express the security property as an expected allow/deny, validation, isolation, or failure behavior. Include a legitimate-use case and a negative case. Record environment, version, method, expected result, actual result, and remaining uncertainty.

## Remediation and verification

Assign an owner and select a fix based on the affected implementation, platform guidance, and the source mitigation above. Verify the corrected behavior at the relevant boundary, review comparable paths, and run regression tests for legitimate workflows. Track residual risk and exception expiry if remediation is incomplete.

## Provenance

This review companion interprets the linked MITRE CWE record for defensive learning. It does not assert that a particular product is vulnerable, that the weakness is exploitable, or that a security incident has occurred. Confirm catalog version and licensing against the original source before redistribution or training use.
