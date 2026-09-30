---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0137"
target_object: "T1218.011"
stix_relationship_id: "relationship--ccc38b61-c517-4186-909a-760f12ef65e8"
---
# Relationship 8326: S0137 — uses → T1218.011

**Source object:** [[01 ATT&CK/S0137 - CORESHELL|S0137: CORESHELL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.011 - Rundll32|T1218.011: Rundll32]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CORESHELL](https://attack.mitre.org/software/S0137) is installed via execution of rundll32 with an export named "init" or "InitW."(Citation: Microsoft SIR Vol 19)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ccc38b61-c517-4186-909a-760f12ef65e8`.
