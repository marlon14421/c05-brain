---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0233"
target_object: "T1053.002"
stix_relationship_id: "relationship--a5f43f22-7157-4e5a-8d08-d700471f1993"
---
# Relationship 5634: S0233 — uses → T1053.002

**Source object:** [[01 ATT&CK/S0233 - MURKYTOP|S0233: MURKYTOP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.002 - At|T1053.002: At]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MURKYTOP](https://attack.mitre.org/software/S0233) has the capability to schedule remote AT jobs.(Citation: FireEye Periscope March 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a5f43f22-7157-4e5a-8d08-d700471f1993`.
