---
tags:
  - cybersecurity
  - defensive-security
  - weakness-review
cwe: "CWE-1395"
source: MITRE CWE
---
# CWE-1395: Dependency on Vulnerable Third-Party Component — Defensive Review

## Source record

- Catalog entry: [[02 Weaknesses CWE/CWE-1395 - Dependency on Vulnerable Third-Party Component|CWE-1395 source record]]
- Abstraction: Class
- Catalog status: Incomplete
- Applicable platforms: Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Weakness description

The product has a dependency on a third-party component that contains one or more known vulnerabilities.

## Defensive review questions

- Identify the affected component, trust boundary, data or operation, and accountable owner.
- Determine whether the described condition exists in the current implementation or configuration; a CWE classification alone is not proof.
- Trace relevant inputs, states, permissions, and downstream effects to establish reachability and realistic impact.
- Review whether existing validation, authorization, isolation, monitoring, and recovery controls change the risk.
- Check adjacent code paths and supported versions for the same underlying cause.

## Catalog mitigations

- **Requirements:** In some industries such as healthcare [REF-1320] [REF-1322] or technologies such as the cloud [REF-1321], it might be unclear about who is responsible for applying patches for third-party vulnerabilities: the vendor, the operator/customer, or a separate service. Clarifying roles and responsibilities can be important to minimize confusion or unnecessary delay when third-party vulnerabilities are disclosed.
- **Requirements:** Require a Bill of Materials for all components and sub-components of the product. For software, require a Software Bill of Materials (SBOM) [REF-1247] [REF-1311].
- **Architecture and Design:** Maintain a Bill of Materials for all components and sub-components of the product. For software, maintain a Software Bill of Materials (SBOM). According to [REF-1247], "An SBOM is a formal, machine-readable inventory of software components and dependencies, information about those components, and their hierarchical relationships."
- **Operation:** Actively monitor when a third-party component vendor announces vulnerability patches; fix the third-party component as soon as possible; and make it easy for operators/customers to obtain and apply the patch.
- **Operation:** Continuously monitor changes in each of the product's components, especially when the changes indicate new vulnerabilities, end-of-life (EOL) plans, etc.

Treat catalog guidance as a starting point. Confirm that each mitigation applies to the actual platform and version, does not introduce a new weakness, and addresses the root cause rather than only suppressing a symptom.

## Safe validation plan

Review source code, configuration, build settings, and test evidence first. If behavior testing is needed, use an owned local or staging system, synthetic data, dedicated test identities, and a non-destructive test case. Define the scope and stop condition in advance. Do not test third-party or production systems without explicit written authorization, and do not collect real credentials or personal data.

For regression coverage, express the security property as an expected allow/deny, validation, isolation, or failure behavior. Include a legitimate-use case and a negative case. Record environment, version, method, expected result, actual result, and remaining uncertainty.

## Remediation and verification

Assign an owner and select a fix based on the affected implementation, platform guidance, and the source mitigation above. Verify the corrected behavior at the relevant boundary, review comparable paths, and run regression tests for legitimate workflows. Track residual risk and exception expiry if remediation is incomplete.

## Provenance

This review companion interprets the linked MITRE CWE record for defensive learning. It does not assert that a particular product is vulnerable, that the weakness is exploitable, or that a security incident has occurred. Confirm catalog version and licensing against the original source before redistribution or training use.
