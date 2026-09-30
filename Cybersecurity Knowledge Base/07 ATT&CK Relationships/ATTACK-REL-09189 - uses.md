---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0203"
target_object: "T1113"
stix_relationship_id: "relationship--a883e4c6-6a40-4660-9120-b2430099ccb6"
---
# Relationship 9189: S0203 — uses → T1113

**Source object:** [[01 ATT&CK/S0203 - Hydraq|S0203: Hydraq]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Hydraq](https://attack.mitre.org/software/S0203) includes a component based on the code of VNC that can stream a live feed of the desktop of an infected host.(Citation: Symantec Hydraq Jan 2010)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a883e4c6-6a40-4660-9120-b2430099ccb6`.
