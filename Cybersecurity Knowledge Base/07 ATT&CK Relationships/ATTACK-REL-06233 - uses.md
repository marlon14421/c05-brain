---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0012"
target_object: "T1497.002"
stix_relationship_id: "relationship--118b2047-826a-4ab0-94b8-69d35a4c8592"
---
# Relationship 6233: G0012 — uses → T1497.002

**Source object:** [[01 ATT&CK/G0012 - Darkhotel|G0012: Darkhotel]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.002 - User Activity Based Checks|T1497.002: User Activity Based Checks]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Darkhotel](https://attack.mitre.org/groups/G0012) has used malware that repeatedly checks the mouse cursor position to determine if a real user is on the system.(Citation: Lastline DarkHotel Just In Time Decryption Nov 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--118b2047-826a-4ab0-94b8-69d35a4c8592`.
