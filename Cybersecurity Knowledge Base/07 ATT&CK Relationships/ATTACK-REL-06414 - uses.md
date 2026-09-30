---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0040"
target_object: "T1070.004"
stix_relationship_id: "relationship--474cec2a-ff0f-40af-ac55-053a0ccebc67"
---
# Relationship 6414: C0040 — uses → T1070.004

**Source object:** [[01 ATT&CK/C0040 - APT41 DUST|C0040: APT41 DUST]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT41 DUST](https://attack.mitre.org/campaigns/C0040) deleted various artifacts from victim systems following use.(Citation: Google Cloud APT41 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--474cec2a-ff0f-40af-ac55-053a0ccebc67`.
