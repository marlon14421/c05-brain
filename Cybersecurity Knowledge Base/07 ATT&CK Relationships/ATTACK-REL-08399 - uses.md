---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0623"
target_object: "T1068"
stix_relationship_id: "relationship--ae5fcb43-0f85-4c96-9b4b-65fe6a19e4fb"
---
# Relationship 8399: S0623 — uses → T1068

**Source object:** [[01 ATT&CK/S0623 - Siloscape|S0623: Siloscape]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1068 - Exploitation for Privilege Escalation|T1068: Exploitation for Privilege Escalation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Siloscape](https://attack.mitre.org/software/S0623) has leveraged a vulnerability in Windows containers to perform an [Escape to Host](https://attack.mitre.org/techniques/T1611).(Citation: Unit 42 Siloscape Jun 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ae5fcb43-0f85-4c96-9b4b-65fe6a19e4fb`.
