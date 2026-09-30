---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1247"
target_object: "T1083"
stix_relationship_id: "relationship--165b726a-1e4c-49ce-af28-92586883dcdf"
---
# Relationship 8695: S1247 — uses → T1083

**Source object:** [[01 ATT&CK/S1247 - Embargo|S1247: Embargo]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Embargo](https://attack.mitre.org/software/S1247) has searched for folders, subfolders and other networked or mounted drives for follow on encryption actions.(Citation: Cyble Embargo Ransomware May 2024) [Embargo](https://attack.mitre.org/software/S1247) has also iterated device volumes using `FindFirstVolumeW()` and `FindNextVolumeW()` functions and then calls the `GetVolumePathNamesForVolumeNameW()` function to retrieve a list of drive letters and mounted folder paths for each specified volume.(Citation: Cyble Embargo Ransomware May 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--165b726a-1e4c-49ce-af28-92586883dcdf`.
