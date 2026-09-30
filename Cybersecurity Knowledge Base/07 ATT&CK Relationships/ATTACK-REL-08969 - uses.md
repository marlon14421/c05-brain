---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0167"
target_object: "T1547.001"
stix_relationship_id: "relationship--4696a49d-caa1-4746-b106-45faf327270b"
---
# Relationship 8969: S0167 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0167 - Matryoshka|S0167: Matryoshka]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Matryoshka](https://attack.mitre.org/software/S0167) can establish persistence by adding Registry Run keys.(Citation: ClearSky Wilted Tulip July 2017)(Citation: CopyKittens Nov 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4696a49d-caa1-4746-b106-45faf327270b`.
