---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0332"
target_object: "T1529"
stix_relationship_id: "relationship--e87ba6d8-8228-45af-b235-54a0e0666a23"
---
# Relationship 6770: S0332 — uses → T1529

**Source object:** [[01 ATT&CK/S0332 - Remcos|S0332: Remcos]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1529 - System Shutdown-Reboot|T1529: System Shutdown/Reboot]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Remcos](https://attack.mitre.org/software/S0332) can shutdown and restart remote devices.(Citation: Fortinet Remcos Campaign NOV 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e87ba6d8-8228-45af-b235-54a0e0666a23`.
