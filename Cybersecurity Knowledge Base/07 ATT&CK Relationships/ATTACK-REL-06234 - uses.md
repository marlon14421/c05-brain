---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0650"
target_object: "T1070.004"
stix_relationship_id: "relationship--ff2b5737-6a87-4ffb-b61a-89d8f21615b1"
---
# Relationship 6234: S0650 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0650 - QakBot|S0650: QakBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[QakBot](https://attack.mitre.org/software/S0650) can delete folders and files including overwriting its executable with legitimate programs.(Citation: Kroll Qakbot June 2020)(Citation: Crowdstrike Qakbot October 2020)(Citation: ATT QakBot April 2021)(Citation: Group IB Ransomware September 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ff2b5737-6a87-4ffb-b61a-89d8f21615b1`.
