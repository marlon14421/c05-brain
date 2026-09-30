---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0376"
target_object: "T1686"
stix_relationship_id: "relationship--4c17948b-96f6-4f0f-ac37-7393ea5d832b"
---
# Relationship 5803: S0376 — uses → T1686

**Source object:** [[01 ATT&CK/S0376 - HOPLIGHT|S0376: HOPLIGHT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1686 - Disable or Modify System Firewall|T1686: Disable or Modify System Firewall]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HOPLIGHT](https://attack.mitre.org/software/S0376) has modified the firewall using [netsh](https://attack.mitre.org/software/S0108).(Citation: US-CERT HOPLIGHT Apr 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4c17948b-96f6-4f0f-ac37-7393ea5d832b`.
