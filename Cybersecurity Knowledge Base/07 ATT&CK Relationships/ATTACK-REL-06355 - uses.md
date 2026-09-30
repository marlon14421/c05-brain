---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0112"
target_object: "T1518"
stix_relationship_id: "relationship--715262b6-9d31-4589-ba53-fb5d7be3f1f5"
---
# Relationship 6355: G0112 — uses → T1518

**Source object:** [[01 ATT&CK/G0112 - Windshift|G0112: Windshift]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518 - Software Discovery|T1518: Software Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Windshift](https://attack.mitre.org/groups/G0112) has used malware to identify installed software.(Citation: BlackBerry Bahamut)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--715262b6-9d31-4589-ba53-fb5d7be3f1f5`.
