---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1043"
target_object: "S0029"
stix_relationship_id: "relationship--bc56eda5-37e8-4478-a0e6-ea73fc6a57ed"
---
# Relationship 5411: G1043 — uses → S0029

**Source object:** [[01 ATT&CK/G1043 - BlackByte|G1043: BlackByte]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0029 - PsExec|S0029: PsExec]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BlackByte](https://attack.mitre.org/groups/G1043) has used [PsExec](https://attack.mitre.org/software/S0029) to remotely execute payloads during wormable ransomware execution.(Citation: Microsoft BlackByte 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bc56eda5-37e8-4478-a0e6-ea73fc6a57ed`.
