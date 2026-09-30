---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0054"
target_object: "T1082"
stix_relationship_id: "relationship--e20b57e5-c010-4b9e-a04e-660daa8b5c87"
---
# Relationship 8229: G0054 — uses → T1082

**Source object:** [[01 ATT&CK/G0054 - Sowbug|G0054: Sowbug]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sowbug](https://attack.mitre.org/groups/G0054) obtained OS version and hardware configuration from a victim.(Citation: Symantec Sowbug Nov 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e20b57e5-c010-4b9e-a04e-660daa8b5c87`.
