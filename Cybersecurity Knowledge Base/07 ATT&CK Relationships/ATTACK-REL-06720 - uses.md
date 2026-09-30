---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0344"
target_object: "T1113"
stix_relationship_id: "relationship--ed8a6815-fd13-4e73-9b17-6b4025c0861c"
---
# Relationship 6720: S0344 — uses → T1113

**Source object:** [[01 ATT&CK/S0344 - Azorult|S0344: Azorult]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Azorult](https://attack.mitre.org/software/S0344) can capture screenshots of the victim’s machines.(Citation: Unit42 Azorult Nov 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ed8a6815-fd13-4e73-9b17-6b4025c0861c`.
