---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0372"
target_object: "T1486"
stix_relationship_id: "relationship--31daba72-fb27-45a9-9224-991032b605a8"
---
# Relationship 9312: S0372 — uses → T1486

**Source object:** [[01 ATT&CK/S0372 - LockerGoga|S0372: LockerGoga]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LockerGoga](https://attack.mitre.org/software/S0372) has encrypted files, including core Windows OS files, using RSA-OAEP MGF1 and then demanded Bitcoin be paid for the decryption key.(Citation: CarbonBlack LockerGoga 2019)(Citation: Unit42 LockerGoga 2019)(Citation: Wired Lockergoga 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--31daba72-fb27-45a9-9224-991032b605a8`.
