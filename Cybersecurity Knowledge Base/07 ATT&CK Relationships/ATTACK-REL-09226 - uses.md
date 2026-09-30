---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0385"
target_object: "T1082"
stix_relationship_id: "relationship--005cbf7d-9d0b-443b-91db-7b148a1eb55b"
---
# Relationship 9226: S0385 — uses → T1082

**Source object:** [[01 ATT&CK/S0385 - njRAT|S0385: njRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[njRAT](https://attack.mitre.org/software/S0385) enumerates the victim operating system and computer name during the initial infection.(Citation: Fidelis njRAT June 2013)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--005cbf7d-9d0b-443b-91db-7b148a1eb55b`.
