---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0660"
target_object: "T1083"
stix_relationship_id: "relationship--292fd2a5-45fa-4125-84ea-8b5f341dc579"
---
# Relationship 5433: S0660 — uses → T1083

**Source object:** [[01 ATT&CK/S0660 - Clambling|S0660: Clambling]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Clambling](https://attack.mitre.org/software/S0660) can browse directories on a compromised host.(Citation: Trend Micro DRBControl February 2020)(Citation: Talent-Jump Clambling February 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--292fd2a5-45fa-4125-84ea-8b5f341dc579`.
