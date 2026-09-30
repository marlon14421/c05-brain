---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1021"
target_object: "T1574.001"
stix_relationship_id: "relationship--0577a90e-88f7-4b33-8dd2-f5e123f63be2"
---
# Relationship 7181: G1021 — uses → T1574.001

**Source object:** [[01 ATT&CK/G1021 - Cinnamon Tempest|G1021: Cinnamon Tempest]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.001 - DLL|T1574.001: DLL]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cinnamon Tempest](https://attack.mitre.org/groups/G1021) has used search order hijacking to launch [Cobalt Strike](https://attack.mitre.org/software/S0154) Beacons.(Citation: Microsoft Ransomware as a Service)(Citation: SecureWorks BRONZE STARLIGHT Ransomware Operations June 2022) [Cinnamon Tempest](https://attack.mitre.org/groups/G1021) has also abused legitimate executables to side-load weaponized DLLs.(Citation: Sygnia Emperor Dragonfly October 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0577a90e-88f7-4b33-8dd2-f5e123f63be2`.
