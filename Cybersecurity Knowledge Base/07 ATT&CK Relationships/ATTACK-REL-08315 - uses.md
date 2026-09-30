---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0163"
target_object: "T1113"
stix_relationship_id: "relationship--fc67e15c-ae09-45e1-925f-8a6b0e8ca4ab"
---
# Relationship 8315: S0163 — uses → T1113

**Source object:** [[01 ATT&CK/S0163 - Janicab|S0163: Janicab]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Janicab](https://attack.mitre.org/software/S0163) captured screenshots and sent them out to a C2 server.(Citation: f-secure janicab)(Citation: Janicab)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fc67e15c-ae09-45e1-925f-8a6b0e8ca4ab`.
