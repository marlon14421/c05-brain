---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0241"
target_object: "T1105"
stix_relationship_id: "relationship--d8d6740b-a359-4f5c-b7d4-2189eea77892"
---
# Relationship 6589: S0241 — uses → T1105

**Source object:** [[01 ATT&CK/S0241 - RATANKBA|S0241: RATANKBA]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RATANKBA](https://attack.mitre.org/software/S0241) uploads and downloads information.(Citation: Lazarus RATANKBA)(Citation: RATANKBA)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d8d6740b-a359-4f5c-b7d4-2189eea77892`.
