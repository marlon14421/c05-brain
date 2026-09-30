---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0025"
target_object: "T1036.005"
stix_relationship_id: "relationship--10976d43-afcf-44d5-bcbf-122f39e0cbff"
---
# Relationship 8030: C0025 — uses → T1036.005

**Source object:** [[01 ATT&CK/C0025 - 2016 Ukraine Electric Power Attack|C0025: 2016 Ukraine Electric Power Attack]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During the [2016 Ukraine Electric Power Attack](https://attack.mitre.org/campaigns/C0025), DLLs and EXEs with filenames associated with common electric power sector protocols were used to masquerade files.(Citation: Dragos Crashoverride 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--10976d43-afcf-44d5-bcbf-122f39e0cbff`.
