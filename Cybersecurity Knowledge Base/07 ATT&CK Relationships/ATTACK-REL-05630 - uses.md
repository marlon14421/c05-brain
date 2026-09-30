---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0198"
target_object: "T1027.002"
stix_relationship_id: "relationship--295f4cf0-1fb7-4d60-8e15-af8f301d0e1b"
---
# Relationship 5630: S0198 — uses → T1027.002

**Source object:** [[01 ATT&CK/S0198 - NETWIRE|S0198: NETWIRE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.002 - Software Packing|T1027.002: Software Packing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NETWIRE](https://attack.mitre.org/software/S0198) has used .NET packer tools to evade detection.(Citation: Red Canary NETWIRE January 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--295f4cf0-1fb7-4d60-8e15-af8f301d0e1b`.
