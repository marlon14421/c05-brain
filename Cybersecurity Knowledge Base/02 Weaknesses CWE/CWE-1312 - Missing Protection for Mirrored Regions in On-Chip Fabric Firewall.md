---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-1312"
status: "Draft"
---
# CWE-1312: Missing Protection for Mirrored Regions in On-Chip Fabric Firewall

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Not OS-Specific, Not Architecture-Specific, Not Technology-Specific

## Description

The firewall in an on-chip fabric protects the main addressed region, but it does not protect any mirrored memory or memory-mapped-IO (MMIO) regions.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** The fabric firewall should apply the same protections as the original region to the mirrored regions.
- **Implementation:** The fabric firewall should apply the same protections as the original region to the mirrored regions.

## Related weaknesses

- CWE-284 (ChildOf)
- CWE-1251 (PeerOf)

## Source

- [CWE-1312 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/1312.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
