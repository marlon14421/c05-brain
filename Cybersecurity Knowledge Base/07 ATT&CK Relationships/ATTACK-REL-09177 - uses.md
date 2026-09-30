---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0078"
target_object: "T1685"
stix_relationship_id: "relationship--0b926b38-f00a-4ea2-a64b-8b4c05851629"
---
# Relationship 9177: G0078 — uses → T1685

**Source object:** [[01 ATT&CK/G0078 - Gorgon Group|G0078: Gorgon Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1685 - Disable or Modify Tools|T1685: Disable or Modify Tools]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Gorgon Group](https://attack.mitre.org/groups/G0078) malware can attempt to disable security features in Microsoft Office and Windows Defender using the taskkill command.(Citation: Unit 42 Gorgon Group Aug 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0b926b38-f00a-4ea2-a64b-8b4c05851629`.
