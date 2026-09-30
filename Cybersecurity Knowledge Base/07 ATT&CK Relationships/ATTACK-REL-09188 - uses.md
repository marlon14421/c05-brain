---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0006"
target_object: "S0100"
stix_relationship_id: "relationship--13984eec-6c33-4bab-a22c-5c061ddd6e44"
---
# Relationship 9188: G0006 — uses → S0100

**Source object:** [[01 ATT&CK/G0006 - APT1|G0006: APT1]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0100 - ipconfig|S0100: ipconfig]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Mandiant APT1)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--13984eec-6c33-4bab-a22c-5c061ddd6e44`.
