---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1044"
target_object: "T1547"
stix_relationship_id: "relationship--eb537310-fa06-4bde-a074-ed3234ec1a27"
---
# Relationship 8216: G1044 — uses → T1547

**Source object:** [[01 ATT&CK/G1044 - APT42|G1044: APT42]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547 - Boot or Logon Autostart Execution|T1547: Boot or Logon Autostart Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT42](https://attack.mitre.org/groups/G1044) has modified the Registry to maintain persistence.(Citation: Mandiant APT42-charms)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--eb537310-fa06-4bde-a074-ed3234ec1a27`.
