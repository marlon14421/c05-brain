---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0586"
target_object: "T1124"
stix_relationship_id: "relationship--bff9fc96-0b27-4c84-ad42-dcea53b907bf"
---
# Relationship 6934: S0586 — uses → T1124

**Source object:** [[01 ATT&CK/S0586 - TAINTEDSCRIBE|S0586: TAINTEDSCRIBE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1124 - System Time Discovery|T1124: System Time Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TAINTEDSCRIBE](https://attack.mitre.org/software/S0586) can execute GetLocalTime for time discovery.(Citation: CISA MAR-10288834-2.v1 TAINTEDSCRIBE MAY 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bff9fc96-0b27-4c84-ad42-dcea53b907bf`.
