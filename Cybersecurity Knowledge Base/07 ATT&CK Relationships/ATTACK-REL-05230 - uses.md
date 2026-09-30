---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0448"
target_object: "T1070"
stix_relationship_id: "relationship--811ba10b-6fe7-40d9-ab98-70d4135ac7cf"
---
# Relationship 5230: S0448 — uses → T1070

**Source object:** [[01 ATT&CK/S0448 - Rising Sun|S0448: Rising Sun]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070 - Indicator Removal|T1070: Indicator Removal]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Rising Sun](https://attack.mitre.org/software/S0448) can clear a memory blog in the process by overwriting it with junk bytes.(Citation: McAfee Sharpshooter December 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--811ba10b-6fe7-40d9-ab98-70d4135ac7cf`.
