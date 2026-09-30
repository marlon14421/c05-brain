---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9027"
target_object: "T1574.001"
stix_relationship_id: "relationship--819fa85e-041c-48a8-9d0c-2db2cd07047b"
---
# Relationship 7089: S9027 — uses → T1574.001

**Source object:** [[01 ATT&CK/S9027 - ANELLDR|S9027: ANELLDR]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.001 - DLL|T1574.001: DLL]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ANELLDR](https://attack.mitre.org/software/S9027) can use DLL sideloading from a legitimate application to initiate execution. (Citation: Trend Micro Earth Kasha Anel NOV 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--819fa85e-041c-48a8-9d0c-2db2cd07047b`.
