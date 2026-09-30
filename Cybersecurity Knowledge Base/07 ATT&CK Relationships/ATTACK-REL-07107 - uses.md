---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0019"
target_object: "S0456"
stix_relationship_id: "relationship--fd8fa359-c13e-4641-9c3e-d03218daee0c"
---
# Relationship 7107: G0019 — uses → S0456

**Source object:** [[01 ATT&CK/G0019 - Naikon|G0019: Naikon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0456 - Aria-body|S0456: Aria-body]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: CheckPoint Naikon May 2020)(Citation: Bitdefender Naikon April 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fd8fa359-c13e-4641-9c3e-d03218daee0c`.
