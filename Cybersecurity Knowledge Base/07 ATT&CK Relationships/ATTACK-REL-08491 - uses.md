---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0107"
target_object: "T1546.010"
stix_relationship_id: "relationship--cb4af413-9bd7-4f1a-a693-57d11ffccbf5"
---
# Relationship 8491: S0107 — uses → T1546.010

**Source object:** [[01 ATT&CK/S0107 - Cherry Picker|S0107: Cherry Picker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1546.010 - AppInit DLLs|T1546.010: AppInit DLLs]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Some variants of [Cherry Picker](https://attack.mitre.org/software/S0107) use AppInit_DLLs to achieve persistence by creating the following Registry key: HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Windows "AppInit_DLLs"="pserver32.dll" (Citation: Trustwave Cherry Picker)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cb4af413-9bd7-4f1a-a693-57d11ffccbf5`.
