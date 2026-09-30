---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1048"
target_object: "T1083"
stix_relationship_id: "relationship--0c75b350-2996-47f8-9e01-38b7cf53481c"
---
# Relationship 5368: G1048 — uses → T1083

**Source object:** [[01 ATT&CK/G1048 - UNC3886|G1048: UNC3886]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[UNC3886](https://attack.mitre.org/groups/G1048) has used `vmtoolsd.exe` to enumerate files on guest machines.(Citation: Google Cloud Threat Intelligence ESXi VIBs 2022)(Citation: Google Cloud Threat Intelligence VMWare ESXi Zero-Day 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0c75b350-2996-47f8-9e01-38b7cf53481c`.
