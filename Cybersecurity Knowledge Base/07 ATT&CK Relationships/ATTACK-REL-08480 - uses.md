---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0391"
target_object: "T1041"
stix_relationship_id: "relationship--7ac3aabb-ed01-4e7f-a247-e043261a1c3b"
---
# Relationship 8480: S0391 — uses → T1041

**Source object:** [[01 ATT&CK/S0391 - HAWKBALL|S0391: HAWKBALL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HAWKBALL](https://attack.mitre.org/software/S0391) has sent system information and files over the C2 channel.(Citation: FireEye HAWKBALL Jun 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7ac3aabb-ed01-4e7f-a247-e043261a1c3b`.
