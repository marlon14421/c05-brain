---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0115"
target_object: "T1057"
stix_relationship_id: "relationship--84f40044-00a2-4015-be0d-1bb0107ef42b"
---
# Relationship 6304: S0115 — uses → T1057

**Source object:** [[01 ATT&CK/S0115 - Crimson|S0115: Crimson]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Crimson](https://attack.mitre.org/software/S0115) contains a command to list processes.(Citation: Proofpoint Operation Transparent Tribe March 2016)(Citation: Kaspersky Transparent Tribe August 2020)(Citation: Cisco Talos Transparent Tribe Education Campaign July 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--84f40044-00a2-4015-be0d-1bb0107ef42b`.
