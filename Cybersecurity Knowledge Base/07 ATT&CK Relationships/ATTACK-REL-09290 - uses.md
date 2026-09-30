---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0596"
target_object: "T1071.004"
stix_relationship_id: "relationship--936ff38b-73f6-48fe-876f-8ebd3b60df1f"
---
# Relationship 9290: S0596 — uses → T1071.004

**Source object:** [[01 ATT&CK/S0596 - ShadowPad|S0596: ShadowPad]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.004 - DNS|T1071.004: DNS]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ShadowPad](https://attack.mitre.org/software/S0596) has used DNS tunneling for C2 communications.(Citation: Kaspersky ShadowPad Aug 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--936ff38b-73f6-48fe-876f-8ebd3b60df1f`.
