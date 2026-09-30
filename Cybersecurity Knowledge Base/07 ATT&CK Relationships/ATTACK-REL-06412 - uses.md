---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0521"
target_object: "T1615"
stix_relationship_id: "relationship--14debfee-3a2d-4184-8f2a-bc07977ce909"
---
# Relationship 6412: S0521 — uses → T1615

**Source object:** [[01 ATT&CK/S0521 - BloodHound|S0521: BloodHound]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1615 - Group Policy Discovery|T1615: Group Policy Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BloodHound](https://attack.mitre.org/software/S0521) has the ability to collect local admin information via GPO.(Citation: GitHub Bloodhound)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--14debfee-3a2d-4184-8f2a-bc07977ce909`.
