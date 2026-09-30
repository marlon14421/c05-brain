---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0499"
target_object: "T1027"
stix_relationship_id: "relationship--c8fb4459-4352-4ee6-bfaf-a97be333bf64"
---
# Relationship 8873: S0499 — uses → T1027

**Source object:** [[01 ATT&CK/S0499 - Hancitor|S0499: Hancitor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Hancitor](https://attack.mitre.org/software/S0499) has used Base64 to encode malicious links.(Citation: Threatpost Hancitor)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c8fb4459-4352-4ee6-bfaf-a97be333bf64`.
