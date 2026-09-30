---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0666"
target_object: "T1082"
stix_relationship_id: "relationship--86b8a22d-66c3-4b54-82fd-662455d0e2c5"
---
# Relationship 5874: S0666 — uses → T1082

**Source object:** [[01 ATT&CK/S0666 - Gelsemium|S0666: Gelsemium]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Gelsemium](https://attack.mitre.org/software/S0666) can determine the operating system and whether a targeted machine has a 32 or 64 bit architecture.(Citation: ESET Gelsemium June 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--86b8a22d-66c3-4b54-82fd-662455d0e2c5`.
