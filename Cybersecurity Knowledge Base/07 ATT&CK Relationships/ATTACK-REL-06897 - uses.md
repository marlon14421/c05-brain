---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0123"
target_object: "T1190"
stix_relationship_id: "relationship--c4bc8f71-e4f4-42b8-a39f-b4512987a423"
---
# Relationship 6897: G0123 — uses → T1190

**Source object:** [[01 ATT&CK/G0123 - Volatile Cedar|G0123: Volatile Cedar]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1190 - Exploit Public-Facing Application|T1190: Exploit Public-Facing Application]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Volatile Cedar](https://attack.mitre.org/groups/G0123) has targeted publicly facing web servers, with both automatic and manual vulnerability discovery.(Citation: CheckPoint Volatile Cedar March 2015) (Citation: ClearSky Lebanese Cedar Jan 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c4bc8f71-e4f4-42b8-a39f-b4512987a423`.
