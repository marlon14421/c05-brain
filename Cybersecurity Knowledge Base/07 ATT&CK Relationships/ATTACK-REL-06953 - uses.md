---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0280"
target_object: "T1033"
stix_relationship_id: "relationship--cb68541e-3ca7-4e2d-892d-c30b50107b39"
---
# Relationship 6953: S0280 — uses → T1033

**Source object:** [[01 ATT&CK/S0280 - MirageFox|S0280: MirageFox]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MirageFox](https://attack.mitre.org/software/S0280) can gather the username from the victim’s machine.(Citation: APT15 Intezer June 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cb68541e-3ca7-4e2d-892d-c30b50107b39`.
