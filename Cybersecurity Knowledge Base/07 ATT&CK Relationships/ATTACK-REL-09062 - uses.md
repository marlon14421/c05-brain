---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1187"
target_object: "T1095"
stix_relationship_id: "relationship--e88cccd3-9559-4b33-adff-268e74bc932f"
---
# Relationship 9062: S1187 — uses → T1095

**Source object:** [[01 ATT&CK/S1187 - reGeorg|S1187: reGeorg]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1095 - Non-Application Layer Protocol|T1095: Non-Application Layer Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[reGeorg](https://attack.mitre.org/software/S1187) can tunnel TCP sessions into targeted networks.(Citation: Fortinet reGeorg MAR 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e88cccd3-9559-4b33-adff-268e74bc932f`.
