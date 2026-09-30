---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0107"
target_object: "S0002"
stix_relationship_id: "relationship--eda182e5-ad1a-466b-8ede-664a2c778076"
---
# Relationship 5044: G0107 — uses → S0002

**Source object:** [[01 ATT&CK/G0107 - Whitefly|G0107: Whitefly]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0002 - Mimikatz|S0002: Mimikatz]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Symantec Whitefly March 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--eda182e5-ad1a-466b-8ede-664a2c778076`.
