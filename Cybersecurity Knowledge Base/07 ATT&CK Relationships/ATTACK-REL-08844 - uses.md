---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0616"
target_object: "T1680"
stix_relationship_id: "relationship--e69dfb2f-c89b-4167-9165-4f3026b32ad7"
---
# Relationship 8844: S0616 — uses → T1680

**Source object:** [[01 ATT&CK/S0616 - DEATHRANSOM|S0616: DEATHRANSOM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1680 - Local Storage Discovery|T1680: Local Storage Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DEATHRANSOM](https://attack.mitre.org/software/S0616) can enumerate logical drives on a target system.(Citation: FireEye FiveHands April 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e69dfb2f-c89b-4167-9165-4f3026b32ad7`.
