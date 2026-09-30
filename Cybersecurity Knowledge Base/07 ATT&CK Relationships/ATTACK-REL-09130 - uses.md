---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1044"
target_object: "T1070.008"
stix_relationship_id: "relationship--a69a3f1a-a912-41e2-b4b5-c320638ce858"
---
# Relationship 9130: G1044 — uses → T1070.008

**Source object:** [[01 ATT&CK/G1044 - APT42|G1044: APT42]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.008 - Clear Mailbox Data|T1070.008: Clear Mailbox Data]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT42](https://attack.mitre.org/groups/G1044) has deleted login notification emails and has cleared the Sent folder to cover their tracks.(Citation: Mandiant APT42-charms)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a69a3f1a-a912-41e2-b4b5-c320638ce858`.
