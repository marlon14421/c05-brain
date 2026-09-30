---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1111"
target_object: "T1614"
stix_relationship_id: "relationship--309c4a23-21dd-41fa-9e0c-ce5c730455fe"
---
# Relationship 7141: S1111 — uses → T1614

**Source object:** [[01 ATT&CK/S1111 - DarkGate|S1111: DarkGate]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1614 - System Location Discovery|T1614: System Location Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DarkGate](https://attack.mitre.org/software/S1111) queries system locale information during execution.(Citation: Ensilo Darkgate 2018) Later versions of [DarkGate](https://attack.mitre.org/software/S1111) query GetSystemDefaultLCID for locale information to determine if the malware is executing in Russian-speaking countries.(Citation: Trellix Darkgate 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--309c4a23-21dd-41fa-9e0c-ce5c730455fe`.
