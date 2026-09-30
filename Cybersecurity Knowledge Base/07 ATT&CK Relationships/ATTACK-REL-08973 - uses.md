---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1186"
target_object: "T1140"
stix_relationship_id: "relationship--20c3b1d7-7702-4a0b-9902-dece6e413bf1"
---
# Relationship 8973: S1186 — uses → T1140

**Source object:** [[01 ATT&CK/S1186 - Line Dancer|S1186: Line Dancer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Line Dancer](https://attack.mitre.org/software/S1186) shellcode payloads are base64 encoded when transmitted to compromised devices.(Citation: CCCS ArcaneDoor 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--20c3b1d7-7702-4a0b-9902-dece6e413bf1`.
