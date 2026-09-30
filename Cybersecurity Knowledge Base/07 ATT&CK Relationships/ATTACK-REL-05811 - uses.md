---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0553"
target_object: "T1547.001"
stix_relationship_id: "relationship--5d036e42-7ce2-499d-b693-12504c8615ca"
---
# Relationship 5811: S0553 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0553 - MoleNet|S0553: MoleNet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MoleNet](https://attack.mitre.org/software/S0553) can achieve persitence on the infected machine by setting the Registry run key.(Citation: Cybereason Molerats Dec 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5d036e42-7ce2-499d-b693-12504c8615ca`.
