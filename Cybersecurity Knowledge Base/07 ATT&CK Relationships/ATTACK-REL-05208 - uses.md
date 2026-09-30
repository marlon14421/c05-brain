---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1055"
target_object: "T1589"
stix_relationship_id: "relationship--19888971-2a8b-4a33-8b80-e02ca4662f8b"
---
# Relationship 5208: G1055 — uses → T1589

**Source object:** [[01 ATT&CK/G1055 - VOID MANTICORE|G1055: VOID MANTICORE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1589 - Gather Victim Identity Information|T1589: Gather Victim Identity Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[VOID MANTICORE](https://attack.mitre.org/groups/G1055) has gathered details on their intended victims to aid in social engineering efforts for leveraging tailored themes of attacks.(Citation: FBI IC3 Flash VOID MANTICORE Handala Hack March 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--19888971-2a8b-4a33-8b80-e02ca4662f8b`.
