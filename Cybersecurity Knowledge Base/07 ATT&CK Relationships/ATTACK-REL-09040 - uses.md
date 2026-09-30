---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0654"
target_object: "T1027.003"
stix_relationship_id: "relationship--b0557c84-d4c5-4016-8381-f419d18f2d47"
---
# Relationship 9040: S0654 — uses → T1027.003

**Source object:** [[01 ATT&CK/S0654 - ProLock|S0654: ProLock]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.003 - Steganography|T1027.003: Steganography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ProLock](https://attack.mitre.org/software/S0654) can use .jpg and .bmp files to store its payload.(Citation: Group IB Ransomware September 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b0557c84-d4c5-4016-8381-f419d18f2d47`.
