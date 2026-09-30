---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-296"
status: "Draft"
---
# CWE-296: Improper Following of a Certificate's Chain of Trust

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific, Web Based

## Description

The product does not follow, or incorrectly follows, the chain of trust for a certificate back to a trusted root certificate.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Ensure that proper certificate checking is included in the system design.
- **Implementation:** Understand, and properly implement all checks necessary to ensure the integrity of certificate trust integrity.
- **Implementation:** If certificate pinning is being used, ensure that all relevant properties of the certificate are fully validated before the certificate is pinned, including the full chain of trust.

## Related weaknesses

- CWE-295 (ChildOf)
- CWE-573 (ChildOf)

## Source

- [CWE-296 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/296.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
