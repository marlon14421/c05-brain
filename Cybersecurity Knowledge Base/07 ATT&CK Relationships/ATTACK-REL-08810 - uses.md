---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0114"
target_object: "T1053.005"
stix_relationship_id: "relationship--1ddc8822-55de-4671-8a73-c95d6383016f"
---
# Relationship 8810: G0114 — uses → T1053.005

**Source object:** [[01 ATT&CK/G0114 - Chimera|G0114: Chimera]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Chimera](https://attack.mitre.org/groups/G0114) has used scheduled tasks to invoke Cobalt Strike including through batch script schtasks /create /ru "SYSTEM" /tn "update" /tr "cmd /c c:\windows\temp\update.bat" /sc once /f /st and to maintain persistence.(Citation: Cycraft Chimera April 2020)(Citation: NCC Group Chimera January 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1ddc8822-55de-4671-8a73-c95d6383016f`.
