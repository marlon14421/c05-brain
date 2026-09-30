---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1002"
target_object: "T1068"
stix_relationship_id: "relationship--81399eeb-a9f0-4e55-baed-2be3829962fe"
---
# Relationship 9659: G1002 — uses → T1068

**Source object:** [[01 ATT&CK/G1002 - BITTER|G1002: BITTER]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1068 - Exploitation for Privilege Escalation|T1068: Exploitation for Privilege Escalation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BITTER](https://attack.mitre.org/groups/G1002) has exploited CVE-2021-1732 for privilege escalation.(Citation: DBAPPSecurity BITTER zero-day Feb 2021)(Citation: Microsoft CVE-2021-1732 Feb 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--81399eeb-a9f0-4e55-baed-2be3829962fe`.
