---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1134"
target_object: "T1561.001"
stix_relationship_id: "relationship--11f7aee6-3479-4756-8300-741e28e75142"
---
# Relationship 7729: S1134 — uses → T1561.001

**Source object:** [[01 ATT&CK/S1134 - DEADWOOD|S1134: DEADWOOD]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1561.001 - Disk Content Wipe|T1561.001: Disk Content Wipe]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DEADWOOD](https://attack.mitre.org/software/S1134) deletes files following overwriting them with random data.(Citation: SentinelOne Agrius 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--11f7aee6-3479-4756-8300-741e28e75142`.
