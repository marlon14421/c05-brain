---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0047"
target_object: "T1057"
stix_relationship_id: "relationship--dfe4c167-8e69-4b15-912f-ccd437674423"
---
# Relationship 8210: G0047 — uses → T1057

**Source object:** [[01 ATT&CK/G0047 - Gamaredon Group|G0047: Gamaredon Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Gamaredon Group](https://attack.mitre.org/groups/G0047) has used tools to enumerate processes on target hosts including Process Explorer.(Citation: Symantec Shuckworm January 2022)(Citation: Unit 42 Gamaredon February 2022)(Citation: SymantecCarbonBlack_ShuckwormUSB_Apr2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dfe4c167-8e69-4b15-912f-ccd437674423`.
