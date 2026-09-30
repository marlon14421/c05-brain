---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0092"
target_object: "T1588.002"
stix_relationship_id: "relationship--3e6b6ed9-4c28-4dd0-903a-360f57864de4"
---
# Relationship 8714: G0092 — uses → T1588.002

**Source object:** [[01 ATT&CK/G0092 - TA505|G0092: TA505]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.002 - Tool|T1588.002: Tool]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TA505](https://attack.mitre.org/groups/G0092) has used a variety of tools in their operations, including [AdFind](https://attack.mitre.org/software/S0552), [BloodHound](https://attack.mitre.org/software/S0521), [Mimikatz](https://attack.mitre.org/software/S0002), and [PowerSploit](https://attack.mitre.org/software/S0194).(Citation: NCC Group TA505)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3e6b6ed9-4c28-4dd0-903a-360f57864de4`.
