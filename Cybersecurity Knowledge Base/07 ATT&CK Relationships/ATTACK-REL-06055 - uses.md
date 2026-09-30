---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0699"
target_object: "T1119"
stix_relationship_id: "relationship--bd651c13-04c8-4bff-9e68-b53b5f662510"
---
# Relationship 6055: S0699 — uses → T1119

**Source object:** [[01 ATT&CK/S0699 - Mythic|S0699: Mythic]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1119 - Automated Collection|T1119: Automated Collection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mythic](https://attack.mitre.org/software/S0699) supports scripting of file downloads from agents.(Citation: Mythc Documentation)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bd651c13-04c8-4bff-9e68-b53b5f662510`.
