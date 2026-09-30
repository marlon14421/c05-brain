---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9025"
target_object: "T1127.001"
stix_relationship_id: "relationship--24744689-49f7-4d67-9214-cb123bc59a97"
---
# Relationship 9686: S9025 — uses → T1127.001

**Source object:** [[01 ATT&CK/S9025 - NOOPLDR|S9025: NOOPLDR]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1127.001 - MSBuild|T1127.001: MSBuild]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NOOPLDR](https://attack.mitre.org/software/S9025) can be executed via MSBuild.(Citation: JPCERT MirrorFace JUL 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--24744689-49f7-4d67-9214-cb123bc59a97`.
