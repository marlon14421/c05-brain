---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1182"
target_object: "T1082"
stix_relationship_id: "relationship--bb4e12ab-cfaa-4693-9156-bb97fc9c5b92"
---
# Relationship 9630: S1182 — uses → T1082

**Source object:** [[01 ATT&CK/S1182 - MagicRAT|S1182: MagicRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MagicRAT](https://attack.mitre.org/software/S1182) collects basic system information from victim machines.(Citation: Cisco MagicRAT 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bb4e12ab-cfaa-4693-9156-bb97fc9c5b92`.
