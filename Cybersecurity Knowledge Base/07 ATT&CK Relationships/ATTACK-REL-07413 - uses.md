---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0140"
target_object: "T1078.002"
stix_relationship_id: "relationship--5e6e745f-d756-4b6e-90e1-3adcf848570b"
---
# Relationship 7413: S0140 — uses → T1078.002

**Source object:** [[01 ATT&CK/S0140 - Shamoon|S0140: Shamoon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1078.002 - Domain Accounts|T1078.002: Domain Accounts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

If [Shamoon](https://attack.mitre.org/software/S0140) cannot access shares using current privileges, it attempts access using hard coded, domain-specific credentials gathered earlier in the intrusion.(Citation: FireEye Shamoon Nov 2016)(Citation: Unit 42 Shamoon3 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5e6e745f-d756-4b6e-90e1-3adcf848570b`.
