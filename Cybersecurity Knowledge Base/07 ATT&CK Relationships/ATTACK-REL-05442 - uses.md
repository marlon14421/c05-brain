---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0139"
target_object: "T1547.001"
stix_relationship_id: "relationship--f0b00a47-9d63-4d05-b771-022a21a4ed06"
---
# Relationship 5442: S0139 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0139 - PowerDuke|S0139: PowerDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PowerDuke](https://attack.mitre.org/software/S0139) achieves persistence by using various Registry Run keys.(Citation: Volexity PowerDuke November 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f0b00a47-9d63-4d05-b771-022a21a4ed06`.
