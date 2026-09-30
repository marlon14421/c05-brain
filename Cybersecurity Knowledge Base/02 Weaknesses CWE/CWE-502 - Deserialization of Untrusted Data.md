---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-502"
status: "Draft"
---
# CWE-502: Deserialization of Untrusted Data

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Java, Ruby, PHP, Python, JavaScript, Not Technology-Specific, ICS/OT, AI/ML

## Description

The product deserializes untrusted data without sufficiently ensuring that the resulting data will be valid.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** If available, use the signing/sealing features of the programming language to assure that deserialized data has not been tainted. For example, a hash-based message authentication code (HMAC) could be used to ensure that data has not been modified.
- **Implementation:** When deserializing data, populate a new object rather than just deserializing. The result is that the data flows through safe input validation and that the functions are safe.
- **Implementation:** Explicitly define a final object() to prevent deserialization.
- **Implementation:** Avoid having unnecessary types or gadgets (a sequence of instances and method invocations that can self-execute during the deserialization process, often found in libraries) available that can be leveraged for malicious ends. This limits the potential for unintended or unauthorized types and gadgets to be leveraged by the attacker. Add only acceptable classes to an allowlist. Note: new gadgets are constantly being discovered, so this alone is not a sufficient mitigation.
- **Architecture and Design:** Employ cryptography of the data or code for protection. However, it's important to note that it would still be client-side security. This is risky because if the client is compromised then the security implemented on the client (the cryptography) can be bypassed.
- **Operation:** Use an application firewall that can detect attacks against this weakness. It can be beneficial in cases in which the code cannot be fixed (because it is controlled by a third party), as an emergency prevention measure while more comprehensive software assurance measures are applied, or to provide defense in depth [REF-1481].

## Related weaknesses

- CWE-913 (ChildOf)
- CWE-913 (ChildOf)
- CWE-915 (PeerOf)

## Source

- [CWE-502 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/502.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
