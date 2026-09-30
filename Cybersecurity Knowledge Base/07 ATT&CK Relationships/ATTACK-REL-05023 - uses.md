---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0226"
target_object: "T1055.012"
stix_relationship_id: "relationship--72cf04c6-5e0b-4743-9386-88f1f1f45899"
---
# Relationship 5023: S0226 — uses → T1055.012

**Source object:** [[01 ATT&CK/S0226 - Smoke Loader|S0226: Smoke Loader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.012 - Process Hollowing|T1055.012: Process Hollowing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Smoke Loader](https://attack.mitre.org/software/S0226) spawns a new copy of c:\windows\syswow64\explorer.exe and then replaces the executable code in memory with malware.(Citation: Malwarebytes SmokeLoader 2016)(Citation: Microsoft Dofoil 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--72cf04c6-5e0b-4743-9386-88f1f1f45899`.
