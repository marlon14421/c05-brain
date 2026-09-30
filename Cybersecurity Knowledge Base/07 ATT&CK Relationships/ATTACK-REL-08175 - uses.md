---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0064"
target_object: "T1057"
stix_relationship_id: "relationship--771c349e-1b23-41ea-bcab-59bdbd6c935f"
---
# Relationship 8175: S0064 — uses → T1057

**Source object:** [[01 ATT&CK/S0064 - ELMER|S0064: ELMER]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ELMER](https://attack.mitre.org/software/S0064) is capable of performing process listings.(Citation: FireEye EPS Awakens Part 2)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--771c349e-1b23-41ea-bcab-59bdbd6c935f`.
