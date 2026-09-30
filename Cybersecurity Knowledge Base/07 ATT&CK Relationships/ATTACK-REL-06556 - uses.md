---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1129"
target_object: "T1082"
stix_relationship_id: "relationship--0d853746-8d17-4d1a-be4a-6133e39a6c84"
---
# Relationship 6556: S1129 — uses → T1082

**Source object:** [[01 ATT&CK/S1129 - Akira|S1129: Akira]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Akira](https://attack.mitre.org/software/S1129) uses the GetSystemInfo Windows function to determine the number of processors on a victim machine.(Citation: Kersten Akira 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0d853746-8d17-4d1a-be4a-6133e39a6c84`.
