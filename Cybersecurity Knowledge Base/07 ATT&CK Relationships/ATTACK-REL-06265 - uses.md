---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1220"
target_object: "T1027.013"
stix_relationship_id: "relationship--35de5c62-00aa-4f6d-a0d8-399cda3bed36"
---
# Relationship 6265: S1220 — uses → T1027.013

**Source object:** [[01 ATT&CK/S1220 - MEDUSA|S1220: MEDUSA]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MEDUSA](https://attack.mitre.org/software/S1220) can XOR encrypt configuration strings.(Citation: Google Cloud Mandiant UNC3886 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--35de5c62-00aa-4f6d-a0d8-399cda3bed36`.
