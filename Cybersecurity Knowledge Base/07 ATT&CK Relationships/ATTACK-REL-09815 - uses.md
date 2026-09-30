---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1005"
target_object: "T1199"
stix_relationship_id: "relationship--b0e3680e-6099-4f33-a45e-5e938a7e7085"
---
# Relationship 9815: G1005 — uses → T1199

**Source object:** [[01 ATT&CK/G1005 - POLONIUM|G1005: POLONIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1199 - Trusted Relationship|T1199: Trusted Relationship]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[POLONIUM](https://attack.mitre.org/groups/G1005) has used compromised credentials from an IT company to target downstream customers including a law firm and aviation company.(Citation: Microsoft POLONIUM June 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b0e3680e-6099-4f33-a45e-5e938a7e7085`.
