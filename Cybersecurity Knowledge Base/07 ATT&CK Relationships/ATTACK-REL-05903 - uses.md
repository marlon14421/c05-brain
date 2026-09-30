---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0115"
target_object: "T1113"
stix_relationship_id: "relationship--513f6b4c-c9b1-4339-910e-376b2a908689"
---
# Relationship 5903: G0115 — uses → T1113

**Source object:** [[01 ATT&CK/G0115 - GOLD SOUTHFIELD|G0115: GOLD SOUTHFIELD]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GOLD SOUTHFIELD](https://attack.mitre.org/groups/G0115) has used the remote monitoring and management tool ConnectWise to obtain screen captures from victim's machines.(Citation: Tetra Defense Sodinokibi March 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--513f6b4c-c9b1-4339-910e-376b2a908689`.
