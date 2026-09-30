---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1180"
target_object: "T1112"
stix_relationship_id: "relationship--c5c1bf20-d215-41cb-a5d2-4388a1ca5e59"
---
# Relationship 6124: S1180 — uses → T1112

**Source object:** [[01 ATT&CK/S1180 - BlackByte Ransomware|S1180: BlackByte Ransomware]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BlackByte Ransomware](https://attack.mitre.org/software/S1180) modifies the victim Registry to prevent system recovery.(Citation: Trustwave BlackByte 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c5c1bf20-d215-41cb-a5d2-4388a1ca5e59`.
