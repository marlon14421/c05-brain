---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1047"
target_object: "T1574.001"
stix_relationship_id: "relationship--1236d556-1b4a-4d0f-96b2-cf036b30ca17"
---
# Relationship 7778: G1047 — uses → T1574.001

**Source object:** [[01 ATT&CK/G1047 - Velvet Ant|G1047: Velvet Ant]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.001 - DLL|T1574.001: DLL]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Velvet Ant](https://attack.mitre.org/groups/G1047) has used malicious DLLs executed via legitimate EXE files through DLL search order hijacking to launch follow-on payloads such as [PlugX](https://attack.mitre.org/software/S0013).(Citation: Sygnia VelvetAnt 2024A)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1236d556-1b4a-4d0f-96b2-cf036b30ca17`.
