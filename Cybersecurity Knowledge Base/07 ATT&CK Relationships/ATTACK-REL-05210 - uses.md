---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0197"
target_object: "T1074.001"
stix_relationship_id: "relationship--f38ae08a-0d59-41e9-a4ca-891a04297299"
---
# Relationship 5210: S0197 — uses → T1074.001

**Source object:** [[01 ATT&CK/S0197 - PUNCHTRACK|S0197: PUNCHTRACK]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PUNCHTRACK](https://attack.mitre.org/software/S0197) aggregates collected data in a tmp file.(Citation: FireEye Know Your Enemy FIN8 Aug 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f38ae08a-0d59-41e9-a4ca-891a04297299`.
