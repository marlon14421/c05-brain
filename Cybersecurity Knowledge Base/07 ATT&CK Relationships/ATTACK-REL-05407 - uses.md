---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0576"
target_object: "T1055.001"
stix_relationship_id: "relationship--71c146b5-9afa-41fa-9339-2a6287e7d309"
---
# Relationship 5407: S0576 — uses → T1055.001

**Source object:** [[01 ATT&CK/S0576 - MegaCortex|S0576: MegaCortex]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.001 - Dynamic-link Library Injection|T1055.001: Dynamic-link Library Injection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MegaCortex](https://attack.mitre.org/software/S0576) loads injecthelper.dll into a newly created rundll32.exe process.(Citation: IBM MegaCortex)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--71c146b5-9afa-41fa-9339-2a6287e7d309`.
