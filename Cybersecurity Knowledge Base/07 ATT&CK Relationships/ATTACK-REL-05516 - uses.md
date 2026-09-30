---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1196"
target_object: "T1070.004"
stix_relationship_id: "relationship--d86959da-9fa3-4d58-bfad-3e6b74a2ab01"
---
# Relationship 5516: S1196 — uses → T1070.004

**Source object:** [[01 ATT&CK/S1196 - Troll Stealer|S1196: Troll Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Troll Stealer](https://attack.mitre.org/software/S1196) creates and can execute a BAT script that will delete the malware.(Citation: S2W Troll Stealer 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d86959da-9fa3-4d58-bfad-3e6b74a2ab01`.
