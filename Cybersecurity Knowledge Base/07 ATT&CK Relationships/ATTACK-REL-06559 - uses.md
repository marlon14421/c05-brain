---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0140"
target_object: "T1059.001"
stix_relationship_id: "relationship--9ee8a8fb-798e-4fa0-9ae0-ab96e75c9f4e"
---
# Relationship 6559: G0140 — uses → T1059.001

**Source object:** [[01 ATT&CK/G0140 - LazyScripter|G0140: LazyScripter]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LazyScripter](https://attack.mitre.org/groups/G0140) has used PowerShell scripts to execute malicious code.(Citation: MalwareBytes LazyScripter Feb 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9ee8a8fb-798e-4fa0-9ae0-ab96e75c9f4e`.
