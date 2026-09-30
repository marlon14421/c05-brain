---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1151"
target_object: "T1561.002"
stix_relationship_id: "relationship--f419f8fb-8a3c-423d-8d01-20e99eb63693"
---
# Relationship 5242: S1151 — uses → T1561.002

**Source object:** [[01 ATT&CK/S1151 - ZeroCleare|S1151: ZeroCleare]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1561.002 - Disk Structure Wipe|T1561.002: Disk Structure Wipe]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ZeroCleare](https://attack.mitre.org/software/S1151) can corrupt the file system and wipe the system drive on targeted hosts.(Citation: Mandiant ROADSWEEP August 2022)(Citation: CISA Iran Albanian Attacks September 2022)(Citation: IBM ZeroCleare Wiper December 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f419f8fb-8a3c-423d-8d01-20e99eb63693`.
