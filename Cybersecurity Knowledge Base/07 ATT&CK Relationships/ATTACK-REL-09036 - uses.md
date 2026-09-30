---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0013"
target_object: "T1564.001"
stix_relationship_id: "relationship--234205d5-cc99-435c-bbc8-e2c1d3eb0ac5"
---
# Relationship 9036: S0013 — uses → T1564.001

**Source object:** [[01 ATT&CK/S0013 - PlugX|S0013: PlugX]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.001 - Hidden Files and Directories|T1564.001: Hidden Files and Directories]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PlugX](https://attack.mitre.org/software/S0013) can modify the characteristics of folders to hide them from the compromised user.(Citation: Proofpoint TA416 Europe March 2022) [PlugX](https://attack.mitre.org/software/S0013) has also modified file attributes to hidden and system.(Citation: Eset PlugX Korplug Mustang Panda March 2022)(Citation: Sophos Mustang Panda PLUGX)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--234205d5-cc99-435c-bbc8-e2c1d3eb0ac5`.
