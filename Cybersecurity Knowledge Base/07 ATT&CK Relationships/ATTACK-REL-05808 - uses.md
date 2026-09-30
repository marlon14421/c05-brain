---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0333"
target_object: "T1071.001"
stix_relationship_id: "relationship--62fbc8c0-0b5c-4650-9f63-696925d5626c"
---
# Relationship 5808: S0333 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0333 - UBoatRAT|S0333: UBoatRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[UBoatRAT](https://attack.mitre.org/software/S0333) has used HTTP for C2 communications.(Citation: PaloAlto UBoatRAT Nov 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--62fbc8c0-0b5c-4650-9f63-696925d5626c`.
