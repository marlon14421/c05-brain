---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1055"
target_object: "T1679"
stix_relationship_id: "relationship--4f5fa4dc-85fe-45df-a559-876f9a536450"
---
# Relationship 9804: G1055 — uses → T1679

**Source object:** [[01 ATT&CK/G1055 - VOID MANTICORE|G1055: VOID MANTICORE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1679 - Selective Exclusion|T1679: Selective Exclusion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[VOID MANTICORE](https://attack.mitre.org/groups/G1055) has avoided interacting with specific directories in order to reduce the likelihood of detection.(Citation: FBI IC3 Flash VOID MANTICORE Handala Hack March 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4f5fa4dc-85fe-45df-a559-876f9a536450`.
