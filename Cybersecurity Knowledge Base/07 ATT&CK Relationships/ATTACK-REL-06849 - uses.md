---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0233"
target_object: "T1059.003"
stix_relationship_id: "relationship--5df81b26-0cbe-4b2e-abce-bb7b98a1064d"
---
# Relationship 6849: S0233 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0233 - MURKYTOP|S0233: MURKYTOP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MURKYTOP](https://attack.mitre.org/software/S0233) uses the command-line interface.(Citation: FireEye Periscope March 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5df81b26-0cbe-4b2e-abce-bb7b98a1064d`.
