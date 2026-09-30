---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0459"
target_object: "T1036.005"
stix_relationship_id: "relationship--08057442-4b2c-4841-b351-8813431704e9"
---
# Relationship 9430: S0459 — uses → T1036.005

**Source object:** [[01 ATT&CK/S0459 - MechaFlounder|S0459: MechaFlounder]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MechaFlounder](https://attack.mitre.org/software/S0459) has been downloaded as a file named lsass.exe, which matches the legitimate Windows file.(Citation: Unit 42 MechaFlounder March 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--08057442-4b2c-4841-b351-8813431704e9`.
