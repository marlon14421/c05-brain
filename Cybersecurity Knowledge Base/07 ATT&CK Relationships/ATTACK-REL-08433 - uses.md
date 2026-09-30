---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "T1620"
stix_relationship_id: "relationship--56fcac64-0f74-4670-8984-2a3fbc1b6685"
---
# Relationship 8433: G0094 — uses → T1620

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1620 - Reflective Code Loading|T1620: Reflective Code Loading]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kimsuky](https://attack.mitre.org/groups/G0094) has used the Invoke-Mimikatz PowerShell script to reflectively load a Mimikatz credential stealing DLL into memory.(Citation: Mandiant APT43 March 2024) [Kimsuky](https://attack.mitre.org/groups/G0094) has also used reflective loading through .NET assembly using `[System.Reflection.Assembly]::Load`.(Citation: Securonix Kimsuky February 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--56fcac64-0f74-4670-8984-2a3fbc1b6685`.
