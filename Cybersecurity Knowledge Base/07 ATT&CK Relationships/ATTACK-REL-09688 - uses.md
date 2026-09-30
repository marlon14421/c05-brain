---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0140"
target_object: "S0332"
stix_relationship_id: "relationship--22d01d2c-6c2e-4e59-98ac-393aef16ffe3"
---
# Relationship 9688: G0140 — uses → S0332

**Source object:** [[01 ATT&CK/G0140 - LazyScripter|G0140: LazyScripter]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0332 - Remcos|S0332: Remcos]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LazyScripter](https://attack.mitre.org/groups/G0140) dropped [Remcos](https://attack.mitre.org/software/S0332) during operations.(Citation: MalwareBytes LazyScripter Feb 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--22d01d2c-6c2e-4e59-98ac-393aef16ffe3`.
