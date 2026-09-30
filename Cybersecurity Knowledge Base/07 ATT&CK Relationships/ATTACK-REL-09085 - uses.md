---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0042"
target_object: "T1059.005"
stix_relationship_id: "relationship--e2a5ad0c-a978-4da8-a634-3bffbf9722d3"
---
# Relationship 9085: C0042 — uses → T1059.005

**Source object:** [[01 ATT&CK/C0042 - Outer Space|C0042: Outer Space]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.005 - Visual Basic|T1059.005: Visual Basic]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Outer Space](https://attack.mitre.org/campaigns/C0042), [OilRig](https://attack.mitre.org/groups/G0049) used VBS droppers to deploy malware.(Citation: ESET OilRig Campaigns Sep 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e2a5ad0c-a978-4da8-a634-3bffbf9722d3`.
