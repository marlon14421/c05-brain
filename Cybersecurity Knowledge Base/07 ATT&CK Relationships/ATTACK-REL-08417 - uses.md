---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0229"
target_object: "T1070"
stix_relationship_id: "relationship--31501f0f-e5be-4980-a2f1-b241d68f654c"
---
# Relationship 8417: S0229 — uses → T1070

**Source object:** [[01 ATT&CK/S0229 - Orz|S0229: Orz]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070 - Indicator Removal|T1070: Indicator Removal]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Orz](https://attack.mitre.org/software/S0229) can overwrite Registry settings to reduce its visibility on the victim.(Citation: Proofpoint Leviathan Oct 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--31501f0f-e5be-4980-a2f1-b241d68f654c`.
