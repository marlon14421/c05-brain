---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1044"
target_object: "T1057"
stix_relationship_id: "relationship--5f7c7285-daa4-499d-b9d6-c1028e5148d4"
---
# Relationship 6070: S1044 — uses → T1057

**Source object:** [[01 ATT&CK/S1044 - FunnyDream|S1044: FunnyDream]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FunnyDream](https://attack.mitre.org/software/S1044) has the ability to discover processes, including `Bka.exe` and `BkavUtil.exe`.(Citation: Bitdefender FunnyDream Campaign November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5f7c7285-daa4-499d-b9d6-c1028e5148d4`.
