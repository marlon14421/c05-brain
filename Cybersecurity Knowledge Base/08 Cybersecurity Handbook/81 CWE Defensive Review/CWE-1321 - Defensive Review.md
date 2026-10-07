---
tags:
  - cybersecurity
  - defensive-security
  - weakness-review
cwe: "CWE-1321"
source: MITRE CWE
---
# CWE-1321: Improperly Controlled Modification of Object Prototype Attributes ('Prototype Pollution') — Defensive Review

## Source record

- Catalog entry: [[02 Weaknesses CWE/CWE-1321 - Improperly Controlled Modification of Object Prototype Attributes ('Prototype Pollution')|CWE-1321 source record]]
- Abstraction: Variant
- Catalog status: Incomplete
- Applicable platforms: JavaScript

## Weakness description

The product receives input from an upstream component that specifies attributes that are to be initialized or updated in an object, but it does not properly control modifications of attributes of the object prototype.

## Defensive review questions

- Identify the affected component, trust boundary, data or operation, and accountable owner.
- Determine whether the described condition exists in the current implementation or configuration; a CWE classification alone is not proof.
- Trace relevant inputs, states, permissions, and downstream effects to establish reachability and realistic impact.
- Review whether existing validation, authorization, isolation, monitoring, and recovery controls change the risk.
- Check adjacent code paths and supported versions for the same underlying cause.

## Catalog mitigations

- **Implementation:** By freezing the object prototype first (for example, Object.freeze(Object.prototype)), modification of the prototype becomes impossible.
- **Architecture and Design:** By blocking modifications of attributes that resolve to object prototype, such as proto or prototype, this weakness can be mitigated.
- **Implementation:** When handling untrusted objects, validating using a schema can be used.
- **Implementation:** By using an object without prototypes (via Object.create(null) ), adding object prototype attributes by accessing the prototype via the special attributes becomes impossible, mitigating this weakness.
- **Implementation:** Map can be used instead of objects in most cases. If Map methods are used instead of object attributes, it is not possible to access the object prototype or modify it.

Treat catalog guidance as a starting point. Confirm that each mitigation applies to the actual platform and version, does not introduce a new weakness, and addresses the root cause rather than only suppressing a symptom.

## Safe validation plan

Review source code, configuration, build settings, and test evidence first. If behavior testing is needed, use an owned local or staging system, synthetic data, dedicated test identities, and a non-destructive test case. Define the scope and stop condition in advance. Do not test third-party or production systems without explicit written authorization, and do not collect real credentials or personal data.

For regression coverage, express the security property as an expected allow/deny, validation, isolation, or failure behavior. Include a legitimate-use case and a negative case. Record environment, version, method, expected result, actual result, and remaining uncertainty.

## Remediation and verification

Assign an owner and select a fix based on the affected implementation, platform guidance, and the source mitigation above. Verify the corrected behavior at the relevant boundary, review comparable paths, and run regression tests for legitimate workflows. Track residual risk and exception expiry if remediation is incomplete.

## Provenance

This review companion interprets the linked MITRE CWE record for defensive learning. It does not assert that a particular product is vulnerable, that the weakness is exploitable, or that a security incident has occurred. Confirm catalog version and licensing against the original source before redistribution or training use.
