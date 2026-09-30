---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-599"
status: "Incomplete"
---
# CWE-599: Missing Validation of OpenSSL Certificate

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific

## Description

The product uses OpenSSL and trusts or uses a certificate without using the SSL_get_verify_result() function to ensure that the certificate satisfies all necessary security requirements.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Ensure that proper authentication is included in the system design.
- **Implementation:** Understand and properly implement all checks necessary to ensure the identity of entities involved in encrypted communications.

## Related weaknesses

- CWE-295 (ChildOf)

## Source

- [CWE-599 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/599.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
