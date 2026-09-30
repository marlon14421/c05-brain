---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0456"
target_object: "T1106"
stix_relationship_id: "relationship--1681f4aa-4bb1-482a-8fdf-8c1b724635d9"
---
# Relationship 5734: S0456 — uses → T1106

**Source object:** [[01 ATT&CK/S0456 - Aria-body|S0456: Aria-body]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Aria-body](https://attack.mitre.org/software/S0456) has the ability to launch files using ShellExecute .(Citation: CheckPoint Naikon May 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1681f4aa-4bb1-482a-8fdf-8c1b724635d9`.
