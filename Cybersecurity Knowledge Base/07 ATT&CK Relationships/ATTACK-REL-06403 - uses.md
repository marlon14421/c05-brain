---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0504"
target_object: "T1027"
stix_relationship_id: "relationship--9297d0b8-3a96-4fb9-90f2-8e3aa9fe4aca"
---
# Relationship 6403: S0504 — uses → T1027

**Source object:** [[01 ATT&CK/S0504 - Anchor|S0504: Anchor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Anchor](https://attack.mitre.org/software/S0504) has obfuscated code with stack strings and string encryption.(Citation: Cyberreason Anchor December 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9297d0b8-3a96-4fb9-90f2-8e3aa9fe4aca`.
