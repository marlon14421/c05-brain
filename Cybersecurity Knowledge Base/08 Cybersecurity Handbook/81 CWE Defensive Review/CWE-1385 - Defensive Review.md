---
tags:
  - cybersecurity
  - defensive-security
  - weakness-review
cwe: "CWE-1385"
source: MITRE CWE
---
# CWE-1385: Missing Origin Validation in WebSockets — Defensive Review

## Source record

- Catalog entry: [[02 Weaknesses CWE/CWE-1385 - Missing Origin Validation in WebSockets|CWE-1385 source record]]
- Abstraction: Variant
- Catalog status: Incomplete
- Applicable platforms: Not Language-Specific, Web Based, Web Server

## Weakness description

The product uses a WebSocket, but it does not properly verify that the source of data or communication is valid.

## Defensive review questions

- Identify the affected component, trust boundary, data or operation, and accountable owner.
- Determine whether the described condition exists in the current implementation or configuration; a CWE classification alone is not proof.
- Trace relevant inputs, states, permissions, and downstream effects to establish reachability and realistic impact.
- Review whether existing validation, authorization, isolation, monitoring, and recovery controls change the risk.
- Check adjacent code paths and supported versions for the same underlying cause.

## Catalog mitigations

- **Implementation:** Enable CORS-like access restrictions by verifying the 'Origin' header during the WebSocket handshake.
- **Implementation:** Use a randomized CSRF token to verify requests.
- **Implementation:** Use TLS to securely communicate using 'wss' (WebSocket Secure) instead of 'ws'.
- **Architecture and Design:** Require user authentication prior to the WebSocket connection being established. For example, the WS library in Node has a 'verifyClient' function.
- **Implementation:** Leverage rate limiting to prevent against DoS. Use of the leaky bucket algorithm can help with this.
- **Implementation:** Use a library that provides restriction of the payload size. For example, WS library for Node includes 'maxPayloadoption' that can be set.
- **Implementation:** Treat data/input as untrusted in both directions and apply the same data/input sanitization as XSS, SQLi, etc.

Treat catalog guidance as a starting point. Confirm that each mitigation applies to the actual platform and version, does not introduce a new weakness, and addresses the root cause rather than only suppressing a symptom.

## Safe validation plan

Review source code, configuration, build settings, and test evidence first. If behavior testing is needed, use an owned local or staging system, synthetic data, dedicated test identities, and a non-destructive test case. Define the scope and stop condition in advance. Do not test third-party or production systems without explicit written authorization, and do not collect real credentials or personal data.

For regression coverage, express the security property as an expected allow/deny, validation, isolation, or failure behavior. Include a legitimate-use case and a negative case. Record environment, version, method, expected result, actual result, and remaining uncertainty.

## Remediation and verification

Assign an owner and select a fix based on the affected implementation, platform guidance, and the source mitigation above. Verify the corrected behavior at the relevant boundary, review comparable paths, and run regression tests for legitimate workflows. Track residual risk and exception expiry if remediation is incomplete.

## Provenance

This review companion interprets the linked MITRE CWE record for defensive learning. It does not assert that a particular product is vulnerable, that the weakness is exploitable, or that a security incident has occurred. Confirm catalog version and licensing against the original source before redistribution or training use.
