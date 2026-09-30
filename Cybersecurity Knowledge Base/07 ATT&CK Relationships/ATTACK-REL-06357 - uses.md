---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0120"
target_object: "S0284"
stix_relationship_id: "relationship--17fc72c1-83be-4dce-a795-d2a36e6354ca"
---
# Relationship 6357: G0120 — uses → S0284

**Source object:** [[01 ATT&CK/G0120 - Evilnum|G0120: Evilnum]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0284 - More_eggs|S0284: More_eggs]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: ESET EvilNum July 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--17fc72c1-83be-4dce-a795-d2a36e6354ca`.
