---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-312"
status: "Draft"
---
# CWE-312: Cleartext Storage of Sensitive Information

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Cloud Computing, ICS/OT, Mobile

## Description

The product stores sensitive information in cleartext within a resource that might be accessible to another control sphere.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Implementation:** When storing data in the cloud (e.g., S3 buckets, Azure blobs, Google Cloud Storage, etc.), use the provider's controls to encrypt the data at rest. [REF-1297] [REF-1299] [REF-1301]
- **Implementation:** In some systems/environments such as cloud, the use of "double encryption" (at both the software and hardware layer) might be required, and the developer might be solely responsible for both layers, instead of shared responsibility with the administrator of the broader system/environment.

## Related weaknesses

- CWE-311 (ChildOf)
- CWE-311 (ChildOf)
- CWE-922 (ChildOf)

## Source

- [CWE-312 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/312.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
