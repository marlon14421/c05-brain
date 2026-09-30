---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0644"
target_object: "T1033"
stix_relationship_id: "relationship--c7c2e904-7797-4d67-a0bf-dae4abf53689"
---
# Relationship 9396: S0644 — uses → T1033

**Source object:** [[01 ATT&CK/S0644 - ObliqueRAT|S0644: ObliqueRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ObliqueRAT](https://attack.mitre.org/software/S0644) can check for blocklisted usernames on infected endpoints.(Citation: Talos Oblique RAT March 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c7c2e904-7797-4d67-a0bf-dae4abf53689`.
