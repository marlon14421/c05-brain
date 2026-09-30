---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0035"
target_object: "S0029"
stix_relationship_id: "relationship--e068332d-0b1c-4aba-a60f-37c640e20d10"
---
# Relationship 6349: G0035 — uses → S0029

**Source object:** [[01 ATT&CK/G0035 - Dragonfly|G0035: Dragonfly]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0029 - PsExec|S0029: PsExec]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Secureworks IRON LIBERTY July 2019)(Citation: US-CERT TA18-074A)(Citation: Symantec Dragonfly Sept 2017)(Citation: Gigamon Berserk Bear October 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e068332d-0b1c-4aba-a60f-37c640e20d10`.
