---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0521"
target_object: "T1482"
stix_relationship_id: "relationship--a79a17c4-02d1-463f-ac0a-d62b20d10b2f"
---
# Relationship 6601: S0521 — uses → T1482

**Source object:** [[01 ATT&CK/S0521 - BloodHound|S0521: BloodHound]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1482 - Domain Trust Discovery|T1482: Domain Trust Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BloodHound](https://attack.mitre.org/software/S0521) has the ability to map domain trusts and identify misconfigurations for potential abuse.(Citation: CrowdStrike BloodHound April 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a79a17c4-02d1-463f-ac0a-d62b20d10b2f`.
