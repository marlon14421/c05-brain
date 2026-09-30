---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1039"
target_object: "T1547.001"
stix_relationship_id: "relationship--d97c5cd6-97e9-4684-a598-1e31406c7e2c"
---
# Relationship 7987: G1039 — uses → T1547.001

**Source object:** [[01 ATT&CK/G1039 - RedCurl|G1039: RedCurl]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RedCurl](https://attack.mitre.org/groups/G1039) has established persistence by creating entries in `HKCU\Software\Microsoft\Windows\CurrentVersion\Run`.(Citation: group-ib_redcurl1)(Citation: group-ib_redcurl2)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d97c5cd6-97e9-4684-a598-1e31406c7e2c`.
