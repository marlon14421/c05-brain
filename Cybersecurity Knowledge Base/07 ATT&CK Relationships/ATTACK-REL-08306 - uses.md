---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0223"
target_object: "T1070.004"
stix_relationship_id: "relationship--c18652f6-e25c-4e01-bec2-04204a50cf23"
---
# Relationship 8306: S0223 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0223 - POWERSTATS|S0223: POWERSTATS]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[POWERSTATS](https://attack.mitre.org/software/S0223) can delete all files on the C:\, D:\, E:\ and, F:\ drives using [PowerShell](https://attack.mitre.org/techniques/T1059/001) Remove-Item commands.(Citation: FireEye MuddyWater Mar 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c18652f6-e25c-4e01-bec2-04204a50cf23`.
