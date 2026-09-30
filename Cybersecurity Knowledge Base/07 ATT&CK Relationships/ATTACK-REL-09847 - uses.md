---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0013"
target_object: "T1135"
stix_relationship_id: "relationship--5e7460f8-9ea9-4aa4-b06e-15861b02d70e"
---
# Relationship 9847: S0013 — uses → T1135

**Source object:** [[01 ATT&CK/S0013 - PlugX|S0013: PlugX]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1135 - Network Share Discovery|T1135: Network Share Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PlugX](https://attack.mitre.org/software/S0013) has a module to enumerate network shares.(Citation: Eset PlugX Korplug Mustang Panda March 2022)(Citation: CIRCL PlugX March 2013)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5e7460f8-9ea9-4aa4-b06e-15861b02d70e`.
