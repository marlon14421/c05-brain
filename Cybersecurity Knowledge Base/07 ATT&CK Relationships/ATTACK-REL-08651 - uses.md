---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0266"
target_object: "T1087.001"
stix_relationship_id: "relationship--76d7d7fa-94a4-4fa6-9fd2-e9af9ab0f356"
---
# Relationship 8651: S0266 — uses → T1087.001

**Source object:** [[01 ATT&CK/S0266 - TrickBot|S0266: TrickBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087.001 - Local Account|T1087.001: Local Account]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TrickBot](https://attack.mitre.org/software/S0266) collects the users of the system.(Citation: S2 Grupo TrickBot June 2017)(Citation: Trend Micro Trickbot Nov 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--76d7d7fa-94a4-4fa6-9fd2-e9af9ab0f356`.
