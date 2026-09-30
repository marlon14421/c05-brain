---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0339"
target_object: "T1560.001"
stix_relationship_id: "relationship--96d8b8bb-3bdc-481e-a554-41790acac66a"
---
# Relationship 7053: S0339 — uses → T1560.001

**Source object:** [[01 ATT&CK/S0339 - Micropsia|S0339: Micropsia]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.001 - Archive via Utility|T1560.001: Archive via Utility]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Micropsia](https://attack.mitre.org/software/S0339) creates a RAR archive based on collected files on the victim's machine.(Citation: Radware Micropsia July 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--96d8b8bb-3bdc-481e-a554-41790acac66a`.
