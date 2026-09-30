---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0266"
target_object: "T1482"
stix_relationship_id: "relationship--f4d15148-3a41-4fbc-a42e-59379724acc5"
---
# Relationship 6104: S0266 — uses → T1482

**Source object:** [[01 ATT&CK/S0266 - TrickBot|S0266: TrickBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1482 - Domain Trust Discovery|T1482: Domain Trust Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TrickBot](https://attack.mitre.org/software/S0266) can gather information about domain trusts by utilizing [Nltest](https://attack.mitre.org/software/S0359).(Citation: Fortinet TrickBot)(Citation: Cyberreason Anchor December 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f4d15148-3a41-4fbc-a42e-59379724acc5`.
