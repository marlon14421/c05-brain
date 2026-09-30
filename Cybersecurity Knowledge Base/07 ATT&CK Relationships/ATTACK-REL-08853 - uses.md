---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0003"
target_object: "S0002"
stix_relationship_id: "relationship--b08e3c96-25a7-412f-bbfb-63e010ef3891"
---
# Relationship 8853: G0003 — uses → S0002

**Source object:** [[01 ATT&CK/G0003 - Cleaver|G0003: Cleaver]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0002 - Mimikatz|S0002: Mimikatz]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Cylance Cleaver)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b08e3c96-25a7-412f-bbfb-63e010ef3891`.
