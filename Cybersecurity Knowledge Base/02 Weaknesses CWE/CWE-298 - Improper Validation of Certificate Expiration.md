---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-298"
status: "Draft"
---
# CWE-298: Improper Validation of Certificate Expiration

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

A certificate expiration is not validated or is incorrectly validated.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Check for expired certificates and provide the user with adequate information about the nature of the problem and how to proceed.
- **Implementation:** If certificate pinning is being used, ensure that all relevant properties of the certificate are fully validated before the certificate is pinned, including the expiration.

## Related weaknesses

- CWE-295 (ChildOf)
- CWE-672 (ChildOf)

## Source

- [CWE-298 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/298.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
