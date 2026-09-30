---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0694"
target_object: "T1497.003"
stix_relationship_id: "relationship--c1db186f-0c57-4c10-b858-3ecc792bb224"
---
# Relationship 7297: S0694 — uses → T1497.003

**Source object:** [[01 ATT&CK/S0694 - DRATzarus|S0694: DRATzarus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.003 - Time Based Checks|T1497.003: Time Based Checks]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DRATzarus](https://attack.mitre.org/software/S0694) can use the `GetTickCount` and `GetSystemTimeAsFileTime` API calls to measure function timing.(Citation: ClearSky Lazarus Aug 2020) [DRATzarus](https://attack.mitre.org/software/S0694) can also remotely shut down into sleep mode under specific conditions to evade detection.(Citation: ClearSky Lazarus Aug 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c1db186f-0c57-4c10-b858-3ecc792bb224`.
