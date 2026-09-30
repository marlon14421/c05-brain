---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0013"
target_object: "T1083"
stix_relationship_id: "relationship--07702379-2d40-48ae-a077-d68e0da5e4be"
---
# Relationship 7485: S0013 — uses → T1083

**Source object:** [[01 ATT&CK/S0013 - PlugX|S0013: PlugX]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PlugX](https://attack.mitre.org/software/S0013) has a module to enumerate drives and find files recursively.(Citation: Eset PlugX Korplug Mustang Panda March 2022)(Citation: Cisco Talos MUSTANG PANDA PLUGX PUBLOAD MAY 2022)(Citation: CIRCL PlugX March 2013)(Citation: Proofpoint TA416 Europe March 2022) [PlugX](https://attack.mitre.org/software/S0013) has also checked the path from which it is running for specific parameters prior to execution. (Citation: Eset PlugX Korplug Mustang Panda March 2022)(Citation: DOJ Affidavit Search and Seizure PlugX December 2024)(Citation: Sophos Mustang Panda PLUGX)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--07702379-2d40-48ae-a077-d68e0da5e4be`.
