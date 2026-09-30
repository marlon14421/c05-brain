---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0431"
target_object: "T1033"
stix_relationship_id: "relationship--c0f13745-074b-46ba-ae7a-03385ef79d31"
---
# Relationship 8580: S0431 — uses → T1033

**Source object:** [[01 ATT&CK/S0431 - HotCroissant|S0431: HotCroissant]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HotCroissant](https://attack.mitre.org/software/S0431) has the ability to collect the username on the infected host.(Citation: Carbon Black HotCroissant April 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c0f13745-074b-46ba-ae7a-03385ef79d31`.
