---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1201"
target_object: "T1102.001"
stix_relationship_id: "relationship--6050e054-c759-4839-9ae4-5820ffcddaee"
---
# Relationship 7797: S1201 — uses → T1102.001

**Source object:** [[01 ATT&CK/S1201 - TRANSLATEXT|S1201: TRANSLATEXT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102.001 - Dead Drop Resolver|T1102.001: Dead Drop Resolver]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TRANSLATEXT](https://attack.mitre.org/software/S1201) has used a dead drop resolver to retrieve configurations and commands from a public blog site.(Citation: Zscaler Kimsuky TRANSLATEXT)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6050e054-c759-4839-9ae4-5820ffcddaee`.
