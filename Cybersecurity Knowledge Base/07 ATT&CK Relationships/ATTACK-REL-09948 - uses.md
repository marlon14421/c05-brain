---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0595"
target_object: "T1486"
stix_relationship_id: "relationship--02c4488b-6041-4222-9363-18a63ce3b835"
---
# Relationship 9948: S0595 — uses → T1486

**Source object:** [[01 ATT&CK/S0595 - ThiefQuest|S0595: ThiefQuest]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ThiefQuest](https://attack.mitre.org/software/S0595) encrypts a set of file extensions on a host, deletes the original files, and provides a ransom note with no contact information.(Citation: wardle evilquest partii)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--02c4488b-6041-4222-9363-18a63ce3b835`.
