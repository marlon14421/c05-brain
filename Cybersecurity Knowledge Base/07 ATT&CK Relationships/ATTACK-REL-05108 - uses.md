---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0266"
target_object: "T1497.003"
stix_relationship_id: "relationship--9e07c247-c778-496d-9972-6581f2d10c93"
---
# Relationship 5108: S0266 — uses → T1497.003

**Source object:** [[01 ATT&CK/S0266 - TrickBot|S0266: TrickBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.003 - Time Based Checks|T1497.003: Time Based Checks]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TrickBot](https://attack.mitre.org/software/S0266) has used printf and file I/O loops to delay process execution as part of API hammering.(Citation: Joe Sec Trickbot)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9e07c247-c778-496d-9972-6581f2d10c93`.
