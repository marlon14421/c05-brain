---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-306"
status: "Draft"
---
# CWE-306: Missing Authentication for Critical Function

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Cloud Computing, ICS/OT

## Description

The product does not perform any authentication for functionality that requires a provable user identity or consumes a significant amount of resources.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** For any security checks that are performed on the client side, ensure that these checks are duplicated on the server side, in order to avoid CWE-602. Attackers can bypass the client-side checks by modifying values after the checks have been performed, or by changing the client to remove the client-side checks entirely. Then, these modified values would be submitted to the server.
- **Implementation:** When storing data in the cloud (e.g., S3 buckets, Azure blobs, Google Cloud Storage, etc.), use the provider's controls to require strong authentication for users who should be allowed to access the data [REF-1297] [REF-1298] [REF-1302].

## Related weaknesses

- CWE-287 (ChildOf)
- CWE-287 (ChildOf)

## Source

- [CWE-306 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/306.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
