---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0112"
target_object: "T1027"
stix_relationship_id: "relationship--996defcb-8a62-4271-9d01-93d66525b159"
---
# Relationship 9102: G0112 — uses → T1027

**Source object:** [[01 ATT&CK/G0112 - Windshift|G0112: Windshift]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Windshift](https://attack.mitre.org/groups/G0112) has used string encoding with floating point calculations.(Citation: BlackBerry Bahamut)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--996defcb-8a62-4271-9d01-93d66525b159`.
