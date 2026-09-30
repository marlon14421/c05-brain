---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1236"
target_object: "T1106"
stix_relationship_id: "relationship--31d36371-b38c-4391-baf9-3b72056c520d"
---
# Relationship 9835: S1236 — uses → T1106

**Source object:** [[01 ATT&CK/S1236 - CLAIMLOADER|S1236: CLAIMLOADER]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CLAIMLOADER](https://attack.mitre.org/software/S1236) has used various Windows API calls during execution, when establishing persistence and defense evasion.(Citation: IBM MUSTANG PANDA PUBLOAD CLAIMLOADER JUNE 2025)(Citation: 2025_IBM_PUBLOAD_TONESHELL_HIUPAN_CLAIMLOADER_MUSTANG PANDA) [CLAIMLOADER](https://attack.mitre.org/software/S1236) has also leveraged the legitimate API functions to run its shellcode through the callback function, including `GetDC()` and `EnumFontsW()`.(Citation: IBM MUSTANG PANDA PUBLOAD CLAIMLOADER JUNE 2025) [CLAIMLOADER](https://attack.mitre.org/software/S1236) established persistence by utilizing the API `SHSetValue()`.(Citation: IBM MUSTANG PANDA PUBLOAD CLAIMLOADER JUNE 2025) [CLAIMLOADER](https://attack.mitre.org/software/S1236) has utilized APIs with callback functions such as `EnumpropsExW`, `EnumSystemLanguageGroupsA`, and `EnumCalendarInfoExW`.(Citation: 2025_IBM_PUBLOAD_TONESHELL_HIUPAN_CLAIMLOADER_MUSTANG PANDA)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--31d36371-b38c-4391-baf9-3b72056c520d`.
