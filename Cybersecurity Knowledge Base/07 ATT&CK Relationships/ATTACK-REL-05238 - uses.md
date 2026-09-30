---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1039"
target_object: "T1102"
stix_relationship_id: "relationship--63b1af38-765d-4181-add0-dbd3f31941ff"
---
# Relationship 5238: S1039 — uses → T1102

**Source object:** [[01 ATT&CK/S1039 - Bumblebee|S1039: Bumblebee]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102 - Web Service|T1102: Web Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Bumblebee](https://attack.mitre.org/software/S1039) has been downloaded to victim's machines from OneDrive.(Citation: Proofpoint Bumblebee April 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--63b1af38-765d-4181-add0-dbd3f31941ff`.
