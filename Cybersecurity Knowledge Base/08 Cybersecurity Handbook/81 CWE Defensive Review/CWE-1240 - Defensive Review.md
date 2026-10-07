---
tags:
  - cybersecurity
  - defensive-security
  - weakness-review
cwe: "CWE-1240"
source: MITRE CWE
---
# CWE-1240: Use of a Cryptographic Primitive with a Risky Implementation — Defensive Review

## Source record

- Catalog entry: [[02 Weaknesses CWE/CWE-1240 - Use of a Cryptographic Primitive with a Risky Implementation|CWE-1240 source record]]
- Abstraction: Base
- Catalog status: Draft
- Applicable platforms: Not Language-Specific, Not OS-Specific, Not Architecture-Specific, System on Chip

## Weakness description

To fulfill the need for a cryptographic primitive, the product implements a cryptographic algorithm using a non-standard, unproven, or disallowed/non-compliant cryptographic implementation.

## Defensive review questions

- Identify the affected component, trust boundary, data or operation, and accountable owner.
- Determine whether the described condition exists in the current implementation or configuration; a CWE classification alone is not proof.
- Trace relevant inputs, states, permissions, and downstream effects to establish reachability and realistic impact.
- Review whether existing validation, authorization, isolation, monitoring, and recovery controls change the risk.
- Check adjacent code paths and supported versions for the same underlying cause.

## Catalog mitigations

- **Requirements:** Require compliance with the strongest-available recommendations from trusted parties, and require that compliance must be kept up-to-date, since recommendations evolve over time. For example, US government systems require FIPS 140-3 certification, which supersedes FIPS 140-2 [REF-1192] [REF-267].
- **Architecture and Design:** Ensure that the architecture/design uses the strongest-available primitives and algorithms from trusted parties. For example, US government systems require FIPS 140-3 certification, which supersedes FIPS 140-2 [REF-1192] [REF-267].
- **Architecture and Design:** Do not develop custom or private cryptographic algorithms. They will likely be exposed to attacks that are well-understood by cryptographers. As with all cryptographic mechanisms, the source code should be available for analysis. If the algorithm may be compromised when attackers find out how it works, then it is especially weak.
- **Architecture and Design:** Try not to use cryptographic algorithms in novel ways or with new modes of operation even when you "know" it is secure. For example, using SHA-2 chaining to create a 1-time pad for encryption might sound like a good idea, but one should not do this.
- **Architecture and Design:** Ensure that the design can replace one cryptographic primitive or algorithm with another in the next generation ("cryptographic agility"). Where possible, use wrappers to make the interfaces uniform. This will make it easier to upgrade to stronger algorithms. This is especially important for hardware, which can be more difficult to upgrade quickly than software; design the hardware at a replaceable block level.
- **Architecture and Design:** Do not use outdated or non-compliant cryptography algorithms. Some older algorithms, once thought to require a billion years of computing time, can now be broken in days or hours. This includes MD4, MD5, SHA1, DES, and other algorithms that were once regarded as strong [REF-267].
- **Architecture and Design:** Do not use a linear-feedback shift register (LFSR) or other legacy methods as a substitute for an accepted and standard Random Number Generator.
- **Architecture and Design:** Do not use a checksum as a substitute for a cryptographically generated hash.
- **Architecture and Design:** Use a vetted cryptographic library or framework. Industry-standard implementations will save development time and are more likely to avoid errors that can occur during implementation of cryptographic algorithms. However, the library/framework could be used incorrectly during implementation.
- **Architecture and Design:** When using industry-approved techniques, use them correctly. Don't cut corners by skipping resource-intensive steps (CWE-325). These steps are often essential for the prevention of common attacks.
- **Architecture and Design:** Do not store keys in areas accessible to untrusted agents. Carefully manage and protect the cryptographic keys (see CWE-320). If the keys can be guessed or stolen, then the strength of the cryptography algorithm is irrelevant.

Treat catalog guidance as a starting point. Confirm that each mitigation applies to the actual platform and version, does not introduce a new weakness, and addresses the root cause rather than only suppressing a symptom.

## Safe validation plan

Review source code, configuration, build settings, and test evidence first. If behavior testing is needed, use an owned local or staging system, synthetic data, dedicated test identities, and a non-destructive test case. Define the scope and stop condition in advance. Do not test third-party or production systems without explicit written authorization, and do not collect real credentials or personal data.

For regression coverage, express the security property as an expected allow/deny, validation, isolation, or failure behavior. Include a legitimate-use case and a negative case. Record environment, version, method, expected result, actual result, and remaining uncertainty.

## Remediation and verification

Assign an owner and select a fix based on the affected implementation, platform guidance, and the source mitigation above. Verify the corrected behavior at the relevant boundary, review comparable paths, and run regression tests for legitimate workflows. Track residual risk and exception expiry if remediation is incomplete.

## Provenance

This review companion interprets the linked MITRE CWE record for defensive learning. It does not assert that a particular product is vulnerable, that the weakness is exploitable, or that a security incident has occurred. Confirm catalog version and licensing against the original source before redistribution or training use.
