---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0660"
target_object: "T1033"
stix_relationship_id: "relationship--dd06865b-d8fa-4626-8ebd-e75289377c4c"
---
# Relationship 8025: S0660 — uses → T1033

**Source object:** [[01 ATT&CK/S0660 - Clambling|S0660: Clambling]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Clambling](https://attack.mitre.org/software/S0660) can identify the username on a compromised host.(Citation: Trend Micro DRBControl February 2020)(Citation: Talent-Jump Clambling February 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dd06865b-d8fa-4626-8ebd-e75289377c4c`.
