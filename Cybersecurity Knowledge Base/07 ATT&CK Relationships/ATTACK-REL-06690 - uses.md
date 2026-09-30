---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0521"
target_object: "T1087.002"
stix_relationship_id: "relationship--4e2594cc-f6e0-4153-b878-930bc03fc0ad"
---
# Relationship 6690: S0521 — uses → T1087.002

**Source object:** [[01 ATT&CK/S0521 - BloodHound|S0521: BloodHound]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087.002 - Domain Account|T1087.002: Domain Account]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BloodHound](https://attack.mitre.org/software/S0521) can collect information about domain users, including identification of domain admin accounts.(Citation: CrowdStrike BloodHound April 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4e2594cc-f6e0-4153-b878-930bc03fc0ad`.
