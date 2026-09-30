---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0642"
target_object: "T1560.002"
stix_relationship_id: "relationship--7b05bdd0-2241-4b2d-a5a0-0531edca6311"
---
# Relationship 8888: S0642 — uses → T1560.002

**Source object:** [[01 ATT&CK/S0642 - BADFLICK|S0642: BADFLICK]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.002 - Archive via Library|T1560.002: Archive via Library]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BADFLICK](https://attack.mitre.org/software/S0642) has compressed data using the aPLib compression library.(Citation: Accenture MUDCARP March 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7b05bdd0-2241-4b2d-a5a0-0531edca6311`.
