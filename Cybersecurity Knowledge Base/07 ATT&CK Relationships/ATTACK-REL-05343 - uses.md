---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0078"
target_object: "T1547.009"
stix_relationship_id: "relationship--a1ec1602-33d6-45be-8eda-2020094e93a4"
---
# Relationship 5343: G0078 — uses → T1547.009

**Source object:** [[01 ATT&CK/G0078 - Gorgon Group|G0078: Gorgon Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.009 - Shortcut Modification|T1547.009: Shortcut Modification]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Gorgon Group](https://attack.mitre.org/groups/G0078) malware can create a .lnk file and add a Registry Run key to establish persistence.(Citation: Unit 42 Gorgon Group Aug 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a1ec1602-33d6-45be-8eda-2020094e93a4`.
