---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0089"
target_object: "T1547.001"
stix_relationship_id: "relationship--cd2a7854-1339-4f40-8ba1-be032dc5249e"
---
# Relationship 8475: S0089 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0089 - BlackEnergy|S0089: BlackEnergy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

The [BlackEnergy](https://attack.mitre.org/software/S0089) 3 variant drops its main DLL component and then creates a .lnk shortcut to that file in the startup folder.(Citation: F-Secure BlackEnergy 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cd2a7854-1339-4f40-8ba1-be032dc5249e`.
