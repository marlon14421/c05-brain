---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0570"
target_object: "T1027.013"
stix_relationship_id: "relationship--54f9c8a5-0677-4be8-bd72-a6a096be00bd"
---
# Relationship 6743: S0570 — uses → T1027.013

**Source object:** [[01 ATT&CK/S0570 - BitPaymer|S0570: BitPaymer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BitPaymer](https://attack.mitre.org/software/S0570) has used RC4-encrypted strings and string hashes to avoid identifiable strings within the binary.(Citation: Crowdstrike Indrik November 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--54f9c8a5-0677-4be8-bd72-a6a096be00bd`.
