---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1239"
target_object: "T1480.001"
stix_relationship_id: "relationship--0a06687e-7e1c-48f1-a3dc-23333f57f215"
---
# Relationship 5308: S1239 — uses → T1480.001

**Source object:** [[01 ATT&CK/S1239 - TONESHELL|S1239: TONESHELL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1480.001 - Environmental Keying|T1480.001: Environmental Keying]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TONESHELL](https://attack.mitre.org/software/S1239) has generated unique GUIDs to identify victim devices.(Citation: Trend Micro Mustang Panda Earth Preta Toneshell February 2025)(Citation: 2022 November_TrendMicro_Earth Preta_Toneshell_Pubload)(Citation: Zscaler) [TONESHELL](https://attack.mitre.org/software/S1239) has leveraged environmental keying in payload delivery using the victim computer name and other configuration values.(Citation: 2025_IBM_PUBLOAD_TONESHELL_HIUPAN_CLAIMLOADER_MUSTANG PANDA) [TONESHELL](https://attack.mitre.org/software/S1239) has also tracked IDs associated with reverse shell subprocesses to manage interactions and terminations from C2.(Citation: Trend Micro Mustang Panda Earth Preta Toneshell February 2025)(Citation: Zscaler)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0a06687e-7e1c-48f1-a3dc-23333f57f215`.
