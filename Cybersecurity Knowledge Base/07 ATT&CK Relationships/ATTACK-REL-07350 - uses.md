---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0379"
target_object: "T1547.004"
stix_relationship_id: "relationship--a01a08e6-3e5a-4674-9d8b-67395fdf9b55"
---
# Relationship 7350: S0379 — uses → T1547.004

**Source object:** [[01 ATT&CK/S0379 - Revenge RAT|S0379: Revenge RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.004 - Winlogon Helper DLL|T1547.004: Winlogon Helper DLL]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Revenge RAT](https://attack.mitre.org/software/S0379) creates a Registry key at HKCU\Software\Microsoft\Windows NT\CurrentVersion\Winlogon\Shell to survive a system reboot.(Citation: Cylance Shaheen Nov 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a01a08e6-3e5a-4674-9d8b-67395fdf9b55`.
