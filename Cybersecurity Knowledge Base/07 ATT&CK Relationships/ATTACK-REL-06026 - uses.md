---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0634"
target_object: "T1027.006"
stix_relationship_id: "relationship--a6006789-f164-4616-9a1f-20fd2b34113f"
---
# Relationship 6026: S0634 — uses → T1027.006

**Source object:** [[01 ATT&CK/S0634 - EnvyScout|S0634: EnvyScout]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.006 - HTML Smuggling|T1027.006: HTML Smuggling]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[EnvyScout](https://attack.mitre.org/software/S0634) contains JavaScript code that can extract an encoded blob from its HTML body and write it to disk.(Citation: MSTIC Nobelium Toolset May 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a6006789-f164-4616-9a1f-20fd2b34113f`.
