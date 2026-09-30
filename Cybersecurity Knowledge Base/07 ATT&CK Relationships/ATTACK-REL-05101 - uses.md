---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0069"
target_object: "T1685"
stix_relationship_id: "relationship--778d26cc-c730-4329-aa66-8c7e83610e99"
---
# Relationship 5101: G0069 — uses → T1685

**Source object:** [[01 ATT&CK/G0069 - MuddyWater|G0069: MuddyWater]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1685 - Disable or Modify Tools|T1685: Disable or Modify Tools]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MuddyWater](https://attack.mitre.org/groups/G0069) can disable the system's local proxy settings.(Citation: Trend Micro Muddy Water March 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--778d26cc-c730-4329-aa66-8c7e83610e99`.
