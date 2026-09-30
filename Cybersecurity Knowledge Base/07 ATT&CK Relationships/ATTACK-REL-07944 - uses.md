---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0372"
target_object: "T1070.004"
stix_relationship_id: "relationship--20904798-df45-48a6-8428-9e4fb913f6ae"
---
# Relationship 7944: S0372 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0372 - LockerGoga|S0372: LockerGoga]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LockerGoga](https://attack.mitre.org/software/S0372) has been observed deleting its original launcher after execution.(Citation: CarbonBlack LockerGoga 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--20904798-df45-48a6-8428-9e4fb913f6ae`.
