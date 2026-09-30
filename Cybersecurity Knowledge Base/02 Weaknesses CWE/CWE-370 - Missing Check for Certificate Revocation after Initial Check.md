---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-370"
status: "Draft"
---
# CWE-370: Missing Check for Certificate Revocation after Initial Check

**Abstraction:** Variant  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific

## Description

The product does not check the revocation status of a certificate after its initial revocation check, which can cause the product to perform privileged actions even after the certificate is revoked at a later time.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Ensure that certificates are checked for revoked status before each use of a protected resource. If the certificate is checked before each access of a protected resource, the delay subject to a possible race condition becomes almost negligible and significantly reduces the risk associated with this issue.

## Related weaknesses

- CWE-299 (ChildOf)
- CWE-296 (PeerOf)
- CWE-297 (PeerOf)
- CWE-298 (PeerOf)

## Source

- [CWE-370 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/370.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
