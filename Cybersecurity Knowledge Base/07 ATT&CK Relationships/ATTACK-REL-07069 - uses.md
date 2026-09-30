---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1002"
target_object: "T1568"
stix_relationship_id: "relationship--24fadb92-7a18-450b-b4ca-f5dd019ce54c"
---
# Relationship 7069: G1002 — uses → T1568

**Source object:** [[01 ATT&CK/G1002 - BITTER|G1002: BITTER]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1568 - Dynamic Resolution|T1568: Dynamic Resolution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BITTER](https://attack.mitre.org/groups/G1002) has used DDNS for C2 communications.(Citation: Forcepoint BITTER Pakistan Oct 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--24fadb92-7a18-450b-b4ca-f5dd019ce54c`.
