---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0013"
target_object: "T1106"
stix_relationship_id: "relationship--deafd60c-af1a-40eb-bc43-287b37553fae"
---
# Relationship 6736: S0013 — uses → T1106

**Source object:** [[01 ATT&CK/S0013 - PlugX|S0013: PlugX]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PlugX](https://attack.mitre.org/software/S0013) can use the Windows API functions `GetProcAddress`, `LoadLibrary`, and `CreateProcess` to execute another process.(Citation: Eset PlugX Korplug Mustang Panda March 2022)(Citation: Proofpoint TA416 Europe March 2022)(Citation: Lastline PlugX Analysis)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--deafd60c-af1a-40eb-bc43-287b37553fae`.
