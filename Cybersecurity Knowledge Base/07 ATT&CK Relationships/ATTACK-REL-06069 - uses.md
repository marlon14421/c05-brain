---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0038"
target_object: "T1012"
stix_relationship_id: "relationship--746b0def-62c8-438d-b5ec-aa6b7dbfb860"
---
# Relationship 6069: G0038 — uses → T1012

**Source object:** [[01 ATT&CK/G0038 - Stealth Falcon|G0038: Stealth Falcon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1012 - Query Registry|T1012: Query Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Stealth Falcon](https://attack.mitre.org/groups/G0038) malware attempts to determine the installed version of .NET by querying the Registry.(Citation: Citizen Lab Stealth Falcon May 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--746b0def-62c8-438d-b5ec-aa6b7dbfb860`.
