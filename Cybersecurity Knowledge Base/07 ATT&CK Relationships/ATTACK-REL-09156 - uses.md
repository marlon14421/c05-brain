---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0051"
target_object: "T1547.001"
stix_relationship_id: "relationship--75b383eb-5483-4c44-a721-ee1cffa6edb7"
---
# Relationship 9156: G0051 — uses → T1547.001

**Source object:** [[01 ATT&CK/G0051 - FIN10|G0051: FIN10]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FIN10](https://attack.mitre.org/groups/G0051) has established persistence by using the Registry option in PowerShell Empire to add a Run key.(Citation: FireEye FIN10 June 2017)(Citation: Github PowerShell Empire)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--75b383eb-5483-4c44-a721-ee1cffa6edb7`.
