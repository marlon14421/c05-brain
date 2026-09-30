---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1036"
target_object: "T1027"
stix_relationship_id: "relationship--a6ea2a1c-dfe9-4599-812a-d1f846fb775b"
---
# Relationship 6908: G1036 — uses → T1027

**Source object:** [[01 ATT&CK/G1036 - Moonstone Sleet|G1036: Moonstone Sleet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Moonstone Sleet](https://attack.mitre.org/groups/G1036) delivers encrypted payloads in pieces that are then combined together to form a new portable executable (PE) file during installation.(Citation: Microsoft Moonstone Sleet 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a6ea2a1c-dfe9-4599-812a-d1f846fb775b`.
