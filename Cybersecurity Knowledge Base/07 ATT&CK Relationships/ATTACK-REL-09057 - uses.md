---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0064"
target_object: "S0129"
stix_relationship_id: "relationship--253ab30c-ec7c-42bc-a27d-984722c59a98"
---
# Relationship 9057: G0064 — uses → S0129

**Source object:** [[01 ATT&CK/G0064 - APT33|G0064: APT33]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0129 - AutoIt backdoor|S0129: AutoIt backdoor]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Symantec Elfin Mar 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--253ab30c-ec7c-42bc-a27d-984722c59a98`.
