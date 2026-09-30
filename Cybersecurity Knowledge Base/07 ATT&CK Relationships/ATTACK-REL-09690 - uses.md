---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0036"
target_object: "T1021.004"
stix_relationship_id: "relationship--7db7f665-6e29-4789-8a3d-d6cb8d0af31e"
---
# Relationship 9690: G0036 — uses → T1021.004

**Source object:** [[01 ATT&CK/G0036 - GCMAN|G0036: GCMAN]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.004 - SSH|T1021.004: SSH]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GCMAN](https://attack.mitre.org/groups/G0036) uses Putty for lateral movement.(Citation: Securelist GCMAN)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7db7f665-6e29-4789-8a3d-d6cb8d0af31e`.
