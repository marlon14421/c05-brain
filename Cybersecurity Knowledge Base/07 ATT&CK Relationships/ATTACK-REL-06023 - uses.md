---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1247"
target_object: "T1068"
stix_relationship_id: "relationship--0cdabb4e-45d7-4307-818e-0647c08a8b45"
---
# Relationship 6023: S1247 — uses → T1068

**Source object:** [[01 ATT&CK/S1247 - Embargo|S1247: Embargo]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1068 - Exploitation for Privilege Escalation|T1068: Exploitation for Privilege Escalation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Embargo](https://attack.mitre.org/software/S1247) has leveraged MS4Killer to deliver a vulnerable driver to the victim device, sometimes referred to as Bring Your Own Vulnerable Driver (BYOVD).(Citation: ESET Embargo Ransomware October 2024) [Embargo](https://attack.mitre.org/software/S1247) has utilized the vulnerable driver probmon.sys version 3.0.0.4 which had a revoked certificated from “ITM System Co.,LTD.”(Citation: ESET Embargo Ransomware October 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0cdabb4e-45d7-4307-818e-0647c08a8b45`.
