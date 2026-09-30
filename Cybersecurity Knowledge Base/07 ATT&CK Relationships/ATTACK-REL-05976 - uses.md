---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0034"
target_object: "S0687"
stix_relationship_id: "relationship--6409dbdd-d253-4b4a-8740-8b9592c75f25"
---
# Relationship 5976: G0034 — uses → S0687

**Source object:** [[01 ATT&CK/G0034 - Sandworm Team|G0034: Sandworm Team]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0687 - Cyclops Blink|S0687: Cyclops Blink]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: NCSC CISA Cyclops Blink Advisory February 2022)(Citation: Trend Micro Cyclops Blink March 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6409dbdd-d253-4b4a-8740-8b9592c75f25`.
