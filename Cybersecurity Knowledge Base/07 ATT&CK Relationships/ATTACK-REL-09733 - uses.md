---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0149"
target_object: "T1059.003"
stix_relationship_id: "relationship--66bb45a4-fadf-4000-9055-90f9bb206b37"
---
# Relationship 9733: S0149 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0149 - MoonWind|S0149: MoonWind]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MoonWind](https://attack.mitre.org/software/S0149) can execute commands via an interactive command shell.(Citation: Palo Alto MoonWind March 2017) [MoonWind](https://attack.mitre.org/software/S0149) uses batch scripts for various purposes, including to restart and uninstall itself.(Citation: Palo Alto MoonWind March 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--66bb45a4-fadf-4000-9055-90f9bb206b37`.
