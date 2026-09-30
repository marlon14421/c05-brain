---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0105"
target_object: "T1059.001"
stix_relationship_id: "relationship--bff00753-95ef-4a13-96fa-963365520573"
---
# Relationship 6214: G0105 — uses → T1059.001

**Source object:** [[01 ATT&CK/G0105 - DarkVishnya|G0105: DarkVishnya]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DarkVishnya](https://attack.mitre.org/groups/G0105) used PowerShell to create shellcode loaders.(Citation: Securelist DarkVishnya Dec 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bff00753-95ef-4a13-96fa-963365520573`.
