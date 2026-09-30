---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-297"
status: "Incomplete"
---
# CWE-297: Improper Validation of Certificate with Host Mismatch

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** Not Language-Specific, Not Technology-Specific, Mobile, Web Based

## Description

The product communicates with a host that provides a certificate, but the product does not properly ensure that the certificate is actually associated with that host.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Fully check the hostname of the certificate and provide the user with adequate information about the nature of the problem and how to proceed.
- **Implementation:** If certificate pinning is being used, ensure that all relevant properties of the certificate are fully validated before the certificate is pinned, including the hostname.

## Related weaknesses

- CWE-923 (ChildOf)
- CWE-295 (ChildOf)

## Source

- [CWE-297 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/297.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
