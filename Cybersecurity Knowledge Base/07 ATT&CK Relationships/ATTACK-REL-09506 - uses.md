---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1228"
target_object: "T1053.005"
stix_relationship_id: "relationship--4cb2ba08-aebd-47f2-b1ea-9e28a2f64f77"
---
# Relationship 9506: S1228 — uses → T1053.005

**Source object:** [[01 ATT&CK/S1228 - PUBLOAD|S1228: PUBLOAD]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PUBLOAD](https://attack.mitre.org/software/S1228) has created scheduled tasks to maintain persistence with the command `schtasks.exe /F /Create /TN Microsoft_Licensing /sc minute /MO 1 /TR C:\\Users\\Public\\Libraries\...`(Citation: Cisco Talos MUSTANG PANDA PLUGX PUBLOAD MAY 2022)(Citation: Lab52 MUSTANG PANDA PUBLOAD MAY 2023)(Citation: 2022 November_TrendMicro_Earth Preta_Toneshell_Pubload)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4cb2ba08-aebd-47f2-b1ea-9e28a2f64f77`.
