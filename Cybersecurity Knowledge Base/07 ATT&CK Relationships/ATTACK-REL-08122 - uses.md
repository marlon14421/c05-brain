---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1239"
target_object: "T1559"
stix_relationship_id: "relationship--ec6b9512-b23a-4aac-87b8-b5c4c19493de"
---
# Relationship 8122: S1239 — uses → T1559

**Source object:** [[01 ATT&CK/S1239 - TONESHELL|S1239: TONESHELL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1559 - Inter-Process Communication|T1559: Inter-Process Communication]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TONESHELL](https://attack.mitre.org/software/S1239) has facilitated inter-process communication between DLL components via the use of pipes.(Citation: Palo Alto Unit42 STATELY TAURUS TONESHELL September 2023) [TONESHELL](https://attack.mitre.org/software/S1239) has also created a reverse shell using two anonymous pipes to write data to stdin and read data from stdout and stderr.(Citation: 2025_IBM_PUBLOAD_TONESHELL_HIUPAN_CLAIMLOADER_MUSTANG PANDA)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ec6b9512-b23a-4aac-87b8-b5c4c19493de`.
