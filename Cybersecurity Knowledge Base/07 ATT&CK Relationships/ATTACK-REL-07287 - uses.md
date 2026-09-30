---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1044"
target_object: "T1583.001"
stix_relationship_id: "relationship--3b8a0295-1b56-4d78-bf91-ed275a7ff55b"
---
# Relationship 7287: G1044 — uses → T1583.001

**Source object:** [[01 ATT&CK/G1044 - APT42|G1044: APT42]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1583.001 - Domains|T1583.001: Domains]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT42](https://attack.mitre.org/groups/G1044) has registered domains, several of which masqueraded as news outlets and login services, for use in operations.(Citation: Mandiant APT42-charms)(Citation: TAG APT42)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3b8a0295-1b56-4d78-bf91-ed275a7ff55b`.
