---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0516"
target_object: "T1087.002"
stix_relationship_id: "relationship--0cf8d5da-a127-4b48-bbf9-e5a0376033b4"
---
# Relationship 7080: S0516 — uses → T1087.002

**Source object:** [[01 ATT&CK/S0516 - SoreFang|S0516: SoreFang]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087.002 - Domain Account|T1087.002: Domain Account]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SoreFang](https://attack.mitre.org/software/S0516) can enumerate domain accounts via net.exe user /domain .(Citation: CISA SoreFang July 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0cf8d5da-a127-4b48-bbf9-e5a0376033b4`.
