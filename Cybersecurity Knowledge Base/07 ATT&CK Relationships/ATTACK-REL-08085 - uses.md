---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0068"
target_object: "T1036"
stix_relationship_id: "relationship--f3b19f07-d8a9-4aca-a649-039024997a4f"
---
# Relationship 8085: G0068 — uses → T1036

**Source object:** [[01 ATT&CK/G0068 - PLATINUM|G0068: PLATINUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036 - Masquerading|T1036: Masquerading]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PLATINUM](https://attack.mitre.org/groups/G0068) has renamed rar.exe to avoid detection.(Citation: Twitter ItsReallyNick Platinum Masquerade)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f3b19f07-d8a9-4aca-a649-039024997a4f`.
