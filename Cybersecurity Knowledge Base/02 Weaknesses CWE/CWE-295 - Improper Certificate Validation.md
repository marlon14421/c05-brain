---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-295"
status: "Draft"
---
# CWE-295: Improper Certificate Validation

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific, Web Based, Mobile

## Description

The product does not validate, or incorrectly validates, a certificate.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Certificates should be carefully managed and checked to assure that data are encrypted with the intended owner's public key.
- **Implementation:** If certificate pinning is being used, ensure that all relevant properties of the certificate are fully validated before the certificate is pinned, including the hostname.

## Related weaknesses

- CWE-287 (ChildOf)
- CWE-287 (ChildOf)
- CWE-322 (PeerOf)

## Source

- [CWE-295 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/295.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
