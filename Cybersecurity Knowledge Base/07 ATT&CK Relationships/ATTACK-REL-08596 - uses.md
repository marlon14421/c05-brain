---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0048"
target_object: "T1021.006"
stix_relationship_id: "relationship--cade04ba-4229-4655-9fe9-9e2d9b44536c"
---
# Relationship 8596: C0048 — uses → T1021.006

**Source object:** [[01 ATT&CK/C0048 - Operation MidnightEclipse|C0048: Operation MidnightEclipse]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.006 - Windows Remote Management|T1021.006: Windows Remote Management]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Operation MidnightEclipse](https://attack.mitre.org/campaigns/C0048), threat actors used WinRM to move laterally in targeted networks.(Citation: Volexity UPSTYLE 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cade04ba-4229-4655-9fe9-9e2d9b44536c`.
